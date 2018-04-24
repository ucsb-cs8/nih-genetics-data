# nih-genetics-data
Getting Genetics Data From NIH

The web page <https://ghr.nlm.nih.gov/about/data-files-api> describes how to get certain types of genetics data from the National Institutes of Health (NIH).

In particular: 

   Information from individual condition, gene, chromosome, and mtDNA pages is available in JSON and XML. 
   Add `?report=json` or `?report=xml` to the page's URL, e.g., <https://ghr.nlm.nih.gov/condition/alzheimer-disease?report=json> 
   To get JSONP that passes the data to a function of your choice, also add `&p=somefunction`

   A compendium of all those XML instances is available in one XML file: <https://ghr.nlm.nih.gov/download/ghr-summaries.xml>
   
 
