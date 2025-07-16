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

## 3. Meta Tags & Schema (Put this as a first thing inside `<head>` on every page)

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
  "startDate": "2025-09-05",
  "endDate": "2025-09-20",
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

## 8. CheckList for developer ( Mr. Amit )

- Ensure every link has been put up correctly.
- <meta property="og:image" content="https://nationalfinanceolympiad.safefintech.in/assets/nflo-2025-poster.png" /> [UPLOAD THE NFLO POSTER WHICH I HAVE SENT TO YOUR EMAIL ID under assets folder] . Ensure every meta tag with og:image have correct link
- 


---


