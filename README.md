# Resume-Web-Parser

Overview
This simple project harnesses the scripting power of Python to scrape information from a specified website. The main goal is to streamline the process of filling in a cover letter with the relevant details about a company and job role.

Features
Web Scraping: Utilizes Python's web scraping capabilities to extract information from a designated website.

Dynamic Cover Letter: Allows for the automated generation of a cover letter by populating placeholders with company-specific details.

How to Use
Install Dependencies:
Make sure you have the necessary Python libraries installed. You can install them by running:
pip install requests bs4 python-docx

Run the Script:
Execute the program by running:
python3 app.py

The terminal will ask for the URL of the website that you are applying through.

Generated Cover Letter:
This program assumes that you have a cover letter already created that needs to be filled in with information specific information, job title, company name, etc... To do this, find the path on your local machine that contains a default cover letter and that has '{' '}' as placeholders. Change the code as necessary towards your cover letter. e.g. change "NAME OF COMPANY" to whatever placeholder you already have.

Example
Suppose you want to generate a cover letter for a software engineering internship at Amazon. Provide the Amazon job posting URL when prompted, and the script will fill in a cover letter tailored to that specific role.

Feel free to customize the script and adapt it to your needs!

Author
Ashton
