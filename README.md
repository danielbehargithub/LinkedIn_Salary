# LinkedIn Data Scraper

## Overview
This project allows users to extract data from LinkedIn profiles and job postings. By providing LinkedIn credentials and URLs, users can fetch skills, certifications, and other profile details. The project also supports job scraping for descriptions, locations, and other related data.

---

## Prerequisites

1. **Python**: Ensure Python 3.7 or higher is installed.

2. **Dependencies**:  
   Install the required Python packages:
   ```bash
   pip install playwright beautifulsoup4 nest_asyncio
   playwright install
   ```

3. **NGROK (Optional)**: If using the web interface with LinkedIn authentication:
   - [Download and set up NGROK](https://ngrok.com/download).
   - Generate an authentication token from NGROK's dashboard.
   - Install NGROK on your system:
     ```bash
     ngrok authtoken <your_auth_token>
     ```

---

## Usage

### 1. Scraping LinkedIn Profiles
1. Open the `profile_data.py` script.
2. Input your LinkedIn credentials and the profile URL(s) you wish to scrape.
3. Run the script to save HTML files for each section.

### 2. Scraping Job Postings
1. Open the `job_data.py` script.
2. Input the job posting URL(s).
3. Run the script to extract job-related details.

### 3. Running the Web Interface
1. Open the `web_interface.py` script.
2. Start the Flask server by running:
   ```bash
   python web_interface.py
   ```
3. Copy the NGROK URL (if applicable) and share it for remote access.

---

## Notes
- **Privacy**: Ensure all LinkedIn credentials are securely managed and not hardcoded in public repositories.
- **API Limitations**: LinkedIn APIs may have rate limits and restrictions on accessing certain data.

---

## Disclaimer
This project is for educational purposes only. Ensure compliance with LinkedIn’s terms of service and obtain user consent before scraping data.
