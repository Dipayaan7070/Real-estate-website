# 🏠  Real Estate Website

A modern, responsive **real estate property website UI** built with **HTML5, CSS3, and JavaScript**. HappyHome is designed as a property discovery platform where users can explore homes for sale or rent, browse properties by city, view property information, and explore testimonials.

The project focuses on responsive frontend development, custom CSS layouts, interactive property sliders, mobile navigation, and a clean real-estate user interface.

---

## 🌐 Project Overview

HappyHome is a frontend real-estate website concept that provides a complete landing-page experience for buying and renting properties.

The website includes:

- Property search interface
- Buy and Rent sections
- Top property listings
- City-based property discovery
- Property image galleries
- Why Choose Us section
- Customer testimonials
- Mobile responsive navigation
- App download section
- Footer with contact and social links

The project is currently a **frontend UI implementation**. It does not use a backend, database, authentication system, or real property-search API.

---

## ✨ Main Features

### 🧭 Responsive Navigation

The header includes:

- HappyHome branding
- Home
- About
- Agents
- Testimonials
- Contact
- Sell Property CTA
- Search icon
- User/login icon
- Responsive hamburger menu

The mobile menu includes JavaScript-based open/close behavior, backdrop handling, Escape-key support, and scroll locking.

---

### 🔎 Property Search

The hero section contains a property search interface with filters for:

- City
- Property Type
- BHK
- Budget

Example property types include:

```text
Apartment
Villa
```

Example locations include:

```text
New York
London
```

The search interface is currently a UI/demo component and is not connected to a property database.

---

### 🏡 Buy Property

The Buy section allows the interface to showcase:

- Houses
- Flats
- Villas
- Townhouses

It includes a responsive text-and-image layout with a **Buy Now** call-to-action.

---

### 🏢 Rent Property

The Rent section provides a similar experience for rental properties.

It contains:

- Rental property information
- Property imagery
- Rent Now CTA
- Responsive image collage

---

### ⭐ Top Properties

The Top Properties section displays property cards containing:

- Property image
- Sale/Rent badge
- Property name
- BHK information
- Area in square feet
- City
- Price

Example listings include:

| Property | Type | Location | Price |
|---|---|---|---|
| Decent House | Sale | Bangalore | ₹69–74 Lacs |
| Modern Apartment | Rent | Mumbai | ₹42k/Month |
| Cozy Townhouse | Rent | Hyderabad | ₹30k/Month |
| Luxury Villa | Sale | Pune | ₹3.2 Cr |
| City Studio | Rent | Delhi | ₹18k/Month |
| Green Suburb Home | Sale | Chennai | ₹1.1 Cr |

> The property information in this project is sample/demo content for the frontend design.

---

### 🏙️ Explore Famous Cities

The website includes a city discovery section featuring:

- Kolkata
- Chennai
- Delhi
- Bangalore
- Mumbai
- Hyderabad

Each city card contains:

- City image
- City name
- Example property count

---

### 💡 Why Choose Us

The section highlights four major service benefits:

1. Find Your Future Home
2. Experienced Agents
3. Deal Closed
4. Verified By Our Team

---

### ⭐ Testimonials

The website includes an interactive testimonial carousel powered by **Swiper.js**.

Features include:

- Multiple testimonial cards
- Customer profile images
- Customer names
- Star ratings
- Automatic autoplay
- Responsive slide layout

---

### 📱 App Download Section

A dedicated section promotes a future mobile application with:

- Google Play badge
- Apple App Store badge
- App download CTA content

The store buttons currently point to the general Google Play and Apple App Store websites.

---

### 📞 Footer

The footer includes:

- HappyHome branding
- Contact information
- Company links
- Property services
- Social media icons
- Newsletter input
- Copyright information

---

## 🛠️ Technologies Used

### Core Technologies

- **HTML5**
- **CSS3**
- **JavaScript**

### Libraries & External Resources

- **Swiper.js 11** – testimonial carousel
- **Font Awesome** – icons
- **Bootstrap Icons** – search and interface icons
- **Google Fonts – Inter**

### Development Tools

- Visual Studio Code
- Git
- GitHub
- Live Server

---

## 📁 Project Structure

```text
Real_Estate/
│
├── index.html
├── style.css
│
└── images/
    ├── header Logo (1).png
    ├── Banner Image (2).png
    ├── Get Your Dream Home Easily.png
    ├── Properties Image 1.png
    ├── Properties Image 2.png
    ├── Properties Image 3.png
    ├── Buy Section Image 1.png
    ├── Buy Section Image 2.png
    ├── Buy Section Image 3.png
    ├── Kolkata.png
    ├── Chennai.png
    ├── Delhi.png
    ├── Bangalore.png
    ├── Mumbai.png
    ├── Hyderabad.png
    ├── Rent Section Image 1.png
    ├── Rent Section Image 2.png
    ├── Rent Section Image 3.png
    ├── Chose Us Background Image.png
    ├── Testimonial image 1.png
    ├── Testimonial images 2.png
    ├── Testimonial images 3.png
    ├── Footer background.png
    ├── Footer logo (2).png
    ├── Search Circle.png
    ├── User Login.png
    └── other image assets
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/happyhome-real-estate.git
```

