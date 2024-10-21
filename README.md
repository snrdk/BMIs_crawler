# BMIs crawler
A web scraping tool for extracting data from [Business Model Ideas](https://www.businessmodelideas.com). This tool automates the collection of company information such as descriptions and business model components from the site.
This code was used as part of the study, which is currently under review.

🐤 **Related work**: Lee, S. and Lee, H., From Networks to Narratives: Data-driven business model ideation using heterogeneous link prediction, Technovation, Submitted on August 2024.




## Components
* Description: Information about the products and services the company offers.

The collected data includes business model canvas data as:  

<div align="center">
    <img src="https://github.com/user-attachments/assets/da56eee7-64a1-489d-b638-638c179fdc00" alt="Business Model Canvas" width="600"/>
    <p style="font-size: 14px; color: gray;">Image source: Strategyzer</p>
</div>

**Business model canvas data**
* Key Partners: External partners such as suppliers and distributors who help run the business
* Key Activities: The main activities a company must perform to deliver value to customers
* Key Resources: Physical, human, intellectual, and financial resources needed to operate the business model
* Value Propositions: The value of products or services that solve customer problems or satisfy their needs
* Customer Relationships: Interaction methods and relationship management strategies for customer retention
* Channels: Communication and distribution channels used to deliver value and interact with customers
* Customer Segments:Characteristics of the company's target customer groups and segmented customer base
* Cost Structure: Main cost items and characteristics required to operate the business model
* Revenue Streams: The way cash flow is generated from each customer segment and the pricing mechanisms




## Features
The script is organized as follows: 

* **Automated login**: Login to the Business Model Ideas website.
* **Data extraction**: Extract company names and details.
* **Headless browser option**: Optionally run the script in headless mode for background execution.
* **Error handling**: Handles missing data and login errors gracefully.
* **Save data**: Save the collected data as a CSV file named collected_all_data.csv.




## Requirements
* Python: 3.x
* Libraries: BeautifulSoup, selenium, pandas, requests, webdriver_manager
* ChromeDriver
* Subscription account is required.
