---
title: Getting Started
category: Data Curation Primer
order: 1
---

> **What is data curation?**

Data curation aids in preserving the value of research data for the long-term by optimizing data for discoverability, interoperability, and reusability (Munoz & Renear 2011; Johnston et al., 2018; Thomer et al, 2022). For more specifics on data curation in practice see the definition below provided by Zorich 1995:

    “Data sets need to be examined for consistency, long-term quality and relevance over time, and new sources of data must be identified and assessed. Changes or updates to data require authentication and verification. Tools which support object databases, such as authority lists, thesauri, data dictionaries and other documentation resources, need to be maintained, updated and distributed at regular intervals, while data security and access must be considered. All these concerns constitute the discipline of data curation.”

> **Why does data curation matter?**

Data curation is important for making sure that datasets are FAIR:findable, accessible, interoperable, and reusable (Wilkinson et al., 2016). Previous work has demonstrated that data that have been curated are more likely to be trusted and reproducible as well as easily understood by other researchers and collaborators (Roche et al., 2015; McNutt 2016; Smith & Roberts 2016; Beagrie & Houghton 2014).

In particular, data curation of genetic and genomic sequence data is valuable because these data have immense reuse value for measuring genetic diversity. However, without information about the spatial and temporal context, the metadata, of the sample organism, the value of the genomic sequence is limited (Toczydlowski et al. 2021).

</p>
</blockquote>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #44729B;
  color: white;
  cursor: pointer;
  padding-bottom: 30px;
  padding-top: 30px;
  padding-left: 20px;
  width: 100%;
  border: none;
  border-bottom: 3px solid white;
  text-align: left;
  outline: none;
}
.active, .collapsible:hover {
  background-color: #345878;
}
.content {
  padding: 0 20px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: rgb(68,114,155,0.2);
}
.collapsible:after {
  color: #ffffff;
  content: "+";
  font-size: 20px;
  float: right;
  margin-left: 5px;
  padding-right: 10px;
}
.active:after {
  content: "-";
  color: #ffffff;
  font-size: 20px;
  padding-right: 10px;
}
</style>
</head>
<body>
<br>
<br>

<h2>Terms to know</h2>

<br>
<br>

<button class="collapsible">Metadata</button>
<div class="content">
  <p><br>Information about a data set that is structured (often in machine-readable format) for purposes of search and retrieval. Metadata elements may include basic information (e.g., title, author, date created, etc.) and/or specific elements inherent to datasets (e.g., spatial coverage, time periods) (Data Curation Network Data Curation Glossary).</p>
</div>
<button class="collapsible">International Nucleotide Sequence Database Collaboration (INSDC)</button>
<div class="content">
  <p><br>Consists of a joint effort to collect and disseminate databases containing DNA and RNA sequences. It involves a collaboration between the following databases: [DNA Data Bank of Japan (DDBJ)](https://www.ddbj.nig.ac.jp/index-e.html), [European Nucleotide Archive (ENA)](https://www.ebi.ac.uk/ena/browser/home), and [GenBank (NCBI)](https://www.ncbi.nlm.nih.gov/genbank/). New and updated data on nucleotide sequences contributed by research teams to each of the three databases are synchronized on a daily basis (https://en.wikipedia.org/wiki/International_Nucleotide_Sequence_Database_Collaboration).</p>
</div>
<button class="collapsible">Nucleotide</button>
<div class="content">
  <p><br>The basic building block of nucleic acids (RNA and DNA) (https://www.genome.gov/genetics-glossary/Nucleotide).</p>
</div>
<button class="collapsible">Genetic and Genomic Sequence Data</button>
<div class="content">
  <p><br>The sequence of nucleotides which tell scientists the kind of genetic information that is carried by a particular segment of DNA or RNA. For example scientists can use sequence information to determine which stretches of DNA contain genes and which stretches carry regulatory instructions, turning genes on or off (https://www.genome.gov/about-genomics/fact-sheets/DNA-Sequencing-Fact-Sheet).</p>
</div>
<button class="collapsible">Digital Object Identifier (DOI)</button>
<div class="content">
  <p><br>A string of numbers, letters, and symbols used to uniquely identify an article or document and to provide it with a permanent web address (URL) (https://ask.library.uic.edu/faq/345899).</p>
</div>
<button class="collapsible">Online Repository</button>
<div class="content">
  <p><br>An archive or collection of documents such as journal articles, datasets, presentations, etc. An online repository can be for general use, institutional use, and/or discipline-specific use. Examples include: Dryad, Zenodo, ScholarSphere.</p>
</div>


<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    }
  });
}
</script>

</body>
</html>

<br>
<br>
