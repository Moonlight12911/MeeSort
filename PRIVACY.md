# Privacy Policy for Meesho Price Sort & Filter (MeeSort)

**Last Updated:** September 2026

At MeeSort, we believe consumer utility extensions should respect user privacy completely. This extension is engineered with a strict **privacy-first, client-only** philosophy.

---

## 1. Zero Personal Data Collection
MeeSort does **not** collect, transmit, sell, or store any personal data. Specifically:
- We do **not** collect your name, email, phone number, address, or credentials.
- We do **not** collect payment, banking, or credit card information.
- We do **not** collect your general browsing history or monitor other websites.
- We do **not** require an account or registration.

---

## 2. What Data Is Accessed & Processed
MeeSort operates exclusively in your browser context on Meesho pages (`https://www.meesho.com/*`):
- **Local DOM Access**: MeeSort reads product names, prices, ratings, and image URLs rendered on the current search or category tab in order to sort and display them in your requested order.
- **In-Memory Store**: Extracted products are kept strictly in temporary browser memory during your active session. They are cleared when you navigate to a new search or close the tab.

---

## 3. Local Browser Storage
If enabled, MeeSort uses `chrome.storage.local` exclusively to remember your personal interface preferences across sessions:
- Default sorting preference (e.g. Price: Low → High)
- Preferred view mode (Sorted Grid vs. Meesho Default)

This information never leaves your device.

---

## 4. No External Communication or Analytics
- MeeSort contains **no tracking beacons**, no Google Analytics, no telemetry, and no third-party SDKs.
- MeeSort does **not** make network requests to any external server or API.
- All sorting, filtering, and rendering is performed 100% client-side via JavaScript on your own computer.

---

## 5. Permissions Justification
- `activeTab`: Used to communicate state (e.g. product count) to the extension toolbar popup for the active tab.
- `storage`: Used to persist user UI preferences locally.
- `host_permissions` (`https://www.meesho.com/*`): Required to inject the sorting toolbar and read product cards on Meesho.

## 6. Client-Side Security & Integrity
MeeSort operates exclusively in the local browser environment. The extension transmits zero information over the internet and maintains complete data privacy by design.

