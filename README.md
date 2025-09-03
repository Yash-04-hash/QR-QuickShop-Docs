# QR-QuickShop-Docs
# 📌 QR QuickShop – Smart Hybrid Shopping System  

## 🔹 Project Title  
**QR QuickShop – Smart Hybrid Shopping System**  

---

## 🔹 Problem Statement  
Online shopping is convenient but has two major issues:  
1. **Delayed delivery** – customers must wait for shipping.  
2. **Stock mismatch** – products shown online may not be available in nearby stores.  

On the other hand, offline shopping requires physically searching and billing products, which is time-consuming.  

There is a need for a system that **combines the ease of online shopping with the instant availability of offline stores**.  

---

## 🔹 Proposed Solution  
QR QuickShop is a **web-based application** that allows customers to:  
1. **Browse products online** and add them to a cart.  
2. **Checkout in two ways:**  
   - **Option 1 – Online Checkout:** Pay online and wait for delivery.  
   - **Option 2 – In-Store Checkout:** Get a unique **QR Code** containing the cart details → visit the nearest store → scan QR at billing counter → pick up items instantly.  

This ensures customers save time and stores can increase sales through faster checkouts.  

---

## 🔹 Key Features  
- 🛒 **Product Browsing:** Customers can view products with details (price, stock, availability).  
- ➕ **Add to Cart:** Simple cart system managed by frontend + backend.  
- 📱 **QR Code Checkout:** Each cart generates a unique QR with order details.  
- 🏬 **In-Store Mode:** Customer shows QR → cashier scans → items directly appear in billing system.  
- 💳 **Dual Checkout:** Choose between online payment or in-store pickup.  

---

## 🔹 Tech Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask)  
- **Database:** SQLite  
- **QR Generation:** Python `qrcode` library  
- **QR Scanning (store side):** Web-based QR scanner or Python script  

---

## 🔹 Workflow  
1. Customer opens the web app → browses products.  
2. Adds products to cart.  
3. At checkout:  
   - If **Online Payment** → order is placed for delivery.  
   - If **In-Store Pickup** → system generates QR Code.  
4. Customer visits nearby store → shows QR Code at billing counter.  
5. Store staff scans QR → retrieves cart details → completes billing instantly.  

---

## 🔹 Benefits  
- ⏱️ Saves customer time by avoiding product search & manual billing.  
- 📦 Reduces delivery waiting time with in-store pickup.  
- 🏬 Encourages hybrid shopping (both online & offline).  
- 📊 Helps stores manage real-time stock availability.  

---

## 🔹 Future Scope  
- Integration with **UPI/Payment Gateway** for real transactions.  
- Real-time **inventory sync** with multiple stores.  
- AI-based **recommendation system** for customers.  
- Mobile app version (Android/iOS).  
