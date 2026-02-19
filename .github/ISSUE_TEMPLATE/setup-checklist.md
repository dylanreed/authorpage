---
name: Set Up Your Author Site
about: Follow this checklist to personalize your new website
title: "Set up my author site"
labels: setup
---

# Welcome to your new author website!

Follow these steps to make it yours. Check each box as you go.
Your site rebuilds automatically every time you save a file (give it about 60 seconds to update).

## Step 1: Pick your theme

- [ ] Open `config.yaml` (click the pencil icon to edit)
- [ ] Find the line that says `theme: "inkwell"`
- [ ] Change it to one of: `inkwell`, `paperback`, or `typewriter`
  - **Inkwell** — Clean and literary, lots of white space, serif fonts
  - **Paperback** — Bold and commercial, book covers front-and-center
  - **Typewriter** — Retro and dark, monospace fonts, vintage feel
- [ ] Click "Commit changes" at the bottom

## Step 2: Add your information

- [ ] Open `data/site.yaml` (click the pencil icon to edit)
- [ ] Replace `Jane Author` with your name
- [ ] Replace the tagline with your own
- [ ] Replace the bio with your own (a few sentences about you)
- [ ] Update the social media links (delete any you don't use)
- [ ] Update the contact email
- [ ] Click "Commit changes"

## Step 3: Add your author photo

- [ ] Click on the `static/images/` folder
- [ ] Click "Add file" -> "Upload files"
- [ ] Upload your author photo and name it `author.jpg`
- [ ] Click "Commit changes"

## Step 4: Add your books

- [ ] Open `data/books.yaml` (click the pencil icon to edit)
- [ ] Replace the example books with your own
- [ ] For each book, fill in: title, tagline, description, published year
- [ ] Upload cover images to `static/images/` (same process as your photo)
- [ ] Update the `cover:` path to match your image filename
- [ ] Add your buy links (Amazon, Bookshop.org, etc.)
- [ ] Set `featured: true` on the ONE book you want on your home page
- [ ] Click "Commit changes"

## Step 5: Check your site!

- [ ] Visit `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`
- [ ] It may take a minute for the first build to complete
- [ ] If you see a 404, go to Settings -> Pages and make sure the Source is set to "GitHub Actions"

## Need help?

If something isn't working, open a new issue and describe what you see. We're happy to help!
