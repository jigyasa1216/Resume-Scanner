# Resume-Scanner
This project is made for MLH NIT Raipur Hackathon October 2021. It is made with Python and NLP.
# WHAT IS RESUME SCANNER? 

**The main objective of this Resume Scanner is to analyse the Resume of the student and to compare it with the company's requirments**

It is completely built using **Python language**. The steps involved in Scanning the resume are following: 

- First the student has to upload their Resume. The Resume uploaded in the **PDF** format is converted into a **txt** file. 
- Then, the text file is scanned and the **keywords** from the file are extracted. **key_phrases.py** 
reads the complete file and the keywords are pointed out. Now the key words are given a Polarity value based on which the student is examined. 
- The Student's qualification is then compared with the Company's **requirements**.

-   If the student's qualifications match with the company's requirments, the student is taken to the **CHATBOT** of the company. **chat.py** is a scalable lightweighted chat which acts as a medium between the company and the student. The Chat Bot is an interactive bot w
which gives information about the company and informs the student about the interview and other things. 
 - A mail is automatically sent to the student regarding the performance and tells the candidate if they are eligble to attend an interview or not. 
 
 - **automail.py** is an easy mail sending software developed in python which is used to send mails automatically to the respective candidate.
 
# WHERE CAN RESUME SCANNER BE USED? 
 
Resume Scanner can be used by Universities and Companies. This software automates the process of Job hiring. 
 
In colleges this can be used in a larger scale since it would be easier for the Placement Cell to assign each student's to the appropriate company. 
 
# TOOLS
- Python
- html css js
- Flask
