# Security-Scripting-Challenge

As a Security Operations Engineer, you face the challenge of preventing internal information from getting into the hands of unwanted recipients. Google Drive contains a lot of valuable information in various file formats. 

There have been several security breaches where employees have misconfigured file permissions, allowing public access to files containing sensitive information, like corporate and PII data. 

To prevent such incidents, the Security Operations Team has decided to scan every employee's Google Drive account and generate a list of all files that are shared publicly (to anyone with the link), along with the employee's name and email address. The team will then reach out to each employee and ask them if such public sharing is necessary. Based on their response, the team will change the file permissions accordingly.

## The expected minimal deliverables are:
1. A script code, coded in the language of your choice (preferebly Python), that scans a Google Drive account and gets all the files shared publicly with the following information: File Name, File Link, File Location, Owner Of the File.
2. A executable file to run (with no errors) and obtain the asked information.
3. A readme that describes how to run the delivered script.

## Optional deliverables:
4. How would you improve the script to avoid any manual load to the Security Operations Team? Taking into account that the final goal is to avoid data breach in Google Drive.
5. How would you make the script more secure?
