# Issue #22 — Deploy to verspa.co.uk via Netlify

**Group:** Deployment
**Priority:** Final step
**Status:** 🔴 Pending

## Steps
1. Connect `ol-s-cloud/VERSPA-V1.O` to Netlify
2. Set publish directory to `/` (root)
3. Set domain to verspa.co.uk
4. Configure DNS at domain registrar (Netlify provides A record + CNAME)
5. Enable HTTPS (Netlify auto-provisions SSL)
6. Test all pages live
7. Test all HubSpot forms → confirm CRM capture
8. Test all thank-you redirects
9. Submit sitemap to Google Search Console

## Netlify settings
- Build command: none (static HTML)
- Publish directory: /
- Auto-deploy: on push to main ✅

## Post-deploy checks
- [ ] All 18 pages load correctly
- [ ] All forms submit and redirect
- [ ] HubSpot contacts appearing in CRM
- [ ] Favicon loading correctly
- [ ] Mobile layout correct
- [ ] FCA disclaimer on every page
- [ ] Privacy policy linked in footer of every page
