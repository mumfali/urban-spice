# 🌶️ Urban Spice – Restaurant Online Ordering Website

Urban Spice is a restaurant online ordering website built using **HTML, CSS, and Vanilla JavaScript**. Customers can browse the menu, add dishes to their cart, change quantities, view a live bill with GST, and place a demo order.

🔗 **Live Website:** [https://mumfali.github.io/urban-spice/](https://mumfali.github.io/urban-spice/)

> ⚠️ **Note:** This is a frontend demonstration project. Orders are not sent to a real restaurant, and no actual payments are processed. Restaurant details are fictional.

---

## ✨ Features

- **Interactive Menu:** 19 dishes displayed as cards with images, descriptions, prices in ₹, and vegetarian/non-vegetarian indicators.
- **Food Categories:** Starters, Main Course, Breads, Rice & Biryani, Snacks, Beverages, Desserts, and Popular dishes.
- **Search Functionality:** Search for dishes by name.
- **Veg-Only Filter:** Filter the menu to display vegetarian dishes.
- **Shopping Cart:**
  - Add dishes to the cart.
  - Increase or decrease item quantities.
  - Automatically remove items when their quantity reaches zero.
  - View the live item count.
  - View each item's price and subtotal.
  - Clear the entire cart.
- **Automatic Bill Calculation:**
  - Item subtotal.
  - GST at a demo rate of 5%.
  - Packaging fee.
  - Delivery fee.
  - Final payable amount.
- **Free Delivery:** Available on orders of ₹499 or more.
- **Order Confirmation:** Displays a confirmation message with an order number and final amount.
- **Local Storage:** Saves the cart in the browser so items remain after refreshing the page.
- **Responsive Design:** Works on desktop and mobile screens.

---

## 🛠️ Technologies Used

- **HTML5** – Website structure and content.
- **CSS3** – Styling, layout, animations, and responsive design.
- **Vanilla JavaScript** – Menu rendering, search, category filtering, cart management, and bill calculations.
- **Local Storage** – Preserves cart data in the browser.

---

## 📁 Project Structure

```text
urban-spice/
├── index.html    # Website structure
├── style.css     # Styling and responsive layout
├── script.js     # Menu data and interactive functionality
└── README.md     # Project documentation
```

---

## 🚀 How to Run Locally

1. Download or clone this repository.
2. Open the `urban-spice` folder in Visual Studio Code.
3. Make sure `index.html`, `style.css`, and `script.js` are in the
