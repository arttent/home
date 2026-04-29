Background  
ARTTENT is a Georgian art management company based in Tbilisi, active across Georgia and internationally since 2019.

Website Purpose  
Promotion of ARTTENT’s art initiatives and services, showcasing artists and projects, and facilitating contact from collectors, institutions, and artists.

Design Preferences  
Clean, contemporary, art‑focused presentation.  
Hero section content centered horizontally and vertically across all viewport sizes, with responsive scaling.  
Hero background image positioned left-bottom so the darkest area is prominent, without device-specific variants.  
Artist blocks use rectangular visuals with names placed in the lower left.  
Logo only on the left side of the navbar, significantly larger than before, scaling down appropriately on mobile.  
Single logo asset with transparent background; visual treatment varies with navbar background (normal on light, inverted on dark/transparent).  
Navigation buttons positioned on the right side of the navbar.  
Mobile navigation menu icon sized for clear tap targets.  
Exactly 12 images in the relevant image section.  
Hero text and icons remain hidden until their respective fonts load; each font independently controls visibility of its related elements.  
Artist visuals use the provided WebP assets.  

Technical / Structural Requirements  
Single-page marketing site.  
Use the provided custom favicon.  
Use preconnect and preload selectively, only where beneficial.  
Only the main CSS file is render‑blocking; all other CSS and all fonts load non‑blocking.  
Fonts above the fold load non‑blocking; layout shifts and animations are deferred per font until that font is loaded.  
“ARTTENT Image Gallery” images load only after primary page content has finished loading.