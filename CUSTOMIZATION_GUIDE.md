# Website Customization Guide

## Overview
This is your customized personal portfolio website template. I've replaced all of Giacomo's personal information with placeholder text that you can fill in with your own details.

## Files You Need to Customize

### 1. Personal Information (HTML Files)
Replace these placeholders in **all HTML files** (`index.html`, `projects.html`, `timeline.html`, `quotes.html`):

- `[YOUR NAME]` → Your full name
- `[YOUR TITLE/ROLE]` → Your current position/title (e.g., "Software Engineer", "Data Scientist", "Student")
- `[YOUR_NAME]_CV.pdf` → Your CV filename (upload your CV to `assets/docs/`)

### 2. Profile Section (`index.html`)
Replace these in the hero section:
- `[YOUR ROLE 1]` → Your primary role/identity
- `[YOUR ROLE 2]` → Secondary role/skill
- `[YOUR ROLE 3]` → Another role/skill
- `[YOUR INTEREST]` → Something you're passionate about
- `[PERSONAL DETAIL]` → Fun personal detail or achievement

Replace the biography paragraphs with your own story:
- Education background
- Career goals and interests
- Organizations/projects you're involved in
- Current work or research

### 3. Projects (`assets/projects.json`)
Replace the template projects with your own:

```json
{
    "title": "Your Project Name",
    "date": "Month Year",
    "tags": "Technology1, Technology2, Category",
    "description": "Brief description of what this project does",
    "links": {
        "Code": "https://github.com/your-username/repo",
        "Demo": "https://your-demo-link.com",
        "Report": "assets/docs/your-report.pdf"
    }
}
```

### 4. Timeline (`assets/timeline.json`)
Add your career and education milestones:

```json
{
    "date": "Month Year",
    "event": "What happened (e.g., Started working at Company X)"
}
```

### 5. Quotes (`assets/quotes.json`)
Add quotes that inspire you:

```json
{
    "text": "Your favorite quote",
    "author": "Author Name",
    "source": "Book/Speech/etc",
    "year": "Year"
}
```

## Files You Need to Replace

### 1. Profile Picture
Replace `assets/img/profile-pic.png` with your own profile picture
- Keep the same filename, or update the reference in `index.html`
- Recommended: Square aspect ratio, good quality

### 2. CV and Documents
- Upload your CV as `assets/docs/[YOUR_NAME]_CV.pdf`
- Remove Giacomo's documents from `assets/docs/`
- Add any of your own documents (thesis, reports, etc.)

## Additional Customizations

### 1. Colors and Styling
Edit `main.css` to change:
- Color scheme (search for CSS variables in `:root`)
- Fonts
- Layout adjustments

### 2. Navigation
If you want to add/remove sections, update the navigation in all HTML files:
```html
<li><a href="your-new-page.html">New Section</a></li>
```

### 3. Footer and Social Links
Check `footer.html` and `main.js` for social media links if you want to add them.

## Steps to Get Started

1. **Replace Personal Info**: Go through each HTML file and replace `[YOUR NAME]` and `[YOUR TITLE/ROLE]`

2. **Update Biography**: Edit the About Me section in `index.html`

3. **Add Your Projects**: Edit `assets/projects.json` with your own projects

4. **Create Your Timeline**: Edit `assets/timeline.json` with your milestones

5. **Add Your Quotes**: Edit `assets/quotes.json` with quotes you like

6. **Replace Images**: Add your profile picture to `assets/img/`

7. **Upload Documents**: Add your CV and any documents to `assets/docs/`

8. **Test**: Open `index.html` in a browser to see your customized website

## Technical Notes

- The website uses Bootstrap for responsive design
- JavaScript files (`main.js`) handle dynamic content loading
- AOS library provides scroll animations
- Font Awesome for icons

## Need Help?

If you run into any issues or want to make more advanced customizations, feel free to ask for help with specific changes!

## Example Customization

Here's an example of how to fill in the placeholders:

**Before:**
```
[YOUR NAME] → John Smith
[YOUR TITLE/ROLE] → Full Stack Developer
```

**After:**
```html
<h1 class="hero-title">John Smith</h1>
<h2 class="hero-subtitle">Full Stack Developer</h2>
``` 