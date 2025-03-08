# Web Traffic Analysis Using Google Analytics (GA4)  
**Website:** [https://challa-obulesh.github.io/personalwebsite.github.io/](https://challa-obulesh.github.io/personalwebsite.github.io/)

---

## 📌 Project Overview

This project focuses on analyzing website traffic, user behavior, and engagement metrics using **Google Analytics 4 (GA4)**. By implementing GA4 on your personal portfolio website hosted on GitHub Pages, you can gain insights that help improve performance, enhance user experience, and optimize marketing strategies.

---

## 🔹 Step 1: Set Up GA4 for Your Website

### 1️⃣ Create a Google Analytics Account  
- **Go to:** [Google Analytics](https://analytics.google.com/)  
- **Action:** Click **"Start Measuring"**  
- **Input:** Enter an Account Name (e.g., *"My Portfolio Website"*)  
- **Proceed:** Click **Next**

> *Screenshot Reference: See uploaded images showing the "Start Measuring" button and account creation steps.*

### 2️⃣ Create a GA4 Property  
- **Input:** Enter a Property Name (e.g., *"Obulesh Portfolio Analytics"*)  
- **Configuration:**  
  - Set Time Zone (e.g., India: UTC+5:30)  
  - Choose Industry → Technology (optional)  
- **Action:** Click **Next** then **Create**

> *Screenshot Reference: Uploaded images highlight the property creation screens.*

### 3️⃣ Set Up a Web Data Stream  
- **Select:** Web (for a website)  
- **Input:**  
  - Website URL: [https://challa-obulesh.github.io/personalwebsite.github.io/](https://challa-obulesh.github.io/personalwebsite.github.io/)  
  - Stream Name: e.g., *"Portfolio Website"*  
- **Action:** Click **Create Stream**  
- **Note:** Copy the **Measurement ID** (e.g., `G-XXXXXXXXXX`) for later use.

> *Screenshot Reference: See images that detail the data stream setup and Measurement ID.*

---

## 🔹 Step 2: Install GA4 Tracking Code on Your Website

Since your website is hosted on GitHub Pages, follow these steps:

1. **Open Your Repository:**  
   - Navigate to your GitHub repository for your website.
2. **Edit HTML Files:**  
   - Open `index.html` (or all relevant pages).
3. **Insert GA4 Tracking Code:**  
   - Add the following code snippet inside the `<head>` section:
   
   ```html
   <!-- Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());
   
     gtag('config', 'G-XXXXXXXXXX'); // Replace with your Measurement ID
   </script
Step 3: Verify GA4 is Working
Open GA4 Dashboard:
Log in to Google Analytics.
Navigate to Realtime Report:
Click Reports → Realtime. 
Test Your Site:
Open your website in a new tab.
Confirm that real-time user data appears in GA4.
Step 4: Analyze Your Website Traffic
After waiting 24-48 hours for GA4 to collect data, you can explore various reports:

Acquisition Analysis
Goal: Identify how users are finding your website (organic, direct, referral, or paid search).
Action: Review the Traffic Acquisition report.
Engagement Analysis
Goal: Understand user behavior on your website.
Key Metrics: Bounce rate, average session duration, pages per session.
Action: Check the Engagement → Pages and Screens report.
Demographics Analysis
Goal: Learn about your audience's age, gender, and location.
Action: Explore the Demographics → Overview report.
🚀 Installation & Usage Summary
Set Up GA4:
Create an account, property, and data stream.
Install Tracking Code:
Insert the GA4 tracking snippet in your website's <head> and push changes.
Verify Setup:
Check the Realtime report in GA4.
Analyze Data:
After data collection, review acquisition, engagement, and demographics reports.
📢 Project Results & Impact
By integrating GA4 with your personal website, you can:

Improve Marketing Strategies: Identify and leverage key traffic sources.
Enhance User Engagement: Optimize content based on user behavior data.
Boost Website Performance: Use data-driven insights to reduce bounce rates.
Inform Business Decisions: Rely on comprehensive analytics to guide improvements.
