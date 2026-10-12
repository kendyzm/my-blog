# [SITE NAME] — static affiliate blog starter

A polished, responsive starter site built with plain HTML, CSS, and JavaScript. It has no build step, framework, or required paid service. Open the folder in Visual Studio Code and edit the files directly.

> **Before publishing:** Search for bracketed placeholders such as `[SITE NAME]`, `[YOUR-DOMAIN]`, `[YOUR-EMAIL]`, `[AUTHOR NAME]`, and `[MONTH YEAR]` and replace them. Sample article copy is a structure to customize, not verified advice. Example affiliate URLs are nonfunctional placeholders and are not real recommendations or relationships. Review the disclosure and privacy pages for accuracy before launch.

## What’s included

```text
static-affiliate-blog-starter/
├── index.html
├── about.html
├── contact.html
├── resources.html
├── affiliate-disclosure.html
├── privacy-policy.html
├── sitemap.xml
├── robots.txt
├── README.md
├── articles/
│   ├── guide-one.html
│   ├── guide-two.html
│   └── guide-three.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
    └── README.md
```

## Preview locally

1. Extract the ZIP file.
2. In Visual Studio Code, choose **File → Open Folder…** and select `static-affiliate-blog-starter`.
3. For a quick preview, open `index.html` in a browser. For a smoother editing workflow, install the **Live Server** extension in VS Code, right-click `index.html`, and choose **Open with Live Server**. The extension is optional.
4. Edit a page and refresh the browser. Keep the folder structure intact so the relative CSS, JavaScript, and article links keep working.

## Customize before publishing

1. Pick your site name, topic, author name, contact email, and canonical domain. Replace the bracketed placeholders across all files.
2. Replace sample copy with original, accurate material. Verify current product details and cite trustworthy sources where useful. Don’t claim testing, credentials, or results you haven’t established.
3. Add your own optimized images in `images/`; update page markup with the correct relative paths and useful alt text.
4. Replace example resource URLs with your actual destination links. Use `rel="sponsored nofollow noopener"` for paid or affiliate links that open in a new tab, and disclose the relationship clearly near relevant recommendations.
5. Customize the privacy policy and affiliate disclosure to match your actual practices and audience. The included examples are starter copy, not legal advice.
6. Update canonical URLs in page `<head>` elements, plus `sitemap.xml` and `robots.txt`, to use the same real HTTPS domain.
7. Check all navigation, contact details, headings, mobile layouts, and links. The contact page is email-only; no form or backend is included.

## Publish with GitHub and Cloudflare Pages

This workflow uses GitHub to store the files and Cloudflare Pages to host them. Both offer free options; availability, limits, and product steps can change, so check the providers’ current screens and terms.

### 1. Put the project in a GitHub repository

1. Create or sign in to a GitHub account.
2. Create a new repository, for example `my-blog`. If you create an empty repository, keep its initial README/license options unchecked to make the first upload straightforward.
3. In the repository, choose **Add file → Upload files** and upload the *contents* of this starter folder so `index.html` sits at the repository root. Alternatively, use Git from VS Code to create a repository and push it to GitHub.
4. Commit the files to the repository’s `main` branch. Keep private details out of a public repository.

### 2. Connect the repository to Cloudflare Pages

1. Sign in to Cloudflare and open **Workers & Pages** (the exact navigation label may change).
2. Create a Pages project and connect the GitHub repository you just created. Authorize access when prompted.
3. Choose the `main` production branch. For this plain static site, no build command is needed. Leave the build command blank; if the setup screen requires an output directory, use `/` (the repository root).
4. Start the first deployment. Cloudflare will provide a preview address under a `pages.dev` domain; open it and check the site.
5. Add your custom domain in the Pages project’s custom domain settings and follow Cloudflare’s prompts. Enable HTTPS using the provider’s guidance. Update the site’s canonical URLs, `sitemap.xml`, and `robots.txt` to match the domain you actually use.

### 3. Make updates

Edit the files in VS Code, then commit and push the changes to GitHub. Cloudflare Pages will deploy the connected branch automatically. Review the live site after each deployment.

## Editing tips

- Each page is a normal `.html` file. Duplicate an article file to add another article, then update its title, description, canonical URL, navigation, and sitemap entry.
- Shared visual styles live in `css/style.css`; the mobile navigation and footer year live in `js/main.js`.
- Keep article and page links relative (for example `../resources.html` from inside `articles/`) so local preview and hosted pages work without a build step.
- Google Fonts are loaded from an external service. If you prefer not to make that request, remove the `@import` at the top of `css/style.css`; the system serif and sans-serif fallbacks will remain.

## Launch checklist

- [ ] No bracketed placeholders remain in the site files.
- [ ] Your real contact email and domain are correct.
- [ ] Sample text has been rewritten and fact-checked.
- [ ] Affiliate links and disclosures match real relationships.
- [ ] Privacy information reflects the services and data practices you actually use.
- [ ] Sitemap, robots file, canonical tags, and custom domain agree.
- [ ] Every page and link has been checked on a phone and desktop.
