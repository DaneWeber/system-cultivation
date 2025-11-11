# Brochure Website

Expected engineering practices that may only be noticed after launch or immediately before.

Issues you will be asked about:

- "Why is the site slow?"
- "Why doesn't Twitter show a preview when I share the link?"
- "Why doesn't Google rank our site well?"
- "Why does the site look broken on my phone?"
- "How many people have visited the site today?"
- "Why are we getting an error now when the site was working fine before?"

Prepare to answer these questions by following best practices during development:

- Test on multiple browsers and devices, especially mobile from the start.
  - Set up automated testing across devices. In 2025, some of the options include BrowserStack, Sauce Labs, TestingBot, and Perfecto.
  - Automated testing might seem excessive for a brochure website, but it can catch layout issues that only appear on specific devices or browsers. It is also important to detect unintended consequences to changes intended to have limited scope.
  - Developers are tempted to use a single desktop browser for testing throughout, which leads to difficult-to-fix issues late in the project.
- Metadata
  - Social sharing metadata (Open Graph, Twitter Cards), especially the preview image.
  - SEO best practices implemented (meta tags, alt text, etc.).
  - Favicon
  - Sitemap.xml and robots.txt files.
- Hosting and CDN setup
  - Consider using a Content Delivery Network (CDN), such as Cloudflare, for faster load times globally. This can be surprisingly affordable.
  - SSL certificate for HTTPS.
  - DNS configuration. DNS changes can take time to propagate, so plan accordingly.
- Analytics and tracking setup (Google Analytics, Tag Manager, etc.).
  - Using a CDN can provide sufficient analytics for basic traffic monitoring.
  - After launch, customers will ask for traffic data.
- Performance optimization
  - Use tools like Google PageSpeed Insights to identify and fix performance bottlenecks.
- Accessibility compliance (WCAG standards).