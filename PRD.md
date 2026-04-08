# Product Requirements Document (PRD)

## Landscaping Services Landing Page

**Version:** 1.0
**Date:** 2026-03-30
**Status:** Draft

---

## 1. Overview

A single-page, conversion-optimized landing page for a professional landscaping company. The page is designed to capture leads through quote requests and booking CTAs, while providing enough information for users who need to explore before committing.

---

## 2. Goals & Success Metrics

### Primary Goal

Convert visitors into leads (quote requests, phone calls, form submissions).

### Success Metrics

| Metric                   | Target        |
| ------------------------ | ------------- |
| Form conversion rate     | 8-12%         |
| Bounce rate              | < 40%         |
| Time to first CTA click  | < 15 seconds  |
| Mobile conversion rate   | Within 80% of desktop |
| Page load time           | < 2.5 seconds |

---

## 3. User Flows

### Primary Flow: Immediate Conversion

```
Land on page → See hero headline + CTA → Click "Get a Free Quote" → Fill short form (name, phone, email, service needed) → Submit → Confirmation
```

This flow targets high-intent users who already know they need landscaping services. The hero must communicate value instantly and make the CTA impossible to miss.

### Secondary Flow: Scroll-to-Discover

```
Land on page → Scroll through services → View social proof (reviews, gallery) → Understand process → Build trust → Click CTA or call phone number
```

This flow serves users who are comparing options or aren't sure what they need yet. Each section should reinforce credibility and nudge toward conversion.

---

## 4. Brand & Design Direction

### Brand Mood: Flat, Professional, Direct

| Attribute     | Direction                                                                 |
| ------------- | ------------------------------------------------------------------------- |
| Tone          | Confident, clear, no-nonsense. "We know what we're doing."               |
| Visual style  | Flat design -- no drop shadows, gradients, or textures. Clean lines.     |
| Typography    | Clean sans-serif (e.g., Inter, DM Sans). Bold headings, generous spacing.|
| Color palette | Deep forest/sage green, warm charcoal text, off-white backgrounds. Accent: muted terracotta or warm gold for CTAs. |
| Imagery       | High-quality, consistently color-graded photos. Slightly warm, not over-saturated. |
| Icons         | Simple geometric line icons. No clip art or stock illustrations.         |
| Whitespace    | Generous. Let content breathe. Less is more.                             |

### Copy Voice

- Short, declarative sentences. Active voice only.
- Benefit-led, not feature-led ("A yard you'll actually enjoy" > "We offer mowing services").
- Concrete over abstract ("15 years, 2,000+ properties" > "extensive experience").
- No exclamation marks. No superlatives. No fluff.

---

## 5. Page Structure & Content Sections

### 5.1 Sticky Header / Navigation

- **Logo** (left)
- **Phone number** (clickable, tap-to-call on mobile)
- **Primary CTA button**: "Get a Free Quote"
- Minimal nav links if any -- this is a landing page, not a full site. Keep navigation stripped to maximize focus on conversion.

### 5.2 Hero Section (Above the Fold)

- **Headline**: Benefit-driven, 6-10 words. Example direction: *"Your Property, Professionally Maintained."*
- **Subheadline**: One sentence expanding the value prop. Example: *"Residential and commercial landscaping. Design, build, maintain."*
- **Primary CTA**: High-contrast button -- "Get a Free Quote"
- **Secondary CTA**: "Call Us: (555) 123-4567"
- **Trust indicator**: Single line -- e.g., "Licensed & Insured | Serving [Area] Since [Year]"
- **3D Lawnmower Hero Visual**: An interactive or animated 3D lawnmower model rendered in the hero area to create a memorable, modern first impression. Assets sourced from `Assets/Lawnmower3DHero/`. This replaces a static hero image with an engaging 3D element that reinforces the landscaping brand identity.

### 5.3 Video Showcase Section

- **Lawnmower Video**: A short, autoplay (muted) background or inline video showcasing landscaping work in action. Video assets sourced from `Assets/LawnmowerVid/`.
- Plays inline on scroll-into-view with subtle fade-in. Looped, muted by default with optional sound toggle.
- Acts as a visual break between the hero and content sections, reinforcing professionalism and real-world capability.
- On mobile: compressed/optimized version for performance. Falls back to a poster frame if video cannot load.

### 5.4 Pain Points / Problem Section

Short section that calls out common homeowner frustrations to create resonance:

- "Tired of an overgrown, neglected yard?"
- "Spending weekends on maintenance instead of enjoying your property?"
- "Not sure where to start with a landscape overhaul?"

Transition into: *"We handle it all."*

### 5.5 Services Overview

Visual card grid (2x3 or 3x2 on desktop, stacked on mobile). Each card:

- Geometric icon
- Service name
- One-line description (benefit-focused)

**Services to feature:**

| Service                     | Description Direction                                      |
| --------------------------- | ---------------------------------------------------------- |
| Lawn Care & Maintenance     | Regular mowing, edging, fertilization. A lawn that stays green. |
| Landscape Design            | Custom plans tailored to your property and budget.         |
| Hardscaping                 | Patios, walkways, retaining walls. Built to last.          |
| Tree & Shrub Care           | Pruning, trimming, removal. Healthy trees, clean lines.    |
| Irrigation Systems          | Efficient watering. Smart controllers, zero waste.         |
| Seasonal Cleanup            | Spring prep, fall cleanup. Your yard, year-round.          |

### 5.6 How It Works

Simple 3-step horizontal layout:

1. **Request a Quote** -- "Tell us about your property and what you need."
2. **We Plan & Design** -- "We visit your site and build a custom plan."
3. **We Get to Work** -- "Sit back. We handle the rest."

### 5.7 Social Proof / Trust Section

