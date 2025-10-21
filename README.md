# AR Events by Tayal Caterers - Website

A vibrant, festive website for AR Events by Tayal Caterers, a premium catering service based in Meerut, Uttar Pradesh.

## 🎉 Features

### Design
- **Festive Indian Theme**: Rich red/maroon and gold color scheme with traditional Indian design elements
- **Responsive Design**: Fully responsive across desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional layout with smooth animations and transitions
- **Hinglish Content**: Mix of Hindi and English to connect with local audience

### Sections
1. **Home/Hero**: Eye-catching hero section with animated statistics
2. **Services Preview**: Quick overview of main service categories
3. **Why Choose Us**: Key features and benefits
4. **About Us**: Company background and values
5. **Services**: Detailed breakdown of all services
   - Wedding Events (Mehendi, Sangeet, Wedding, Reception)
   - Social Functions (Birthdays, Anniversaries, etc.)
   - Corporate Events
6. **Menu**: Comprehensive food menu with categories
   - Starters (Veg & Non-Veg)
   - Main Course (North Indian, South Indian, Chinese, Continental)
   - Breads & Rice
   - Desserts
   - Live Counters
7. **Gallery**: Filterable image gallery with lightbox
8. **Testimonials**: Customer reviews and ratings
9. **Contact**: Contact form with WhatsApp integration

### Interactive Features
- Mobile-responsive navigation with hamburger menu
- Smooth scrolling navigation
- Animated statistics counter
- Gallery filtering system
- Image lightbox for gallery
- Form validation with WhatsApp integration
- Scroll-to-top button
- WhatsApp floating button
- Lazy loading for images
- Fade-in animations on scroll

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, animations
- **JavaScript (Vanilla)**: Interactive features without dependencies
- **Font Awesome**: Icons
- **Google Fonts**: Poppins & Roboto fonts
- **Unsplash**: Placeholder images

## 📁 File Structure

```
Website/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # All styles
├── js/
│   └── script.js      # All JavaScript functionality
└── README.md          # This file
```

## 🚀 Getting Started

1. **Open the website**:
   - Simply open `index.html` in any modern web browser
   - Or use a local server for better performance

2. **Using a local server** (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the website**:
   - Open browser and navigate to `http://localhost:8000`

## 📝 Customization Guide

### Update Contact Information

In `index.html`, search and replace:
- Phone: `+91 98765 43210`
- Email: `info@arevents.com`
- Address: `Shop No. 123, Gandhi Nagar, Meerut, Uttar Pradesh - 250001`

In `js/script.js`, update WhatsApp number:
- Line ~220: `const whatsappNumber = '919876543210';`

### Update Social Media Links

In `index.html`, find the social media sections and update `href="#"` with actual URLs:
- Facebook
- Instagram
- YouTube
- Twitter

### Replace Images

Replace Unsplash URLs with your own images:
1. Gallery images: Update `src` attributes in gallery section
2. Service images: Update in services section
3. About image: Update in about section

### Modify Colors

In `css/style.css`, update CSS variables:
```css
:root {
    --primary-color: #C41E3A;    /* Main red/maroon */
    --secondary-color: #FFD700;   /* Gold */
    --accent-color: #FF6B35;      /* Orange */
    --bg-cream: #FFF8F0;          /* Background cream */
}
```

### Update Menu Items

Edit the menu section in `index.html` to add/remove dishes.

## 🎨 Color Scheme

- **Primary**: #C41E3A (Deep Red/Maroon) - Traditional Indian wedding color
- **Secondary**: #FFD700 (Gold) - Festive and auspicious
- **Accent**: #FF6B35 (Orange) - Vibrant and energetic
- **Background**: #FFF8F0 (Cream) - Warm and inviting
- **Text**: #2C1810 (Dark Brown) - Easy to read

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ✨ Key Features Explained

### WhatsApp Integration
- Contact form submissions open WhatsApp with pre-filled message
- Floating WhatsApp button for quick contact
- Form data is formatted and sent via WhatsApp

### Gallery Filtering
- Click filter buttons to show specific categories
- Smooth transitions between filtered states
- Lightbox view for enlarged images

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 968px
- Touch-friendly navigation on mobile

### Performance Optimizations
- Lazy loading for images
- Debounced scroll events
- Intersection Observer for animations
- Minimal external dependencies

## 🔧 Future Enhancements

Potential additions:
- Backend integration for form submissions
- Admin panel for content management
- Online booking system
- Payment gateway integration
- Multi-language support
- Blog section
- Customer portal
- Real-time chat support

## 📞 Support

For any questions or support regarding this website:
- **Phone**: +91 98765 43210
- **Email**: info@arevents.com
- **Location**: Meerut, Uttar Pradesh

## 📄 License

This website is created for AR Events by Tayal Caterers. All rights reserved.

---

**Made with ❤️ in Meerut**

*Aapke Har Khushi Ke Pal Ko Banaye Yaadgaar*
