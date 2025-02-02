# 🔍 Matching & Salary Recommendation for Your Dream Job

## 🚀 Overview
This project allows users to extract data from LinkedIn profiles and job postings to:
- Calculate a **matching score** between their skills and job requirements.
- Estimate a **salary range** based on their skills and match score.

💡 **Two Ways to Use This Tool:**
- **Automated**: Provide LinkedIn credentials for direct data extraction.
- **Manual**: Upload exported HTML files from LinkedIn (for privacy-conscious users).

---

## ⚡ Quick Start

- 📌 **Run in Google Colab** → No installation needed!
- 🛡️ **Privacy** → Credentials are not stored or shared.
- 📊 **Outputs** → Matching Score & Salary Estimate.

---

## 🖥️ Environment
- Google Colab (click `.ipynb` file for link)
- No local installations required

---

## 📌 **Step 1: Scrape LinkedIn Profile & Job Data**

### **Option 1: Automated Scraping (With Credentials)**

1. Open **`Profile_Data.ipynb`** in Google Colab.
2. Enter:
   - **LinkedIn Email**: `your_email@example.com`
   - **LinkedIn Password**: `your_password`
   - **LinkedIn Profile URL**: `https://www.linkedin.com/in/your-profile-id/`
   - **Job URL**: `https://www.linkedin.com/jobs/view/job_number/`
3. Click `Runtime → Run all`.
4. **Outputs**:  
   ✅ `profile_data.txt` (LinkedIn profile)  
   ✅ `job_details.txt` (Job posting)  

### **Option 2: Manual Upload (No Credentials Needed)**

1. Open **`Profile_Data_Without_Auth.ipynb`** in Google Colab.
2. Upload your saved LinkedIn **HTML files**:
   - **Experience**
   - **Education**
   - **Skills**
3. Enter the **Job URL**: `https://www.linkedin.com/jobs/view/job_number/`
4. Click `Runtime → Run all`.
5. **Outputs**:  
   ✅ `profile_data.txt` (LinkedIn profile)  
   ✅ `job_details.txt` (Job posting)  

---

## 📊 **Step 2: Get Matching Score & Salary Estimate**
1. Open **`Wage_and_Similarity.ipynb`** in Google Colab.
2. Upload the extracted files:
   - `profile_data.txt`
   - `job_details.txt`
3. Click `Runtime → Run all`.
4. **Outputs:**
   - 📌 **Matching Score** → % match & skill improvement suggestions.
   - 💰 **Salary Range** → Estimated based on skills & job market data.

---

## 🔐 Security Considerations
- **Credentials are used locally** and never stored/shared.
- If concerned, use the **manual upload method**.

---

## 💾 **Saving LinkedIn HTML Pages (Manual Method)**
1. Open your LinkedIn **Skills Page**.
2. Press `Ctrl + Shift + I` (or `Cmd + Option + I` on Mac) → Open Developer Tools.
3. Right-click `<html>` → `Save As...` → Choose **"Web Page, HTML Only"**.
4. Upload the `.html` file when running the script.

---

## 📢 **Disclaimer**
This project is for **educational purposes only**.  
It does not store user data, nor does it guarantee accuracy in salary estimation.

---

## 🎯 **Future Enhancements**
- ✅ Add support for **more job platforms** (e.g., Indeed, Glassdoor).
- ✅ Improve **salary model accuracy** using real-time job market data.
- ✅ Build a **browser extension** for LinkedIn scraping.

---


