Background  
ARTTENT is a Georgian art management company based in Tbilisi, active across Georgia and internationally since 2019.

Website Purpose  
Promotion of ARTTENT’s art initiatives and services, showcasing artists and projects, and facilitating contact from collectors, institutions, and artists.

Design Preferences  
Clean, contemporary, art‑focused presentation.  
Hero section content centered horizontally and vertically across all viewport sizes, with responsive scaling.  
Hero background image positioned left-bottom so the darkest area is prominent.  
Artist blocks use rectangular visuals with names placed in the lower left.  
Logo only on the left side of the navbar, larger than before, scaling down on mobile.  
Single logo asset with transparent background; visual treatment varies with navbar background (normal on light, inverted on dark/transparent).  
Navigation buttons on the right side of the navbar.  
Mobile navigation menu icon sized for clear tap targets.  
Exactly 12 images in the designated image section.  
Hero text and icons hidden until their respective fonts load; each font independently controls visibility of its related elements.  
Artist visuals use the provided WebP assets.

Technical / Structural Requirements  
Single-page marketing site.  
Custom favicon.  
Preconnect and preload used selectively only when beneficial.  
Only the main CSS file is render‑blocking; all other CSS and all fonts load non‑blocking.  
Fonts above the fold load non‑blocking; layout shifts and animations deferred per font until that font is loaded.  
“ARTTENT Image Gallery” images load only after primary page content has finished loading.  
Use Umami for analytics instead of Google Analytics.