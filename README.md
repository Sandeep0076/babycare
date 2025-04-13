# Gentle Hands Vietnam - Baby Care Website

A multilingual (Vietnamese/English) single-page website for "Gentle Hands Vietnam," a professional baby care agency. The website showcases the agency's services, qualifications, and contact information in both Vietnamese and English.

![Gentle Hands Vietnam Website](media/hero-image.jpg)

## Features

- **Fully Bilingual**: Seamlessly switch between Vietnamese (default) and English
- **Responsive Design**: Optimized for all devices (mobile, tablet, desktop)
- **Modern UI**: Clean, professional design with soft colors appropriate for childcare
- **Service Showcase**: Detailed information about newborn, infant, and toddler care services
- **Professional Qualifications**: Information about staff training and expertise
- **Image Gallery**: Visual representation of the care environment
- **Contact Form**: Easy way for potential clients to reach out

## Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML/CSS/JavaScript if you plan to modify the site

### Setup
1. Clone the repository:
```bash
git clone https://github.com/Sandeep0076/babycare.git
```

2. Navigate to the project directory:
```bash
cd babycare
```

3. No build process or dependencies required - this is a simple HTML/CSS/JS website.

## Running the Website

### Local Development
1. Open the project folder and double-click on `index.html`, or
2. Use a local development server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (after installing http-server)
   npx http-server
   ```
3. Visit `http://localhost:8000` in your browser

### Production Deployment
- Upload all files to your web hosting service
- Ensure all files maintain their relative paths
- No server-side processing is required as this is a static website

## Language Switching

The website defaults to Vietnamese and allows users to switch to English:

- Language preference is stored in the browser's local storage
- Clicking the language toggle buttons (VI/EN) in the header changes the language
- All text content is managed through a translation system in the JavaScript file

## Project Structure

```
babycare/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality including translations
├── media/              # Images and other media files
└── README.md           # This documentation file
```

## Technologies Used

- **HTML5**: For structure and content
- **CSS3**: For styling and responsive design
- **JavaScript**: For language switching and interactive elements
- **Font Awesome**: For icons
- **Google Fonts**: For typography

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Customization

To customize the website:

1. **Content**: Edit the translation dictionaries in `script.js` to change text content
2. **Styling**: Modify `styles.css` to change colors, fonts, and layout
3. **Images**: Replace images in the `media` folder with your own (maintain the same filenames or update references in HTML)

## License

This project is available for use by Gentle Hands Vietnam.

## Contact

For questions or support regarding this website, please contact:
- Email: [your-email@example.com]
- GitHub: [https://github.com/Sandeep0076](https://github.com/Sandeep0076)
