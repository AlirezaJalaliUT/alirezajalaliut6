# Dr. Alireza Jalali — Website concept 06

A Jekyll / GitHub Pages and Pages CMS project with a visual layout modeled on the public faculty website [sabokrou.github.io](https://sabokrou.github.io/) as a user-requested reference. This project contains original HTML, CSS and JavaScript, its own scientific illustrations, and Dr. Jalali’s portrait. It does not import the other site’s assets or source code.

## Deployment
1. Create a **public** GitHub repository named `alirezajalaliut6` under `AlirezaJalaliUT`.
2. Upload the **contents of this archive** to the repository root. Include the hidden `.pages.yml`.
3. In **Settings > Pages**, select **Deploy from a branch**, branch `main`, folder `/(root)`.
4. Browse `https://alirezajalaliut.github.io/alirezajalaliut6/` after deployment.

`_config.yml` already uses `baseurl: /alirezajalaliut6`; local navigation and assets use Jekyll's `relative_url` filter. Previews are set `noindex`, and robots.txt disallows crawler visits to the demo path. Remove this for production.

## Editing
Log in to https://pagescms.org/ and connect the repository. Site settings and biography use `_data/*.yml`; research, projects, publications, people, teaching, awards, talks, news and positions are Jekyll collections. All entries require `published: true` to display; do not publish unverified claims. Upload portraits/files in Pages CMS.

## Local Jekyll build
`bundle install && bundle exec jekyll build` and optionally `bundle exec jekyll serve`. See `Gemfile`.

## Content integrity
Published records were carried over from previous drafts and should be verified against DOI/official university records before a final public launch. No student names, awards or grants were invented. The three scientific graphics are original conceptual SVG artwork, not photographs of the University of Tehran laboratory.
