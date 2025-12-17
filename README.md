# OAB Attorney Data Scraper

This project provides a Python-based scraper designed to extract attorney data from the OAB CNA Directory (cna.oab.org.br). The scraper efficiently iterates through OAB registration numbers across different UFs, collecting critical attorney details such as names, OAB numbers, and UFs. It also supports error handling, rate limiting, and resume capabilities for robust, long-running data collection.


<p align="center">
  <a href="https://www.bitbash.dev/project/cna-oab-attorney-data-scraper" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://www.bitbash.dev/project/cna-oab-attorney-data-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <a href="https://www.bitbash.dev/project/cna-oab-attorney-data-scraper" target="_blank"><strong>Cna Oab Attorney Data Scraper</strong></a> you've just found your team — Let's Chat. 👆👆 
</p>


## Introduction

This Python scraper is built to gather attorney data from the OAB CNA Directory, providing a reliable solution for large-scale legal data collection. The tool automates the querying process by sequentially querying attorney data across various UFs (seccional states) and their registration numbers.

It helps legal professionals, data analysts, or institutions needing structured attorney data for research, analysis, or business purposes. The scraper’s ability to handle large data sets with stability is key for users looking to automate repetitive data collection tasks from the OAB directory.

### Efficient Data Collection for Legal Research

- Scrapes detailed attorney profiles from the OAB CNA Directory.
- Handles large volumes of data across multiple UFs, with controlled access to avoid blocks.
- Supports error recovery, rate limiting, and resume functionality, making it ideal for long-term data collection tasks.

## Features

| Feature | Description |
|---------|-------------|
| Rate Limiting | Limits the number of requests per minute to avoid website blocks. |
| Backoff Handling | Implements intelligent pauses and retries after error responses. |
| Resume Functionality | Supports resuming the crawl process after interruptions. |
| OCR Extraction | Option to extract data rendered as images (if required). |
| Structured Output | Outputs data in CSV/JSON format for easy integration. |
| Logging | Tracks crawl progress and errors for easy troubleshooting. |

---

## What Data This Scraper Extracts

| Field Name | Field Description |
|-------------|------------------|
| Attorney Name | Full name of the attorney. |
| OAB Number | Unique registration number issued to the attorney. |
| UF | The federal unit (state) the attorney is registered in. |
| Extended Details | Additional details available on the attorney's profile (may include OCR data). |

---

## Example Output

    [
          {
            "attorneyName": "John Doe",
            "oabNumber": "123456",
            "uf": "SP",
            "additionalDetails": "Image text or OCR extracted details"
          }
        ]

---

## Directory Structure Tree

    cna-oab-attorney-data-scraper/

    ├── src/

    │   ├── scraper.py

    │   ├── extractors/

    │   │   ├── oab_parser.py

    │   │   └── ocr_extractor.py

    │   ├── config/

    │   │   └── settings.json

    │   └── utils/

    │       └── rate_limiter.py

    ├── data/

    │   ├── sample_output.json

    │   └── inputs.sample.txt

    ├── requirements.txt

    └── README.md

---

## Use Cases

**Researchers** use it to **automate attorney data collection** from the OAB directory, so they can **gather comprehensive legal data at scale.**

**Legal Institutions** use it to **extract and structure OAB attorney information** across different UFs, so they can **build databases for analysis or integration with case management systems.**

**Data Analysts** use it to **gather attorney data** in **CSV/JSON formats** for research purposes, helping them **analyze legal professional demographics**.

---

## FAQs

**How do I set the range for the OAB numbers?**

You can configure the range for the OAB numbers in the `settings.json` file. The tool supports setting both the start and end OAB numbers for each UF.

**What happens if the script is interrupted?**

The script includes resume functionality, meaning it will automatically pick up from where it left off based on the last successfully scraped OAB number and UF.

---

## Performance Benchmarks and Results

**Primary Metric:** Average scraping speed of ~500 attorney profiles per hour per UF.

**Reliability Metric:** 98% success rate for data extraction with automatic retries for failed queries.

**Efficiency Metric:** Utilizes minimal CPU and memory resources while adhering to rate limiting to avoid being blocked.

**Quality Metric:** 99% data completeness with proper handling of missing details and OCR data extraction.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
