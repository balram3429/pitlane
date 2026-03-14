# 🏁 Pit Lane Checkout Template

A lightweight **E-commerce Checkout Template** built as a **single
self-contained HTML file**.

The template is currently themed for an **Automobile Service Station**,
but it can easily be adapted for **any E-commerce application** such as
spare parts, accessories, digital products, groceries, or services.

------------------------------------------------------------------------

# 🚀 Features

## 🛒 Smart Checkout Flow

-   Hash-based routing for smooth navigation
    -   `#home`
    -   `#product/1`
    -   `#cart`
    -   `#checkout`

## 💾 Persistent Shopping Cart

-   Cart is stored in **localStorage**
-   Storage key: `Pit_Lane`
-   Cart remains intact even after page refresh.

## 📦 Dynamic Product System

Products are defined in a simple **JavaScript array**.

Each product contains:

-   `id`
-   `name`
-   `price`
-   `category`
-   `description`
-   `images` (array of image URLs)
-   `stock`

Any changes to the product list **automatically update the entire
site**.

------------------------------------------------------------------------

# 🧩 Built-in Components

## 📊 Category Filter

-   Category bar **auto-generates from product data**
-   Allows quick filtering of products.

## 🖼 Product Image Gallery

-   Main product image
-   Thumbnail preview images
-   Click thumbnails to change view.

## 🔁 Related Products

-   Automatically suggests **products from the same category**.

## 🔢 Quantity Controls

Quantity selectors available in: - Product page - Cart page

## ✔ Cart Sync Indicator

Product cards display:

`In Cart ✓`

This stays **perfectly synced with the cart state**.

------------------------------------------------------------------------

# 📬 Checkout & Order Submission

Orders are submitted through **Formspree**.

After submission: - A **success overlay** is shown - The page
**automatically redirects after 3 seconds**

------------------------------------------------------------------------

# ⚙️ Configuration

Before going live, edit **two things at the top of the HTML file**.

## 1️⃣ Formspree Endpoint

Find the following in the **CONFIG block**:

``` javascript
formspreeUrl: "https://formspree.io/f/YOUR_FORM_ID"
```

Replace it with your **actual Formspree endpoint**.

Example:

``` javascript
formspreeUrl: "https://formspree.io/f/xyknponj"
```

------------------------------------------------------------------------

## 2️⃣ Product Catalog

The `PRODUCTS` array sits directly below the `CONFIG`.

Example:

``` javascript
{
  id: 1,
  name: "Premium Engine Oil",
  price: 1200,
  category: "Fluids",
  description: "High performance synthetic engine oil",
  images: ["image1.jpg","image2.jpg"],
  stock: 25
}
```

You can:

-   Add products
-   Remove products
-   Update prices
-   Change categories

The site will **automatically update everywhere**.

------------------------------------------------------------------------

# 🎨 UI & Design

The template uses a **modern automotive aesthetic**.

Design highlights:

-   Warm **earthy color palette**
-   Elegant **Playfair Display** headings
-   Clean **DM Sans** body text
-   Smooth UI interactions
-   Card hover effects
-   Fully **mobile responsive layout**

------------------------------------------------------------------------

# 📱 Mobile Ready

The template includes:

-   Responsive grid layout
-   Touch-friendly controls
-   Mobile optimized cart
-   **Hamburger navigation menu**

Works smoothly across:

-   📱 Mobile
-   💻 Desktop
-   📟 Tablets

------------------------------------------------------------------------

# 📁 Deployment

Since this project is a **single HTML file**, deployment is extremely
simple.

You can host it on:

-   GitHub Pages
-   Netlify
-   Vercel
-   Any static hosting service

Just upload the HTML file and it's ready.

------------------------------------------------------------------------

# 🧠 Use Cases

This template can be adapted for:

-   Automobile Service Stations
-   Spare Parts Stores
-   Bike Accessories Shops
-   Garage Booking Systems
-   Small E-commerce stores
-   Digital product checkout pages

------------------------------------------------------------------------

# 👨‍💻 Credits

**Template Developed by:**\
**Zomb-AI (balram3429)**

------------------------------------------------------------------------

# ⭐ Support

If you find this template useful:

-   ⭐ Star the repository
-   🍴 Fork it
-   🔧 Customize it for your project

Happy building 🚀
