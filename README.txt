═══════════════════════════════════════════════════════════════
WOOFIFI — WEBSITE DELIVERABLE
Design & Build by your website consultant (Claude)
═══════════════════════════════════════════════════════════════

📁 FILES INCLUDED
─────────────────────────────────────────────────
  index.html      → Main single-page website (Home, About, Products,
                    App/Services, How It Works, Testimonials, Gallery,
                    FAQ, Newsletter, Contact)
  blog.html       → Blog listing + 3 full articles (in one file,
                    expands inline when reader clicks "Read article")
  privacy.html    → Privacy Policy (Singapore PDPA-compliant template)
  terms.html      → Terms of Service (Singapore law template)
  README.txt      → This file

🎨 DESIGN SYSTEM
─────────────────────────────────────────────────
  Colors:
    Navy       #262354   (headings, buttons, logo stroke)
    Yellow     #FCC156   (CTAs, accents, hero wordmark)
    Cream      #FFF9F0   (main background — warm, cozy)
    Cream-warm #FDF2DF   (alternating sections)

  Typography (loaded from Google Fonts, free):
    Headings   Fraunces    — warm, friendly serif that echoes
                             the "Woofifi" logo wordmark
    Body       Plus Jakarta Sans — clean, highly readable modern
                             sans-serif

  Logo: Embedded as inline SVG (transparent, scales perfectly
        on any background, no file dependency, loads instantly).

⚡ HOW TO DEPLOY / CONNECT TO www.woofifi.com
─────────────────────────────────────────────────
  1. Upload the 4 HTML files to your web host's public folder
     (usually called "public_html", "htdocs", "www", or "site").
     Common hosts: Hostinger, Cloudflare Pages, Netlify, Vercel,
     GoDaddy, SiteGround. Drag-drop works for all of them.

  2. Point your domain (www.woofifi.com) to the host. Your host
     provides a nameserver — update it at your domain registrar.

  3. Enable SSL (free, one-click on every modern host) so your
     site loads as https://www.woofifi.com

  4. Visit your domain — you're live! 🎉

  EASY FREE HOSTING RECOMMENDATION: Cloudflare Pages
   • Drag-drop the folder at https://pages.cloudflare.com
   • Free SSL, free CDN, extremely fast from Singapore
   • Connect custom domain with one click

🖼️ REPLACING PLACEHOLDER IMAGES
─────────────────────────────────────────────────
  All dog photos are currently hosted on Unsplash (free to use).
  To swap in your own photos (Whiskey the Cavapoo, Woofifi IG):

  1. Create an "assets" folder next to index.html
  2. Save your images inside (name them clearly, e.g. whiskey.jpg)
  3. Open index.html in any text editor
  4. Search (Ctrl+F) for: [IMG-SWAP]
     — each placeholder image is marked with this tag
  5. Replace the Unsplash URL with "assets/your-photo.jpg"

  Example BEFORE:
    <img src="https://images.unsplash.com/photo-1591160690555-..."/>

  Example AFTER:
    <img src="assets/whiskey-hero.jpg" alt="Whiskey the Cavapoo"/>

  TIP: Image sizes for best performance
   • Hero photo:      1200×1500 px, <500KB
   • Product cards:   700×525 px, <200KB each
   • Gallery:         500×500 px (square), <150KB each
   • Testimonials:    200×200 px (avatars), <50KB

  Free image compression: https://tinypng.com

📬 CONTACT FORM SETUP
─────────────────────────────────────────────────
  The contact form currently shows a demo alert. To route real
  submissions to orders@woofifi.com:

  1. Sign up (free, 50 submissions/month) at https://formspree.io
  2. Create a new form — Formspree gives you a URL like:
       https://formspree.io/f/abcd1234
  3. Open index.html, find this line:
       action="https://formspree.io/f/YOUR_FORMSPREE_ID"
  4. Replace YOUR_FORMSPREE_ID with your actual ID (abcd1234)
  5. In index.html, also remove the onsubmit="handleContact(event)"
     attribute from the <form> tag so the form submits normally
  6. Test! Submissions will now arrive at the email you registered.

  ALTERNATIVE (zero-setup): Replace the form's action with:
    mailto:orders@woofifi.com
  (This opens the user's default email app with pre-filled data.
  Works everywhere, but less reliable than Formspree.)

