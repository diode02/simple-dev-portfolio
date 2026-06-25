# Technical Decisions

## Static HTML And CSS

The portfolio is implemented as static `index.html` and `styles.css` files. This keeps the site easy to inspect, easy to run locally, and appropriate for the simple one-page scope.

## No JavaScript Dependency

No JavaScript is required for the requested behavior. Native anchor navigation handles section jumps, and CSS covers responsive layout, hover states, and focus states.

## Layout Approach

The page uses semantic landmarks and sections with responsive CSS Grid. Project cards are the only card-style repeated content, keeping the page compact and professional.

## Content Approach

Content uses the provided Alex Carter placeholder profile, suggested skills, and the three suggested sample projects. The copy avoids unsupported claims about employers, education, awards, or years of experience.
