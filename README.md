# pdf_to_text
## Convert a folder full of PDFs into Text files 


This is something I coded based on resources available on the web. My initial motivation was to figure out a way to convert PDFs into text format. I also wanted to do this in bulk or in bath fashion.

There are two types of PDFs out there, from what I know. You have your regular "binary" PDFs which are text files such as Word doc that were saved as PDFs. These are essentially easy to convert into text. 

The more challenging PDFs are the ones that are scanned "images". So for example, a document that was printed then later scanned. Now, converting these images into text require learning about "OCR" (Optical Character Recognition). 

So here I am using [Pytesserect](https://pypi.org/project/pytesseract/) which uses Google's OCR tool: [Tesserect](https://github.com/tesseract-ocr/tesseract). There are more info on Tesserect and other OCR tools in the resource section below.


## Additional Resources:

* What are the best OCR tools: [Link](https://source.opennews.org/articles/so-many-ocr-options/)

* Tesserect: [More Info](https://github.com/tesseract-ocr/docs/blob/master/das_tutorial2016/1Intro-history.pdf)

* Tessrect Parameters [Link](https://wilsonmar.github.io/tesseract/)

* Using Tesserect with Python: [Link](https://www.pyimagesearch.com/2017/07/10/using-tesseract-ocr-python/)

