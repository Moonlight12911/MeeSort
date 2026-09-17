<div align="center">
  <img src="assets/icon128.png" alt="MeeSort Logo" width="100" height="100" />
  <h1>MeeSort</h1>
  <p><strong>Bringing Back Price Sorting & Smart Filtering to Meesho</strong></p>
  <p><em>A lightweight, zero-tracking browser extension engineered for value-conscious Meesho shoppers.</em></p>

  <p>
    <img src="https://img.shields.io/badge/Manifest-V3-blue?style=flat-square" alt="Manifest V3" />
    <img src="https://img.shields.io/badge/Platform-Chrome%20%7C%20Edge%20%7C%20Firefox-orange?style=flat-square" alt="Browser Support" />
    <img src="https://img.shields.io/badge/Privacy-100%25%20Client--Side-brightgreen?style=flat-square" alt="Client Side Privacy" />
    <img src="https://img.shields.io/badge/Telemetry-Zero-red?style=flat-square" alt="Zero Telemetry" />
    <img src="https://img.shields.io/badge/Version-1.0.0-purple?style=flat-square" alt="Version 1.0.0" />
  </p>
</div>

---

## 🛑 The Problem: Where Did "Sort by Price" Go?

Meesho is one of India’s most popular e-commerce destinations, beloved by millions of shoppers for its incredible value, wholesale pricing, and budget-friendly products across fashion, home, and daily essentials.

However, shoppers quickly face a major frustration:

> **Meesho removed the standard "Sort by Price: Low to High" and "Price: High to Low" options from its website.**

Without price sorting:
- ❌ **No way to find the lowest price**: Shoppers are forced to scroll past hundreds of randomly ordered products just to find budget-friendly options.
- ❌ **Buried deals**: Bargain finds are scattered across dozens of scroll screens, mixed among higher-priced or sponsored items.
- ❌ **Wasted time & fatigue**: Comparing prices between similar items requires manual scanning and endless tabs.
- ❌ **No price-to-rating balance**: It is nearly impossible to quickly identify items that are both affordable **and** highly rated (★ 4.0+).

Value-conscious shopping shouldn't feel like finding a needle in a haystack.

---

## 💡 The Solution: MeeSort

**MeeSort was built to solve this exact problem.**

Designed specifically for Meesho shoppers, MeeSort seamlessly injects an intuitive, non-intrusive toolbar right above Meesho’s search and category product grids. With a single click, your search results are instantly sorted by price, rating, or discount—without leaving the page, without opening external tabs, and without disrupting Meesho's native layout.

<div align="center">
  <br />
  <strong>Search on Meesho &rarr; Click "Price: Low to High" &rarr; Shop the Best Deals Instantly</strong>
  <br /><br />
</div>

---

## ✨ Features

### 🏷️ 1. Instant Price Sorting
- **Price: Low &rarr; High**: Instantly bubbles the cheapest products to the very top. Perfect for finding the lowest prices on everyday essentials.
- **Price: High &rarr; Low**: Flip the order to explore premium, combo, or higher-tier listings first.

### ⭐ 2. Verified Rating Sort & Filters
- **Sort by Rating**: Prioritize top-rated products with the most positive customer feedback.
- **Minimum Rating Filters**: Easily filter the catalog by **★ 4.0+**, **★ 3.5+**, or **★ 3.0+** so you never sacrifice product quality for a cheap price.

### 💥 3. Deep Discount Discovery
- **Sort by % Discount**: Discover real clearance deals with the steepest price cuts (e.g. 50%+ off).

### 💰 4. Custom Price Range Filtering
- Define custom minimum (`₹ Min`) and maximum (`₹ Max`) thresholds or use quick-select budget presets to view only products that fit your wallet.

### ⚡ 5. Seamless Native Integration
- **In-Place Transformation**: MeeSort updates only the product grid. Meesho’s top navigation, search bar, and left category filters remain 100% functional and untouched.
- **Zero Page Reloads**: Works dynamically with single-page application (SPA) searches—type a new query and MeeSort automatically resets and adapts.

### 🔍 6. "Scan More Products" Feed Expander
- Meesho loads items dynamically as you scroll. MeeSort includes a safe, throttled **Scan More Products** feature that gathers additional catalog pages into memory so you can sort across a wider catalog of products at once.

### 🔒 7. 100% Client-Side Privacy
- Runs purely inside your own browser.
- **Zero data collection**: No accounts, no sign-ups, no tracking cookies, and zero external server calls.

---

## 🌐 Supported Browsers

MeeSort is architected with modern **Manifest V3** standards and supports:

| Browser | Compatibility | Status |
| :--- | :--- | :--- |
| **Google Chrome** | Chrome 100+ | Supported |
| **Microsoft Edge** | Edge 100+ | Supported |
| **Mozilla Firefox** | Firefox 109+ | Supported |
| **Brave / Opera / Vivaldi** | Chromium-based | Supported |

---

## 🚀 How to Install

### Option A: Load Unpacked (Developer Mode)

1. **Download the Release Package** (ZIP) from the [Releases](https://github.com/Moonlight12911/MeeSort/releases) section and unzip it.
2. Open your browser's extension manager:
   - **Chrome / Brave**: Navigate to `chrome://extensions/`
   - **Edge**: Navigate to `edge://extensions/`
3. Toggle on **Developer mode** (usually found in the top-right or left sidebar).
4. Click **Load unpacked** and select the unzipped folder for your browser.
5. Go to [Meesho.com](https://www.meesho.com/), search for any product, and enjoy price sorting!

---

## 🛡️ Privacy & Security

MeeSort takes consumer privacy seriously:
- **No Analytics / Telemetry**: We do not monitor what you search or what you buy.
- **No Third-Party Requests**: The extension makes zero background network requests to third-party servers.
- **No Account Required**: No logins, subscriptions, or credentials.
- **Local Storage Only**: Only your interface preferences (like your preferred sort order) are saved in local browser storage.

For full details, read our complete [Privacy Policy](PRIVACY.md).

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><strong>Does MeeSort require my Meesho account credentials?</strong></summary>
No. MeeSort never asks for, accesses, or requires your Meesho login, passwords, or payment details. It operates strictly as a visual client-side assistant on public search results.
</details>

<details>
<summary><strong>Will using MeeSort slow down my browser?</strong></summary>
No. MeeSort is built with lightweight vanilla JavaScript without heavy external libraries or frameworks. It only runs when you are actively on Meesho product catalog pages.
</details>

<details>
<summary><strong>Why do some products have multiple prices?</strong></summary>
Certain products on Meesho have multiple sizes or variations (e.g. ₹199 base, ₹249 for larger sizes). MeeSort sorts products by the primary displayed card price shown in the catalog.
</details>

<details>
<summary><strong>Can I sort after searching for a different keyword?</strong></summary>
Yes! MeeSort listens to search transitions. When you search for a new item, the store clears automatically and populates with the new search results ready to sort.
</details>

---

## ⚠️ Disclaimer

**MeeSort is an independent utility and is not affiliated with, endorsed by, sponsored by, or in any way officially connected with Meesho or Fashnear Technologies Pvt. Ltd.**

"Meesho" as well as related names, marks, emblems, and images are registered trademarks of their respective owners.

---

## 📄 License & Copyright

Copyright © 2026 Mukesh. All rights reserved.  
MeeSort is a proprietary consumer browser utility. Unauthorized reproduction, distribution, or reverse engineering is prohibited.

