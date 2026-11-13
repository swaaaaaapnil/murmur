# Murmur

Hold a key, talk, let go. Your words appear wherever you're typing.
Speech-to-text runs locally on your computer, for Mac and Windows.

This repository holds the **landing page** only.

## Download

| Platform | File | Requirements |
| --- | --- | --- |
| Mac | [Murmur.dmg](https://github.com/swaaaaaapnil/murmur/releases/latest/download/Murmur.dmg) | macOS 14+, Apple silicon |
| Windows | [Murmur-Setup.exe](https://github.com/swaaaaaapnil/murmur/releases/latest/download/Murmur-Setup.exe) | Windows 10/11, 64-bit |

All versions are on the [Releases](https://github.com/swaaaaaapnil/murmur/releases) page.

## Repository layout

```
.
├── index.html    # the whole site: markup, styles and script in one file
├── vercel.json   # Vercel static config (clean URLs, security headers)
└── README.md
```

Installers are attached to GitHub Releases rather than committed, so the
download buttons always point at `releases/latest/download/<file>`.

## Develop

No build step. Serve the folder and open it:

```bash
python3 -m http.server 4173
```

## Deploy

The site is deployed on Vercel from the `main` branch; every push redeploys.

## Releasing a new version

```bash
gh release create vX.Y.Z Murmur.dmg Murmur-Setup.exe --title "Murmur vX.Y.Z" --notes "..."
```

---

Made by [Swapnil](https://github.com/swaaaaaapnil).
