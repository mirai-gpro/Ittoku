# Ginza Ittoku Landing Page - Complete Package

**Version:** 1.0  
**Last Updated:** March 2026  
**Project Type:** Landing Page for Luxury Cultural Experience Venue  
**Target Market:** International Tourists (English & Chinese speaking)

---

## 📦 What's Included in This Package

This complete package contains everything a web developer needs to build a high-converting landing page for Ginza Ittoku:

### 📄 Documentation (in `docs/` folder):
1. **LANDING_PAGE_DESIGN.md** - Complete design specification (70+ pages)
2. **ASSET_INVENTORY.md** - All images/videos with usage guidelines
3. **This README** - Project overview and getting started guide

### ✍️ Content (in `content/` folder):
1. **ENGLISH_COPY.md** - All English copywriting ready to use

### 🎨 Assets (in `assets/` folder):
1. **Images** (2 files):
   - a5-wagyu-dish.jpg (429 KB)
   - kinbi-gin-bottle.jpg (294 KB)

2. **Videos** (4 files):
   - geiko-performance.mp4 (15 MB) - 56 seconds
   - vip-room-tour.mp4 (25 MB) - 14 seconds
   - seasonal-plants.mp4 (8 MB) - 7 seconds  
   - ginza-entrance-reel.mp4 (8.8 MB) - 34 seconds ⭐ **RECOMMENDED FOR HERO**

---

## 🎯 Project Goals

### Primary Objective:
**Drive private bookings at ¥33,000 per person**

### Success Metrics (Month 3):
- 3,000+ unique visitors
- 300+ email signups
- 10-20 confirmed bookings
- 10-30 booking inquiries

### Target Audience:
- **Primary:** International tourists (USA, Europe, China)
- **Secondary:** Tokyo expats and business travelers
- **Demographic:** High-net-worth individuals, cultural enthusiasts, ages 35-65

---

## 🏗️ Project Structure

```
ginza-ittoku-landing-page/
│
├── README.md (this file)
│
├── docs/
│   ├── LANDING_PAGE_DESIGN.md (⭐ START HERE - Complete design spec)
│   └── ASSET_INVENTORY.md (Image/video usage guide)
│
├── content/
│   └── ENGLISH_COPY.md (All copywriting in English)
│
└── assets/
    ├── images/
    │   ├── a5-wagyu-dish.jpg
    │   └── kinbi-gin-bottle.jpg
    └── videos/
        ├── geiko-performance.mp4
        ├── vip-room-tour.mp4
        ├── seasonal-plants.mp4
        └── ginza-entrance-reel.mp4 (⭐ Hero section video)
```

---

## 🚀 Quick Start Guide

### For Web Developers:

**Step 1: Read the Design Doc**
```bash
Open: docs/LANDING_PAGE_DESIGN.md
```
This is your complete specification - read thoroughly before starting.

**Step 2: Review Assets**
```bash
Open: docs/ASSET_INVENTORY.md
Check: assets/images/ and assets/videos/
```
Understand what media you have and how to use it.

**Step 3: Review Copy**
```bash
Open: content/ENGLISH_COPY.md
```
All text content is written and ready to paste into your design.

**Step 4: Choose Your Platform**
Recommended options:
- **Custom HTML/CSS/JS** (best performance, full control)
- **WordPress + Premium Theme** (Divi, Elementor Pro)
- **Webflow** (visual design + clean code)
- **Squarespace** (easiest, but limited)

See `docs/LANDING_PAGE_DESIGN.md` Section 3 for detailed platform recommendations.

**Step 5: Build**
Follow the section-by-section design in the design document.

---

## 📋 Design Overview

### Page Sections (in order):

1. **Hero Section** - Video background with main CTA
2. **Video Experience** - 30-60 second showcase
3. **The Story** - ¥300M investment narrative
4. **Cultural Treasures** - Interactive gallery (5 cards)
5. **The Experience** - Tabbed interface (Standard/VIP/Events)
6. **Testimonials** - 6 customer reviews
7. **Pricing & Booking** - Clear pricing, booking CTAs
8. **FAQ** - 12 common questions answered
9. **Location & Access** - Map and directions
10. **Final CTA** - Last conversion opportunity

**Total Estimated Length:** Single long-scroll page (equivalent to 8-10 traditional pages)

