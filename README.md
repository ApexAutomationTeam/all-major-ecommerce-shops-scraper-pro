# all-major-ecommerce-shops-scraper-pro
Universal Chrome extension for scraping products, prices, and PDP data across Amazon, AliExpress, Alibaba, 1688, Daraz, eBay, Temu, Walmart, Etsy &amp; more. Engineered with AI-resilient architecture by Apex Automation Team.


# 🛒 All Major E-Commerce Shops Scraper Pro

> 💡 **Community Project**: This enterprise-grade Chrome extension is open-sourced and provided for free as part of our automation initiatives by **[Apex Automation Team](https://apexautomationteam.com/)**. Visit our official website for custom AI agents, browser automation tools, and automated enterprise workflows.

An all-in-one, multi-platform Chrome Extension designed to scrape product catalogs, search listings, and deep Product Detail Pages (PDP) across all major global e-commerce and wholesale marketplaces.

---

## 🌐 Supported E-Commerce Marketplaces

The extension includes built-in specialized scrapers and also PDP as well as PLP extractors for:
* **Amazon** (`amazon.com`)
* **AliExpress** (`aliexpress.com`)
* **Alibaba** (`alibaba.com`)
* **1688** (`1688.com`)
* **Daraz** (`daraz.pk` / regional)
* **eBay** (`ebay.com`)
* **Temu** (`temu.com`)
* **Walmart** (`walmart.com`)
* **Etsy** (`etsy.com`)
* **DHgate** (`dhgate.com`)
* **Made-in-China** (`made-in-china.com`)

---

## ⚡ Dynamic DOM Architecture & AI-Engineered Resilience

> ⚠️ **Important Notice Regarding E-Commerce Site Updates**:  
> Major e-commerce platforms constantly modify their frontend DOM structures, CSS selectors, obfuscated class names, and anti-scraping protections. Consequently, scrapers can occasionally face broken field extractors when a platform deploys an unannounced frontend redesign.

### How We Solved This:
To make this tool significantly more durable than conventional web scrapers, our core architecture was engineered and refined utilizing **advanced AI reasoning models (Claude (Fable) / Anthropic)**. 

* **Multi-Strategy Fallback Selectors**: Scrapers do not rely on fragile static CSS classes; they dynamically scan semantic attributes, metadata JSON-LD blocks, structured script tags, and fallback XPath hierarchies.
* **Site Detector & Visibility Spoofing**: Built-in background evasion layers prevent scraping interruptions caused by background tab throttles or lazy rendering.
* **Community Contributions & Maintenance**: Developers are welcome to submit pull requests to patch or upgrade selectors if a platform rolls out major breaking layout updates. Alternatively, you can contact **[Apex Automation Team](https://apexautomationteam.com/)**, and our team will issue an updated build.

---

## 📺 Video Demos & Release Assets

Video walkthroughs and setup guides are hosted in our official release section:

* 📦 **[View Official Release & Video Assets](https://github.com/ApexAutomationTeam/all-major-ecommerce-shops-scraper-pro/releases/tag/v3.1.6)**
* 📥 Two zip files of all stores videos, Last time how they worked and their resulted exported scraped xlxvs.Download the video demonstrations directly from the release page to see installation, live product extraction, and export features.

---

## 💻 How to Install & Run Locally in Google Chrome (Step-by-Step)

Because this is an unpacked developer build, follow these simple steps to load it into Chrome:

### 1. Download & Extract the Files
1. Download this repository as a `.ZIP` file (or clone it using Git).
2. Unzip the folder on your local computer so that you see the inner `multi_scraper_ext` directory containing `manifest.json`.

### 2. Enable Developer Mode in Chrome
1. Open Google Chrome and navigate to:  
   `chrome://extensions/`
2. In the top-right corner, toggle **Developer mode** to **ON**.

### 3. Load the Extension
1. Click the **Load unpacked** button that appears in the top-left toolbar.
2. Select the `multi_scraper_ext` folder (the folder containing `manifest.json` and all other files).
3. The extension **"Universal Shop Scraper Pro"** will now appear in your active extensions list.

### 4. Pin & Launch
1. Click the **Extensions puzzle icon (🧩)** in the Chrome toolbar.
2. Pin the extension to your toolbar.
3. Open any supported e-commerce site (e.g., Amazon, AliExpress, or Daraz) and conduct a product search.
4. Click the extension icon in your toolbar to open the control panel, configure page ranges, and start extracting!

---

## 📊 Core Features

* **Listing & PDP Crawling**: Scrapes top-level catalog listings as well as deep-diving into individual Product Detail Pages (PDP) for comprehensive descriptions and specs.
* **Direct Spreadsheets Output**: Built-in in-memory XLSX builder exports data instantly to Microsoft Excel workbooks without external CDN bottlenecks.
* **Persistent Progress Tracking**: Storage handlers maintain task progress in local session storage to prevent data loss across page loads.

---

## 🏢 About Apex Automation Team

We specialize in designing enterprise data collectors, custom web scrapers, browser extensions, and end-to-end AI automation workflows.

* **Official Website:** [https://apexautomationteam.com/](https://apexautomationteam.com/)
* **Custom Scraping & Support Inquiries:** Reach out through our portal for enterprise upgrades, selector maintenance, or tailored scraping solutions.
