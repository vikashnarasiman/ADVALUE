# AdValue Advertising Website Design Guidelines

## Design Approach

**Reference-Based Approach**: Drawing from premium B2B tech companies (Stripe, Vercel, Linear) combined with ad-tech platforms, emphasizing bold typography, dark aesthetics, and professional credibility. The design must maintain strict brand consistency with the AdValue logo's visual identity: dark backgrounds (black/slate) with bold red/coral accents, creating a premium, tech-forward aesthetic.

## Core Design Principles

1. **Premium Dark Aesthetic**: Dark theme throughout reinforcing sophistication and modern ad-tech positioning
2. **Bold Visual Hierarchy**: Large, confident typography that commands attention
3. **Breathing Room**: Generous spacing between sections to convey premium positioning
4. **Strategic Accent Usage**: Red/coral accents used purposefully for CTAs and key highlights
5. **B2B Credibility**: Clean, professional layouts that build trust with building owners and brands

## Typography System

**Font Stack**: Inter (primary) or Poppins (alternative)

**Hierarchy**:
- Hero Headlines: 3xl to 5xl (font-bold, tracking-tight)
- Section Headlines: 2xl to 3xl (font-bold)
- Subheadings: xl to 2xl (font-semibold)
- Body Text: base to lg (font-normal, leading-relaxed)
- Small/Meta Text: sm (font-medium)

**Line Height**: Tight for headlines (leading-tight), relaxed for body (leading-relaxed)

## Layout & Spacing System

**Tailwind Spacing Units**: Consistent use of 4, 6, 8, 12, 16, 20, 24, 32

**Vertical Rhythm**:
- Section padding: py-20 to py-32 (desktop), py-12 to py-16 (mobile)
- Content spacing: space-y-8 to space-y-12
- Component margins: mb-8, mb-12, mb-16

**Container Strategy**:
- Full-width sections: w-full with max-w-7xl mx-auto px-6
- Content sections: max-w-6xl
- Text-focused areas: max-w-4xl

## Section Specifications

### Hero Section
- Height: 90vh minimum with natural content flow
- Large background image: High-rise buildings with digital displays visible (sharp, professional photography)
- Overlay: Dark gradient overlay for text readability
- Layout: Centered content with headline, subtext, and prominent CTA button
- CTA Button: "Partner With Us" with blurred background treatment (backdrop-blur-sm)
- Spacing: p-8 to p-12 around content

### About Us Section
- Two-column layout on desktop (grid-cols-1 lg:grid-cols-2, gap-12)
- Left: Mission statement and explanation text
- Right: Supporting image or statistics grid
- Typography: Large section headline with 2-3 paragraph blocks

### Services Showcase
- Four-column grid on desktop (grid-cols-1 md:grid-cols-2 lg:grid-cols-4)
- Service Cards: p-6 to p-8, rounded-lg, hover:transform hover:scale-105 transition
- Icon + Title + Description structure
- Each card elevated with subtle borders

### For Building Owners Section
- Two-column split (grid-cols-1 lg:grid-cols-2, gap-16)
- Left: Compelling headline, benefits list, revenue messaging
- Right: Partnership inquiry form (WhatsApp integration)
- Form styling: p-6 inputs with focus states, clear visual feedback

### Brands/Advertisers Section
- Benefits grid: 3 columns (grid-cols-1 md:grid-cols-3, gap-8)
- Feature cards with icons, bold statements, supporting text
- Stats/metrics display if available

### Contact Section
- Centered single-column form (max-w-2xl mx-auto)
- Form fields: name, email, message (textarea)
- Social media icon links below form
- Submit button: prominent with accent color

### Footer
- Three-column grid (grid-cols-1 md:grid-cols-3)
- Left: AdValue logo and tagline
- Center: Quick navigation links
- Right: Contact info and social links
- Bottom: Copyright bar with centered text

## Component Library

### Buttons
**Primary CTA**: 
- Size: px-8 py-4 (desktop), px-6 py-3 (mobile)
- Typography: font-semibold text-base to text-lg
- Rounding: rounded-lg
- Hover: transform scale-105, transition-all

**Secondary Button**:
- Outlined style with border-2
- Same padding as primary

### Cards
- Padding: p-6 to p-8
- Rounding: rounded-xl
- Transitions: hover:shadow-2xl transition-all duration-300
- Borders: border with subtle contrast

### Form Inputs
- Padding: px-4 py-3
- Rounding: rounded-lg
- Focus states: ring-2 with accent color
- Labels: text-sm font-medium mb-2

### Icons
- Library: Heroicons (outline style for consistency)
- Sizes: w-6 h-6 (standard), w-8 h-8 (feature highlights)
- Placement: Above text in cards, inline with navigation

## Images Strategy

**Hero Section**: 
- Large background image: Modern high-rise building exterior with visible digital displays/screens in lobby or elevator banks (professional photography, sharp, high-resolution)
- Treatment: Dark overlay (opacity-60) for text legibility

**About/Services Sections**:
- Supporting images: Professional photos of installed displays, urban settings, brand advertisements on screens
- Image ratio: 16:9 or 4:3 for consistency

**Optional**: Video background in hero (muted, subtle movement of urban scenes)

## Navigation

**Header**:
- Sticky position (sticky top-0 z-50)
- Height: h-20 to h-24
- Logo left, navigation center/right
- Backdrop blur: backdrop-blur-md for scroll elegance
- Links: text-base font-medium with hover:text-accent

## Responsive Behavior

**Breakpoints**:
- Mobile: base (stack all columns)
- Tablet: md (2-column grids)
- Desktop: lg and xl (full multi-column layouts)

**Mobile Adjustments**:
- Reduce hero height to 70vh
- Stack all grids to single column
- Reduce font sizes by one step
- Padding: py-12 instead of py-20

## Animations & Interactions

**Minimal, Professional Approach**:
- Fade-in on scroll: opacity and translateY transitions
- Card hover: subtle scale (scale-105) and shadow enhancement
- Button hover: slight scale and glow effect
- Page transitions: smooth, no jarring effects
- Load animations: fade-in for hero content only

**Performance**: Use CSS transforms (translate, scale) over position changes

## Accessibility

- Focus indicators: visible ring-2 on all interactive elements
- Contrast ratios: Maintain WCAG AA standards (light text on dark backgrounds)
- Form labels: Always visible, properly associated
- Alt text: Descriptive text for all images
- Keyboard navigation: Fully supported throughout

This design creates a premium, conversion-focused B2B website that positions AdValue Advertising as a sophisticated, modern player in the digital advertising space while maintaining strict brand consistency throughout.