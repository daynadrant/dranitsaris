# dranitsaris

Source for my personal portfolio site, live at **[dranitsaris.ca](https://dranitsaris.ca)**.

It's a single-page static site: one `index.html` styled with Tailwind CSS (loaded from the Tailwind CDN) and the Inter font from Google Fonts. There is no build step.

## Sections

- **About**: who I am and what I'm involved in
- **Skills**: languages, frameworks and tools
- **Certifications**: Credly badges, embedded with Credly's script
- **Projects**: write-ups with links to the code, including several repos from this account
- **Resume**: `Dayna_Dranitsaris_Resume.pdf`, linked from the nav bar

## Repo layout

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, Tailwind classes and the small mobile-menu script |
| `Dayna_Dranitsaris_Resume.pdf` | Resume linked from the nav |
| `*.jpg`, `*.png` | Project images and profile photo |
| `CNAME` | Custom domain for hosting (`dranitsaris.ca`) |

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

An internet connection is needed for Tailwind, fonts and the Credly badges to load.
