# Murmur

Hold a key, talk, let go. Your words appear wherever you're typing.
Speech-to-text runs locally on your computer, for Mac and Windows.

This repository holds the **landing page** only.

## Download

Get Murmur for Mac or Windows from the [Releases](https://github.com/swaaaaaapnil/murmur/releases) page.

## Repository layout

```
.
├── index.html    # the whole site: markup, styles and script in one file
├── vercel.json   # Vercel static config (clean URLs, security headers)
└── README.md
```

## Develop

No build step. Serve the folder and open it:

```bash
python3 -m http.server 4173
```

## Deploy

The site is deployed on Vercel from the `main` branch; every push redeploys.

---

Made by [Swapnil](https://github.com/swaaaaaapnil).
