# ORBIT-8 Project

## Project Overview
ORBIT-8 is a landing page for a fictional audio product: a groovebox/sampler/synth engine called "ORBIT-8" by Phaseform Audio. The site features a modern, space-themed design with a clean, minimalist aesthetic.

## Tech Stack
- Pure HTML/CSS (no frameworks)
- Google Fonts: Space Grotesk (headings) & Inter (body text)
- Responsive design with mobile breakpoints

## Design System

### Colors
- **Primary Blue**: `#4a9eff` - Used for CTAs, links, borders, and accents
- **Background**: `#000` (pure black)
- **Text Primary**: `#fff` (white)
- **Text Secondary**: `#b0b0b0` (gray)
- **Text Muted**: `#666` (dark gray)
- **Gradient**: `linear-gradient(180deg, #6eb5ff 0%, #ffffff 100%)` - Used for ORBIT-8 header text

### Typography
- **Headings/Display**: Space Grotesk (500, 600, 700 weights)
- **Body/UI**: Inter (400, 500, 600 weights)
- **Letter Spacing**: Generous spacing throughout for modern tech aesthetic

### Layout
- **Max Width**: 1500px container
- **Padding**: 40px horizontal on desktop, 20px on mobile
- **Grid**: 3-column feature grid (collapses to 1 column on mobile)

## File Structure
```
/orbit8
├── index.html          # Main landing page
├── assets/
│   ├── orbit-8-background.png    # Space background image
│   └── orbit-8-product-image.png # Product photo
└── design/             # Design assets/resources
```

## Key Features & Sections

### 1. Navigation
- Logo: "PHASEFORM AUDIO"
- Nav links: Features, Sounds, Specs
- Pre-order CTA button with blue border/hover effect

### 2. Hero Section
- Large "ORBIT-8" title with gradient effect (blue to white)
- Subtitle: "Groovebox • Sampler • Synth Engine"
- Tagline: "EXPLORE NEW ORBITS OF SOUND"
- Learn More CTA button
- Product image with drop shadow

### 3. Features Grid
Three feature cards:
1. Powerful Sampler - Dynamic Sampling & FX
2. Advanced Synth Engine - Dual Oscillators & Filters
3. Sequencing Freedom - 64-Step Pattern Sequencer

### 4. Audio Demo Section
- "HEAR THE SOUND OF ORBIT-8" heading
- Play button (circular with triangle icon)
- Currently non-functional (placeholder)

### 5. Footer
- "CREATE. PERFORM. EVOLVE." tagline
- Social media icons (Instagram, YouTube, Twitter) from CDN
- Copyright notice: © 2026 PHASEFORM AUDIO

## Responsive Breakpoints
- **1024px**: Reduced font sizes, single-column features
- **768px**: Smaller spacing, compressed nav
- **480px**: Further font reduction, wrapped navigation

## Development Notes

### Recent Changes
- Added color gradient to ORBIT-8 header text (PR #1)
- Product images added to assets folder
- Clean git status as of last commit

### Interaction Patterns
- Hover states on all interactive elements (blue glow/background)
- Smooth transitions (0.3s) on buttons and links
- Scale transform on play button hover (1.05)

### Image Requirements
- Background image should be high-res space/cosmic theme
- Product image should show the device clearly with transparency or clean background
- Social icons loaded from cdnjs (Simple Icons)

## Future Enhancements (Potential)
- Functional audio player
- Product specifications section
- Pre-order functionality
- Animation on scroll
- Interactive product visualization

## Design Philosophy
Modern, minimal, tech-forward aesthetic inspired by premium audio gear marketing. Clean typography, generous whitespace, and restrained color palette create focus on the product. Space theme reinforces the "orbit" concept.
