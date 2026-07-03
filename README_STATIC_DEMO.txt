Tatweer static demo export

Host this folder as the web root for a management demo.
For Netlify-style hosts, _redirects enables SPA fallback.
For basic file/static servers, localized route folders contain index.html copies for direct deep links.

Quick local preview:
  python3 -m http.server 4174 -d static-copy
  open http://127.0.0.1:4174/en
