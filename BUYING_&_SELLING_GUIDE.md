# 📘 Buyer & Seller Management Guide

This document explains how to browse, purchase, and list websites in this repository.

---

## 🛒 For Buyers: How to Purchase a Website

1. **Browse the Catalog**: Open [README.md](./README.md) or open [index.html](./index.html) in your browser.
2. **Test Live Demo**: Click **View Demo** on any website card to see the actual live output.
3. **Contact the Seller**: Note down the **Website Name** or **ID** and contact the owner via:
   - 📧 Email: `your.email@example.com`
   - 💬 Discord / Telegram: `@yourhandle`
4. **Receive Files & Setup**: After payment confirmation, you will receive full source code access (ZIP or private repository invite) plus 7 days of deployment assistance!

---

## ➕ For Sellers: How to Add a New Website to this Repo

Adding a new website template or client project link takes less than 60 seconds:

### Step 1: Add Entry to `sites.json`
Open `sites.json` and add a new JSON object:

```json
{
  "id": "my-new-site",
  "name": "My New Website Title",
  "category": "SaaS",
  "description": "Short description of what this website does.",
  "tech": ["HTML5", "CSS3", "JavaScript"],
  "price": "$49",
  "status": "Available",
  "demoUrl": "https://your-live-demo-link.com",
  "image": "https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=800&q=80",
  "featured": true
}
```

### Step 2: Update the `README.md` Table
Open `README.md` and add a row to the **Featured Websites Table**:

```markdown
| 🚀 | **My New Website Title**<br><sub>SaaS</sub> | `HTML5` `CSS3` `JS` | `Available`<br>**$49** | [🌐 View Demo](https://your-live-demo-link.com) | [📩 Inquire / Buy](#-contact--inquiries) |
```

### Step 3: Commit and Push
```bash
git add .
git commit -m "Add new website listing: My New Website Title"
git push origin main
```

---

## 🌐 Hosting Your Interactive Web Showcase (GitHub Pages)

To make `index.html` live on the web for anyone to visit:
1. Go to your repository settings on GitHub.
2. Scroll to **Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**.
4. Select `main` branch and root `/` folder, then click **Save**.
5. Your live showcase website will be available at `https://anandpandey2005.github.io/website-template/`.
