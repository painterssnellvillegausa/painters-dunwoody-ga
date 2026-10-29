Render static site release notes

Primary homepage: https://painters-dunwoody-ga.onrender.com/
/index.html redirects in the browser via location.replace to /. This is NOT an HTTP 301 redirect.
Render Static Sites generally serve existing files before redirect rules, so a dashboard redirect for /index.html may not take effect.
Canonical tags now point to the new Render URLs. Internal Home links use ./. Sitemap and robots.txt included.
The homepage JSON-LD URL fields point to the root.
For an actual server-side 301, use a server/proxy/CDN that supports redirects for existing index.html files.
