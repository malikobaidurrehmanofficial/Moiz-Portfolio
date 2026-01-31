You are building a modern, cinematic portfolio website for a professional
VIDEO EDITOR & MOTION DESIGNER.

The design inspiration is a dark, minimal, creative video editor portfolio
with strong typography, full-width sections, and focus on video content.
(No need to copy any specific design pixel-by-pixel.)

==============================
TECH STACK (STRICT)
==============================
- HTML5
- CSS3 (modern CSS, flexbox, grid)
- Vanilla JavaScript (NO React, NO frameworks)
- Clean, readable, commented code

==============================
PROJECT STRUCTURE
==============================
/index.html
/css/style.css
/js/main.js
/images/moiz.png (profile image placeholder)
/videos/ (video links will be external Google Drive links)

==============================
GENERAL DESIGN STYLE
==============================
- Dark theme (near black background)
- Cinematic feel
- Minimal text
- Large headings
- Smooth transitions
- Professional creative studio look

==============================
SECTIONS REQUIRED
==============================

1) HERO SECTION
- Full viewport height
- Left side: text
  - Name (placeholder)
  - Title: "Video Editor & Motion Designer"
  - Short tagline (placeholder)
- Right side:
  - Profile image loaded from ./images/moiz.png
  - Image should be circular or softly rounded
- CTA buttons:
  - "View Work"
  - "Contact"

2) SHOWREEL / PORTFOLIO SECTION
- Grid layout for videos
- Total videos: 8
- Videos will be embedded using Google Drive links (placeholders for now)
- Each video card:
  - Thumbnail placeholder
  - Title
  - Short description
- Clicking opens video in modal/lightbox overlay
- Categorize visually:
  - Short-form
  - Long-form

3) ABOUT SECTION
- Short professional bio placeholder
- Focus on:
  - Experience
  - Creative style
  - Tools expertise (Premiere Pro, After Effects – text only)

4) SOCIAL LINKS SECTION
- Icons only UI
- Facebook, X (Twitter), LinkedIn
- Links will be added later, but UI must be present
- Hover animation on icons

5) FOOTER
- Minimal
- Name + role
- Dark and subtle

==============================
UNIQUE FEATURE (IMPORTANT)
==============================

Create a FIXED bottom mini timeline inspired by video editing software.

TIMELINE REQUIREMENTS:
- Fixed at bottom of screen
- Small height (approx 32–40px)
- Dark UI
- Horizontal bar
- Movable playhead indicator
- Play and Pause buttons

TIMELINE BEHAVIOR:
- When Play is clicked:
  - Playhead animates smoothly from left to right
  - Duration approx 6–8 seconds
- When it reaches the end:
  - Animation stops
  - Playhead resets to the start
  - Page smoothly scrolls back to the top
- Pause button stops animation immediately
- Timeline should NOT interfere with page scrolling

Use vanilla JavaScript animation logic.
GSAP is NOT required but smooth CSS transforms are preferred.

==============================
CODE QUALITY
==============================
- Use semantic HTML
- Use CSS variables for colors
- Add meaningful comments
- Make layout responsive
- Keep JS modular (functions)

==============================
PLACEHOLDERS
==============================
- Profile image path: ./images/moiz.png
- Video links: placeholder Google Drive URLs
- Social media links: "#" for now

==============================
GOAL
==============================
Create a visually impressive, professional video editor portfolio
that feels inspired by real video editing software UI,
with a unique interactive timeline at the bottom.
