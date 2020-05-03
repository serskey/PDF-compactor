# PDF-compactor
Implement a web that allows users to upload a pdf file which might be huge (up to 30 MB) and return a compacted version of the file based on the user specified constraints (such as DPI).
Tools

frontend: Bootstrap4 + HTML + jQuery+ CSS
backend: Node.js + express
PDF Optimizer API : PDFtron.
Functions

User can set Quality and DPI to get different compressed size.

Quality: from 1 to 10 where 10 is lossless. There is an example:

Quality	DPI	Original zise	compressed size
1	100	8.9MB	2.59MB
10	100	8.9MB	4.20MB
1	50	8.9MB	1.57MB
Store the uploaded files in our own (NodeJS or Python) server.

compact the PDF from large size to small size.

Implement API endpoints to a file list, user can download, and remove files for user.

can send email to producer. use nodemailer.

can support English and Chinese.

show the total Web Hit.

Getting started

To get the Node server running locally:

Clone this repo
to install all required dependencies
$ npm install
to install PDFtron,you can learn more in PDFtron.
$ npm install @pdftron/pdfnet-node
go to /frontend, then run
$ node app.js
Future Work

we will add more functions, such as PDF convert, combining pdf, image compress ...
More

This project is for USC EE599 project. 😊    
