### Exploit Title: Stored Cross Site Scripting(XSS) vulnerability in Egavilan Media Resumes Management and Job Application Website v1.0
Date: 2020-12-27

Exploit Author:  Kshitiz Raj(manitorpotterk)

Vendor Homepage: https://github.com/EGavilan-Media/Resumes-Management-and-Job-Application-Website-with-PHP-Bootstrap-and-MySQL

Software Link: https://github.com/EGavilan-Media/Resumes-Management-and-Job-Application-Website-with-PHP-Bootstrap-and-MySQL

Version: 1.0

Tested on: Windows 10/Kali Linux

POC

Step 1- Go to url http://localhost/Resumes/

Step 2 - Fill the <script>alert(1)</script> in First Name and Last Name in Apply For This Job Section

Step 3- Go to http://localhost/Resumes/login.html and login as admin

Alert pop will get executed.
