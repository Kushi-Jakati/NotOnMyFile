# NotOnMyFile

A common method in forensics is checking files for the correct file signature. Attackers may disguise their files so they cannot be opened (i.e., viewed as a corrupted file) by renaming the file with a different file extension. This NetBeans application takes a file as input and correctly detects whether or not the file's MIME type matches up with the file's presented extension. If there is a contradiction, the program will output a "Not on My File!" with the application interface turning red and a textbox displaying what the file's type is (versus what it is presented as). 

This was a rudimentary project in high school, so there are some flaws. Namely, this program cannot handle big files (which causes a memory overflow--a security issue) and takes a long time to recognize large files it can process.

Most commonly supported file types this app handles: 
-DOCX
-PPTX
-XLSX
-MP3
-EPUB
-PNG
-JPEG
-PDF
-ZIP
-BMP

Overall, this was a project done to see how expansive and accurate a file identifier I could build based on just file signatures and MIME types as an analysis tool. Results and the process of coding this project told me that it would be difficult to ensure 100% performance with just these analysis tools, but I would say using file signatures and MIME types does provide a useful and convenient tool for digital forensic professionals when dealing with common file types 

