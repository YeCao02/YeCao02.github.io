# Ye Cao Academic Homepage

This repository is a customized academic website built on top of the `AcadHomepage` Jekyll template for deployment on GitHub Pages.

## Site Structure

- `_config.yml`: global site settings, profile details, sidebar links
- `_data/navigation.yml`: top navigation links
- `_pages/about.md`: homepage content
- `_pages/publications.md`: full publications page
- `files/`: CV and downloadable attachments
- `images/`: avatar, paper thumbnails, and other site images

## Deployment Steps

1. Create or rename your GitHub repository to `F90Silenteagle.github.io`.
2. Copy this site into that repository.
3. Push the `main` branch to GitHub.
4. Open `Settings -> Pages`.
5. Set the publishing source to `Deploy from a branch`.
6. Select `main` and `/(root)`.
7. Wait for GitHub Pages to publish the site at `https://f90silenteagle.github.io/`.

## Daily Editing Workflow

### Update profile information

Edit `_config.yml` when you want to change:

- site title and description
- affiliation and location
- email, GitHub, WeChat, CV link
- avatar image path

### Update homepage sections

Edit `_pages/about.md` for:

- biography
- research interests
- selected publications
- projects
- talks
- awards
- education
- skills

### Update the publications page

Edit `_pages/publications.md` for:

- peer-reviewed articles
- manuscripts under review
- conference presentations

### Add a new paper with image or PDF

1. Upload the thumbnail image to `images/` or `images/papers/`.
2. Upload the PDF to `files/` or `files/papers/`.
3. Add or update the paper entry in `_pages/about.md` and `_pages/publications.md`.
4. Link the new image and PDF using site-relative paths such as `/images/papers/example.svg` or `/files/papers/example.pdf`.

## Local Preview

This site uses Jekyll. To preview locally you will need Ruby and Bundler installed, then run:

```bash
bundle exec jekyll serve
```

If you do not want to set up Ruby locally, you can still make small edits in GitHub's web editor and rely on GitHub Pages for publishing.

## Credits

- Based on [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)
- Influenced by [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)
- Influenced by [academicpages](https://github.com/academicpages/academicpages.github.io)