- **Review highlights**: 3 short customer testimonials with name, location, and star rating.
- **Aggregate rating**: "Rated 4.9/5 from 200+ reviews"
- **Trust badges**: Licensed & Insured, BBB Accredited, any local/industry certifications.
- **Stats bar**: Years in business | Properties served | Projects completed

### 5.8 Before/After Gallery

- 4-6 project images in a before/after slider or side-by-side layout.
- Brief caption per project (service type + location).
- Demonstrates transformation -- the strongest visual proof of capability.

### 5.9 Secondary CTA Block

Full-width section with a repeated CTA:

- Headline: *"Ready to transform your property?"*
- CTA: "Get a Free Quote"
- Seasonal urgency (authentic): *"Spring slots are filling up -- book your consultation today."*

### 5.10 FAQ Section

Collapsible accordion. Address the top objections:

| Question                                    | Answer Direction                                      |
| ------------------------------------------- | ----------------------------------------------------- |
| How much does landscaping cost?              | Varies by scope. Free estimates, no obligation.       |
| Do you offer free estimates?                 | Yes, always.                                          |
| Are you licensed and insured?                | Yes. Full licensing and liability coverage.            |
| What areas do you serve?                     | List service area.                                    |
| How long does a typical project take?        | Depends on scope. We provide timelines upfront.       |
| Do you offer maintenance plans?              | Yes, weekly/biweekly/monthly options.                 |

### 5.11 Footer

- Company name & logo
- Phone number (tap-to-call)
- Email address
- Service area
- Social media links
- "Licensed & Insured" badge
- Copyright

---

## 6. Conversion Elements

### Forms

- **Fields**: Name, phone, email, service type (dropdown), brief description (optional textarea)
- Keep it to 4-5 fields max. Each additional field reduces conversions.
- Form appears: in hero section (or modal on CTA click) AND after the gallery section.

### CTA Strategy

| Location            | CTA Text              | Style             |
| ------------------- | --------------------- | ----------------- |
| Sticky header       | "Get a Free Quote"    | Accent color, small |
| Hero                | "Get a Free Quote"    | Accent color, large |
| After services      | "See What We Can Do"  | Secondary style   |
| After gallery       | "Get a Free Quote"    | Accent color, large |
| Footer              | Phone + email         | Text links        |

### Phone Number

- Visible in sticky header at all times
- Clickable on mobile (tel: link)
- Floating call button on mobile that follows scroll

### Trust Signals

- Placed immediately after hero (trust bar) and in dedicated section
- Licensed & Insured, BBB, review aggregation
- Trust badges near forms to reduce friction at point of conversion

---

## 7. Technical Requirements

| Requirement          | Specification                                           |
| -------------------- | ------------------------------------------------------- |
| Framework            | Next.js (already initialized)                           |
| Styling              | Tailwind CSS                                            |
| Responsive           | Mobile-first, breakpoints at sm/md/lg/xl                |
| Performance          | Lighthouse score > 90. Optimized images (WebP/AVIF).   |
| Accessibility        | WCAG 2.1 AA minimum. Semantic HTML, proper ARIA labels. |
| SEO                  | Meta tags, Open Graph, structured data (LocalBusiness schema). |
| Analytics-ready      | Placeholder for GA4 / conversion tracking events.       |
| Forms                | Client-side validation. Ready for backend integration.  |
| Animations           | Subtle, purposeful. Scroll-triggered fade-ins only. No heavy animation libraries. |
| 3D Rendering         | Three.js or React Three Fiber for the hero 3D lawnmower model (`Assets/Lawnmower3DHero/`). Lazy-loaded to avoid blocking initial paint. |
| Video                | HTML5 `<video>` for the lawnmower video (`Assets/LawnmowerVid/`). Lazy-loaded, muted autoplay on scroll. Compressed for web (MP4 H.264 + WebM fallback). |

### Asset Directory Structure

```
Assets/
├── Lawnmower3DHero/    # 3D model files for the hero section (e.g., .glb, .gltf, textures)
└── LawnmowerVid/       # Video files for the video showcase section (e.g., .mp4, .webm, poster images)
```

---

## 8. Content Requirements

| Content Asset             | Needed From Client           | Placeholder Strategy         | Location                     |
| ------------------------- | ---------------------------- | ---------------------------- | ---------------------------- |
| 3D Lawnmower model        | 3D model file (.glb/.gltf)  | Simple placeholder geometry  | `Assets/Lawnmower3DHero/`    |
| Lawnmower/landscaping video | Short video clip (15-30s)  | Static poster image fallback | `Assets/LawnmowerVid/`       |
| Service photos            | 6 service category photos    | Stock per category           | `public/`                    |
| Before/after pairs        | 4-6 project pairs            | Stock pairs                  | `public/`                    |
| Testimonials              | 3-5 real customer reviews    | Realistic placeholder copy   | --                           |
| Company stats             | Years, project count, rating | Placeholder numbers          | --                           |
| Logo                      | SVG logo file                | Text-based logo              | `public/`                    |
| Phone number              | Business phone               | Placeholder                  | --                           |
| Service area              | Cities/regions served         | Placeholder area             | --                           |

---

## 9. Out of Scope (v1)

- Blog / content pages
- Individual service detail pages
- Online scheduling / calendar integration
- Payment processing
- Customer portal / login
- Live chat widget
- Multi-language support

---

## 10. Open Questions

1. Does the client have an existing brand guide, logo, or color preferences?
2. What is the primary service area (city/region)?
3. Which services should be emphasized most prominently?
4. Are there real testimonials and project photos available, or do we start with placeholders?
5. Is there a preferred form submission backend (email, CRM, etc.)?
6. Should the seasonal urgency messaging reference a specific season/promotion?
