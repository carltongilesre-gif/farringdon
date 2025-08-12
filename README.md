# 765 Farringdon Ln – Single Property Site

Static site for **765 Farringdon Ln, Burlingame, CA 94010**, built with HTML + Tailwind CDN.

## Quick Deploy (GitHub Pages)

1) Create a new repo on GitHub, for example `farringdon` (public is fine).
2) Upload the contents of this folder (or unzip & drag‑drop in the GitHub web UI).
3) Add a file **CNAME** in the repo root with exactly:
```
765FarringdonLn.com
```
(This repo already includes it.)
4) In **Settings → Pages → Build and deployment**, choose **Deploy from branch**, set **Branch: main** and **Folder: /(root)**.
5) In your DNS provider, add these **A** records for the apex domain:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

If you also want **www.765FarringdonLn.com**, add a **CNAME** record for `www` that points to `<your‑github‑username>.github.io`.

> Tip: after DNS propagates, GitHub Pages will issue HTTPS automatically.

## Update Contact Info

Search for `your-email-here@example.com` and `your-phone-here` in `index.html` and replace with your real contact details.

## Notes on square footage

Public portals currently show ~1,829 sqft total (main + ADU). This site displays **1,528 sqft** for the main house per seller, plus a **studio ADU** with full bath.
