# Goobs CMS

Flask Static Site CMS

My idea is Goobs CMS is a semi-WordPress replacement. The Python3 Flask interface is only used for basic administration and post/page creation. Site is generated into a static directory and deployed on a web server.

- Themes should have some method of being swapped out.
- Databaseless, prefer YAML then JSON


### Required Features

- Basic User Login
- YAML Front Matter
- Draft and Published States (Scheduled in the future)
- Page hierarchy. Child -> Parent -> Grandparent
- Tags
- Custom Site Branding via YAML
- RSS Feed Generator on build
- Sitemap generated on build
- robots.txt on build
- Basic image uploads.
- PNG/JPG to WebP converter.

#### WordPress Features I Do NOT Need

- Multisite
- XML-RPC
- Plugin Marketplace
- Block Editors
- Pingbacks

File Structure

```txt
_site
_data
-> authors.md
-> nav.yml
-> ui.yml
_includes
-> 
theme
-> 
```