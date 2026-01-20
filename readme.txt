--Readme document for Vibha Yarlagadda, vsyarlag@uci.edu--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else's code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- */1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- Multiple images with descriptive alt attributes (profile photo on landing page, decorative images on about page)
- Appropriate headings (h1-h4) and paragraph text throughout all pages
- Links to external pages (LinkedIn, GitHub, Twitter links on index page, W3C validator links in footer)
- Multiple pages with navigation (6 total pages: index, about, experience, projects, skills, contact)
- Semantic HTML tags (nav, main, section, article, aside, footer used throughout)
- Custom icons from Google Material Icons (used for navigation, skills, contact info, and decorative elements)

(b) CSS features
- Extensive padding and margins to enhance readability and visual spacing (hero sections, cards, content sections all have carefully tuned spacing)
- Comprehensive color modifications using a cohesive dark maroon (#722F37) and olive green (#6B8E23) color palette throughout
- Bootstrap CSS helpers (Bootstrap grid system, navbar component, card components, form components, responsive utilities)
- Custom fonts from Google Fonts (Space Grotesk for body text, Playfair Display for headings) with appropriate fallbacks (Helvetica Neue, Arial, Georgia, serif)

(c) Advanced features
- Contact form on contact.html page leveraging HTML forms with required fields, email validation, and proper form labels
- Nested CSS selectors used extensively throughout styles.css (e.g., .contact-form .contact-form-element .form-control:focus, main .container .row .col-lg-6 .project-card)
- Complex page layout with navigation bar, sidebar (on about page), and multi-column layouts
- Responsive design implementation using Bootstrap's grid system and custom media queries for mobile, tablet, and desktop views

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

All HTML pages include proper semantic structure, alt text for images, proper heading hierarchy, form labels with for attributes, and ARIA labels where appropriate. All links have descriptive text. The color contrast ratios meet WCAG guidelines (dark maroon text on light backgrounds, light text on dark maroon backgrounds). If any warnings appear about decorative elements (like the sun/moon icons), these are purely decorative and do not convey essential information, so they can be safely ignored. Form fields are properly labeled and have required attributes for screen readers.

4. How long, in hours, did it take you to complete this assignment?

[To be filled in by student]

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

- Bootstrap 5 documentation: https://getbootstrap.com/docs/5.3/
- Google Fonts: https://fonts.google.com/
- Google Material Icons: https://fonts.google.com/icons
- W3C HTML Validator: https://validator.w3.org/
- W3C CSS Validator: https://jigsaw.w3.org/css-validator/
- Reference design inspiration: https://urvidhomne.github.io/index.html

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

[To be filled in by student]

7. Is there anything special we need to know in order to run your code?

No special setup required. Simply open index.html in a web browser. All external resources (Bootstrap, Google Fonts, Material Icons) are loaded via CDN, so an internet connection is required for full functionality and styling. The portfolio is fully functional as static HTML/CSS files.

File Structure:
- index.html (landing page)
- about.html (about page with education and background)
- experience.html (professional experience timeline)
- projects.html (portfolio projects)
- skills.html (technical skills organized by category)
- contact.html (contact information and form)
- styles.css (main stylesheet with all custom styling)
- readme.txt (this file)

All pages include navigation between each other and are fully responsive. The design uses a dark maroon and olive green color palette with mid-century modern inspired styling, including subtle sun and moon decorative elements.