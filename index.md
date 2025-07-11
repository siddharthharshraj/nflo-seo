# NFLO 2025 SEO & Digital Campaign Assets


## 1. sitemap.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset
  xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
  xmlns:xhtml="http://www.w3.org/1999/xhtml">
  <url>
    <loc>https://nationalfinanceolympiad.safefintech.in/</loc>
    <priority>1.0</priority>
    <changefreq>daily</changefreq>
  </url>
  <url>
    <loc>https://nationalfinanceolympiad.safefintech.in/about</loc>
    <priority>0.9</priority>
    <changefreq>weekly</changefreq>
  </url>
  <url>
    <loc>https://nationalfinanceolympiad.safefintech.in/register</loc>
    <priority>1.0</priority>
    <changefreq>daily</changefreq>
  </url>
  <url>
    <loc>https://nationalfinanceolympiad.safefintech.in/faq</loc>
    <priority>0.8</priority>
    <changefreq>weekly</changefreq>
  </url>
  <url>
    <loc>https://nationalfinanceolympiad.safefintech.in/results</loc>
    <priority>0.8</priority>
    <changefreq>weekly</changefreq>
  </url>
  <url>
    <loc>https://nationalfinanceolympiad.safefintech.in/contact</loc>
    <priority>0.7</priority>
    <changefreq>monthly</changefreq>
  </url>
</urlset>
```

---

## 2. robots.txt

```
User-agent: *
Disallow: /admin/
Disallow: /dashboard/
Allow: /

Sitemap: https://nationalfinanceolympiad.safefintech.in/sitemap.xml
Host: https://nationalfinanceolympiad.safefintech.in
```

---

## 3. Meta Tags & Schema (Put inside `<head>` on every page)

```html
<title>National Financial Literacy Olympiad 2025 | Register Now | SAFEFINTECH</title>
<meta name="description" content="Participate in  NFLO 2025 by SAFEFINTECH – India’s largest financial literacy olympiad for school students. Register, compete & win big. Open for 6th-12th students PAN India.">

<link rel="canonical" href="https://nationalfinanceolympiad.safefintech.in/" />

<!-- OpenGraph / Facebook / WhatsApp -->
<meta property="og:title" content="National Financial Literacy Olympiad 2025 – India’s Largest Financial Literacy Olympiad" />
<meta property="og:description" content="Compete with 1 lakh plus students, win awards, get certified. Registration open now! PAN India. Organized by SAFEFINTECH." />
<meta property="og:url" content="https://nationalfinanceolympiad.safefintech.in/" />
<meta property="og:type" content="website" />
<meta property="og:image" content="https://nationalfinanceolympiad.safefintech.in/assets/nflo-2025-poster.png" />
<meta property="og:site_name" content="National Financial Literacy Olympiad 2025" />

<!-- Twitter Cards -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="NFLO 2025 – India’s Largest Financial Literacy Olympiad" />
<meta name="twitter:description" content="Compete, Learn, Win. Join India’s biggest financial literacy contest for students. Register today!" />
<meta name="twitter:image" content="https://nationalfinanceolympiad.safefintech.in/assets/nflo-2025-poster.png" />
<meta name="twitter:site" content="@safefintech" />

<!-- Schema.org (JSON-LD) -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "EducationEvent",
  "name": "National Financial Literacy Olympiad 2025",
  "startDate": "2025-09-01",
  "endDate": "2025-12-31",
  "eventStatus": "https://schema.org/EventScheduled",
  "eventAttendanceMode": "https://schema.org/OnlineEventAttendanceMode",
  "location": {
    "@type": "VirtualLocation",
    "url": "https://nationalfinanceolympiad.safefintech.in/"
  },
  "image": "https://nationalfinanceolympiad.safefintech.in/assets/nflo-2025-poster.png",
  "description": "NFLO 2025 is India’s largest financial literacy olympiad for school students, conducted by SAFEFINTECH. Register to win prizes and certification.",
  "organizer": {
    "@type": "Organization",
    "name": "SAFEFINTECH",
    "url": "https://safefintech.in"
  }
}
</script>
```

---

## 4. Analytics & Pixel Scripts (before `</head>`) [LATER I WILL PROVIDE]

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'G-XXXXXXXXXX', { 'anonymize_ip': true });
</script>

<!-- Meta Pixel -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', 'YOUR_PIXEL_ID');
fbq('track', 'PageView');
</script>
<noscript>
<img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=YOUR_PIXEL_ID&ev=PageView&noscript=1"/>
</noscript>

<!-- Google Ads -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-XXXXXXXXX"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'AW-XXXXXXXXX');
</script>

<!-- Twitter Pixel -->
<script>
!function(e,t,n,s,u,a){
e.twq||(s=e.twq=function(){s.exe?s.exe.apply(s,arguments):s.queue.push(arguments);
},s.version='1.1',s.queue=[],u=t.createElement(n),u.async=!0,u.src='//static.ads-twitter.com/uwt.js',
a=t.getElementsByTagName(n)[0],a.parentNode.insertBefore(u,a))
}(window,document,'script');
twq('init','YOUR_TWITTER_PIXEL_ID');
twq('track','PageView');
</script>
```

---

## 5. Share Buttons (Put where you want virality/referral)

```html
<!-- WhatsApp Referral -->
<a href="https://wa.me/?text=Register%20for%20NFLO%202025%20now%3A%20https%3A%2F%2Fnationalfinanceolympiad.safefintech.in%2F" target="_blank">
  <img src="/assets/whatsapp-share.png" alt="Share on WhatsApp">
</a>

<!-- Telegram Share -->
<a href="https://t.me/share/url?url=https://nationalfinanceolympiad.safefintech.in/&text=NFLO%202025%20Registrations%20Open%21" target="_blank">
  <img src="/assets/telegram-share.png" alt="Share on Telegram">
</a>

<!-- Facebook Share -->
<a href="https://www.facebook.com/sharer/sharer.php?u=https://nationalfinanceolympiad.safefintech.in/" target="_blank">
  <img src="/assets/facebook-share.png" alt="Share on Facebook">
</a>
```

---

## 6. Sticky Registration Bar (Paste before `</body>` of main landing/registration pages)

```html
<div style="position:fixed;bottom:0;width:100%;background:#F8C400;color:#000;text-align:center;z-index:9999;padding:10px;">
  <strong>NFLO 2025 Registrations Now Open! <a href="/register" style="color:#0B5ED7;text-decoration:underline;">Register Now</a></strong>
</div>
```

---

## 7. UTM Sample Campaign Links (track in Google Analytics/Ads)

```
https://nationalfinanceolympiad.safefintech.in/register?utm_source=google&utm_medium=cpc&utm_campaign=nflo2025
https://nationalfinanceolympiad.safefintech.in/register?utm_source=facebook&utm_medium=meta_ad&utm_campaign=nflo2025
https://nationalfinanceolympiad.safefintech.in/register?utm_source=youtube&utm_medium=video&utm_campaign=nflo2025
```

---

## 8. Pro Tips

- Submit sitemap in Google Search Console & Bing Webmaster Tools before campaign launch.
- Use Google Tag Manager for pixel/analytics scripts for faster deployment.
- Validate all share links on WhatsApp, Facebook, Twitter, Telegram.
- Add OpenGraph, Twitter, and JSON-LD schema to every main page.
- Use sticky CTA on all main registration and landing pages.
- Use UTM links for every paid campaign to track performance granularly.
- Review Google Search Console weekly for crawl/index errors.
- Make share/virality part of every email, SMS, and landing page CTA.

---

**Deploy these assets, and you are ready for maximum discoverability, campaign tracking, and virality across India.**

