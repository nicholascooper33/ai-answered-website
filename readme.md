# AI Answered Website

Modern, professional website for AI Answered - Leading AI education provider for UK businesses.

## 🎨 Features

- **Modern Design**: Bold, distinctive aesthetic with blue and yellow brand colors
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Subtle scroll animations and hover effects
- **Fast Loading**: Optimized static HTML/CSS/JS
- **Easy to Maintain**: Simple structure, easy to update content
- **Blog Ready**: Blog page with placeholder posts ready for your content

## 📁 Files Included

- `index.html` - Main homepage
- `blog.html` - Blog page
- `styles.css` - Main stylesheet
- `blog.css` - Blog-specific styles
- `script.js` - JavaScript for interactions and animations
- `README.md` - This file

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended - FREE)

1. Create a GitHub account at https://github.com
2. Create a new repository called `ai-answered-website`
3. Upload all files to the repository
4. Go to Settings > Pages
5. Under "Source", select "main" branch
6. Click Save
7. Your site will be live at `https://yourusername.github.io/ai-answered-website`

**To add a custom domain:**
- In GitHub Pages settings, add your domain (e.g., `www.aianswered.co.uk`)
- Update your domain's DNS settings as instructed by GitHub

### Option 2: Netlify (Also FREE)

1. Sign up at https://netlify.com
2. Drag and drop your website folder
3. Your site goes live instantly!
4. Free custom domain connection included

### Option 3: Vercel (Also FREE)

1. Sign up at https://vercel.com
2. Import your GitHub repository or upload files
3. Automatic deployment on every update

## ✏️ Customizing Your Website

### 1. Add Your Calendar Booking Link

In `index.html`, find this line (appears twice):
```html
<a href="CALENDAR_LINK_HERE" ...>
```
Replace `CALENDAR_LINK_HERE` with your actual booking link (e.g., Calendly, Cal.com).

### 2. Update Testimonials

In `index.html`, find the `testimonials` section and replace the placeholder testimonials with real ones:
```html
<div class="testimonial-card">
    <div class="testimonial-content">
        <p class="testimonial-text">
            "Your actual testimonial here..."
        </p>
    </div>
    <div class="testimonial-author">
        <div class="author-info">
            <div class="author-name">Client Name</div>
            <div class="author-title">Client Title, Company</div>
        </div>
    </div>
</div>
```

### 3. Update Statistics

In `index.html`, find the "about-stats" section and update the numbers:
```html
<div class="stat-number">100%</div>
<div class="stat-label">Your Stat Label</div>
```

### 4. Change Brand Colors (Optional)

In `styles.css`, find the `:root` section at the top:
```css
:root {
    --primary-blue: #0052FF;    /* Your blue */
    --primary-yellow: #FFD600;  /* Your yellow */
    /* ... */
}
```
Replace with your exact brand colors.

### 5. Update Contact Information

Add your email, phone, or social media links in the footer section of `index.html`.

### 6. Add Blog Posts

When ready to add actual blog posts:

**Option A: Manual Updates**
1. Open `blog.html`
2. Edit the placeholder posts with your content
3. Create individual blog post pages if needed

**Option B: Substack Integration**
1. Create your Substack at https://substack.com
2. Add an embed or link in `blog.html`
3. You can replace the entire blog section with a Substack embed

## 🔧 Technical Notes

### Browser Support
- Chrome, Firefox, Safari, Edge (all modern versions)
- Internet Explorer: Not supported (by design - it's 2024!)

### Performance
- No dependencies except Google Fonts
- Optimized CSS and JavaScript
- Fast load times (<2 seconds on decent connection)

### SEO Ready
The site includes:
- Semantic HTML5
- Proper meta tags
- Clean URL structure
- Fast loading times

### Accessibility
- Proper heading hierarchy
- Keyboard navigation support
- Sufficient color contrast
- Responsive design

## 📝 Content Tips

### Writing for Your Homepage
- Keep hero message clear and benefit-focused
- Use real client testimonials (with permission)
- Update stats regularly to maintain credibility
- Make your value proposition immediately clear

### Blog Best Practices
- Post consistently (weekly or bi-weekly)
- Focus on practical, actionable advice
- Use real examples from your work
- Keep posts around 800-1,500 words
- Include clear calls-to-action

## 🎯 Next Steps

1. **Immediate**:
   - Add your calendar booking link
   - Replace testimonials with real ones
   - Update any placeholder text

2. **Week 1**:
   - Set up hosting (GitHub Pages recommended)
   - Connect custom domain if you have one
   - Test on mobile devices
   - Share with team for feedback

3. **Ongoing**:
   - Start writing blog posts
   - Collect more testimonials
   - Update case studies
   - Track analytics (add Google Analytics if needed)

## 🆘 Need Help?

### Common Issues

**Q: How do I change the text?**
A: Open the HTML files in any text editor and edit directly.

**Q: The colors look different on my screen**
A: Colors can vary between displays. Test on multiple devices.

**Q: How do I add more pages?**
A: Copy `blog.html`, rename it, and update the content. Link to it from the navigation.

**Q: Can I use WordPress instead?**
A: Yes, but this static site is faster, more secure, and free to host. Consider starting here.

### Making Updates
1. Edit the HTML/CSS files locally
2. Test in your browser (just open index.html)
3. Upload changes to GitHub/Netlify/Vercel
4. Changes go live automatically

## 📊 Analytics (Optional)

To track visitors, add Google Analytics:
1. Get your tracking code from Google Analytics
2. Add it to the `<head>` section of both HTML files
3. Monitor traffic and user behavior

## 💡 Future Enhancements

Ideas for later:
- Add a contact form (use Formspree or similar)
- Integrate with CRM (HubSpot, Pipedrive)
- Add live chat widget
- Create more case study pages
- Add video testimonials
- Build a resources library

## 📄 License

This website is built for AI Answered. All content and branding © AI Answered.

---

**Built with care for AI Answered** 🚀

For questions about the website, refer to this README or reach out to your web developer.