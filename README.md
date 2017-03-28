# AdvanceSoftwareEngineering
The repository contains documents related to Advance Software Engineering submissions

pdfrenamer is a program which extracts below mentioned information from pdf files

Authors: One-author-name consists of [First Middle* Last], list of author names is comma separated. Ex: Umme Ayda Mannan, Iftekhar Ahmed, Rana Abdullah M Almurshed, Danny Dig, Carlos Jensen. This example has 5 authors.
Issue: Usually a number. Some times a name. Ex: "3" "March"

Sample pdfs are placed in the folder testpdfs. 
The program works only if the pdfs are in the same format as sample pdfs placed in the testpdfs folder 


Reviews - Contains review comments for various documents submitted by other team in the course.
pdfrenamer-v1.0 - Source code in Java
extractAuthorIssue.jar - Executable to run the program
testpdfs - Contains template pdfs which the program is designed for



Command to Run:
java -jar extractAuthorIssue.jar <path to folder containing pdfs> (eg: /users/Courses/Advance_Software_Engineering/workspace/testpdfs)
