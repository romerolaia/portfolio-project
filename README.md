# Laia Romero — Portfolio

Static site, no build step. Public DNS for laiaromerodesign.com points to Vercel (www is a CNAME to vercel-dns; apex A record is a Vercel IP). Fonts and React are served from `assets/` (no third-party CDNs).

## Pages

| URL | File |
| --- | --- |
| / (Web Development) | `index.html` |
| /design.html | `design.html` |
| /case-study-flycalm.html | `case-study-flycalm.html` |
| /apps/ (App Development) | `apps/index.html` |
| /apps/criptika/ | `apps/criptika/index.html` |
| /apps/criptika/privacy/ | `apps/criptika/privacy/index.html` |
| /apps/criptika/terms/ | `apps/criptika/terms/index.html` |
| /apps/criptika/support/ | `apps/criptika/support/index.html` |
| /privacy/ (website privacy) | `privacy/index.html` |

The Criptika privacy, terms and support pages are plain HTML (no JavaScript) so they load anywhere, including from the app and App Store Connect.

## Running locally

```bash
python3 -m http.server 8000
```
