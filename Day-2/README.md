🧱 Bootstrap Classes Practice

This project demonstrates the use of Bootstrap 5 utility classes through hands-on examples. Each section covers a core concept in Bootstrap, including layout, positioning, display, typography, buttons, and the grid system.

📘 Topics Covered
1. Box Model

Covers Bootstrap spacing and sizing utilities:

Margin: .m-0, .m-1, .m-2, ..., .mt-3, .ms-5

Padding: .p-0, .p-1, .p-2, ..., .pt-3, .ps-5

Border: .border, .border-0, .border-1, .border-2, etc.

Rounded Corners: .rounded, .rounded-circle, .rounded-pill

Width / Height: .w-25, .w-50, .w-75, .w-100, .h-25, .h-50, etc.

📂 Example:
Badge on cart icon using positioning and rounded classes.

<button class="bi bi-cart4 position-relative">
  Your Cart 
  <span class="bg-danger text-white rounded-circle badge position-absolute top-0 end-0">2</span>
</button>

2. Text & Background Colors

Bootstrap provides text and background color utilities:

.text-{color} → e.g. .text-primary, .text-success, .text-danger

.bg-{color} → e.g. .bg-light, .bg-dark, .bg-warning

3. Position Classes

Used to control element positioning:

.position-static

.position-relative

.position-absolute

.position-fixed

.position-sticky

Position offset helpers:

.top-{0|50|100}

.bottom-{0|50|100}

.start-{0|50|100}

.end-{0|50|100}

📂 Example:
Sticky header while scrolling.

<h1 class="bg-dark text-white p-2 position-sticky top-0">Welcome</h1>

4. Display Classes

Control how elements are displayed and aligned using flex utilities.

.d-none, .d-block, .d-inline, .d-inline-block

.d-flex, .flex-row, .flex-column

.justify-content-{start|center|end|between|around|evenly}

.align-items-{start|center|end|baseline}

.flex-wrap

📂 Example:
Responsive Navbar using Flexbox.

<header class="border p-3 d-flex justify-content-between">
  <div>Shopper.</div>
  <nav>
    <span>Home</span><span class="px-3">Shop</span><span>Blog</span>
  </nav>
  <div>
    <span class="bi bi-heart"></span>
    <span class="bi bi-cart4"></span>
  </div>
</header>

5. Grid System

Bootstrap’s 12-column responsive grid system using .row and .col.

.row → defines a horizontal group of columns

.col or .col-{n} (1–12) → defines column width

📂 Example 1: Loan Calculator Grid Layout
📂 Example 2: Form Layout using <dl> with grid columns

6. Float Classes

Align elements horizontally using float utilities:

.float-start

.float-end

7. Text Effects

Typography and text decoration classes:

Font Size: .fs-{1-7}

Font Weight: .fw-bold, .fw-light

Font Style: .fst-italic

Alignment: .text-start, .text-center, .text-end, .text-justify

Decorations: .text-decoration-{underline|none|overline|line-through}

📂 Example:

<div class="fs-2 fw-bold fst-italic text-decoration-underline pb-5">
  Register Product
</div>

8. Button Classes

Various styles and button group utilities:

.btn (base)

.btn-{contextual} → .btn-primary, .btn-danger, .btn-success

.btn-outline-{contextual}

.btn-sm, .btn-lg

.btn-link, .btn-close

.btn-group, .btn-group-vertical

.btn-toolbar

📂 Example:
Toolbar with grouped buttons and contextual styles.

<nav class="btn-toolbar bg-danger justify-content-between">
  <div class="btn-group">
    <button class="btn btn-danger">Home</button>
    <button class="btn btn-danger">Shop</button>
  </div>
  <div class="btn-group">
    <button class="bi bi-person btn btn-danger"></button>
    <button class="bi bi-cart4 btn btn-danger"></button>
  </div>
</nav>

⚙️ Setup Instructions

Clone or download this project.

Make sure Bootstrap and Bootstrap Icons are installed in the project using npm install bootstrap bootstrap-icons.

Include Bootstrap CSS and JS in your HTML files:

<link rel="stylesheet" href="../node_modules/bootstrap/dist/css/bootstrap.css">
<link rel="stylesheet" href="../node_modules/bootstrap-icons/font/bootstrap-icons.css">
<script src="../node_modules/bootstrap/dist/js/bootstrap.bundle.js"></script>


Open any .html file in your browser to see the live examples.

🧩 Purpose

This practice file helps you understand Bootstrap utility classes through real examples.
It’s designed for beginners to quickly learn:

Spacing, layout, and positioning

Flexbox and grid systems

Typography and colors

Button designs and toolbars

🧑‍💻 Author

Koushik Bajpayee
Frontend & Laravel Developer | Bootstrap Learner