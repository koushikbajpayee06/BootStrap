"# BootStrap" 

🚀 What is Bootstrap?

Bootstrap is a frontend toolkit packed with prebuilt components, responsive utilities, and powerful customization options.
It helps developers build modern, mobile-first, and interactive UIs faster than writing everything from scratch.

💡 Key Highlights

✅ Prebuilt UI components (Navbar, Cards, Carousel, etc.)
✅ Responsive & mobile-first grid system
✅ Open-source & cross-platform
✅ Fully customizable (via SCSS or overrides)
✅ Latest version Bootstrap 5 — No jQuery required!

⚙️ Setup Instructions

1️⃣ Open terminal in your project folder
2️⃣ Install Bootstrap & Bootstrap Icons

npm install bootstrap bootstrap-icons --save


3️⃣ Link Bootstrap & Icons in your HTML file

../node_modules/bootstrap/dist/css/bootstrap.css
../node_modules/bootstrap-icons/font/bootstrap-icons.css
../node_modules/bootstrap/dist/js/bootstrap.bundle.js

🎨 Commonly Used Classes
🧱 Box Model Utilities

Margins

.m-{1–5} → All sides

.mt-{} → Top

.mb-{} → Bottom

.ms-{} → Start (Left)

.me-{} → End (Right)

.mx-{} → Left & Right

.my-{} → Top & Bottom

Padding

.p-{1–5} → All sides

.pt-{} .pb-{} .ps-{} .pe-{} .px-{} .py-{} → Directional padding

Borders

.border → Base border

.border-{size} → Border thickness

.border-{contextual} → Success, Danger, Warning, Primary, Info, etc.

Width & Height

.w-{25,50,75,100}

.h-{50,100}

Border Radius

.rounded, .rounded-{1–5}

.rounded-pill, .rounded-circle

🎨 Text & Background Colors

.bg-{contextual} → Background color

.text-{contextual} → Text color

Common Contextual Colors:
primary, secondary, success, danger, warning, info, light, dark

Example:

<div class="bg-secondary text-light p-4 rounded-4">
  Bootstrap Styling Example
</div>

🧠 Summary
Feature	Description
Version	Bootstrap 5
Install via	npm or CDN
Purpose	Rapid & responsive UI development
Customization	Full control via SCSS or CSS
Popular Components	Navbar, Cards, Carousel, Buttons, Forms
✅ End of Day 1 Recap

🎯 You learned:

What Bootstrap is and why it’s used

How to install and link it in a project

Core utility classes (margin, padding, borders, colors)

How to apply text & background styling

