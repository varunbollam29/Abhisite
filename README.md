# Abhishek Iyer - Professional Portfolio Website

A modern, responsive portfolio website for Abhishek Iyer, showcasing his expertise in Learning & Development and Talent Transformation.

## Features

- **Modern Design**: Black background with cyan accents
- **Responsive Layout**: Works perfectly on all devices
- **Interactive Elements**: Smooth animations and hover effects
- **Professional Sections**: About, Services, Experience, and Contact
- **Mobile-Friendly Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Enhanced user experience with smooth navigation

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── [Your Image Files]  # Add your profile images here
```

## How to Add Your Profile Image

### Option 1: Replace the Placeholder (Recommended)

1. **Add your image file** to the project folder (e.g., `profile.jpg`, `abhishek-iyer.jpg`)
2. **Open `index.html`** and find this section (around line 50):

```html
<div class="hero-image">
    <!-- TODO: Add profile image here -->
    <div class="profile-placeholder">
        <i class="fas fa-user-circle"></i>
        <p>Add Profile Image Here</p>
        <small>Replace this placeholder with your professional photo</small>
    </div>
</div>
```

3. **Replace it with**:

```html
<div class="hero-image">
    <img src="your-image-filename.jpg" alt="Abhishek Iyer" class="profile-image">
</div>
```

4. **Add CSS for the image** in `styles.css` (replace the `.profile-placeholder` styles):

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #00d4ff;
    box-shadow: 0 10px 30px rgba(0, 212, 255, 0.3);
    transition: all 0.3s ease;
}

.profile-image:hover {
    transform: scale(1.05);
    box-shadow: 0 15px 40px rgba(0, 212, 255, 0.4);
}
```

### Option 2: Multiple Images

You can also add additional images throughout the website:

1. **About section image**: Add an image to the about section
2. **Service icons**: Replace Font Awesome icons with custom images
3. **Background images**: Add subtle background patterns

## Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `abhishek-iyer-portfolio`)
4. Make it public
5. Don't initialize with README (since we already have one)
6. Click "Create repository"

### Step 2: Upload Your Files

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/abhishek-iyer-portfolio.git
   cd abhishek-iyer-portfolio
   ```

2. **Copy all website files** into the repository folder:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
   - Your profile images

3. **Add and commit the files**:
   ```bash
   git add .
   git commit -m "Initial website upload"
   git push origin main
   ```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section (in the left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Website

Your website will be available at:
```
https://yourusername.github.io/abhishek-iyer-portfolio
```

## Customization Options

### Colors
The website uses a black and cyan color scheme. To change colors, edit these CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #00d4ff;
--secondary-color: #0099cc;
--background-color: #000000;
--text-color: #ffffff;
```

### Content Updates
- **Personal Information**: Update contact details in `index.html`
- **Experience**: Modify the timeline section with your latest experience
- **Services**: Add or remove services as needed
- **Quotes**: Update the inspirational quotes in service cards

### Adding New Sections
To add new sections (e.g., Testimonials, Blog, Projects):

1. Add the HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add navigation link in the navbar
4. Update JavaScript if needed for interactivity

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress your profile images before uploading
2. **Minimize Files**: Consider minifying CSS and JS for production
3. **CDN**: The website already uses CDN for Font Awesome and Google Fonts

## Support

If you need help with:
- Customization
- Adding new features
- Troubleshooting
- Hosting issues

Feel free to reach out or create an issue in the repository.

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: Remember to replace placeholder content with your actual information and add your professional profile image for the best presentation. 
--test--