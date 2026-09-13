# JB Home Improvement LLC

Owner-operated home improvement site for Saint Charles, Missouri.

**Repository:** https://github.com/Joshlbritt/jb-home-improvement

**HTTPS site (after Pages is enabled):**  
https://joshlbritt.github.io/jb-home-improvement/

## Turn on GitHub Pages + HTTPS

`github.io` sites already use HTTPS. You only need to publish the site:

1. Open https://github.com/Joshlbritt/jb-home-improvement/settings/pages
2. **Build and deployment → Source**
   - Option A (simplest): **Deploy from a branch** → `main` / `/ (root)` → Save
   - Option B: **GitHub Actions** (uses `.github/workflows/pages.yml`)
3. Wait 1–2 minutes, then open https://joshlbritt.github.io/jb-home-improvement/
4. The padlock is automatic on `*.github.io`. No extra HTTPS toggle is required for that URL.

### Custom domain HTTPS (Cloudflare)

After DNS points at `Joshlbritt.github.io`:

1. Same Pages settings page → **Custom domain** → enter `www.yourdomain.com` → Save
2. Wait for the DNS check to turn green
3. Check **Enforce HTTPS**
4. In Cloudflare, keep records **DNS only** until that box works, then SSL/TLS mode **Full** or **Full (strict)**
