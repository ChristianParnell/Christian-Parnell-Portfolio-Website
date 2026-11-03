IMPORTANT: Upload the CONTENTS of this ZIP directly to the root of your GitHub repository, including index.html and css/site.css. Do NOT upload a containing folder. This corrected build includes a static fallback and its own inline JavaScript so no separate script files are required for the page to display.

# Christian Parnell — Portfolio

A complete, static, GitHub Pages-ready profile site. Rebuilt from the original Orbit Website source and inspired by the reference website's compact menu, bold headings, section-based navigation and project-gallery layout. The code and text are original to this project.

## Upload to GitHub Pages

1. Unzip this archive. Upload the **contents** of the `Christian_Parnell_Profile` folder to the root of your GitHub repository, not the containing folder.
2. In GitHub **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`.
3. Open your published Pages URL. The site works at a repository subpath and uses hash navigation (`#/hello/`, `#/gallery/`, etc.).
4. Copy the missing video and image files into `assets/` with the filenames listed below. Commit them and GitHub Pages will show them automatically.

No dependencies, build commands, package manager, third-party JavaScript or API keys needed. Google Fonts are optional; local system font fallbacks are provided.

## Restoring videos and images

The following original paths were taken from the supplied `pages/js/page-gallery.js` file. Keep exact capitalisation: GitHub hosting is case sensitive.

### Videos
- `assets/gallery/videos/video-01-showreel.mp4` — Portfolio Showreel 2026
- `assets/gallery/videos/video-02-22-minutes-trailer.mp4` — 22 Minutes Trailer
- `assets/gallery/videos/Video-03-Fun-Animation.mp4` — Fun Animation
- `assets/gallery/videos/video-04-Woe-Intro.mp4` — Woe Intro
- `assets/gallery/videos/video-05-character-animation.mp4` — Space Ship Animation
- `assets/gallery/videos/video-06-underwater-prototype.mp4` — Underwater Horror Prototype
- `assets/gallery/videos/video-07-vfx-breakdown.mp4` — Old Woe
- `assets/gallery/videos/video-08-ui-motion-pass.mp4` — UI Motion Graphics Pass
- `assets/gallery/videos/video-09-lighting-study.mp4` — Stop Motion Animation
- `assets/gallery/videos/video-10-turntable.mp4` — Spider Motion Capture

### Renders
- `assets/gallery/renders/render-01-orbit-portrait.png` — Hero Render Orbit Portrait
- `assets/gallery/renders/render-02-dusk-environment.png` — 22 Minutes Reactor Core
- `assets/gallery/renders/render-03-character-front.png` — WW2 Render
- `assets/gallery/renders/render-04-character-profile.png` — All Blacks Photobooth Concept
- `assets/gallery/renders/render-05-diving-helmet.png` — Ocean Render
- `assets/gallery/renders/render-06-underwater-bell.png` — Asteroid Belt
- `assets/gallery/renders/render-07-wet-metal-study.png` — Motion Design Animation Render
- `assets/gallery/renders/render-08-blue-grade.png` — Woe 2.0
- `assets/gallery/renders/render-09-wide-composition.png` — Character Animation Render
- `assets/gallery/renders/render-10-final-beauty.png` — Woe 2.0 Bunker

### Optional covers

- `assets/covers/steam_22minutes.png`
- `assets/covers/gallery.png`
- `assets/covers/fab.png`
- `assets/covers/achievements.jpg`

Cards have built-in cover artwork if these files are not added. The moth, orbit, model viewer and related scripts are no longer required. The site intentionally does not include 3D model viewers or model-store cards.

## Editing content

- `index.html`: page text, experience details, projects and links (inline JavaScript for reliable GitHub Pages deployment).
- `index.html`: all 20 media filenames, titles and descriptions (search for `const media`).
- `css/site.css`: colours, font sizes, spacing and responsive layouts.
- `index.html`: navigation and basic metadata.

## Pages

Home, About, Projects, Gallery (filterable with full-size video/image viewer), Experience and Contact. Accessible labels, keyboard focus, Escape-to-close viewer, mobile menu and reduced-motion preferences are included.

## Content notes

Biography, education and job dates follow the uploaded 2026 CV. No private reference contact information is included in the public site. External project links are from the original project and CV. The site does not claim current job availability beyond the short sidebar label, which you can remove if preferred.

This is a style adaptation, not a copy of the reference site's proprietary assets or source code.
