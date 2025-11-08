# Emma Jane Gallagher - Official Website

Personal website for Emma Jane Gallagher (@emmajane_gallagher), content creator and "The Relatable Mum."

## About

This is a simple, elegant holding page showcasing Emma's social media presence and business contact information.

## Live Site

Visit: [emmajanegallagher.com](https://emmajanegallagher.com)

## Setup with GitHub Pages

1. Fork or clone this repository
2. Go to repository Settings → Pages
3. Under "Source", select "Deploy from a branch"
4. Select branch: `main` and folder: `/ (root)`
5. Click Save
6. Your site will be live at `https://[username].github.io/[repo-name]`

## Custom Domain Setup

To use emmajanegallagher.com:

1. In your repository, go to Settings → Pages
2. Under "Custom domain", enter: `emmajanegallagher.com`
3. Check "Enforce HTTPS" (after DNS propagates)
4. In your domain registrar (where you bought the domain):
   - Add an A record pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Add a CNAME record: `www` pointing to `[username].github.io`

5. Wait for DNS propagation (can take up to 24 hours)

## File Structure

```
/
├── index.html          # Main website page
├── CNAME              # Custom domain configuration
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Contact

For business enquiries: socials@emmajanegallagher.com

Instagram: [@emmajane_gallagher](https://www.instagram.com/emmajane_gallagher/)

---

© 2024 Emma Jane Gallagher. All rights reserved.
