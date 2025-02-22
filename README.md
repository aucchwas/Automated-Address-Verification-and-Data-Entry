<div align="center">

# Automated Address Verification and Data Entry

<p id="intro">Automated Address Verification and Data Entry automates the process of verifying the authenticity of addresses for room service eligibility and retrieving detailed specifications across multiple websites. Utilizing Selenium for web automation and GPT for handling missing data, Automated Address Verification and Data Entry significantly reduces manual effort in data entry tasks.</p>

### Supported Platforms

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()

---

</div>

## Table of Contents 📝

- [Features and Benefits](#features-and-benefits-)
- [Use Cases](#use-cases-)

- [Usage](#usage)

## Features and Benefits ✨

- **Automated Address Lookup**: Seamlessly searches and verifies addresses across Zillow, Trulia, Apartments.com, and Redfin.
- **Detailed Address Specifications**: Automatically retrieves specific details such as building type, complex address, units count, buildings count, apartment availability, complex name, URL, apartment alternate address, and comments.
- **Web Automation with Selenium**: Efficiently interacts with web pages, mimicking manual search tasks to collect and verify data.
- **Handles Missing Information**: Utilizes a reverse-engineered GPT model to predict missing address data when websites do not provide complete information.
- **Customizable and Scalable**: Easily adaptable to include additional websites or other data verification tasks.
- **Time-Saving**: Drastically reduces the time spent on repetitive data entry by automating the entire process.
- **Error Reduction**: Minimizes human error by automating the verification and data entry process.
- **Seamless Integration**: Combines web scraping and AI to ensure accuracy and reliability in data collection.

## Use Cases ✅

- **Data Entry Automation**: Ideal for businesses or individuals needing to verify large lists of addresses quickly and accurately, along with detailed specifications.
- **Room Service Eligibility Verification**: Ensures addresses qualify for room service by cross-referencing multiple reliable sources.
- **Real Estate Data Collection**: Gathers comprehensive details about properties, including availability, building type, and more.
- **Scalable Web Scraping**: Can be adapted for scraping other types of data from various websites.
- **Data Completeness**: Uses AI to predict and fill in missing information, ensuring complete data sets.
- **Customized Data Verification**: Suitable for any task requiring verification of information and detailed specifications across multiple online sources.

---
## Usage

- **Step 1:** Install required libraries.

```bash
pip install -r requirements.txt
```

- **Step 2:** Store input as `data.xlsx` in `input` directory.

- **Step 3:** Run `nexaauto.py` in terminal

```bash
python nexaauto.py
```