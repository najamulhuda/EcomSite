markdown
# Fashion E-Commerce Website

A responsive fashion e-commerce website built with Bootstrap and custom CSS, featuring a modern design with product listings, interactive modals, and a fully responsive layout.

## 🌐 Live Demo
https://najamulhuda.github.io/EcomSite/

## 📁 Project Structure
project-folder/
│

├── index.html # Main HTML file

├── style.css # Custom styles

├── images/ # All project images

│ ├── logo.webp

│ ├── Hero section img1.jpg

│ ├── Hero section img2.jpg

│ ├── Hero section img3.jpg

│ ├── 12.jpg

│ ├── 13.jpg

│ ├── 14.jpg

│ ├── 15.jpg

│ └── payment logos/
└── README.md # This file text

## 🚀 Features

### 1. **Responsive Design**
- Fully responsive across all devices (mobile, tablet, desktop)
- Mobile-first approach with custom media queries
- Adaptive hero section with adjustable image heights

### 2. **Navigation Bar**
- Responsive Bootstrap navbar with toggle for mobile
- Logo integration
- Search functionality
- Smooth navigation links

### 3. **Hero Section**
- Bootstrap carousel with 3 slides
- Custom overlay text with semi-transparent background
- Auto-sliding functionality
- Mobile-optimized image display

### 4. **Product Section**
- 8 product cards with consistent styling
- Each card includes:
  - Product image
  - Title and price
  - "Add to cart" button
  - Bootstrap modal for order confirmation
- Grid layout with flexbox for optimal spacing

### 5. **Interactive Elements**
- Bootstrap modals for each product
- Form validation-ready newsletter subscription
- Social media links (Facebook, Instagram)
- Payment method icons

### 6. **Footer Section**
- Multi-column layout
- Useful links (Privacy Policy, Terms & Conditions)
- Social media integration
- Newsletter subscription form
- Payment method display
- Copyright information

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with Flexbox
- **Bootstrap 5.3.8** - Responsive framework
- **Bootstrap 4.5.2** - Additional components
- **Font Awesome 6.5.1** - Icons
- **Google Fonts** - Mona Sans & Mulish

### JavaScript Libraries
- **Bootstrap JS** - Component functionality
- **jQuery 3.5.1** - DOM manipulation
- **Popper.js** - Tooltip positioning

## 📱 Responsive Breakpoints

### Mobile (max-width: 768px)
- Hero images: max-height 300px
- Font sizes reduced for better readability
- Adjusted hero container height

### Desktop
- Hero images: max-height 500px
- Full-width carousel
- Multi-column product grid

## 🎨 Design Features

### Color Scheme
- **Primary**: `#3E3630` (footer background)
- **Secondary**: White text on dark backgrounds
- **Accents**: Bootstrap primary colors

### Typography
- **Mona Sans** - Primary font (headings, footer)
- **Arial/Helvetica** - Fallback fonts
- **Mulish** - Secondary font option

### Visual Effects
- Image brightness filter (60%) on hero section
- Box shadows on product cards
- Hover effects on interactive elements
- Smooth transitions

## 🔧 Installation & Setup

1. **Clone the repository:**
   
git clone https://github.com/najamulhuda/EcomSite.git
Navigate to project folder:

bash
cd EcomSite
Open in browser:

Simply open index.html in any modern browser

No server setup required

📝 Customization Guide
Change Images
Replace images in the images/ folder

Update image paths in index.html

Modify Colors
Edit style.css:

css
.footer-section {
    background-color: #3E3630;
}
Add Products
Duplicate a card section in index.html and update:

Image source

Product title

Price

Modal IDs (must be unique)

Update Links
Social media links in footer

Navigation links in navbar

External resources in head section

🌟 Key Components
Carousel Customization
html
<div class="carousel-item" data-bs-interval="2000">
    <!-- Change interval for slide duration -->
</div>
Modal System
Each product has a unique modal with:

Unique ID (exampleModal1, exampleModal2...)

Product-specific title

Confirmation/Close buttons

Newsletter Form
Email input with placeholder

Submit button

Ready for backend integration

🐛 Known Issues
Bootstrap Version Conflict

Using both Bootstrap 4 and 5

Some components may have conflicting styles

Modal IDs

Some modals have incorrect ID references

Ensure data-target matches modal ID

Image Optimization

Hero images are large (800px height)

Consider compression for faster loading

📱 Browser Support
Chrome (latest)

Firefox (latest)

Safari (latest)

Edge (latest)

Opera (latest)

📄 License
This project is open-source and available for personal and commercial use.

👥 Contributing
Fork the repository

Create a feature branch

Commit your changes

Push to the branch

Open a pull request

📧 Contact
For questions or feedback, please contact:

najamulhuda791@gmail.com

https://github.com/najamulhuda

Note: This is a frontend-only project. Backend integration would be required for:

User authentication

Shopping cart functionality

Payment processing

Newsletter subscription storage

Order management system

