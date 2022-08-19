# Code on ECL

This folder contains code file. This code file consists of code to use dataset (input files 
of wikitexts), run analyzer (built using NLP engine) on ECL of HPCC systems and code to 
build a record structure of Nepali dictionary.

## Procedure to build record structure of Nepali dictionary using HPCC Systems

Step 1: Start HPCC systems remotely using WSL or virtual machine

	Code: sudo /etc/init.d/hpcc-init start

Step 2: Open ECl watch on browser: http://127.0.0.1:8010/

Step 3: Click on Files icon 

Step 4: Click on Landing Zones

Step 5: Click on upload and upload all the data files on ECL watch

Step 6: Click on "mydropzone..." and select all files that you want to run analyzer on

Step 7: Click on "BLOB" and choose group, queue, and give target name relevant to dataset

Step 8: In BLOB prefix, type "filename,filesize" 

Step 9: Click on "Spray" button

Step 10: It creates a logical file which can be viewed under "Logical Files" menu

Step 11: Once logical file is created click on gear icon followed by Playground to write code

Step 12: Once code is written and is ready to run, click on "Submit button" by choosing target 


