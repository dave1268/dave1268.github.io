# Portfolio Build Plan: About, Projects & Contact Sections

## Overview
Build three core sections of Dave's portfolio based on Tony Batts' design aesthetic: About section with personality cards, Projects section with placeholder cards, and Contact section with form and social media icons.

## Implementation Steps

### 1. Fixed Navigation Header
- Add a `<nav>` element at the top of the page with black background
- Navigation links: About, Projects, Contact
- Use anchor links (#about, #projects, #contact) for smooth scrolling
- Keep the nav fixed at the top of the viewport

### 2. About Section
- Section ID: `#about`
- Create 4 personality/trait cards with generic content
- Each card contains:
  - **Title** (e.g., "Always Learning", "Problem Solver", etc.)
  - **Description** (2-3 sentence explanation)
- Layout: Grid or flexbox display of cards
- Styling: White cards with subtle shadow, matching Tony Batts' minimal aesthetic

### 3. Projects Section
- Section ID: `#projects`
- Create 4 placeholder project cards
- Each card contains:
  - **Project Title** (generic like "Project 1", "Project 2", etc.)
  - **Description** (2-3 sentences about what the project does)
  - **Links**: "View App" and "GitHub" (placeholder URLs to update later)
- Layout: Similar grid/flexbox layout as About section
- Styling: Consistent with About cards

### 4. Contact Section
- Section ID: `#contact`
- Include a contact form with:
  - **Name** (input field)
  - **Email** (input field)
  - **Message** (textarea)
  - **Submit button**
- Below the form, add social media icons/links:
  - **GitHub** (placeholder URL)
  - **LinkedIn** (placeholder URL)
  - **Email** (mailto: link)
- Styling: Form inputs styled to match card aesthetic

### 5. CSS Updates
- Fixed navigation bar positioning and styling
- Card layouts and spacing
- Form input styling (borders, padding, focus states)
- Smooth scroll behavior (`scroll-behavior: smooth`)
- Responsive design considerations
- Maintain the green color scheme from the original design (or adjust to match Tony Batts' aesthetic)

## Design Specifications
- **Color scheme**: Green theme (#f0fdf4 background, #166534 text) with white cards, or match Tony Batts' color scheme
- **Typography**: Sans-serif font (existing)
- **Spacing**: Consistent padding and margins between sections
- **Card shadow**: Subtle box-shadow for depth
- **Navigation style**: Fixed black header with white text

## Placeholder Content
- **About cards**: Generic personality traits (4 total)
- **Projects**: 4 placeholder projects with generic titles and descriptions
- **Social media URLs**: Placeholder URLs to be updated later with actual GitHub, LinkedIn, and email

## Future Enhancements (Not Included Now)
- Skills section
- Hero section above navigation
- Adventure/gallery section with images
- Backend contact form functionality
