# www-redirect

GitHub Pages site for `nyades.dev` (and `www.nyades.dev`, which GitHub redirects to it): every path redirects to https://n1ades.github.io (path, query and hash kept).
`404.html` is the same page, so unknown paths redirect too.

DNS (Cloudflare, DNS only, not proxied): CNAME `nyades.dev` -> `n1ades.github.io` (flattened) and CNAME `www` -> `n1ades.github.io`.
