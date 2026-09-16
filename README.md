# GitDownloader

**[gitdownloader.com](https://gitdownloader.com/)** — download any GitHub folder, sub-directory or single file as a ZIP, without cloning the whole repository.

GitHub only offers a "Download ZIP" button for an entire repository. GitDownloader lets you paste a GitHub folder URL and get back just the files you need.

## Features

- **Any sub-directory** — download a single folder or file instead of the whole repo.
- **Smart tree API** — uses GitHub's tree endpoint to list thousands of files in a single request.
- **Private repos** — paste a personal access token to grab folders from repositories you can access.
- **Git LFS ready** — large-storage files are detected and fetched from the correct media endpoint.
- **Browser-only** — your token and files never touch our servers; zipping happens locally.
- **Resilient** — retries failed downloads and gracefully handles huge, truncated directories.

## How it works

1. Paste the URL of any GitHub folder (or file).
2. The tool reads the directory through GitHub's API and downloads every file in parallel.
3. All files are packaged into a single ZIP archive that starts downloading automatically.

## Languages

The site is available in:

- English — [gitdownloader.com](https://gitdownloader.com/)
- German — [/de/](https://gitdownloader.com/de/)
- Spanish — [/es/](https://gitdownloader.com/es/)
- French — [/fr/](https://gitdownloader.com/fr/)
- Japanese — [/ja/](https://gitdownloader.com/ja/)
- Korean — [/ko/](https://gitdownloader.com/ko/)
- Portuguese — [/pt/](https://gitdownloader.com/pt/)

## Repository layout

This repository holds the static site served at [gitdownloader.com](https://gitdownloader.com/):

```
/                 English site (index, blog, faq, privacy, terms)
/de /es /fr /ja /ko /pt   Localized versions of the same pages
/static           Compiled CSS and web fonts
/404.html         Not-found page
```

Everything is plain static HTML/CSS/JS — no build step and no server-side code is required to serve it.

## Privacy

GitDownloader is a static website. File contents are fetched by your browser straight from GitHub and zipped locally. Nothing is uploaded to or kept on our servers. See the [privacy policy](https://gitdownloader.com/privacy/) for details.

## Links

- Website: [https://gitdownloader.com/](https://gitdownloader.com/)
- Guide: [How to download a folder from GitHub](https://gitdownloader.com/blog/how-to-download-folder-from-github/)
- FAQ: [https://gitdownloader.com/faq/](https://gitdownloader.com/faq/)
