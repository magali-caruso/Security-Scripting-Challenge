# Security-Scripting-Challenge

As a Security Operations Engineer, you have the challenge to stop internal information from reaching to unwanted recipients. There is a lot of valuable information gathered in Google Drive in all kind of file formats. 

There has been a lot of security incidents related to employees misconfiguring file permissions and allowing public access to internal files with corporate and PII information in it. 

We, as the Security Operations Team, want to scan each employee Google Drive account and get a list of all the files shared publicly (To anyone with the link) along with the employee name and email. After this we will ask each of them if the public-sharing is needed and then proceed to change the permissions accordingly. 

## The expected minimal deliverables are:
1. A script code, coded in the language of your choice (preferebly Python), that scans a Google Drive account and gets all the files shared publicly with the following information: File Name, File Link, File Location, Owner Of the File.
2. A executable file to run (with no errors) and obtain the asked information.
3. A readme that describes how to run the delivered script.

## Optional deliverables:
4. How would you improve the script to avoid any manual load to the Security Operations Team? Taking into account that the final goal is to avoid data breach in Google Drive.
5. How would you make the script more secure?
