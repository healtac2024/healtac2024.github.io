---
permalink: /programme/
title: "Programme"
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 80%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #009999
}
</style>
</head>
<body>

<h2>Keynote Speakers</h2>
<br>

  <div class="column">
    <div class="card">
      <img src="https://liacs.leidenuniv.nl/~verbernes/wordpress/wp-content/uploads/2020/04/pasfoto_SuzanVerberne_2019-640x640.jpg" alt="suzan" style="width:100%">
      <div class="container">
        <h3>Suzan Verberne </h3>
        <p class="title">Professor of Natural Language Processing (NLP) </p>
        <p stype><b>Large Language Models in healthcare: should we care more?</b></p>
        <p>ChatGPT can do a lot for us: it can serve as a text corrector, as a source of inspiration, as a programming aid, and as an interactive search engine. ChatGPT is also widely used in the health domain, both by doctors and patients. Large language models (LLMs) such as ChatGPT can write very convincing texts, but being able to write fluently is not the same as providing correct information. Should we worry about that? In my presentation I will first discuss our work on text mining from patient experiences, highlighting the challenges of extracting medical information from informal text. Then I will discuss the opportunities of using LLMs, and go into the risks and challenges. I will also make suggestions for responsible use of LLMs for medical applications.</p>
        <a href="https://liacs.leidenuniv.nl/~verbernes/"><button class="button">More info</button></a>
        <p> </p>
      </div>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <img src="/assets/images/alistair_johnsoncairem-birem.jpg" alt="alistair" style="width:100%">
      <div class="container">
        <h3>Alistair Johnson </h3>
        <p class="title">Glowyr, Inc.</p>
        <p stype><b>The bottleneck has always been data!</b></p>
        <p>The world has been in awe at the recent applications of sophisticated machine learning models derived from large datasets. Yet in medicine, we continue to use decades old algorithms to support patient care. Models for cancer progression are based upon staging guidelines defined in the 70s, patient severity of illness is estimated using a scoring system from the 90s, and our latest and greatest criteria for sepsis was a model with three input variables. The reasons for the technological naivety in medicine are multifactorial, but one aspect stands out: researchers simply do not have much data. In this talk I will highlight the MIMIC series of databases, a suite of publicly accessible deidentified medical records. I'll give an insider's view on how the electronic health records for thousands of individuals were comprehensively deidentified, transformed, and shared for research without harm to the individual's themselves. I'll overview the utility of this data, and highlight some of our own work on language modeling enabled by the broad access to deidentified free-text clinical notes. I'll conclude with my thoughts on how the field should better balance the benefits and risks of using patient data for research.</p>
         <a href="https://ca.linkedin.com/in/alistairewj"><button class="button">More info</button></a>
         <p> </p>
      </div>
    </div>
  </div>

</body>
</html>
