# Automated Literature Tagging

Thanks for your interest. This quick guide has been developed to help you apply the Entity Linking Method. 
This section of the method comprises 12 simple steps and covers steps 11 and 12 of our step-by-step guideline published in the Organization Research Methods Journal. 

Step 1)
- Get an authorization token from TagMe. This is easy - just create a new account (called a TagMe VRE account) here: https://sobigdata.d4science.org/web/tagme/tagme-help

Step 2) 
- Download your file from Scopus. After running your Scopus query Click the square next to the "All" button to download all the articles returned by the search string. Then click export. Select CSV / Excel as a method of export and click Abstract and Keywords from the menu on information do you want to export. 

Step 3)
- If you have never ran python code using your computer:
  - Download Anaconda (https://www.anaconda.com/distribution/) which allows you to run python code. 
  - Install Anaconda
  - Launch Anaconda and click on "Jupyter Notebook"
  
 Step 4) 
 - Copy and paste the python code provided to a new notebook
 - Rename the file that you downloaded to "scopus.csv"
 - Move the file to the jupyter folder where you are running your code.
 
 Step 5) 
 - Run the code (by clicking the Play button)
 - Now, wait. It can take 20 minutes for the program to run. You will get constant updates telling you where the program is at with regards to tagging. 
 
 Step 6)
 - The program will create two outputs. One CSV file called "scopus_results.csv" and "scopus_results.txt". 
 - The CSV file will have a new column called Anotations which will contain the tags present in the text.
 - The TXT file will have only the tags present in the text. 
 - You can now check for false positives. False positives are tags that are incorrect - examples of these when using TagMe include ForButNotWith and Library (often mistagged for internet). Rename or delete the false positives. 
 
 Step 7)
 - Within AntConc (https://www.laurenceanthony.net/software/antconc/) you can see the frequency with which tags appear. You can also do this with other tools such as https://voyant-tools.org (which creates word clouds and other nice visualizations). 
 - In AntConc, you can also compare two or more sets of tags. You can do this by:
 
a. Open AntConc

b. Click File / Open File and select the Target file.

c. Click Settings / Tool Preferences and under Category select Keyword List.

d. Click Add file and select your Reference file. Click Load and Apply.

e. Click on Word List and click Start. Click on Keyword List and click Start. 

 
 
 
