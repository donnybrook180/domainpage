# Sonatris Limited

Marketing website for **Sonatris Limited**, a software development studio
building mobile applications (including TOEIC Coach).

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Landing page |
| `privacy.html` | Privacy policy for Sonatris Limited apps |
| `styles.css` | Site styling (responsive, light/dark) |
| `app-ads.txt` | Authorized ad-seller declarations for AdMob |

## Running locally

This is a static site — no build step. Serve the folder and open it in a browser:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Deploying

The site can be hosted on any static host (GitHub Pages, Netlify, Vercel, etc.).
For `app-ads.txt` to work, it must be reachable at the domain root
(`https://yourdomain.com/app-ads.txt`), and each app's store listing must set its
"Developer website" to that same domain.
