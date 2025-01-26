# Salary Recommendation:

## Overview
This project allows users to extract data from LinkedIn profiles and job postings. By providing LinkedIn credentials and URLs, users can fetch skills, certifications, and other profile details.

If you prefer not to provide credentials, alternative methods like uploading HTML files or using LinkedIn’s data export feature are available.

---

## **Environment**
Run scripts in Google Colab (click ipymb file to find link to colab). No previous downloads or installations are needed if running the provided scripts in Google Colab.

---

## Instructions

### 1. Scraping LinkedIn Profile and Job
There are two ways to scrape your LinkedIn's data:
1. Automaticly by providing LinkedIn credentials
2. Manually saving html's of your profile and uploading it.
   
In both ways we will recieve the same result.
In addition, we will scrape your job data that you are interested in.

## Option 1:

1. Open the `Profile_Data.ipynb` script in Google Colab.
2. Click on Runtime -> Run all
3. Input your LinkedIn credentials (email and password), the URL of your LinkedIn profile and the job url in the script.
- **Privacy**: Ensure all LinkedIn credentials are securely managed and not hardcoded in public repositories.
- Your LinkedIn credentials and URL are used locally and are not shared with any third party. This ensures the security of your personal information. The script is run locally or on Colab, so you maintain full control of your data.

#### **Example Input:**
- **LinkedIn Email:** your_email@example.com  
- **LinkedIn Password:** your_password  
- **LinkedIn Profile URL:** `https://www.linkedin.com/in/your-profile-id/`
- **Job URL:** `https://www.linkedin.com/jobs/view/job_number/`

3. You will recieve two files, one for the LinkedIn profile and the other for the job data.

## Option 2:

1. Open the `Profile_Data_Without_Auth.ipynb` script in Google Colab.
2. Click on Runtime -> Run all
3. Input your LinkedIn Html files (experience, education, skills) and the job url in the script.
- Full Guide below
#### **Example Input:**
- **LinkedIn Html:** my.html or my.txt  
- **Job URL:** `https://www.linkedin.com/jobs/view/job_number/`

3. You will recieve two files, one for the LinkedIn profile and the other for the job data.

### 3. To be continued
  
# Disclaimer
This project is for educational purposes only.

## Quick Guide to Saving the HTML Pages
Example: Saving the HTML of the Skills page allows you to process your data locally.

### Same idea for other Html pages.

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

