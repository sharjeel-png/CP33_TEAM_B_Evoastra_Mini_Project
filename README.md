# 🕸️ CP33_TEAM_B_Evoastra_Mini_Project

### Evoastra Data Science Internship – Mini Project (October 2025)
Web Scraping Mini Project by Team B (CP33) under Evoastra Data Science Internship — extracting and analyzing Honda car data from Cars24.com using Python, Selenium, and Pandas.

---

## 📘 Project Title
**Web Scraping Car Details from Cars24.com using Selenium**

---

## 🎯 Objective
The goal of this mini project is to **gain practical experience with automated web scraping** using **Selenium WebDriver** to extract structured car data from [Cars24.com](https://www.cars24.com/).  

**Team B (CP33)** is assigned to focus on the **Honda** brand, scraping car listings from the **Mumbai** location.  

By the end of this project, interns will have:  
- Automated browser control with Selenium  
- Extracted structured data from dynamically loaded web pages  
- Cleaned and organized data using Pandas  

---

## 🧩 Project Requirements

### 1️⃣ Scraping Target
Cars listed on **Cars24.com** from **three locations**, primarily **Mumbai**.

### 2️⃣ Data to Collect
| Field | Description |
|:--|:--|
| Kilometers Driven | Distance traveled by the car |
| Year of Manufacture | Model year of the car |
| Fuel Type | Petrol / Diesel / CNG / Electric |
| Transmission | Manual / Automatic |
| Price | Listed price of the car |

### 3️⃣ Brand Assignments
| Team | Brand |
|:--|:--|
| Team A | Toyota |
| **Team B** | **Honda 🏎️** |
| Team C | Hyundai |
| Team D | Maruti Suzuki |
| Team E | Tata |
| Team F | Ford |
| Team G | Mahindra |

---

## 🧠 Steps Followed

### 1️⃣ Research and Planning
- Analyzed the **structure and behavior** of Cars24.com using browser developer tools.  
- Identified HTML elements and **XPath locators** for data extraction.  

### 2️⃣ Data Extraction (Using Selenium)
- Used **Selenium WebDriver** with Python to automate browsing and scrape car details.  
- Collected key fields:
  - Kilometers Driven  
  - Year of Manufacture  
  - Fuel Type  
  - Transmission  
  - Price  

### 3️⃣ Data Cleaning (Using Pandas)
- Cleaned and formatted the scraped data.  
- Removed duplicates and missing entries.  
- Converted extracted lists into structured tabular format.  

### 4️⃣ Data Storage
- Exported final structured data into a **CSV file** for analysis and reporting.  



---

## ⚙️ Tools & Libraries
- **Python 3.x**
- **Selenium**
- **ChromeDriver**
- **Pandas**
- **Jupyter Notebook / Google Colab**

---

# 🔄 Data Extraction Process

## **Technical Implementation**
- Built Selenium-based scraper with intelligent scrolling for dynamic content
- Developed robust CSS selectors for multi-field data extraction
- Implemented headless browser automation with anti-detection measures

## **Data Processing**
- Created advanced parsers for kilometers and price conversion
- Standardized transmission (Auto/Manual) and fuel type formats
- Extracted brand/model from names and calculated vehicle age

## **Quality Assurance**
- Removed duplicates and validated data ranges
- Maintained 100% data completeness with 0 missing values
- Applied ethical scraping practices with rate limiting

## **Results**
- Successfully extracted 196 Honda vehicles from Cars24 Mumbai
- Delivered cleaned dataset with parsed numerical values
- Generated analysis-ready CSV files for market insights 

---

## 🔍 Learnings
- Learned to automate browser operations using **Selenium WebDriver**.  
- Gained practical understanding of **dynamic content scraping** using XPath and explicit waits.  
- Improved teamwork through regular collaboration in Google Meets.  
- Enhanced data organization and cleaning skills using **Pandas**.  
- Developed awareness of **ethical web scraping practices** and performance optimization.  

---
# ⚠️ Challenges & Solutions

## **Technical Challenges**
- **Dynamic Content Loading**: Pages loaded content progressively via scrolling
- **Price Format Variability**: Multiple price formats and display patterns
- **Anti-Bot Detection**: Website protection against automated scraping

## **Solutions Implemented**
- **Intelligent Scrolling**: Developed multi-pass scrolling with content detection
- **Multi-layer Parsing**: Created fallback strategies for price extraction
- **Stealth Configuration**: Configured browser options to avoid detection

## **Data Quality Issues**
- **Inconsistent Formatting**: Varied kilometer and price representations
- **Duplicate Listings**: Multiple entries for same vehicles
- **Missing Model Information**: Incomplete car naming patterns

## **Data Processing Solutions**
- **Regex-based Cleaners**: Built specialized parsers for each data type
- **Duplicate Removal**: Implemented multi-column deduplication logic
- **Model Extraction**: Created known-model lookup system for classification
---

## 📊 Honda Used Car Market Insights (Based on Scraped Data)

Analysis of scraped Honda car listings from Cars24.com reveals several key market trends:

### 🏆 The Undisputed Value King: Honda City
- The Honda City is the most listed model in the used car market
- It commands the highest resale prices among Honda's lineup

---

## 📦 Deliverables

| Deliverable | Description |
|:--|:--|
| **1️⃣ Python Notebook (.ipynb)** | A well-documented Jupyter Notebook containing Selenium-based scraping code. |
| **2️⃣ Presentation File (PDF)** | A concise presentation summarizing objectives, workflow, challenges, and key results. |
| **3️⃣ Project Report (.MD)** | A report explaining methodology, Selenium automation steps, challenges faced, and insights gained. |

## 📅 Project Timeline

| Date | Event | Time |
|:--|:--|:--:|
| **17th October 2025** | 1st Google Meet – Initial discussion, project planning | 🕛 12:00 PM |
| **18th October 2025** | 2nd Google Meet – Progress review & code discussion | 🕚 11:00 AM |
| **18th October 2025** | 3rd Google Meet – Final review & presentation planning stage 1 | 🕣 08:30 PM |
| **19th October 2025** | 4rd Google Meet – Final review & presentation planning stage 2 | 🕣 11:30 AM |

---

## 👥 Team Members
**Team B – CP33**  
- **MOHAMMAD SHARJEEL YAZDANI** – Team Lead
- **Rishabh Tanpure** – Co-Lead 1  
- **Samradnyi Kale** – Co-Lead 2
- **Sakshi Giglani** – Member
- **MONU KUMAR JHA** – Member
- **Sriya Sahu** – Member
---

## 🏢 Organization
**Evoastra Data Science Internship Program – 2025**  
🔗 [https://www.evoastra.in](https://www.evoastra.in)

---

## 🧾 License
This repository is intended for **academic and internship learning purposes** under **Evoastra**.  
Unauthorized redistribution or commercial use of scraped data is strictly prohibited.

---

