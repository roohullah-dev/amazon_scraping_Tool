Amazon Automation Tool

A powerful Amazon product scraper built using Python and Selenium, designed to extract high-value product data including titles, prices, bullet points, ASINs, shipping info, and
images—automated across multiple pages with smart human-like delays and captcha detection handling.

🧰 Features

🔍 Search Page Automation
  Navigates Amazon search pages and visits product listings automatically.
📦 Detailed Product Extraction
  Extracts:
  * Title
  * Full description
  * Bullet points
  * Price and shipping
  * ASIN and part number
  * Material and color
  * High-quality product image URLs

1) 🔁 Pagination Support
  Scrapes through up to N-number of pages per session automatically.
2) ⚙️ Smart Captcha Detection
  Detects Amazon captchas and stops execution safely.
3) ✅ Duplicate ASIN Check
  Prevents scraping of already existing ASINs stored in `amazon_products.csv`.
4) 📍 Auto ZIP Code Setup
  Automatically sets a custom ZIP code for location-specific results.
5) 💾 Data Export to CSV
  All scraped data is exported in a well-structured CSV format.
6) 🧠 Human-like Delays
  Adds random sleep timers to avoid bot detection.
7) 🪪 Cookie Loader
  Loads stored cookies for smoother browsing and login bypass.

🛠️ Technologies Used

* Python 3.9+
* Selenium WebDriver
* Chrome WebDriver (Headed)
* CSV, JSON, Pickle, Logging Modules
* XPath / CSS Selectors for Precision Scraping

📁 Output Example (CSV Columns)

| Title | Description | Image URLs | Price | ASIN | Part Number | Shipping Price | Bullet Points | Material | Color |
| ----- | ----------- | ---------- | ----- | ---- | ----------- | -------------- | ------------- | -------- | ----- |

🚀 How It Works

1. Sets up a real Chrome browser session with a spoofed user agent.
2. Loads cookies (if available) to reduce login friction.
3. Automatically sets your ZIP code for region-specific data.
4. Visits Amazon's search result pages based on a predefined URL.
5. Scrapes all product details and saves to CSV.
6. Avoids captcha triggers with delays and browser flags.
7. Moves to the next page until the maximum page count is reached.

📸 Sample Use Case
> Need to scrape all cabinet hardware listings under a certain category?
> Just update the search URL and ZIP code—this tool will handle the rest automatically.

📩 Hire Me
Do you need custom automation for Amazon, AliExpress, eBay, or any other e-commerce platform?
💼 I'm available for freelance projects!

📧 Contact Me:

Email: `your-email@example.com`
Fiverr: \[your-fiverr-link]

Let’s automate your next scraping or e-commerce project! 🤖✨
