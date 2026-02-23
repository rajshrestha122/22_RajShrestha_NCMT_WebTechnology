
# Chapter 4: Website Design Principles – Answers Adjusted by Marks

### Group A: Short Questions (2 Marks each) – Keep answers short & precise

1. Differentiate between Legibility and Readability.  
Legibility is how clearly individual letters and characters can be identified (depends on font design: stroke contrast, letter spacing, x-height).  
Readability is how easily and comfortably a block of text can be read and understood (depends on line length, leading, contrast, paragraph spacing, alignment).  
In short: Legibility = recognizing single letters; Readability = reading long passages without strain.

2. What is the "Rule of Thirds" in layout design?  
The Rule of Thirds divides a layout into a 3×3 grid (two horizontal + two vertical lines).  
Important elements are placed along these lines or at the four intersection points instead of dead center.  
This creates more balanced, dynamic, and visually interesting compositions.

3. Why should you limit the number of font families used on a website?  
Limiting to 2–3 font families maintains visual consistency, strengthens typography hierarchy, reduces page load time (fewer font files), and lowers user
 cognitive load.  
Too many fonts make the site look chaotic, amateur, and slower.

5. Define "Responsive Web Design."  
Responsive Web Design (RWD) is an approach where a single website automatically adapts its layout, images, and content to any screen size (mobile, tablet, desktop) using fluid grids, flexible images, and CSS media queries.

### Group B: Long Questions (4 Marks each) – Medium-long answers with explanation & examples

5. Explain the "F-Pattern" of scanning and how it influences the placement of content on a web page.  
The F-Pattern is a common user scanning behavior discovered through eye-tracking studies (Nielsen Norman Group).  
Users typically:  
1. Read horizontally across the top of the page (top bar of F),  
2. Move down slightly and read another shorter horizontal line (second bar),  
3. Then scan vertically down the left side (stem of F).  

This happens because people scan quickly for relevant info rather than read everything, and Western reading goes left-to-right, top-to-bottom.  
Design implication: Place the most important content (headline, main CTA, hero image, value proposition) in the top horizontal area.  
Secondary important items (subheadings, benefits, trust signals) go along the left column or second horizontal zone.  
Less critical content can be lower or right.  
Ignoring the F-Pattern often causes users to miss key messages and leave the page quickly.

6. Discuss the psychological impact of colors in web design. Give examples of where Blue, Red, and Green should be used.  
Colors strongly influence emotions, trust, and behavior subconsciously.  
- Blue → trust, calmness, professionalism, security.  
  Best for: banks, tech companies, corporate sites, social platforms (Facebook, LinkedIn, PayPal use blue heavily). Use for backgrounds, nav bars, trust badges.  
- Red → energy, urgency, excitement, danger, importance.  
  Best for: call-to-action buttons (“Buy Now”, “Sale”), warnings, error messages (Netflix, YouTube, Coca-Cola). Use sparingly as dominant color because it can feel aggressive.  
- Green → growth, health, nature, money, safety, positivity.  
  Best for: finance apps, eco-friendly brands, health sites, success messages (“Go” buttons – Spotify, Android green).  

Choose colors that match brand personality and audience, ensure good contrast (WCAG), and test real user reactions.

7. Explain the "60-30-10 Rule" regarding color balance on a website.  
The 60-30-10 rule is a simple guideline for balanced, professional color schemes:  
- 60% → Dominant color (usually neutral – white, light gray, soft blue/black). Used for largest areas (main background, body content) to set the overall tone.  
- 30% → Secondary color (stronger but supporting – dark gray, navy, medium green). Used for headers, sidebars, sections, hover states to add structure.  
- 10% → Accent color (boldest – red, orange, gold, electric blue). Used sparingly for CTAs, links, buttons, icons to draw attention and guide action.  

Example: 60% white background + 30% navy headers + 10% orange buttons.  
This prevents visual overload, creates clear hierarchy, and makes the site feel intentional and polished.

