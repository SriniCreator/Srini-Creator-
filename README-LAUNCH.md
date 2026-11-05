# Srini Creator: Launch Guide

## A. Find & replace (in all files)
| Find | Replace with |
|---|---|
| YOURDOMAIN.com | your domain, or your yourname.pages.dev address |
| YOURNAME.gumroad.com | your Gumroad username |
| /l/EBOOK-LINK, NOTION-LINK, EXCEL-LINK, BUNDLE-LINK | your Gumroad product slugs |
| G-XXXXXXXXXX | GA4 Measurement ID |
| YOUR MAILING ADDRESS | a real address (PO box or virtual mailbox works) |
| YOUR STATE/COUNTRY | your governing law location |

## B. Deploy on Cloudflare Pages (free)
1. Create a GitHub account, then a new public repository named srini-creator.
2. Click Add file > Upload files and upload everything in this folder.
3. Go to dash.cloudflare.com > Workers & Pages > Create > Pages > Connect to Git.
4. Pick the repo. Framework: None. Build command: blank. Output directory: /
5. Click Deploy. Your site goes live at yourname.pages.dev with HTTPS.

## C. Google & analytics setup
1. analytics.google.com: create a GA4 property, copy the Measurement ID into index.html.
2. In GA4 > Admin > Events, mark `gumroad_click` as a key event.
3. search.google.com/search-console: add your site, verify, submit sitemap.xml.
4. bing.com/webmasters: import from Search Console.
5. clarity.microsoft.com: optional heatmaps (add its script inside the loadGA function so it loads only after consent).
6. Run pagespeed.web.dev on your URL.

## D. Email list (free)
1. Sign up at Brevo or MailerLite, create a list, turn on double opt-in.
2. Create a signup form, copy its form action URL into the form in index.html.
3. Upload a free lead-magnet file and set it as the welcome email attachment/link.

## E. Gumroad
1. Create products: clear cover image (1280x720), benefit-led title, 3-5 bullet description.
2. Add a refund policy in product settings that matches terms.html.
3. Turn on the affiliate program (Settings > Affiliates) and set a 20-30% commission.
4. Create launch discount codes.
5. Use UTM links: ?utm_source=instagram&utm_medium=social&utm_campaign=launch

## F. First 10 blog post ideas (US buyers)
1. 7 free Notion templates for freelancers (and the one I use daily)
2. How to build a monthly budget in Excel, step by step
3. Notion vs Excel: which is better for tracking projects?
4. Best Notion template for content creators
5. How to make and sell a Notion template on Gumroad
6. Small business expense tracker in Excel (free download)
7. How to write your first ebook in a weekend
8. Excel formulas every creator should know
9. Notion habit tracker setup guide
10. Digital products to sell online in 2026

## G. Social posting plan
- 3 short tips per week (Instagram Reels, TikTok, Pinterest, X, LinkedIn). Each one links to the homepage or a blog post, not straight to Gumroad.
- Pin a post that offers the free template.
- Best US posting windows: weekdays 9-11 AM and 6-8 PM Eastern.

## H. Before going live checklist
- [ ] All placeholders replaced
- [ ] Mobile test on a real phone
- [ ] Every Gumroad button opens the right product
- [ ] Cookie banner works; analytics loads only after Accept
- [ ] Test the signup form and the unsubscribe link
- [ ] Privacy and Terms reviewed by a professional
