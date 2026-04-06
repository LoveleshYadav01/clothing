# 🔥 DRIPP STORE — Your E-Commerce Website

A complete, ready-to-deploy fashion e-commerce website.

---

## 🚀 HOW TO GO LIVE (GitHub Pages — FREE)

### Step 1 — Upload to GitHub
1. Go to [github.com](https://github.com) → Sign up / Log in
2. Click **"New repository"** (green button)
3. Name it: `dripp-store` (or anything you like)
4. Set it to **Public**
5. Click **"Create repository"**
6. Click **"uploading an existing file"**
7. Drag & drop your `index.html` → Click **"Commit changes"**

### Step 2 — Enable GitHub Pages
1. Go to your repo → click **"Settings"** tab
2. Scroll to **"Pages"** on the left menu
3. Under "Branch" → select `main` → click **Save**
4. Wait 2 minutes → your site is live at:
   ```
   https://YOUR_GITHUB_USERNAME.github.io/dripp-store
   ```

### Step 3 — Instagram Bio Link
1. Copy your GitHub Pages URL
2. Go to Instagram → Edit Profile
3. Paste URL in the **"Website"** field
4. Done! People from your ads will land on your store 🎯

---

## 📧 HOW TO RECEIVE ORDERS BY EMAIL (FREE)

### Formspree Setup
1. Go to [formspree.io](https://formspree.io) → Sign up free
2. Click **"New Form"**
3. Copy your **Form ID** (looks like: `xrgvwbkp`)
4. Open `index.html` in Notepad/VS Code
5. Find this line (near line 550):
   ```javascript
   const FORMSPREE_ID = "YOUR_FORMSPREE_ID";
   ```
6. Replace `YOUR_FORMSPREE_ID` with your actual ID:
   ```javascript
   const FORMSPREE_ID = "xrgvwbkp";
   ```
7. Save and re-upload to GitHub → every order = email to you! 📬

---

## ✏️ HOW TO CUSTOMIZE

### Change Store Name
Find this line in the script section:
```javascript
const STORE_NAME = "DRIPP STORE";
```
Change to your brand name.

### Change Products
Find the `PRODUCTS` array in the script. Each product looks like:
```javascript
{
  id: 1,
  name: "Product Name",
  cat: "Clothing",        // Clothing / Footwear / Accessories / Watches
  price: 649,             // Price in ₹
  oldPrice: 999,          // Original price (null if no discount)
  badge: "Sale",          // "Sale" / "New" / "Hot" / null
  desc: "Description...",
  img: "https://...",     // Image URL (use unsplash.com for free images)
  sizes: ["S","M","L","XL"],
  rating: 4.8,
  reviews: 128
}
```

### Change Contact Info
- Email: Search for `hello@drippstore.in` and replace
- WhatsApp: Replace `919999999999` with your number (91 = India code)
- Instagram handle: Replace `@drippstore` with yours

### Change Colors (Brand Colors)
At the top of the file, find `:root { ... }` and change:
```css
--gold: #c9a84c;   /* Main accent color */
--black: #0a0a0a;  /* Background */
--white: #f5f5f0;  /* Text color */
```

### Change Hero Images (Instagram Gallery)
Replace the Unsplash URLs in the `#instagram` section with your own product photos.

---

## 📦 WHAT'S INCLUDED

- ✅ Beautiful homepage with hero banner
- ✅ Product categories (Clothing, Footwear, Accessories, Watches)
- ✅ 16 sample products with filters
- ✅ Product detail modal with size selector
- ✅ Full shopping cart (persists after page refresh)
- ✅ Complete checkout form (Name, Email, Phone, Address, State, PIN, Payment)
- ✅ Order placed → Email to you via Formspree
- ✅ Order confirmation screen with Order ID
- ✅ Mobile responsive
- ✅ Instagram gallery section
- ✅ Cash on Delivery / UPI / Card payment options
- ✅ Shipping calculator (FREE above ₹999)
- ✅ Toast notifications
- ✅ Animated hero, product hover effects

---

## 📱 FOR INSTAGRAM ADS

Make sure your Instagram ad links to:
```
https://YOUR_USERNAME.github.io/dripp-store
```

The site is mobile-optimized — works perfectly on phones 📱

---

## 💡 PRO TIPS

1. **Add your real product photos** — Replace Unsplash URLs with your product images (upload to Imgur or Cloudinary for free)
2. **Custom domain** — Buy a domain (e.g., drippstore.in) and connect it to GitHub Pages for ₹500/year
3. **WhatsApp orders** — Add a WhatsApp button linking to `https://wa.me/91XXXXXXXXXX?text=Hi, I want to order...`
4. **Google Analytics** — Track your ad traffic by adding Google Analytics to the head section

---

Made with ❤️ for DRIPP STORE