### 2. Open the project

```bash
cd happyhome-real-estate
```

### 3. Run the website

Open `index.html` directly in a browser.

For development, the recommended option is **Live Server** in Visual Studio Code.

```text
Right Click index.html
        ↓
Open with Live Server
```

No backend server or database is required.

---

## 📱 Responsive Design

The project contains extensive responsive CSS media queries for different screen sizes.

Supported layouts include:

| Device | Support |
|---|---|
| Large Desktop | ✅ |
| Desktop | ✅ |
| Laptop | ✅ |
| Tablet | ✅ |
| Mobile | ✅ |
| Small Mobile | ✅ |
| 320px screens | ✅ |

The responsive implementation adjusts:

- Navigation
- Property cards
- Search form
- Image galleries
- Buy/Rent sections
- City cards
- Testimonials
- Footer
- Typography
- Spacing

---

## ⚙️ JavaScript Functionality

### Mobile Navigation

JavaScript controls the responsive navigation menu.

Features include:

- Open/close menu
- Mobile backdrop
- Escape key support
- Automatic menu closing after selecting a navigation link
- Responsive breakpoint handling
- Page scroll locking

### Top Property Slider

The Top Properties section uses custom JavaScript scrolling.

It supports:

- Previous/Next controls
- Smooth horizontal scrolling
- Dynamic card width calculation
- Responsive gap calculation
- Disabled navigation buttons at scroll limits
- Keyboard arrow navigation
- ResizeObserver for responsive updates

### Testimonial Slider

Swiper.js provides:

- Automatic autoplay
- Multiple slides
- Responsive presentation
- Smooth transitions

---

## 🎨 Design & Layout

The project uses a custom CSS layout system instead of relying on a complete CSS framework.

Custom column classes include:

```text
.col100
.col80
.col60
.col50
.col45
.col40
.col35
.col33
.col30
.col25
.col20
```

The main content container uses a maximum width of:

```css
.container {
    max-width: 1430px;
    margin: 0 auto;
}
```

The design primarily uses an orange/gold accent color:

```css
--color-primary: #ffa600;
```

The Inter font is used throughout the interface.

---

## 📚 Learning Outcomes

This project demonstrates practical experience with:

- Semantic HTML5
- Advanced CSS layouts
- CSS Flexbox
- CSS Grid
- Responsive web design
- Custom responsive breakpoints
- CSS variables
- Image positioning and cropping
- Property card UI design
- Horizontal scrolling interfaces
- JavaScript DOM manipulation
- JavaScript event handling
- Responsive navigation
- Swiper.js integration
- Accessibility attributes
- Lazy-loaded images
- Mobile-first UI considerations

---

## ⚠️ Current Limitations

This project is currently a **frontend real-estate UI**, not a production property marketplace.

The following features are not connected to a backend:

- Property search
- Property filtering
- Buy/Rent actions
- User authentication
- User registration
- Agent management
- Property submission
- Property database
- Newsletter subscription
- Contact form
- Payment processing

Several navigation and CTA links currently use `#` as placeholders.

Some text and testimonial content is also placeholder/demo content.

---

## 🔮 Future Improvements

Possible future development:

- [ ] Connect property search to a backend
- [ ] Add property filtering
- [ ] Add property detail pages
- [ ] Add property database
- [ ] Add user registration/login
- [ ] Add agent profiles
- [ ] Add property listing submission
- [ ] Add favorites/wishlist
- [ ] Add location-based search
- [ ] Add Google Maps integration
- [ ] Add contact form backend
- [ ] Add newsletter subscription
- [ ] Add real authentication
- [ ] Add payment/booking functionality
- [ ] Add admin dashboard
- [ ] Improve SEO
- [ ] Optimize images
- [ ] Deploy the website

---

## 👨‍💻 Author

**Dipayan Chowdhury**

Frontend Developer

### Skills Demonstrated

```text
HTML5
CSS3
JavaScript
Responsive Web Design
CSS Flexbox
CSS Grid
Swiper.js
Font Awesome
Bootstrap Icons
Git
GitHub
```

---

## 📄 License

This project was created for **learning, practice, and portfolio purposes**.

Images, logos, icons, and other third-party assets should be used according to their respective ownership and licensing terms.

---

⭐ If you like this project, consider giving the repository a star.