### Group C: Scenario-Based Questions (5 Marks each) – Longer, detailed answers with analysis & suggestions

8. A website loads very slowly... Explain the importance of Image Optimization and file formats (JPEG vs PNG) to solve this.  
High-resolution raw images from cameras (often 5–20 MB each) are a leading cause of slow websites.  
Users abandon pages that take >3 seconds to load (Google studies), hurting bounce rate, conversions, and SEO (Core Web Vitals).  

**Importance of image optimization:**  
- Drastically reduces file size (50–90% smaller) → faster loading  
- Improves Largest Contentful Paint (LCP) and overall performance  
- Saves mobile data usage  
- Boosts SEO ranking and user satisfaction  

**JPEG vs PNG comparison:**  
- JPEG: Lossy compression → excellent for photos/realistic images with many colors. Achieves very small sizes but loses some detail (can show artifacts if over-compressed). No transparency support.  
  → Use for: hero photos, product images, blog pictures.  
- PNG: Lossless compression → no quality loss, supports full transparency (alpha channel). File size larger than JPEG for photos.  
  → Use for: logos, icons, screenshots, illustrations needing sharp edges or transparent backgrounds.  

**Modern best practices (2025+):**  
- Resize images to match display size (never serve 4000px image on mobile)  
- Compress with tools (TinyPNG, Squoosh, ImageOptim)  
- Prefer WebP or AVIF formats (better compression than JPEG/PNG, good browser support)  
- Use lazy loading (`loading="lazy"`)  
- Serve responsive images via `<picture>` or `srcset`  

Implementing these can cut load time dramatically and retain users.

9. You are designing a website for a Law Firm. The client wants to use a bright yellow background with Comic Sans font to look "friendly." Critique this choice... and suggest a better alternative.  
The client’s goal (friendly feel) is understandable, but the choices are inappropriate for a law firm where **trust, authority, and professionalism** are essential.  

**Critique:**  
- Bright yellow background: High energy and cheerful, but fatiguing for reading legal text. Low contrast with most text → poor legibility & accessibility (likely WCAG failure). Associated with warnings, cheap products, fast food — not seriousness or reliability.  
- Comic Sans: Playful, child-like, informal font designed for comics. Poor spacing, inconsistent strokes, widely considered unprofessional. Using it severely damages credibility — clients may question competence.  

**Better alternative:**  
Color palette:  
- Dominant (60%): Charcoal gray (#1F2937), navy blue (#0F172A), or deep teal → trust & calm authority  
- Secondary (30%): Medium gray or soft blue-gray → clean supporting areas  
- Accent (10%): Subtle gold (#D4A017), burgundy, or dark green → prestige without being flashy  

Typography:  
- Headings: Serif font with tradition (Merriweather, Georgia, Playfair Display)  
- Body: Clean, legible sans-serif (Inter, Roboto, Source Sans Pro, system-ui)  
-Buttons/links: Same sans-serif or slight variation for consistency  

This combination feels professional yet approachable through good white space, clear language, and client testimonials — exactly what legal clients need.  
Show the client side-by-side mockups to demonstrate why the original choice risks losing trust.

10. A website looks great on a laptop but is unreadable on a mobile phone because the user has to zoom in and scroll horizontally. Identify the design principle missing here and explain how Media Queries/Fluid Grids could fix it.  
**Missing principle:** Responsive Web Design (RWD) — the site uses a fixed-width layout (e.g., 960–1200px container) that doesn’t adapt to smaller screens.  

**Problems caused:**  
- Tiny text requiring zoom  
- Horizontal scrolling (annoying on touch devices)  
- Poor usability → high bounce rate, bad SEO (Google’s mobile-first indexing penalizes non-responsive sites)  

**How to fix with Fluid Grids + Media Queries:**  

1. **Fluid Grids** (foundation):  
   Replace fixed pixels with relative units  
   ```css
   .container { width: 90%; max-width: 1200px; margin: 0 auto; }
   .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; }
   img { max-width: 100%; height: auto; }
