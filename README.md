# LinkedIn Data Scraper

## Overview
This project allows users to extract data from LinkedIn profiles and job postings. By providing LinkedIn credentials and URLs, users can fetch skills, certifications, and other profile details. The project also supports job scraping for descriptions, locations, and other related data.

---

## Enviroment
Run scripts in Google Colab (click ipymb file to find link to colab). No previous downloads or installations are needed if running the provided scripts in Google Colab.

---

## Instructions

### 1. Scraping LinkedIn Profile
1. Open the `profile_data.py` script.
2. Input your LinkedIn credentials (email and password) and the URL of your LinkedIn profile in the script.
* Note about privacy in end of text

**Example input:**

* LinkedIn Email: your_email@example.com
* LinkedIn Password: your_password
* LinkedIn Profile URL: https://www.linkedin.com/in/your-profile-id/

4. Run the script to process the profile URL and extract the list of skills. The output will be a complete list of skills found on the LinkedIn profile.

### 2. Scraping Job Postings
1. Open the `job_data.py` script.
2. Input the job posting URL(s).
3. Run the script to extract job-related details.

### 3. To be continued

## Notes
- **Privacy**: Ensure all LinkedIn credentials are securely managed and not hardcoded in public repositories.
- Your LinkedIn credentials and URL are used locally and are not shared with any third party. This ensures the security of your personal information. The script is run locally or on Colab, so you maintain full control of your data.
  
## Optional Alternatives
If you prefer not to input your LinkedIn credentials, alternative methods can be explored:

1. Manually Download HTML: Use your browser to save the HTML of your LinkedIn profile (skills) and upload it for processing.

2. LinkedIn allows downloading your profile data directly. Use this method to retrieve skills and other profile details.

* This methods will be limited as in comparision to the way recomended.
  
# Disclaimer
This project is for educational purposes only.


## Quick Guide to Downloading Your LinkedIn Data 
LinkedIn allows users to download their profile data directly. Follow these steps:

Log in to Your LinkedIn Account:

Sign in to your LinkedIn account.
Go to Settings:

Click on your profile picture in the top-right corner.
Select Settings & Privacy from the dropdown menu.
Navigate to Data Privacy:

On the left-hand menu, click Data Privacy.
Request Your Data:

Under "How LinkedIn uses your data" section, click "Get a copy of your data".

Choose "Want something in particular?", and check all boxes.

Click Request archive.
Confirm Your Request:

LinkedIn will prompt you to enter your password for verification.
You’ll receive an email with a download link within a few minutes to a few hours.

## Quick Guide to Saving the HTML of the Skills Page
Saving the HTML of the Skills page allows you to process your data locally. Here’s how:

Open the Skills Page:

Go to your LinkedIn profile and click on Skills.

Alternatively, use the URL https://www.linkedin.com/in/your-profile-id/details/skills/.

Open Developer Tools:

Press Ctrl + Shift + I (or Cmd + Option + I on Mac) to open the developer tools.
Alternatively, right-click anywhere on the page and select Inspect.
Save the HTML:

Click on the first <html> tab and Press Ctrl + S (or Cmd + S on Mac).
Choose where to save the file, and ensure the file type is set to Web Page, HTML Only.

Click Save.
Verify the File:

Open the saved file in a text editor (like Notepad or VS Code) to confirm that all the desired content is included.
