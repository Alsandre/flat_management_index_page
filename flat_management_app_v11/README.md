# ჩვენი ბინები - Rental Property Platform Prototype

## 📋 Project Overview

This is a **mobile-first, multilingual-friendly HTML prototype** for a rental property self-service platform. Built specifically for a 6-property rental business in Batumi, Georgia, this prototype serves as a visual reference for developers to build the real application.

## ✨ Features

### 🏠 **Homepage (`index.html`)**

- Clean, welcoming design with gradient header
- Responsive property grid (1-4 columns based on screen size)
- 4 property cards with Georgian property data
- Language switcher placeholder (Georgian, English, Russian)
- Mobile-first responsive design

### 🏢 **Property Detail Page (`property-detail.html`)**

- Large photo carousel placeholder
- Comprehensive property information grid
- Price breakdown (July/August pricing)
- Expandable instructions section with:
  - How to find the property
  - Key location details
  - Lockbox code information
  - Additional amenities
- Prominent booking CTA button

### 📝 **Booking Form (`booking.html`)**

- Multi-section form with Georgian labels
- Personal information fields
- Date selection with automatic price calculation
- Guest count selection
- Special requests textarea
- Real-time price calculator
- Form validation
- Success confirmation message

### ⚙️ **Admin Panel (`admin.html`)**

- Simple login form (demo: admin/password123)
- Dashboard with statistics overview
- Property management cards
- Mini calendar visualization for each property
- Recent bookings list
- Status indicators (Available/Booked/Confirmed)

## 🏗️ **Technical Implementation**

### **Technology Stack**

- **HTML5** - Semantic structure
- **CSS3** - Mobile-first responsive design
- **Vanilla JavaScript** - Form handling and interactions
- **Noto Sans Georgian** - Georgian font support

### **Design Principles**

- ✅ Mobile-first responsive design
- ✅ Georgian as primary language
- ✅ Friendly, welcoming aesthetic (not corporate)
- ✅ Accessible color contrast
- ✅ Clean, modern UI with soft gradients
- ✅ Component-based CSS architecture

### **Responsive Breakpoints**

- **Mobile**: 320px+
- **Small**: 576px+
- **Medium**: 768px+
- **Large**: 992px+
- **Extra Large**: 1200px+

## 🏠 **Property Data Used**

### **ბინა 1 & 2 - ნიუ ვეივი**

- Address: ბათუმი, ჟიული შარტავას 10 (გმირთა ხეივანი)
- Type: სტუდიო (Studio)
- Floor: 14th
- Capacity: 4 guests
- Distance to sea: 5-7 minutes walk
- Pricing: July 100-110₾, August 120₾

### **ბინა 3 & 4 - მეტროსითი**

- Address: შერიფ ხიმშიაშვილის 65, მეტროსითთან
- Type: ცალკე საძინებლით (Separate bedroom)
- Floor: 15th (Property 3), 7th (Property 4)
- Capacity: 4 guests (Property 3), 3 guests (Property 4)
- Distance to sea: 3-4 minutes walk
- Pricing: August 130₾

## 🚀 **Getting Started**

### **Requirements**

- Modern web browser
- No server required (static HTML)

### **Installation**

1. Clone or download the project files
2. Open `index.html` in your web browser
3. Navigate through the pages using the links

### **File Structure**

```
flat_management_app_v11/
├── index.html           # Homepage with property grid
├── property-detail.html # Property detail page
├── booking.html         # Booking form
├── admin.html          # Admin panel
├── styles.css          # All CSS styles
└── README.md           # This file
```

## 🎯 **Demo Features**

### **Interactive Elements**

- **Property Cards**: Hover effects and smooth transitions
- **Expandable Sections**: Click to reveal property instructions
- **Form Validation**: Real-time validation for booking form
- **Price Calculator**: Automatic calculation based on dates
- **Admin Login**: Demo login (admin/password123)
- **Responsive Design**: Test on different screen sizes

### **Georgian Language Features**

- All content in Georgian (ქართული)
- Georgian font support (Noto Sans Georgian)
- Proper RTL considerations
- Multilingual expansion ready

## 📱 **Mobile Experience**

- **Touch-friendly**: Large buttons and touch targets
- **Fast loading**: Optimized images and minimal dependencies
- **Offline capable**: All resources included locally
- **Progressive enhancement**: Works without JavaScript

## 🎨 **Design System**

### **Colors**

- **Primary Gradient**: `#667eea → #764ba2`
- **Success**: `#28a745`
- **Background**: `#f8f9fa`
- **Text**: `#2c3e50`
- **Muted**: `#6c757d`

### **Typography**

- **Font Family**: Noto Sans Georgian, system fonts
- **Weights**: 300, 400, 500, 600
- **Responsive scaling**: 1.8rem mobile → 2.5rem desktop

## 📋 **Development Progress**

### ✅ **Completed Features**

- [x] Mobile-first HTML structure with semantic markup
- [x] Homepage with 4 property cards in Georgian
- [x] Property detail page with photo carousel and booking info
- [x] Booking form with Georgian form fields and price calculation
- [x] Admin panel mockup with login and dashboard
- [x] CSS styling with Georgian font support and friendly design
- [x] Responsive design testing and semantic HTML structure
- [x] Complete README documentation

### 🔄 **Future Enhancements** (For Real Implementation)

- [ ] Backend integration (Node.js/PHP)
- [ ] Database setup (MySQL/PostgreSQL)
- [ ] Payment processing
- [ ] Email/SMS notifications
- [ ] Real calendar system
- [ ] Photo upload functionality
- [ ] Multi-language switching
- [ ] User authentication
- [ ] Analytics integration

## 🤝 **Usage for Developers**

This prototype is designed to be a comprehensive visual and functional reference for building the real application. Key considerations:

1. **Component Architecture**: Each section is cleanly separated for easy component extraction
2. **CSS Classes**: Reusable class system for consistent styling
3. **JavaScript Patterns**: Simple, clear functions that can be expanded
4. **Georgian Content**: All text is properly localized and ready for internationalization
5. **Responsive Patterns**: Mobile-first approach with clear breakpoints

## 📞 **Support & Questions**

For questions about this prototype or implementation guidance:

- Review the code comments for implementation notes
- Check the CSS for responsive patterns
- Test all interactive features on different devices
- Use browser developer tools to inspect the structure

---

**Built with ❤️ for Georgian rental property management**
