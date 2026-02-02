# Academic Website for Dong Kyu Shin

This is a Jekyll-based academic website using the Minimal theme.

## Setup Instructions

1. **Update Social Links**
   - In `index.md`, replace the following placeholders with your actual URLs:
     - `YOUR_LINKEDIN_USERNAME` with your LinkedIn username
     - `YOUR_GOOGLE_SCHOLAR_ID` with your Google Scholar user ID
   
   To find your Google Scholar ID:
   - Go to your Google Scholar profile
   - Look at the URL: `https://scholar.google.com/citations?user=XXXXX`
   - Copy the value after `user=`

2. **Update _config.yml**
   - Also update the LinkedIn username and Google Scholar ID in `_config.yml`

3. **File Structure**
   ```
   /
   ├── _config.yml          # Jekyll configuration
   ├── index.md             # Main page content
   ├── assets/
   │   ├── profile.png      # Your profile photo
   │   ├── saxophone.png    # Saxophone photo
   │   └── css/
   │       └── style.scss   # Custom CSS styles
   └── README.md            # This file
   ```

4. **Testing Locally**
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
   Then visit `http://localhost:4000`

5. **Deploy to GitHub Pages**
   - Push all files to your GitHub repository
   - Enable GitHub Pages in repository settings
   - Select the main branch as source

## Key Features

- **Clean, professional layout** with profile photo and header section
- **Social media buttons** for Email, LinkedIn, and Google Scholar
- **Responsive design** that works on mobile and desktop
- **Easy to update** - just edit the markdown in `index.md`
- **Custom styling** that enhances the minimal theme

## Customization

- **Colors**: Edit the color values in `assets/css/style.scss`
- **Layout**: Modify the structure in `index.md`
- **Sections**: Add or remove sections as needed

## Notes

- Make sure your image files (`profile.png`, `saxophone.png`) are in the `/assets/` folder
- The custom CSS will automatically override the theme's default styles
- All links open in new tabs for external resources
