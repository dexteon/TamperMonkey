# TamperMonkey Scripts for Instacart Automation

Welcome to the **TamperMonkey Scripts for Instacart Automation** repository! This collection of scripts is designed to enhance your shopping experience on Instacart by automating repetitive tasks and improving navigation and usability. Whether you want to remove ads, automatically sort products, or dynamically load sales pages, these scripts have you covered.

---

## Scripts Overview

### 1. **Instacart Ad Remover**
- **Purpose:** Removes intrusive advertisements on Instacart pages for a cleaner browsing experience.
- **How it works:** The script dynamically scans for ad containers and hides them, ensuring your focus remains on shopping.

---

### 2. **Instacart Automated Sort & Load**
- **Purpose:** Automatically scrolls and loads all items on Instacart sales pages and sorts them by price.
- **How it works:**
  - Continuously scrolls down and clicks the "Load More" button until all items are visible.
  - Sorts products in ascending order of price (low to high).
  - Offers console output to track the script's progress.
- **Features:** 
  - Easy debugging through console logs.
  - Dynamic detection of product containers to accommodate changing page structures.

---

### 3. **Instacart Sales Page Loader & Sorter**
- **Purpose:** Designed specifically for Instacart sales pages. Automates loading all sale items and sorts them by price.
- **How it works:**
  - Scrolls to the bottom of the page multiple times to ensure all items are loaded.
  - Sorts items dynamically by finding the appropriate product container.
- **Debugging:** Logs script progress, errors, and issues to the browser console for easy troubleshooting.

---

## How to Use These Scripts

1. **Install TamperMonkey:**
   - Download and install the [TamperMonkey browser extension](https://www.tampermonkey.net/) for your preferred browser.

2. **Install the Scripts:**
   - Copy the script code for any of the scripts above into a new TamperMonkey script.
   - Save the script, and it will automatically run on the corresponding Instacart pages.

3. **Run the Scripts:**
   - Open the relevant Instacart page (e.g., sales or product category pages).
   - The script will automatically start working based on the page type.

---

## Troubleshooting

### How to Debug
- **Check the Console:**
  - Open the developer console (press `F12` or `Ctrl+Shift+I` and navigate to the "Console" tab).
  - Look for log messages like:
    - "Starting automated loading..."
    - "Scroll attempt X completed."
    - "Sorting products by price..."
  - Errors (if any) will also appear in the console for easier diagnosis.

- **Possible Errors:**
  - `No products found to sort:` Check if the page structure has changed.
  - `Access to storage is not allowed from this context:` This is usually related to browser settings or content restrictions.

---
