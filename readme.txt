--Readme document for *Y Nhi Tran*, *tranyn1@uci.edu*--

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

- Semantic HTML structure including <header>, <nav>, <main>, <section>, and <footer>.
- Multi-page navigation (Home, Projects, Experience, Contact).
- Portfolio content featuring personal biography, professional experience, and academic projects.
- Use of accessible links, images with alt text, and structured lists.

(b) CSS features

- CSS variables: Implemented a central color palette (Navy adn Cyan) for global consistency.
- Flexbox & grid: used for alignment, specifically for the "Sticky Footer" and the Contact page's split layout.
- Custom typography: integration of Montserrat fonts via Google Fonts.
- UI Refinements: custom styling for form inputs, including ':focus' states, border-radius, and stylized placeholders.

(c) Advanced features

- Responsive timeline: a complex CSS timeline that transition from a zig-zag desktop view to a single-column left-aligned layout on mobile.
- Interactive contact form: a fully styled form with client-side validation and high-contrast accessibility focus.
- Google maps integration: a responsive embedded map of the UC Irvine campus with custom CSS dimensions.

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

I have assessed every potential issue that the AChecker tool identified. For manual verification, several of these are automatic questions. My explanation for the warnings that were left in the final code is given below:

- Non-text content (Success Criteria 1.1.1):
	Rationale: The checker identifies images such as my-profile.jpg and uci-logo.svg to verify they are not solely decorative. I have confirmed that all images include descriptive alt text (e.g., "UCI Logo"). These images convey significant context pertaining to my identity and education, and are therefore not considered decorative elements. A "long description" (Check 8) was deemed unnecessary, as the existing alt text and surrounding content offer sufficient information.

- Link purpose & meaning (Success Criteria 2.4.4):
	Rationale: Hyperlinks, including "Home," "Projects," and "CS @ UCI," were flagged as potentially lacking clear meaning. However, within the context of a portfolio navigation menu, these terms are standard, unambiguous, and effectively communicate their destinations to all users, including those utilizing screen readers. Social icons also include explicit ‘aria-label’ attributes (LinkedIn, GitHub) to ensure clarity.

- Heading hierarchy (Success Criteria 2.4.6):
	Rationale: The tool flags <h2> and <h3> tags to ensure they aren't used just for font sizing. I have manually verified that my headings follow a logical document outline (e.g., <h2> for "Academic Foundation" and <h3> for the specific University name), which aids navigation for assistive technologies.

- Bypass blocks & site map (Success Criteria 2.4.1 & 2.4.5):
	Rationale: For my small-scale personal portfolio, which consists of only 4 pages, a "Skip to Content" link and a dedicated "Site Map" were omitted. The navigation is concise, and keyboard users can reach the main content within a few "Tab" presses.

- Script-related aarnings (Checks 89, 87, 86):
	Rationale: These warnings refer to the standard Bootstrap 5.3 library. I have verified that the script does not cause screen flickering and that the navigation remains keyboard-accessible. These are generic warnings triggered by any external JavaScript.

- Adaptable & language (Success Criteria 1.3.1 & 3.1.2):
	Rationale: Warnings regarding ‘dir’ attributes and Unicode marks were ignored as the site content is entirely in English (declared in <html lang=”en”>) and does not contain right-to-left text or complex multilingual phrases that would require such markers.

4. How long, in hours, did it take you to complete this assignment?

Approximately 15 - 20 hours.

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

- W3C Validation Service: https://validator.w3.org/
- CSS Validation Service: https://jigsaw.w3.org/css-validator
- Bootstrap 5 Documentation: for grid and navbar components.
- Generative AI (Gemini): used as a thought partner to debug CSS "margin collapse" issues and improve the timeline's and footer's responsiveness.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

Gemini (AI Assistant): Discussed CSS positioning for the mobile timeline, resolving margin collapse between the <main> content in <body> and <footer>, and improving form accessibility.

7. Is there anything special we need to know in order to run your code?

No special setup is required.