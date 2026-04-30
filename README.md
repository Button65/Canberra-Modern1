# Canberra Modern
Redesign of Website

## Canberra Modern - HTML5 & CSS3

### Files Included

- `index.html` - About page with hero section and info cards
- `explore.html` - Explore page with horizontal scrolling gallery
- `events.html` - Events page with event cards grid
- `get-involved.html` - Get Involved page with form and images
- `styles.css` - Universal stylesheet used by all pages
- `images/` - Directory for all image assets

### Features

✅ Fully responsive (Mobile, Tablet, Desktop)
✅ Modern design with gradients and layered shadows
✅ Fixed header with mobile hamburger menu
✅ Horizontal scrolling image gallery
✅ Working contact form
✅ Consistent styling across all pages
✅ No embedded CSS - all styles in external stylesheet

## Required Images

### Home Page
- `logo.png` - Header logo (173px × 139px)
- `hero-building.png` - HC Coombs Building main image
- `event1.png` - First event image
- `event2.png` - Second event image
- `explore-hero.png` - Explore section image
- `get-involved.png` - Get Involved section image

### Explore Page
- `gallery1.png` through `gallery8.png` - Eight building images for scrolling gallery
- `map.png` - Places to Visit map

### Events Page
- `event-image1.png` through `event-image4.png` - Four event images

### Get Involved Page
- `building1.png`, `building2.png`, `building3.png` - Three heritage building images

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS3 features: gradients, box-shadows, flexbox, grid
- HTML5 semantic elements

## Responsive Breakpoints

- **Mobile**: Default (up to 767px)
- **Tablet**: 768px and up
- **Desktop**: 1024px and up

## How to Use

1. Add all required images to the `images/` folder
2. Open any HTML file in a web browser
3. No build process or server required - works as static HTML

## Rationale

The development of my responsive website involved transforming a high-fidelity prototype into a functional product using HTML5 and CSS3. This required careful planning, organisation, and ongoing evaluation to ensure the final result reflected the original design while functioning effectively across multiple devices. By following a structured workflow, from site maps and low-fidelity wireframes to high-fidelity prototypes and final development in Visual Studio Code, I developed a clearer understanding of the full production pipeline and how each stage informs the next.

A key strength of my project was the organisation of files and code. I ensured that my file structure in Visual Studio Code aligned with the folder structure in Explorer, making it easy to locate assets such as images and stylesheets. All code was clearly commented, allowing me to quickly identify sections when making updates. Another success was regularly checking the website across different screen sizes to ensure responsiveness, functionality, and visual consistency. This included verifying links, checking alignment and spacing, and ensuring that images scaled correctly without losing clarity. When issues arose, I returned to the code to refine the layout.

In terms of implementation, I used several responsive design techniques. Media queries at 768px and 1024px allowed the layout to adapt for tablet and desktop devices (Graham, 2024). These breakpoints enabled changes such as transforming the navigation from a mobile hamburger menu to a full desktop layout. The hamburger-style menu was used on mobile because it creates a cleaner interface and saves screen space, improving usability on smaller devices (Caron, 2017).
CSS Grid was used for complex layouts such as card sections and image grids, allowing content to shift from single-column to multi-column structures (House, 2024). Flexbox was applied to simpler, one-dimensional layouts like navigation bars and footers, enabling efficient alignment and spacing (Coyier, 2024). Typography was also considered through the use of Roboto Flex and Inter to maintain readability and a modern aesthetic. However, the site relied on breakpoint-based typography rather than fully fluid scaling. Techniques such as clamp (), as discussed by Trent Walton (Walton, 2011; Walton, 2012), could have improved responsiveness between screen sizes.

My low-fidelity prototypes were important in guiding the layout and structure of the final website. Most core elements, such as navigation and content hierarchy, were successfully implemented. However, some adjustments were made during development. For example, a hero image and introductory text were added to the mobile homepage to improve clarity and engagement, as this was lacking in earlier designs.
I also used Figma Make to generate initial HTML and CSS code from my designs. This helped ensure correct structure and styling from the beginning. However, I followed best practice by keeping HTML and CSS in separate files to improve organisation and maintainability. Additionally, I used the AI chat function in Visual Studio Code to fix errors such as incorrect font sizes, broken links, and layout inconsistencies, which improved both efficiency and my understanding of the code.

Despite these strengths, there were areas for improvement. One limitation was the reliance on breakpoint-based responsiveness rather than a fully fluid approach. While this method is easier to maintain, incorporating more fluid techniques could have enhanced adaptability. I could have also improved image selection and quality to strengthen the visual impact of the site. The places to visit on the explore page should have been created with table instead of using and image. I would have liked the mobile version table to collapse into 2 columns.
Another area for improvement was accessibility. While the site is functional and visually clear, I did not fully implement accessibility best practices such as detailed alt text, strong colour contrast, or testing with screen readers. Improving accessibility would make the website more inclusive and aligned with modern standards. Additionally, I did not extensively test the website across multiple browsers such as Google Chrome, Safari, and Mozilla Firefox, which may result in minor inconsistencies.

There were also several challenges throughout the project. Managing assets required resizing large image files exported from Figma to ensure optimal performance. Testing on mobile devices was another challenge, particularly due to limitations with iOS file handling, which required me to use an alternative device. Additionally, maintaining consistency between the design prototype and the final coded product proved difficult, as some spacing and layout details did not translate perfectly from Figma into code.

Overall, this project strengthened my understanding of responsive web development and highlighted the importance of planning, testing, and adaptability in creating effective digital solutions. 

## References

Canberra Modern. (2017). Canberra Modern. Canberra Modern. https://canberramodern.com/

caron. (n.d.). Caron, A. (2017). Responsive, Pure CSS Off-Canvas Hamburger Menu. [Review of Caron, A. (2017). Responsive, Pure CSS Off-Canvas Hamburger Menu.]. 

coyier. (n.d.). CSS Flexbox Layout Guide. [Review of CSS Flexbox Layout Guide.].

graham. (2024). Media Queries for Standard Devices. [Review of Media Queries for Standard Devices.].

house. (2024). CSS Grid Layout Guide. [Review of CSS Grid Layout Guide.]. ‌

walton. (n.d.). Fit to Scale. [Review of Fit to Scale.].

walton. (n.d.). fluid type [Review of fluid type].