---

## 🎨 Design Principles

### Visual Style:
- **Luxury** without being pretentious
- **Japanese aesthetic** - simplicity, space, quality
- **Cultural respect** - authentic, not stereotypical
- **Mobile-first** - must work perfectly on smartphones

### Color Palette:
- **Primary:** Gold (#D4AF37) or Deep Red (#8B0000)
- **Accent:** Black, White, Natural wood tones
- **Background:** Off-white or very light gray
- **Text:** Dark gray (not pure black for readability)

### Typography:
- **Headings:** Serif or elegant sans-serif (Playfair Display, Cormorant)
- **Body:** Clean sans-serif (Open Sans, Lato, Noto Sans)
- **Japanese text:** Noto Sans JP, Yu Gothic

### Imagery:
- High-quality, professional photography
- Cultural authenticity
- No stock photos of generic "Japanese" imagery
- Real photos from the venue preferred

---

## ⚡ Technical Requirements

### Performance:
- **Page Load:** < 3 seconds (desktop), < 5 seconds (mobile)
- **Mobile-First:** Responsive design essential
- **Video Optimization:** Compress videos < 10MB for hero
- **Image Optimization:** WebP format, lazy loading

### Browser Support:
- Chrome/Safari/Firefox/Edge (latest 2 versions)
- Mobile Safari (iOS 14+)
- Mobile Chrome (Android 10+)

### Required Features:
- Responsive navigation menu
- Smooth scroll to sections
- Video autoplay (muted, with fallback)
- Contact form with validation
- Email signup integration
- Google Maps embed
- Language selector (EN/CN/JP prep)

### SEO Requirements:
- Semantic HTML5
- Meta tags (title, description, OG tags)
- Alt text on all images
- Schema markup (LocalBusiness, Restaurant)
- Clean URLs
- Fast load times

---

## 📱 Responsive Design

### Breakpoints:
```css
Mobile: 320px - 767px
Tablet: 768px - 1023px
Desktop: 1024px - 1919px
Large Desktop: 1920px+
```

### Mobile Priorities:
1. Hero video must work on mobile (consider static image fallback)
2. Navigation must collapse to hamburger menu
3. Touch-friendly buttons (min 44x44px)
4. Readable text without zooming
5. Forms easy to fill on mobile
6. Videos should not autoplay on mobile (data usage)

---

## 🌍 Multilingual Setup

### Languages Required:
1. **English** (primary) - Complete copy provided
2. **Simplified Chinese** - Translation needed
3. **Traditional Chinese** - Translation needed
4. **Japanese** - Translation needed

### Implementation Options:

**Option A: Language Selector with Translation**
- Dropdown in header (EN | 中文 | 日本語)
- Swaps all text dynamically
- Single URL, language stored in cookie

**Option B: Separate Pages**
- `/en/`, `/zh/`, `/ja/` subdirectories
- Better for SEO
- Easier to manage translations

**Option C: Translation Plugin**
- WordPress: WPML or Weglot
- Automatic translation with manual editing
- Monthly subscription cost

### Translation Guidelines:
- **DO NOT use Google Translate**
- Hire professional translators
- Cultural nuances matter (especially Chinese market)
- Maintain tone: sophisticated, respectful, factual

---

## 💰 Budget Estimates

### Development Costs:

**DIY (Template-based):**
- Platform: $20-50/month
- Time: 20-40 hours
- **Total: $500-1,000**

**Semi-Professional (WordPress):**
- Premium theme + developer setup
- **Total: $1,000-2,500**

**Professional (Custom):**
- Designer + Developer + Copywriter
- **Total: $6,500-17,500**

**Premium (Agency):**
- Full-service digital agency
- **Total: $15,000-40,000**

See `docs/LANDING_PAGE_DESIGN.md` Section 10 for detailed breakdown.

---

## 📊 Success Metrics & KPIs

### Track These Metrics:

**Immediately After Launch:**
- Page views
- Bounce rate
- Average time on page
- Video play rate
- Scroll depth
- CTA click rate

**Within First Month:**
- Unique visitors: Target 1,000+
- Email signups: Target 100+
- Booking inquiries: Target 5-10
- Confirmed bookings: Target 2-5

**Within First Quarter:**
- Unique visitors: Target 3,000+
- Booking conversion rate: Target 3-5%
- Average booking value: ¥33,000 x group size
- ROI: Target 10x+ on landing page investment

### Analytics Setup:
- Google Analytics 4 (required)
- Google Tag Manager (recommended)
- Facebook Pixel (if running ads)
- Hotjar or similar (heat mapping)

---

## ✅ Pre-Launch Checklist

### Content:
- [ ] All copy reviewed and approved
- [ ] Translations completed (if multilingual)
- [ ] All images optimized for web
- [ ] All videos compressed
- [ ] Contact information verified
- [ ] Pricing confirmed
- [ ] Legal pages added (privacy policy, terms)

### Technical:
- [ ] Mobile responsiveness tested on real devices
- [ ] All forms tested (submit test bookings)
- [ ] All links work (no 404 errors)
- [ ] Videos play on all browsers
- [ ] Page load speed < 3 seconds
- [ ] SSL certificate installed (HTTPS)
- [ ] Favicon added
- [ ] Meta tags implemented
- [ ] Google Analytics tracking code added

### SEO:
- [ ] Title tags optimized (< 60 chars)
- [ ] Meta descriptions written (< 160 chars)
- [ ] Alt text on all images
- [ ] Schema markup implemented
- [ ] XML sitemap generated
- [ ] robots.txt configured
- [ ] 301 redirects planned (if replacing existing site)

### Testing:
- [ ] Cross-browser testing (Chrome, Safari, Firefox, Edge)
- [ ] Mobile testing (iOS and Android)
- [ ] Form validation working
- [ ] Video autoplay working (muted)
- [ ] Language switcher working (if multilingual)
- [ ] Map directions working
- [ ] Phone/email links working
- [ ] Booking system integrated

---

## 🔧 Common Issues & Solutions

### Issue 1: Videos not autoplaying
**Solution:** Videos must be muted to autoplay. Add `muted` attribute.
```html
<video autoplay muted loop playsinline>
```

### Issue 2: Page loads slowly
**Solution:**
- Compress images (use TinyPNG or similar)
- Lazy load images and videos
- Minimize CSS/JavaScript
- Use CDN for assets

### Issue 3: Not mobile responsive
**Solution:**
- Use mobile-first approach
- Test on actual devices, not just desktop browser resize
- Use responsive units (%, vw, rem) not pixels

### Issue 4: Forms not submitting
**Solution:**
- Check email server configuration
- Add proper validation
- Test with real email address
- Add success/error messages

### Issue 5: Videos too large
**Solution:**
- Compress using HandBrake or similar
- Target 1080p max resolution
- Use H.264 codec
- Aim for < 10MB for hero videos

---

## 🎯 Conversion Optimization Tips

### Increase Bookings:

**1. Clear Value Proposition**
- State ¥300M investment upfront
- Emphasize "private bookings only" exclusivity
- Show authentic cultural treasures

**2. Trust Signals**
- Display Google rating (5.0★)
- Show media mentions
- Include authentic testimonials
- Professional photography

**3. Strong CTAs**
- Use action verbs ("Reserve", "Experience", "Book")
- Make buttons prominent (gold or red)
- Multiple CTAs throughout page
- Clear pricing (no hidden fees)

**4. Reduce Friction**
- Easy booking process
- Multiple contact methods
- FAQ answers objections
- Clear cancellation policy

**5. Urgency & Scarcity**
- "Limited availability"
- "Private bookings only"
- Show upcoming events with limited spots
- Email signup for exclusivity

---

## 📞 Support & Questions

### If You Need Help:

**Technical Questions:**
- Refer to `docs/LANDING_PAGE_DESIGN.md` Section 3
- All platforms/tech specs covered there

**Content Questions:**
- Refer to `content/ENGLISH_COPY.md`
- All copywriting provided

**Design Questions:**
- Refer to `docs/LANDING_PAGE_DESIGN.md` Section 2
- Detailed layouts for each section

**Asset Questions:**
- Refer to `docs/ASSET_INVENTORY.md`
- Usage guidelines for all media

### Contact:
[Insert client contact information]

---

## 🗓️ Recommended Timeline

### Realistic Development Timeline:

**Week 1: Planning & Setup**
- Review all documentation
- Choose platform
- Set up development environment
- Create wireframes

**Week 2: Design Approval**
- Create mockups
- Client review and feedback
- Revisions
- Final design approval

**Week 3-4: Development**
- Build page structure
- Implement responsive design
- Add all content
- Integrate videos/images

**Week 5: Content & Testing**
- Populate all copy
- Optimize images/videos
- Cross-browser testing
- Mobile testing

**Week 6: QA & Polish**
- Fix bugs
- Performance optimization
- SEO implementation
- Final client review

**Week 7: Pre-Launch**
- Set up analytics
- Final testing
- Backup plan
- Soft launch to test group

**Week 8: Launch**
- Go live
- Social media announcement
- Monitor analytics
- Be ready for quick fixes

**Total: 8-10 weeks for professional implementation**

---

## 📈 Post-Launch Strategy

### Week 1 After Launch:
- Monitor analytics daily
- Check for broken links or errors
- Collect initial user feedback
- Fix any reported issues
- Respond to all inquiries within 24 hours

### Month 1 After Launch:
- Review conversion data
- A/B test different CTAs
- Optimize underperforming sections
- Start content marketing (blog, social)
- Begin collecting testimonials

### Month 3 After Launch:
- Comprehensive analytics review
- Identify traffic sources
- Double down on what's working
- Consider paid advertising (Google Ads, Facebook)
- Add new content (events, blog posts)

### Month 6 After Launch:
- Major data analysis
- ROI calculation
- Plan improvements (version 2.0)
- Scale successful tactics
- Consider expanding to other languages

---

## 🏆 Best Practices

### DO:
✅ Follow the design document closely
✅ Optimize for mobile first
✅ Test on real devices
✅ Compress all images and videos
✅ Use professional photography
✅ Write clear, compelling copy
✅ Make CTAs prominent
✅ Include trust signals
✅ Answer common objections in FAQ
✅ Track everything with analytics

### DON'T:
❌ Use stock photos of generic "Japan" imagery
❌ Overcomplicate the design
❌ Use autoplay video with sound
❌ Ignore mobile users
❌ Use Google Translate for important text
❌ Hide pricing or make booking difficult
❌ Forget alt text on images
❌ Launch without testing
❌ Ignore page load speed
❌ Use too many fonts or colors

---

## 📚 Additional Resources

### Recommended Tools:

**Design:**
- Figma or Adobe XD (wireframing)
- Canva (quick graphics)

**Development:**
- VS Code (code editor)
- Chrome DevTools (debugging)
- Responsively App (responsive testing)

**Optimization:**
- TinyPNG (image compression)
- HandBrake (video compression)
- GTmetrix (speed testing)
- Google PageSpeed Insights

**Analytics:**
- Google Analytics 4
- Google Search Console
- Hotjar (heat mapping)

**SEO:**
- Yoast SEO (if WordPress)
- Screaming Frog (site audit)

### Inspiration:
Look at luxury hotel websites for design inspiration:
- Aman Tokyo
- The Peninsula Tokyo
- Park Hyatt Tokyo
- Mandarin Oriental Tokyo

---

## 📄 License & Usage

**Copyright:** All content, images, and videos are property of Ginza Ittoku

**Usage Rights:**
- This package is for development of Ginza Ittoku's official landing page only
- Do not redistribute assets to third parties
- Do not use for other projects or clients
- All final work belongs to Ginza Ittoku

---

## 🎉 Final Notes

This is a **complete, production-ready package**. Everything you need to build a high-converting landing page is included:

✅ Detailed design specifications  
✅ Professional copywriting  
✅ High-quality images and videos  
✅ Technical requirements  
✅ SEO guidelines  
✅ Conversion optimization tips

**Your job is to bring this to life beautifully and efficiently.**

The design document is comprehensive - read it thoroughly before starting. Don't skip sections. Everything is there for a reason based on best practices and conversion optimization principles.

**Questions? Issues? Suggestions?**
Contact the project stakeholder with specifics. This README should answer 95% of your questions.

---

**Good luck with the build! 🏯**

---

**Package Version:** 1.0  
**Last Updated:** March 2026  
**Total Package Size:** ~57 MB (mostly videos)  
**Estimated Build Time:** 8-10 weeks professional / 20-40 hours DIY  
**Complexity Level:** Medium (requires web development experience)

---

**End of README**
