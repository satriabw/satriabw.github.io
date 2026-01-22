# Personal Website Setup - Satria Bagus Wicaksono

## Completed Changes

### Site Configuration (_config.yml)
- ✅ Changed site title to "Personal Page"
- ✅ Updated name to "Satria Bagus Wicaksono"
- ✅ Updated description to "Software engineer | Applied deep learning | Research"
- ✅ Updated URL to https://satriabw.github.io
- ✅ Updated repository to satriabw/satriabw.github.io

### Sidebar (Author Profile)
- ✅ Removed profile picture (set avatar to empty string)
- ✅ Name: Satria Bagus Wicaksono
- ✅ Bio: "Software engineer | Applied deep learning | Research"
- ✅ Location: Belgium
- ✅ Institution: IMOB, UHasselt
- ✅ Email: contact@satriabw.dev
- ✅ Google Scholar: https://scholar.google.com/citations?user=k3686FsAAAAJ&hl=en
- ✅ LinkedIn: https://www.linkedin.com/in/satriabw/
- ✅ GitHub: https://github.com/satriabw
- ✅ Removed ORCID
- ✅ Removed PubMed
- ✅ Removed Bluesky

### Navigation Menu (_data/navigation.yml)
- ✅ Publications
- ✅ Portfolio
- ✅ Blog Posts (redirects to https://medium.com/@satriabw)
- ✅ CV
- ✅ Removed Talks, Teaching, Guide

### Content Pages
- ✅ Updated home page (_pages/about.md) with personal intro
- ✅ Updated Publications page with placeholder and Google Scholar link
- ✅ Updated Portfolio page with placeholder
- ✅ Updated CV page with overview and placeholder
- ✅ Updated footer with new text and date (2026-01-04)

### Cleanup
- ✅ Removed all example publications from _publications/
- ✅ Removed all example talks from _talks/
- ✅ Removed all example teaching materials from _teaching/
- ✅ Removed all example blog posts from _posts/
- ✅ Removed all example portfolio items from _portfolio/
- ✅ Removed unnecessary pages (talks, teaching, talkmap, markdown guide, etc.)
- ✅ Removed unnecessary root files (talkmap.py, .ipynb, docker files, etc.)
- ✅ Removed unnecessary directories (talkmap/, docs/, markdown_generator/, blog/)

## Still To Do

### Portfolio Content
- ✅ **Completed**: Added CV.pdf (from Profile.pdf) to files/ directory
- ✅ Portfolio page now links to CV PDF and GitHub
- 📝 **Optional**: Create individual portfolio project pages in _portfolio/ folder
  - Each project should be a markdown file with project details

### CV Content
- ✅ **Completed**: Profile.pdf copied to files/CV.pdf
- ✅ CV page now has download button for full PDF
- ✅ CV page includes basic structure with placeholders
- 📝 **Optional**: You can manually add more details to the CV page from the PDF

### Dark/Light Mode Toggle
- ⚠️ **Note**: The AcademicPages theme has built-in theme support (configured via site_theme in _config.yml)
- Available themes: "default", "air", "sunrise", "mint", "dirt", "contrast"
- For a true dark/light mode toggle, additional customization would be required

## Next Steps

1. **Review your website locally**:
   ```bash
   bundle exec jekyll serve
   ```
   Then visit http://localhost:4000

2. **Optional - Add Portfolio Items**: Create markdown files in `_portfolio/` following this format:
   ```markdown
   ---
   title: "Project Title"
   excerpt: "Short description"
   collection: portfolio
   ---
   
   Detailed project description...
   ```

3. **Optional - Expand CV page**: Add more details from your PDF to the CV page markdown

4. **Commit and push changes**:
   ```bash
   git add .
   git commit -m "Customize personal website with profile information"
   git push origin master
   ```

## What's Been Set Up

✅ Profile.pdf has been copied to `files/CV.pdf`  
✅ CV page includes a download button for the PDF  
✅ Portfolio page links to the CV PDF and your GitHub  
✅ All personal information updated  
✅ Navigation menu configured  
✅ Unnecessary files cleaned up  

## File Locations

- Configuration: `_config.yml`
- Navigation: `_data/navigation.yml`
- Pages: `_pages/`
- Profile HTML: `_includes/author-profile.html`
- Footer: `_includes/footer.html`
- Static files (PDFs, etc.): `files/`
- Images: `images/`
