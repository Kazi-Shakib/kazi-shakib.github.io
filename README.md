# Kazi Hassan Shakib: Academic Homepage

**Live site:** https://kazi-shakib.github.io

Personal academic website of **Kazi Hassan Shakib**, PhD Candidate in Computer Science at Kansas State University (ISCAAS Lab, advised by Dr. Arslan Munir).

My research covers post-quantum and hybrid cryptographic protocol design, provable security (eCK, QROM, ProVerif), quantum key distribution authentication, and communication security for smart grids and other critical infrastructure.

## What's on the site

- **Research:** hybrid deniable key exchange, QKD authentication, smart grid protocol security (DNP3, ANSI C12.22), and quantum threats to vehicular networks
- **Interactive demo:** a browser-based illustration of how hybrid key exchange (X25519 + ML-KEM-768 + QKD/PSK) keeps a session key secret against classical and quantum attackers
- **Research vision, experience, education, publications, and awards**
- **CV:** [download](https://kazi-shakib.github.io/files/cv.pdf)

## Repository layout

| Path | Purpose |
|---|---|
| `index.html` | The homepage: a self-contained HTML page with inline CSS and JavaScript |
| `images/profile.png` | Profile photo |
| `files/cv.pdf` | CV |
| `_config.yml` | Site settings (name, URL, author links) |
| `_pages/`, `_publications/` | Additional pages from the Academic Pages template |

## Updating the site

Edit files directly on GitHub (pencil icon → **Commit changes**) or push from a local clone. GitHub Pages rebuilds automatically; changes go live in 1–2 minutes. Build status is under the **Actions** tab.

To preview locally:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
# open http://localhost:4000
```

## Contact

- Email: [kshakib@ksu.edu](mailto:kshakib@ksu.edu)
- LinkedIn: [kazi-hassan-shakib](https://www.linkedin.com/in/kazi-hassan-shakib-780308127)
- GitHub: [Kazi-Shakib](https://github.com/Kazi-Shakib)

## Credits

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is derived from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) © 2016 Michael Rose, released under the MIT License (see `LICENSE.md`). The homepage design and content are my own.
