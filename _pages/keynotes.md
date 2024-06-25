---
permalink: /keynotes/
title: "Keynote Speakers"
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Times New Roman;
}
html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}
.column {
  float: left;
  width: auto;
  margin-bottom: 16px;
  padding: 0 8px;
}
@media screen and (max-width: 650px) {
  .column {
    width: auto;
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
  font-family: Times New Roman;
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
  width: 45%;
  font-family: Times New Roman;
}
.button-1 {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: DodgerBlue;
  text-align: center;
  cursor: pointer;
  width: 45%;
  font-family: Times New Roman;
}
.button:hover {
  background-color: DodgerBlue
}
.button-1:hover {
  background-color: black
}
.button-2 {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: DodgerBlue;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-family: Times New Roman;
}
.button-2:hover {
  background-color: black
}
table {
  width: auto;
}
th, td {
  text-align: left;
  padding: 40px;
}
td {
  border-bottom: 1px solid #ddd;
}
</style>
</head>
<body>
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
        <a href="https://youtu.be/m3-AEOHoXCI?si=SSTvQMz4HNdnv2Q6"><button class="button-1">View Talk</button></a>
        <p> </p>
      </div>
      <br>
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
         <a href="https://youtu.be/nuRs41057Z4?si=7fPieZHnxLnVhXvX
"><button class="button-1">View Talk</button></a>
         <p> </p>
      </div>
    </div>
    <br>
  </div>

<h2> Tutorials </h2>
  <div class="column">
    <div class="card">
        <div class="container">
        <h3>Healthcare Text Analytics in the Era of Large Language Models</h3>
        <p>A team from the Institute of Health Informatics, University College London (Yunsoo Kim, Jinge Wu, Honghan Wu) will deliver a tutorial on'Healthcare Text Analytics in the Era of Large Language Models'. </p>

<p>Recent advancements in large language models (LLMs), such as ChatGPT, has revolutionised the field of natural language processing (NLP) and opened new
possibilities for healthcare text analytics. This tutorial, structured as a combination of lectures and demonstrations, aims to provide a comprehensive guide to leveraging large language models in the healthcare domain, focusing on advanced techniques and applications. The tutorial will begin with an overview of the open source LLMs, emphasising their potential in addressing complex challenges within healthcare text analytics. Special attention will be given to the unique issues surrounding privacy, security, and domain-specific nuances inherent in healthcare data. Participants will be guided through practical applications of LLMs in two distinct healthcare text domains: 1) Discharge Note Generation and 2) PubMed Abstract Information Extraction. Practical demonstrations will illustrate how LLMs can be tailored for each specific domain using prompting, in-context learning, instruction tuning (finetuning). Furthermore, we will delve into LLMs’ challenges in adapting to handle multi-modal data representations.</p>
<a href="https://ca.linkedin.com/in/alistairewj"><button class="button-2">Resources</button></a>
     <p> </p>
     </div>
    </div>
    <br>
    <br>
    <br>
  </div> 
  
</body>
</html>

