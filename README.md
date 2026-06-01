# CDS Shop Automation Project

This repository contains a **Selenium automation project** for interacting with a demo e-commerce site (CDS Shop). The project is organized as a set of practical web automation tasks, such as logging in, placing orders, scraping product data, and handling special events like flash sales.

## Project Description

The goal of this project is to practice and demonstrate skills in **web automation** and **browser scripting** using Selenium in Python. The code is structured as a Jupyter Notebook (`mini_proj1.ipynb`) with clear step-by-step tasks.

By completing this project, you will learn how to:

- Automate login and form filling on websites
- Navigate multi-page product listings
- Scrape and process product data (names, prices, quantities)
- Simulate typical e-commerce flows: add to cart, checkout, and payment
- Handle special scenarios like captchas (using OCR) and flash sales under time constraints
- Interact with dynamic web elements and browser tabs

## Main Features

- **Selenium WebDriver** automation with Chrome
- Example solutions and code templates for:
  - **Login automation**
  - **Placing orders for specific products**
  - **Bulk product data scraping**
  - **Automated checkout and payment (captcha included)**
  - **Flash sale participation (bonus task)**
- Designed for educational use in web automation and software testing courses

## Tasks Overview

1. **Task 0: Login (Demo)**
   - Automate the login process for the CDS Shop using test credentials.

2. **Task 1: Place an Order**
   - Find and order 5 units of the last product in the shop.

3. **Task 2: Scrape Products by Stock**
   - Find and record all products with at least 20 units in stock.

4. **Task 3: Buy the 10 Most Expensive Products**
   - Find, add, and purchase the 10 priciest items, with captcha handling during payment.

5. **Task 4: Flash Sale (Bonus)**

      During the flash sale, one random product will receive a discount. Your task is to detect which product it is, place an order for that product, and complete the payment.
   - Schedule:
      - The flash sale starts at 11:00 p.m.
      - The discounted product will appear at a random time between 11:00 p.m. and 11:10 p.m.
   - Quotas:
      - 500 units on 16/10
      - 150 units on 21/10
      - 30 units on 23/10
   - Preparation:
      - Fetch and save all product prices in advance.
      - If you don’t have enough time to fetch all prices, note that on the first day the discounted product will appear on the first page. As a fallback, you can save a screenshot of the first page to record product prices for your first attempt.

   - Ordering and payment:
      - You must complete payment; only paid orders will be counted. Delivery will be arranged based on the payment time.
      - The order must contain only the flash sale product. If your order includes more than one product, it will not be considered.
   - Confirmation:
      - A successful order will display “Delivered” information as shown below.
   ![alt text](image.png)

## Technologies Used

- **Python 3**
- **Selenium WebDriver**
- **ddddocr** (for captcha recognition)

## Setup Instructions

1. **Install dependencies:**
   ```bash
   pip install selenium ddddocr
   ```
2. **Download ChromeBrowser** 
3. **Clone or download** this repository.
4. **Open `mini_proj1.ipynb`** in Jupyter Notebook or VS Code.
5. **Replace demo credentials** with your own test account for the CDS Shop.
6. **Run and modify** notebook cells as required by your assignment.

## Educational Use

This project is intended for students learning web automation, QA automation, or software testing. **Do not** use this code for unauthorized automation on real commercial sites.

---

**For questions, please contact TA(paklonip).**