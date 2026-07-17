# meadowhughes.github.io
# meadowhughes.com

Personal CV / portfolio site. Static HTML/CSS, hosted on GitHub Pages, DNS via Porkbun.

## Structure
```
index.html   — page content
style.css    — all styling
robots.txt   — blocks search indexing while in draft (delete before going live)
cv/          — put Meadow-Hughes-CV.pdf here
assets/      — put headshot.jpg here, then update the <img> in index.html
```

## Go-live checklist
- [ ] Add real headshot to `assets/headshot.jpg`, swap the placeholder div in `index.html` for an `<img>` tag
- [ ] Add `cv/Meadow-Hughes-CV.pdf`
- [ ] Remove the `<meta name="robots" content="noindex, nofollow">` line from `index.html`
- [ ] Delete or empty `robots.txt`'s `Disallow: /` line
- [ ] Update social links in the contact section
- [ ] Add the `CNAME` file (see below) and confirm DNS is resolving
