# Glam Products Landing Page

A professional product advertisement landing page with WhatsApp integration.

## Features

- **Responsive Design** - Works seamlessly on all devices (desktop, tablet, mobile)
- **Theme Integration** - Uses all styling from the assets folder:
  - Colors from `mainffaf.css` CSS variables (--tp-theme-primary, --tp-theme-secondary, etc.)
  - Fonts: Kumbh Sans (from assets/fonts folder)
  - Buttons with theme button styles
  - Professional animations using WOW.js
- **WhatsApp Integration** - Multiple contact buttons linking to: `https://api.whatsapp.com/send/?phone=%2B233246493903`
- **Product Showcase** - 6 featured products with images from assets/img/project/
- **Video Section** - Area for product demonstration videos
- **Gallery Section** - Additional product images from assets/img/banner/
- **Floating WhatsApp Button** - Always visible for easy contact
- **Smooth Animations** - WOW.js animations on scroll

## Structure

### Header
- Logo (from assets/img/logo/)
- WhatsApp contact button
- Sticky navigation

### Hero Section
- Eye-catching gradient using theme colors
- Main call-to-action button
- Animated title and subtitle

### Products Section
- 6 product cards with:
  - Product images
  - Product badges (New, Hot, Trending, Sale)
  - Descriptions
  - Individual "Order Now" buttons with pre-filled WhatsApp messages

### Video Section
- Responsive video player
- Replace `your-video.mp4` with your actual video file
- Or use YouTube embed (commented in code)

### Gallery Section
- 3 additional product images
- Hover effects

### Footer
- Company information
- WhatsApp contact button
- Copyright notice

## Customization

### To Add Your Video:
1. Add your video file to the project folder
2. Update line 569: `<source src="your-video.mp4" type="video/mp4">`

Or use YouTube:
1. Uncomment line 573
2. Replace `YOUR_VIDEO_ID` with your YouTube video ID

### To Change Products:
Edit the product cards in the Products Section (starting at line 454):
- Update product images: `src="assets/img/project/X.png"`
- Change product titles and descriptions
- Modify WhatsApp messages in the `&text=` parameter

### Theme Colors Used:
- Primary: `--tp-theme-primary` (#d90a2c - Red)
- Secondary: `--tp-theme-secondary` (#0f0d1d - Dark)
- Text: `--tp-text-body` (#55585B - Grey)
- Background: `--tp-grey-1` (#F6F7F9 - Light Grey)

## Assets Used

### CSS Files:
- bootstrap.css
- font-awesome-pro.css
- flaticon_tecz.css
- animate.css
- magnific-popup.css
- swiper-bundle.css
- slick.css
- spacing.css
- mainffaf.css (Main theme file)

### JS Files:
- jQuery
- Bootstrap Bundle
- Swiper
- Slick
- Magnific Popup
- WOW.js (animations)
- Main theme JS

### Images:
- Logo: assets/img/logo/logo_black.png, logo_white.png
- Products: assets/img/project/ (1.png, 3.png, 5.png, 7.png, 9.png, 11.png)
- Banners: assets/img/banner/ (2x.png, 3x.png, 4x.png, 5x.png)

### Fonts:
- Kumbh Sans (Google Fonts)
- Font Awesome Pro (icons)
- Flaticon (custom icons)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Notes

- All WhatsApp links include the phone number: +233246493903
- Product images are from assets/img/project/ folder
- Animations trigger on scroll using WOW.js
- Fully responsive with mobile-first approach
