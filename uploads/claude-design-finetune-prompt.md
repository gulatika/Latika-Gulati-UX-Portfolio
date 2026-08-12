# Claude Design prompt: fine-tune my portfolio (do not redesign)

I'm attaching a working HTML prototype of my portfolio (portfolio-final-mock.html). It is already designed, structured, and approved. Your job is FINE-TUNING and polish, not redesign. Keep the structure, palette, typography, copy placement, and interaction patterns exactly as they are unless I ask otherwise.

## Who I am (context, not copy to rewrite)
Latika Gulati, senior UX designer with an engineering background (24 patents). The site's thesis is "calibrating friction": knowing when to smooth a path and when a little resistance is the point. Audience: hiring managers and recruiters for senior product design roles. Desired reaction: "she knows her stuff, I want to talk to her."

## Locked decisions (do not change)
- **Structure:** single-scroll Home (hero, six case studies with the top three as full cards and three as a light list, dark philosophy block, Off the Clock teaser, About teaser, footer contact). Separate pages for each case study, About, and Off the Clock. No separate Work page; "Work" in nav anchors to the home work section. No contact page, no forms, no blog.
- **Case study template:** back link, eyebrow, title, one-line summary, spec-token metadata row (Role / Team / Timeline / Tools), periwinkle-tag row, "Ask me about" hooks box, then The Problem / The Approach / Key Decisions / Outcome / Reflection, one testimonial quote, and Previous/Next cards at the bottom so readers never have to navigate back.
- **Palette:** Old Lace #F5EEE0 base, Carbon Black #231F1A text, Brandy #862809 primary (buttons, links, headers accents), Soft Periwinkle #A09BE7 as the single loud pop (hero highlight, eyebrow squares, "calibrated" word), Palm Leaf #758E4F as the quiet accent (tags, some sparkles). Only periwinkle gets to be loud.
- **Type:** Newsreader for display/headlines (chosen specifically over Fraunces, whose lowercase f I dislike; do not swap back to Fraunces), Inter for body, JetBrains Mono for labels/metadata/eyebrows. Mono is used sparingly.
- **Voice:** warm, direct, first person. No em dashes or en dashes anywhere, ever. Most copy is placeholder that I will rewrite myself; do not "improve" it into AI-speak.
- **Signature elements:** hand-drawn portrait placeholder (I will supply my own drawing), hand-drawn sparkles (stars, squiggles, spirals, plus marks) scattered lightly, the rotating "currently excited about" hobby module, and the footer note "Built in collaboration with Claude. Designed and coded by me."
- **Motion philosophy:** calm and minimal. Gentle scroll reveals, slight hover lifts, slow ambient bob/spin on a few sparkles. prefers-reduced-motion must disable all of it. Do not add parallax, cursor effects, page transitions, or anything showy.

## What I DO want you to fine-tune
1. **Spacing consistency across breakpoints.** The prototype uses a spacing scale (8/16/24/40/64/96). Audit every section on desktop, tablet (~768-820px), and mobile (~375px) so vertical rhythm feels identical in character across sizes: nothing cramped, nothing cavernous, no orphaned elements, nothing clipped or overflowing.
2. **Navigation seamlessness.** The hamburger appears at 820px and below. Polish the open/close feel, tap targets (44px minimum), active states, and make sure anchor scrolling (Work, Say hi) lands with comfortable offset below the sticky nav on all screen sizes.
3. **Sparkle placement.** Keep the existing sparkle system (reusable SVG stars, squiggles, spirals, plus marks in periwinkle, green, and brandy). Refine positions so they feel hand-placed and never collide with text at any viewport width. A few per screen, not confetti. They should feel like marginalia doodles, not decoration spam.
4. **Micro-interaction polish.** Hover states on cards, list rows, and buttons are sketched in; make the timing and easing feel cohesive (one easing family sitewide). Case study thumbnails lift slightly on hover; keep that subtle.
5. **Typography refinement.** Check heading line lengths, widows on the hero and philosophy block, and mobile heading sizes. The hero headline should never break awkwardly on common widths.
6. **Accessibility pass.** WCAG AA contrast on all text over Old Lace and the dark philosophy block, visible focus states, alt text placeholders, correct landmarks and heading order, keyboard-navigable menu.
7. **Performance.** Keep it lightweight and dependency-free. System-hosted Google Fonts only, no frameworks, no build step required.

## Placeholders to preserve (I will supply real assets later)
- Hand-drawn portrait (currently a simple line-art stand-in) plus sticker doodles
- All case study visuals ("case study visual" figures)
- Ceramics and hobby photos on Off the Clock
- Testimonials (marked as placeholder)
- Resume PDF link
Keep every placeholder clearly labeled and easy to swap.

## Real details already final
- Email latika.gulati.0@gmail.com, LinkedIn linkedin.com/in/latikagulati/, Calendly calendly.com/latika-gulati/new-meeting
- Nav: Latika Gulati wordmark, Work, About, Off the Clock, Say hi (button)
- Hobby rotation list: junk journaling, crochet, watercolor, hand-sewing, knitting, scrapbooking, throwing a new mug

## Output
Return the refined site as clean, semantic, componentized static HTML/CSS/JS that I can deploy to latikagulati.com. Show me desktop and mobile views of Home and one case study before finalizing.
