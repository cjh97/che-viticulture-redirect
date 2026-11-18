# che-viticulture-redirect

Forwards **che-viticulture.com** (and www.che-viticulture.com) to **https://che-weinbau.com**.

Served by GitHub Pages so that the domain gets a valid HTTPS certificate.
`index.html` and `404.html` send every visitor to che-weinbau.com and point search engines
there with a canonical link; `CNAME` holds the custom domain.

DNS for che-viticulture.com (Telekom DNS-Administration):

- `che-viticulture.com` A 185.199.108.153 / .109 / .110 / .111.153, AAAA 2606:50c0:8000–8003::153
- `www.che-viticulture.com` A 185.199.108.153, AAAA 2606:50c0:8000::153
- MX and TXT records stay with Telekom (email).
