# Maryam Torkashvand Website and Portfolio

## Project Overview

Multi-page personal/professional website for Maryam Torkashvand, a portfolio/resume/skill-oriented website. Static HTML files with embedded CSS and JavaScript—no build step required.

## Related Sites

- **a good example of GIS portfolio**: https://gispro.me/
- **old maryamtorkashvand.com website**: https://maryamtorkashvand.com/

## Tech Stack

- **Framework**: Static HTML (no build step)
- **Styling**: Embedded CSS
- **JavaScript**: Vanilla JS, embedded
- **Hosting**: cloudflare
- **Fonts**: Inter (Google Fonts CDN)

## File Structure

```
/personalwebsite/
├── index.html          # Main landing page
├── about.html          # About page 
├── contact.html        # Contact page
├── competencies.html   # Short description of skills
├── projects 		# separated projects that each link to the main page or external link
├── CLAUDE.md           # This file
├── experiences.html 	# profetional experiences
```


## Design System

### Colors
| Hex | Usage |
|----|-------|
| `d7cec7` | Background |
| `#76323f`| Accents, CTAs |
| `#c7d0d7` | boxes, sections |
| `#d7c7d0` | Hover states |
| `#d7c7d0` | Active states |

### Typography
- **Font**: Inter
- **Weights**: 300-800
- **Letter spacing**: -0.03em (tight)

### Corner Radii
Squared/luxe aesthetic — avoid rounded pills:
- Small: `4px`
- Medium: `6px`
- Large: `8px`


## Page Structure and content and goal

- Inspired by https://gispro.me/ and combine it with the context from https://maryamtorkashvand.com/ and https://www.linkedin.com/in/maryam-torkashvand/

- Extract content from the CV, résumé, skills, etc, files in the resume directory (if available) and linkdin and maryamtorkashvand.com and generate clear, simple, concise, related, and professional content for each section.

- The goal of this website is to showcase the variation of my skill range efficiently. So it can help me land various positions.

## Interactive Features

- Scroll-triggered reveal animations via Intersection Observer
- Animated counters with easeOutQuart easing
- Mouse-following cursor glow effect (desktop only)
- Scroll progress indicator in header
- Smooth scroll navigation
- Fully responsive down to mobile


## External Dependencies

- **Google Fonts**: Inter font family via CDN

## Common Tasks

### Update Content
Edit the relevant HTML file directly. All content, styles, and scripts are embedded.


## Notes

- Keep the single-file architecture — no bundlers or build steps
- You may add needed files for new pages — files that are needed for the website
- Maintain the squared corner aesthetic (no pills)
- Test scroll animations after content changes
- Counter animations trigger on scroll into view
- **index.html is the main landing page** — don't overwrite with feature content
