# First Smile Dental Clinic Website

Premium static website for **First Smile Dental Clinic, Katihar**, led by **Dr. Chandan Kumar, BDS, MIDA, FAGE**. The site is built for local search visibility, fast loading, mobile-first browsing, and simple WhatsApp appointment booking.

## Project Overview

This repository contains the complete website source and generated static output for First Smile Dental Clinic. It includes the homepage, About page, doctor profile, service pages, gallery, testimonials, FAQ, blog, contact page, appointment flow, SEO files, and local preview-ready paths.

Primary output:

```text
outputs/first-smile-dental-clinic/
```

## Features

- Premium responsive dental clinic design
- SEO pages for local Katihar dental searches
- Dedicated treatment pages:
  - Root Canal Treatment
  - Dental Implants
  - Teeth Cleaning
  - Teeth Whitening
  - Braces
  - Tooth Extraction
  - Dental Fillings
  - Dentures
  - Pediatric Dentistry
  - Smile Makeover
  - Emergency Dental Care
- WhatsApp appointment booking
- Click-to-call phone links
- Google Maps integration
- FAQ accordion
- Gallery lightbox
- Smooth reveal animations
- `robots.txt` and `sitemap.xml`
- Canonical URLs, Open Graph tags, Twitter card metadata
- JSON-LD schema for dental clinic and FAQ content
- Local preview-friendly internal links

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Node.js build script
- Static hosting compatible output

No framework or database is required.

## Folder Structure

```text
.
├── outputs/
│   ├── first-smile-dental-clinic/   # Production static website output
│   └── premierartsdental-clone/     # Mirrored output copy
├── scripts/
│   └── build-first-smile-pages.mjs  # Static page generator
├── package.json
├── README.md
└── .gitignore
```

## Installation

Install Node.js, then run:

```bash
npm install
```

There are no external package dependencies at this time.

## Build

Regenerate the static pages:

```bash
npm run build
```

The generated website is written to:

```text
outputs/first-smile-dental-clinic/
```

## Local Preview

Start a local static server:

```bash
npm run preview
```

Then open:

```text
http://localhost:8080
```

You can also open `outputs/first-smile-dental-clinic/index.html` directly in a browser.

## Environment Variables

No environment variables are required.

## Deployment

Deploy the contents of:

```text
outputs/first-smile-dental-clinic/
```

to any static hosting provider, such as:

- GitHub Pages
- Netlify
- Vercel static deployment
- Cloudflare Pages
- cPanel or traditional shared hosting

Make sure the production domain is updated in `scripts/build-first-smile-pages.mjs` if the final domain is different from the placeholder canonical domain.

## SEO Notes

The website includes local SEO targeting for:

- Dental Clinic in Katihar
- Best Dental Clinic in Katihar
- Dentist in Katihar
- Best Dentist in Katihar
- Root Canal Treatment in Katihar
- Dental Implants in Katihar
- Teeth Cleaning in Katihar
- Braces in Katihar
- Emergency Dentist in Katihar
- Kids Dental Clinic in Katihar

Generated SEO files:

```text
outputs/first-smile-dental-clinic/robots.txt
outputs/first-smile-dental-clinic/sitemap.xml
```

## Clinic Information

**First Smile Dental Clinic**  
Dr. Chandan Kumar, BDS, MIDA, FAGE  
Oral & Dental Surgeon  
Phone & WhatsApp: +91 8171515184  
Address: Kalibari Road, Behind Sakshi Medical, Near FirstCry Showroom, Katihar, Bihar

## License

All clinic branding, local content, and supplied assets are intended for First Smile Dental Clinic.
