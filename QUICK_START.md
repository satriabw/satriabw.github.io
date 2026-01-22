# Quick Start Guide

## Issues Fixed

✅ **Removed old index.html** - Your new about.md page will now be the home page
✅ **Created Gemfile** - Required for Jekyll to run

## Important: Ruby Version

Your system uses Ruby 2.6.10, which is too old for the latest gems. You have two options:

### Option 1: Just Deploy to GitHub (Recommended)

GitHub Pages will build your site automatically with the correct Ruby version. Simply:

```bash
git add .
git commit -m "Setup personal website"
git push origin master
```

Your site will be live at **https://satriabw.github.io** in a few minutes!

### Option 2: Test Locally (Requires Ruby 3.0+)

If you want to test locally before deploying, install a newer Ruby:

```bash
# Install rbenv and ruby-build
brew install rbenv ruby-build

# Install Ruby 3.2
rbenv install 3.2.0
rbenv local 3.2.0

# Verify
ruby --version

# Then install gems and run Jekyll
bundle install
bundle exec jekyll serve
```

## What's Changed

- ✅ Old portfolio index.html removed
- ✅ New Jekyll-based site active
- ✅ Gemfile created for dependencies
- ✅ Your personal information configured
- ✅ CV PDF ready at /files/CV.pdf

## Deploy Now

Since GitHub Pages will build everything correctly, you can deploy immediately:

```bash
git add .
git commit -m "Setup personal academic website"
git push origin master
```

Wait 1-2 minutes, then visit: **https://satriabw.github.io**
