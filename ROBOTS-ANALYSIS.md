# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on 02/27/2025

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation

The robots.txt file communicates what scraping is allowed or disallowed to webscrapers.
The first section (User-agent: *, Crawl-delay: 10, Allow: /) allows any webcrawler with a 10-second crawl delay to crawl from the root directory onwards (whole site).
The second section (User-agent: SemrushBot, Disallow: /) bans the webcrawler SemrushBot, which collects SEO/marketing data from Semrush about websites.
