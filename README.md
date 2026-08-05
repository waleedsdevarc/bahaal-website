# Bahaal

Public documentation site for Bahaal, a volunteer-led project in Gujranwala, Pakistan that repairs water pumps and leaks and installs low-cost solar and biogas systems for low-income and elderly families.

Live site: https://bahaalgrw.site

## Structure

Static HTML/CSS, no build step or framework.

```
index.html          Home page
approach/index.html Our Approach page
impact/index.html   Impact page
privacy/index.html  Privacy policy
style.css           Shared stylesheet
logo.svg            Site logo / favicon
og-image.png         Social share preview image
robots.txt, sitemap.xml, llms.txt
CNAME               GitHub Pages custom domain config
```

Pages use root-absolute links (e.g. `/approach/`) and folder-based
routing (`approach/index.html`) so URLs have no `.html` extension.

## Deployment

Hosted on GitHub Pages via the GitHub Actions workflow in
`.github/workflows/deploy.yml`. Any push to `main` redeploys the site
automatically.

## License

All rights reserved, see [LICENSE](LICENSE).
