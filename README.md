# Hridesh Fitness — Portfolio Website

## Overview
A fast, responsive portfolio website for Hridesh, a gym instructor and personal trainer. It showcases services, certifications, client success stories, pricing, sample schedule, and a contact form that composes an email.

Key features:
- Lightweight, no external dependencies for fast loads
- Responsive design with accessible navigation
- Programs, testimonials, certifications, pricing, schedule, and gallery sections
- Contact form with mailto submission, plus direct contact details
- SEO meta tags and JSON-LD structured data
- Dark/light theme toggle with preference saved locally
- MIT-licensed

## Setup
- No build steps required.
- Download or clone the repository.
- Open index.html in any modern browser.

Optional:
- Host on any static hosting (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
- Replace placeholder links and contact details with real ones:
  - hridesh.fit@example.com
  - +91 99999 99999
  - Social links and website URL in JSON-LD

## Usage
Customize content:
- Branding: Change the “Hridesh Fitness” title, favicon SVG, and hero text in index.html.
- Programs, testimonials, certifications, pricing: Edit the relevant section content.
- Schedule: Update the table under the Schedule section.
- Contact details: Update email, phone, social links, and location in the Contact section and JSON-LD.
- Colors and styles: Adjust CSS variables in the :root block.
- Gallery: Replace placeholder tiles with real images or keep the abstract look for performance.

Form handling:
- By default, the form uses mailto to open the user’s email client with pre-filled content.
- For server-side handling, point the form to your backend endpoint and remove the mailto logic in the script.

Performance tips:
- Keep images optimized; use modern formats (WebP/AVIF).
- Avoid heavy third-party scripts to ensure the page loads within 15 seconds on slow networks.

## License
MIT License

Copyright (c) 2025 Hridesh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.