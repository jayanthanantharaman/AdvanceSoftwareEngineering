# AdvanceSoftwareEngineering
The repository contains documents related to Advance Software Engineering submissions

pdfrenamer is a program which extracts below mentioned information from pdf files

Authors: One-author-name consists of [First Middle* Last], list of author names is comma separated. Ex: Umme Ayda Mannan, Iftekhar Ahmed, Rana Abdullah M Almurshed, Danny Dig, Carlos Jensen. This example has 5 authors.
Issue: Usually a number. Some times a name. Ex: "3" "March"

Sample pdfs are placed in the folder testpdfs. 
The program works only if the pdfs are in the same format as sample pdfs placed in the testpdfs folder 


<li>Reviews - Contains review comments for various documents submitted by other team in the course</li>
<li>pdfrenamer-v1.0 - Source code in Java</li>
<li>extractAuthorIssue.jar - Executable to run the program</li>
<li>testpdfs - Contains template pdfs which the program is designed</li>




Command to Run:


java -jar extractAuthorIssue.jar < path to folder containing pdfs >

(eg: java -jar extractAuthorIssue.jar /users/Courses/Advance_Software_Engineering/workspace/testpdfs)
