# Unimarx - Premium Export Website

A modern, high-conversion B2B export-import website for Unimarx, built with Next.js, Tailwind CSS, and Framer Motion.

## 🚀 Features

### 🎨 Modern Design
- **Glassmorphism Navbar**: Transparent-to-solid sticky navigation with smooth transitions
- **Mobile-First Design**: Fully responsive with three-dot hamburger menu
- **Professional Aesthetic**: Deep Navy (#002147), Emerald Green (#006837), and Clean White color scheme

### 📱 Mobile Navigation
- **Three-Dot Menu**: Prominent kebab menu on mobile devices
- **Full-Screen Overlay**: Mobile menu with all sections and CTA button
- **Smooth Animations**: Framer Motion powered transitions

### 🏢 Business Sections
1. **Hero Section**: Split-screen design with Black Tiger Shrimp showcase
2. **Trust Bar**: Scrolling marquee of partners and certifications
3. **Product Hub**: Filtered grid with technical specs and seasonality badges
4. **Supply Chain**: Vertical timeline visualization
5. **Leadership**: High-quality cards with visible quotes
6. **B2B RFQ Form**: Advanced quotation request form
7. **Footer**: Google Maps integration and professional dark theme

### ⚡ Interactive Features
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **Product Filtering**: Dynamic product category filtering
- **Technical Specs Modal**: Detailed product information popups
- **Form Validation**: Client-side validation for RFQ form
- **Hover Effects**: Interactive elements with micro-animations

## 🛠 Tech Stack

- **Framework**: Next.js 14
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Responsive**: Mobile-first approach

## 📦 Project Structure

```
unimarx-website/
├── app/
│   ├── globals.css
│   ├── layout.js
│   └── page.js
├── components/
│   ├── Navbar.js
│   ├── Hero.js
│   ├── TrustBar.js
│   ├── ProductHub.js
│   ├── SupplyChain.js
│   ├── Leadership.js
│   ├── ContactForm.js
│   └── Footer.js
├── public/
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── next.config.js
└── README.md
```

## 🚀 Getting Started

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Run Development Server**
   ```bash
   npm run dev
   ```

3. **Open Browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📱 Mobile Features

### Navigation
- **Three-Dot Menu**: Right-aligned hamburger menu on mobile
- **Full-Screen Overlay**: Slide-in menu with all navigation options
- **Touch Gestures**: Swipe to close menu functionality
- **CTA Button**: Prominent "Request a Quote" button in mobile menu

### Responsive Design
- **Tablet**: Optimized layouts for iPad and similar devices
- **Mobile**: Collapsible grids and touch-friendly interfaces
- **Performance**: Optimized animations for mobile devices

## 🎯 Business Information

### Company Details
- **Name**: Unimarx
- **Location**: KDA Avenue, Khulna, Bangladesh
- **Phone**: +880 1711 777 500
- **Email**: info@unimarx.com

### Products
- **Seafood**: Black Tiger Shrimp, White Shrimp
- **Vegetables**: Fresh Cauliflower, Premium Potatoes, Frozen Sweet Corn
- **Agro**: Basmati Rice, Agricultural commodities

### Certifications
- ISO 9001:2015
- HACCP Certified
- BRC Global Standards
- GlobalG.A.P

## 🎨 Design System

### Colors
- **Navy**: #002147 (Primary)
- **Emerald**: #006837 (Secondary)
- **Emerald Light**: #00a651 (Accent)
- **White**: #ffffff (Background)

### Typography
- **Font Family**: Inter
- **Weights**: 300, 400, 500, 600, 700, 800

### Components
- **Buttons**: Primary, Secondary, Outline variants
- **Cards**: Product cards, leadership cards, trust cards
- **Forms**: RFQ form with validation
- **Navigation**: Desktop and mobile variants

## 📊 Performance

### Optimization
- **Lazy Loading**: Images and components load as needed
- **Code Splitting**: Automatic with Next.js
- **Optimized Animations**: 60fps smooth transitions
- **Mobile Performance**: Optimized for mobile devices

### SEO
- **Meta Tags**: Optimized for search engines
- **Semantic HTML**: Proper heading structure
- **Alt Text**: Images with descriptive alt text
- **Structured Data**: JSON-LD for business information

## 🔧 Customization

### Adding Products
Edit `components/ProductHub.js` to add new products:

```javascript
{
  id: 7,
  name: 'New Product',
  scientificName: 'Scientific Name',
  category: 'Category',
  origin: 'Origin',
  season: 'Season',
  image: Icon,
  description: 'Product description',
  specs: {
    // Technical specifications
  }
}
```

### Updating Contact Info
Edit contact information in `components/Footer.js` and `components/ContactForm.js`.

### Customizing Colors
Update `tailwind.config.js` to modify the color scheme.

## 📞 Support

For support or customization requests:
- **Email**: info@unimarx.com
- **Phone**: +880 1711 777 500

---

© 2023 Unimarx. All rights reserved.
