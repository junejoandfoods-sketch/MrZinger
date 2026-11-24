# Mr. Zinger - Fast Food Ordering & Management Web App

A production-ready, highly responsive fast food ordering and management platform built with **Tailwind CSS**, **JavaScript**, and **FontAwesome**. Perfect for restaurants, cafes, and burger joints.

## 🚀 Features

- **Dynamic Menu & Categories:** Browse items by category (Burgers, Deals, Sides, Drinks) with real-time search.
- **Interactive Cart & Checkout:** Add items, manage quantities, calculate totals with delivery charges, and place orders with Instant Order Tracking.
- **Top Promotional Banner Slider:** Auto-playing running promotional slides with call-to-action buttons.
- **Mr. Zinger TV Widget:** Embedded video or media player for recipes and promotional videos.
- **Complete Admin Panel (Secured with PIN):**
  - **Menu Management:** Add, edit, or delete menu items and change product images.
  - **Slider Banners:** Add or remove promotional top slider cards.
  - **Video Widget:** Update YouTube embed links or MP4 video URLs.
  - **Branding & Logo:** Change the store name and logo URL.
  - **Store Contact Info:** Update address, phone helpline, and opening hours.
  - **Security:** Update the 4-digit admin access PIN.
  - **Live Orders Feed:** View incoming customer orders and manage history.
- **Data Persistence:** Uses `localStorage` so changes and order histories are saved across sessions.
- **PWA Ready:** Installable on mobile phones ("Add to Home Screen" prompt and sharing support).

---

## 📂 Project Structure

```text
mr-zinger-app/
├── index.html          # Main application file
├── README.md           # Documentation & GitHub Deployment Guide
└── assets/             # Images, logos, and static resources
    └── logo.png        # Placeholder / brand logo
```

---

## 🛠️ How to Deploy on GitHub Pages

1. **Create a New Repository:**
   - Go to [GitHub](https://github.com) and click **New Repository**.
   - Name your repository (e.g., `mr-zinger-app`), select **Public**, and click **Create repository**.

2. **Upload Files:**
   - You can upload `index.html` and the `assets/` folder directly via the GitHub web interface by clicking **uploading an existing file**, or push via Git:
     ```bash
     git init
     git add .
     git commit -m "Initial commit - Mr. Zinger App"
     git branch -M main
     git remote add origin https://github.com/YOUR_USERNAME/mr-zinger-app.git
     git push -u origin main
     ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub.
   - Click on **Settings** -> **Pages** (in the left sidebar under "Code and automation").
   - Under **Build and deployment**, set **Source** to `Deploy from a branch`.
   - Set **Branch** to `main` (or `master`) and `/ (root)` folder, then click **Save**.
   - Within 1 minute, GitHub will provide your live website URL! 🎉

---

## 🔐 Default Admin Access
- **Admin PIN:** `1234` (Click the **Admin Panel** button in the header and enter `1234`).
- You can change this PIN anytime inside the Admin Dashboard under **Admin Code/PIN**.
