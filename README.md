# Edward Newsome - Engineering Portfolio

Static website ready for GitHub Pages.

## Deploy in a few minutes

1. Create a new GitHub repository. For a personal site, the easiest option is:
   `YOUR-GITHUB-USERNAME.github.io`
2. Upload **all files and folders in this directory** to the repository.
3. In GitHub go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. GitHub will publish the site at your Pages address.

## Before / after deployment

The site works without any images, so it can be deployed immediately.

Replace these placeholders:
- `your.email@example.com` in `index.html`
- LinkedIn URL in `index.html`
- GitHub URL in `index.html`
- Add your CV as `assets/documents/Edward_Newsome_CV.pdf`

## Adding project photos

Put images in `assets/images/`, then replace a project's placeholder visual with an image.

Example:
```html
<div class="project-visual">
  <img src="assets/images/origami-facade.jpg" alt="Adaptive origami façade prototype">
</div>
```

You can then add CSS such as:
```css
.project-visual img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

## Updating the site

Everything is deliberately kept simple:
- `index.html` = text/content
- `style.css` = appearance/layout
- `assets/images/` = project images
- `assets/documents/` = CV and other documents

To add a new personal project, copy an existing `<article>` inside `.personal-grid`.
To add an achievement, copy an existing timeline item.

After editing locally, commit and push the changes to GitHub. GitHub Pages will redeploy the site.

## Suggested future additions

- Real project photography
- CAD screenshots / renders
- FEA and CFD plots
- Project-specific galleries
- Individual project pages
- Embedded GitHub/Kaggle links
- Custom domain
