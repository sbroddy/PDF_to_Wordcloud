# PDF_to_Wordcloud
Simple python script to generate a Wordcloud from an online PDF

Inspired by this work:  https://towardsdatascience.com/word-clouds-in-python-comprehensive-example-8aee4343c0bf

Consolodated everything into one script, and changed from 
reading local files to retrieving URLs for the input PDF 
and the image mask.

usage:  cmd "<pdf_url>" "<mask_url>" "[optional, additional, stop, words]" 
<pdf_url> is the URL to the PDF to be analyzed 
<mask_url> is the URL to a PNG file to be used as the mask for the word cloud 
Optional stop words are an additional list of words not to be included in the word cloud in the form of a python list. 