📱 SOCIAL LINKS TO UPDATE
─────────────────────────────────────────────────
  Open index.html and search for:
    instagram.com/woofifi   → replace with your actual IG handle
    tiktok.com/@woofifi     → replace with your actual TikTok handle
    (Xiaohongshu)           → add your XHS profile URL

  Same for blog.html and the footer section.

🛒 E-COMMERCE LINKS TO UPDATE
─────────────────────────────────────────────────
  In the Products section of index.html, find the three "#" hrefs
  near "Shopee / TikTok Shop / Scan PayNow" and replace with:
    • Your Shopee store URL
    • Your TikTok Shop URL
    • Your PayNow QR image or shop link

✅ WHAT'S LIVE & WORKING
─────────────────────────────────────────────────
  ✓ Responsive: looks great on mobile, tablet, desktop
  ✓ SEO meta tags (title, description, Open Graph, Twitter)
  ✓ Smooth scroll anchor links
  ✓ Reveal-on-scroll animations
  ✓ Mobile hamburger menu
  ✓ Hover states on every interactive element
  ✓ Phone mockup animation in the App section
  ✓ FAQ accordion (expand/collapse)
  ✓ Instagram-style gallery
  ✓ Floating feature cards on hero photo
  ✓ Newsletter form (demo — wire to Mailchimp/ConvertKit)
  ✓ Contact form (demo — wire to Formspree)
  ✓ Blog listing with 3 full articles
  ✓ PDPA-compliant Privacy Policy + Terms of Service
  ✓ Favicon (inline SVG heart — no file needed)
  ✓ Print-friendly
  ✓ Accessible (ARIA labels, semantic HTML, keyboard navigable)

🎯 RECOMMENDED NEXT STEPS
─────────────────────────────────────────────────
  Priority 1 — Before launch
    • Swap placeholder dog photos with real Whiskey / IG shots
    • Update social media handles
    • Update Shopee / TikTok Shop links
    • Set up Formspree for contact form
    • Set up Mailchimp for newsletter signups
    • Deploy to Cloudflare Pages / Netlify / Vercel

  Priority 2 — First month
    • Add Google Analytics / Meta Pixel tracking code
       (paste the <script> tags before </head> in each HTML file)
    • Register for Google Search Console and submit your domain
    • Create an Open Graph social share image (1200×630 px)
       and save as assets/og-image.jpg
    • Commission professional product photography when snacks
       launch (current product images are stock placeholders)

  Priority 3 — Phase 2 prep
    • Add app download badges (Apple App Store, Google Play)
      when app ships
    • Add a groomer sign-up flow
    • Embed real Instagram feed using a widget like LightWidget
      or Elfsight (free tiers available)

💡 TIPS FROM 20 YEARS OF EXPERIENCE
─────────────────────────────────────────────────
  • PHOTOS MATTER MORE THAN CODE. Great photography on this site
    will triple conversion vs. stock photos. Invest in one good
    photoshoot day — it pays for itself.

  • SPEED IS A FEATURE. Keep each image under 300KB. Compress
    everything at tinypng.com before uploading.

  • WRITE LIKE YOU TALK. Your brand voice is friendly & playful —
    I've kept the copy that way throughout. Resist the urge to make
    it sound "corporate" — stick with warm and human.

  • TEST ON REAL MOBILE. Not just Chrome dev tools. Actual phone.
    Borrow a friend's Android if you only have iPhone.

  • BACKUP BEFORE EVERY EDIT. Copy the folder, make changes in the
    copy, then swap if it works. Saves heartbreak.

If anything breaks or feels off, tell me what you're seeing and
I'll fix it. This is YOUR site — it should feel like home.

Made with 💛 for Woofifi
═══════════════════════════════════════════════════════════════
