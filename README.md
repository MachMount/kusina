# 🌿 Kusina — Recipe, Meal, & Grocery Aide

**Kusina** (Filipino for *"Kitchen"*) is a lightweight, mobile-responsive web application built to serve as a Master Cookbook, Multi-Dish Meal Planner, Smart Grocery Aggregator, and Live Pantry Inventory Aide.

Designed for seamless collaborative cooking, Kusina connects directly to a live cloud database so multiple household members can view, plan, and manage dishes simultaneously across phones, tablets, and PCs.

---

## 🌟 Key Features

* **📖 Master Cookbook:** Browse and organize recipes with dish-type tagging (`Chicken`, `Beef`, `Pork`, `Fish / Seafood`, `Vegetable`, `Pasta`, `Rice`, `Sandwich`, `Soup / Stew`), auto-calculated calories per serving, ingredient autocomplete, and step-by-step instructions.
* **📅 Multi-Dish Meal Planner:** Schedule single or multiple dishes per calendar day using Weekly or Monthly view layouts.
* **🛒 Smart Grocery Aggregator:** Select date ranges to aggregate required recipe ingredients, auto-converting measurements into unified shopping units (`ml` / `g`). Cross-references live pantry stock (`To Buy = Needed - In Pantry`) and auto-adds out-of-stock household items.
* **🔍 Interactive Ingredient Inspector:** Tap any ingredient in the Grocery List or Pantry to inspect every recipe in your database that requires it.
* **🏺 Pantry Inventory Management:** Track active stock levels with 1-click duplicate merging, fuzzy key matching, and plural normalization (`cloves`, `pieces`, `g`, `ml`).
* **🍳 Focus Cook Mode & Screen Stay-Awake:** Fullscreen cooking view featuring large text, prep checklist, instruction step checkboxes, and screen stay-awake integration (`navigator.wakeLock`).
* **📦 Dynamic Stock Deduction & Revert:** Finish cooking with automatic pantry stock subtraction, backed by a 1-tap **"↺ Undo & Restock"** safety banner.
* **🔒 Public Cookbook & Granular Admin Mode:** Read-only guest mode for quick browsing, paired with password-protected Admin editing. Uses non-destructive granular per-recipe cloud writes to allow simultaneous multi-user edits without overwriting data.

---

## 🛠️ Technology Stack

* **Frontend:** Single-File Vanilla HTML5, Tailwind CSS, JavaScript (ES6+)
* **Typography:** Playfair Display, Plus Jakarta Sans, Caveat
* **Database:** Google Firebase Realtime Database
* **Hosting:** GitHub Pages
* **Data Portability:** 1-Click JSON Local Backup Export & Restore

---

## 🚀 How to Add to Your Mobile Phone (PWA Style)

1. Open your live GitHub Pages link in **Safari (iOS)** or **Chrome (Android)**.
2. Tap the **Share / Menu** icon in your browser.
3. Select **"Add to Home Screen"**.
4. Kusina will now launch directly from your home screen as a clean, full-screen app icon!

---

*Prompt Coded by ✈️ • 2026*
