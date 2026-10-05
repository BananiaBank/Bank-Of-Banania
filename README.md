# 🏦 Banania National Bank

Welcome to the official digital banking portal for **The Sovereign Realm of Banania**. This application is a self-sovereign, serverless banking web app built using **Vanilla HTML/JavaScript**, **Tailwind CSS**, and **Supabase**, hosted live via **GitHub Pages**.

---

## ✨ Features & Architecture

* **Secure Authentication:** Log in seamlessly using your unique Citizen ID or account username.
* **Account Review Workflow:** New citizen registrations are automatically placed in a `PENDING` state under bank review until approved by an administrator.
* **P2P Transfers with Escrow Protection:** Citizen-to-citizen transfers enter a 15-minute escrow review window, allowing the bank to approve or reject/refund transactions. If unreviewed, transactions auto-clear.
* **National Treasury Admin Panel:** 
  * Total Realm Wealth tracker.
  * Direct currency minting and fine/tax application.
  * Transfer review center and complete citizen registry management.
* **Responsive Design:** Fully mobile and tablet friendly (optimized for iPhones, iPads, and desktop monitors).

---

## 🚀 Tech Stack

* **Frontend:** HTML5, JavaScript (ES6), Tailwind CSS (CDN)
* **Backend / Database:** Supabase (PostgreSQL relational database)
* **Hosting:** GitHub Pages

---

## 🛠️ Setup & Deployment

1. Clone or download this repository.
2. Ensure your Supabase database has the required `citizens` and `transactions` tables set up.
3. Configure your Supabase Project URL and Public Anon Key in the script configuration of `index.html`.
4. Enable **GitHub Pages** in your repository settings targeting the `main` branch to make your bank instantly accessible online!

https://tinyurl.com/Bank-Of-Banania
---
*Official Financial Institution of the Sovereign Realm of Banania.*
