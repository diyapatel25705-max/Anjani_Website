# Anjani Spring Co. — website starter

A responsive single-page website concept for Anjani Spring Co., based on the supplied logo and business cards. It includes a navy/white industrial design system, a scroll-responsive hero, product categories, manufacturing and quality sections, application areas, a quote enquiry form, and mobile navigation.

## Important product-photo choice

The hero uses the spring image supplied in this conversation (`assets/spring-reference.png`) instead of a glowing procedural 3D spring. Because the supplied source image is very small, it may look soft when enlarged. For the final production site, replace it with a high-resolution photograph of an actual Anjani product on a clean background. Do not present generated factory or product concepts as documentary proof of the real facility or product range.

## Run locally

Requires Python 3 (or any local static web server). From this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`. The core layout, animations, and form preview work without external JavaScript libraries. Google Fonts require an internet connection; fallback fonts are configured.

## Included

- `index.html` — responsive homepage and quote form
- `styles.css` — navy, white, steel visual system and mobile layout
- `script.js` — scroll-driven photo movement, reveal effects, mobile navigation, progress indicator, and email-draft form behavior
- `assets/anjani-logo.png` — supplied company logo
- `assets/spring-reference.png` — supplied spring photo

## Before production launch — verification checklist

1. **Contact details conflict across the supplied cards.** The contact card lists `+91 63592 71231` and `+91 99241 00016`; the profile card lists different numbers. Confirm primary and secondary phone numbers.
2. **Email addresses conflict across the cards.** The contact card lists `anjanispring2012@gmail.com`; the profile card lists `info@anjanispringco.com`. Confirm the preferred enquiry inbox and update all links.
3. **ISO certification:** verify the current ISO 9001:2015 certificate, issuing body, scope, validity, and permitted logo use. The website marks the claim for verification.
4. **Capabilities:** confirm supported spring types, materials, wire diameters, tolerances, loads, and production quantities. Numeric capability claims are not invented in this draft.
5. **Industries:** the listed sectors are illustrative application areas, not verified customer/supply history. Approve or remove each.
6. **Factory imagery:** replace illustrative CSS graphics with real factory/machinery/inspection photos or approved video before claiming they show your facility.
7. **Quote form:** currently opens the visitor's email app through `mailto:` and does not transmit or store data. For production, connect a secure server-side form or CRM, add validation and spam protection, and implement secure file uploads if required.
8. Add privacy policy, legal/business registration details, and consent wording as applicable.
9. Test current mobile and desktop browsers, keyboard navigation, reduced-motion settings, performance, and form behavior.

## Suggested production upgrade

For advanced 3D effects in a future iteration, use Three.js/React Three Fiber and GSAP only after sourcing a high-resolution, approved product model or photo. The current hero deliberately prioritizes the supplied product photo over a synthetic spring model.

## Draft content note

All marketing copy is a first draft based on the supplied cards and the requested brand direction. Verify factual statements, contact details, product capabilities, and certification information before publication.
