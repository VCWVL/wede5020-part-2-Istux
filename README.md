The Green Basket Website

Name and Surname: Istiyak Patel
Student Number: ST10471810
Group: HAW1 Group 1

Project Title
The Green Basket: A Responsive Organic Grocery Website

Project Overview
The Green Basket website is a fully responsive platform for an organic grocery retail business based in South Africa. It is designed to promote organic groceries, raise awareness about sustainable living, and provide customers with a seamless browsing experience. The site allows users to explore products, learn about the company, and submit enquiries easily.
The website emphasizes eco-conscious design and responsive layouts to ensure accessibility across desktop, tablet, and mobile devices. Future upgrades will include JavaScript-based product filters, backend enquiry form integration, and a newsletter subscription option.

Website Goals and Objectives
Promote Organic Living: Educate customers about sustainable practices and the benefits of organic produce.
Increase Customer Engagement: Offer an easy way for customers to browse, learn, and enquire.
Provide Product Awareness: Highlight fresh fruits and vegetables through visual grids.
Establish Brand Presence: Present company values, mission, and eco-friendly practices.
Enable Scalability: Build a structure that can easily incorporate future enhancements such as product filtering, newsletter signups, and full e-commerce integration.

Key Features and Functionality

Hero Image
Appears at the top of every page.
Represents freshness and nature (e.g., meadow/grass image).
Purpose: creates immediate brand recognition and sets the theme of an eco-friendly grocery store.

Navigation Menu
Present on all pages.
Links: Home, About, Products, Team, Contact.
Purpose: allows customers to move between sections quickly without scrolling endlessly.

Home Page (index.html)
Contains a welcome paragraph introducing The Green Basket.
Purpose: first impression for customers — explains what the store is about and invites them to explore further.

About Page (about.html)
Explains the mission and vision of The Green Basket.
Includes a blockquote to highlight a customer review.
Purpose: builds trust by showing transparency and customer satisfaction.

Products Page (products.html)
Contains a table with product names, prices, and images.
Purpose: informs customers of what is available before they visit.
Customers browsing online can compare options easily.

Team Page (team.html)
Displays a group/team photo.
Purpose: puts faces to the business, creating a personal connection with customers and showing who is behind the store.

Contact Page (contact.html)
Contains a contact form with fields for name, email, phone number, and message.
Purpose: allows potential customers to ask questions about products, place special orders, or give feedback.
The form is directed towards The Green Basket store staff (not random users) so they can respond directly to customers.
Includes a Google Maps iframe showing the store’s location.
Purpose: helps customers physically locate the store.


Timeline and Milestones

Phase 1: Research and Planning (Week 1)
Identify goals, target audience, and competitors.
Gather content and images.
Define sitemap.
Milestone: Approved project plan.

Phase 2: Design and Wireframes (Week 2)
Create low-fidelity wireframes for all five pages.
Finalize branding (colors, fonts, logos).
Milestone: Mockups approved.

Phase 3: Development (Weeks 3–4)
Build website structure using HTML5.
Apply CSS for layout, typography, and color scheme.
Add images, banners, and responsive product grids.
Milestone: Functional static site created.

Phase 4: Testing and Debugging (Week 5)
Test across devices and browsers.
Fix layout, accessibility, and responsiveness issues.
Milestone: Fully functional website without errors.

Phase 5: Deployment (Week 6)
Deploy to GitHub Pages, Netlify, or cPanel hosting.
Configure domain and hosting.
Milestone: Live website accessible publicly.

Phase 6: Maintenance and Updates (Ongoing)
Regularly update product catalog.
Add seasonal promotions.
Monitor and maintain website stability.
Milestone: Up-to-date stable site.

Sitemap
<img width="1639" height="1282" alt="image" src="https://github.com/user-attachments/assets/f576766a-7bdd-4808-a245-b0899cb38bc3" />


Visuals of From Part 1.
<img width="216" height="334" alt="Screenshot 2025-08-27 175539" src="https://github.com/user-attachments/assets/8718db53-76dd-48a0-92ae-4f0164e1c151" />
<img width="1916" height="1014" alt="Screenshot 2025-08-27 175607" src="https://github.com/user-attachments/assets/889d0a25-e41f-4ad3-9eb7-123df1656781" />
<img width="1913" height="1019" alt="Screenshot 2025-08-27 175626" src="https://github.com/user-attachments/assets/343d0e6a-8e31-4de2-b280-4d55b5384f0c" />
<img width="1917" height="1017" alt="Screenshot 2025-08-27 175641" src="https://github.com/user-attachments/assets/587a7a75-431a-42f1-976d-80fb49015076" />
<img width="1916" height="1020" alt="Screenshot 2025-08-27 175700" src="https://github.com/user-attachments/assets/031296b2-ec6a-4d4e-b82e-5191d771a77e" />
<img width="1917" height="1019" alt="Screenshot 2025-08-27 175712" src="https://github.com/user-attachments/assets/b7989ae4-feac-4717-a6db-c0c8c7497e4c" />
<img width="1917" height="1015" alt="Screenshot 2025-08-27 180021" src="https://github.com/user-attachments/assets/df944c20-f6e9-46f9-93f9-cc359054800f" />
<img width="1912" height="975" alt="Screenshot 2025-08-27 180454" src="https://github.com/user-attachments/assets/5b998741-9948-4536-832c-ab4e15a32260" />
<img width="1906" height="963" alt="Screenshot 2025-08-27 180510" src="https://github.com/user-attachments/assets/686389fc-c367-4442-930f-f431cb2ec48d" />
<img width="1918" height="915" alt="Screenshot 2025-08-27 180528" src="https://github.com/user-attachments/assets/2460be86-190d-4c57-99a1-6cf7e7fb3bca" />
<img width="1912" height="907" alt="Screenshot 2025-08-27 180540" src="https://github.com/user-attachments/assets/181c1cf4-b7b0-45f0-9c97-21b1cf358291" />
<img width="1918" height="923" alt="Screenshot 2025-08-27 180608" src="https://github.com/user-attachments/assets/6b0e9d93-d251-4567-8bed-b587ebfe4e98" />


PART 2

CSS Styling for Desktop Solution

External Stylesheet
Created style.css and linked it to all HTML pages.
Ensured consistent naming conventions across all files.

Base Style
Defined site-wide styles: font family (Arial, sans-serif), font size, margins, and color scheme.
Implemented a CSS reset to maintain cross-browser consistency.

Typography Styles
Applied font-family, font-size, font-weight, line-height, and letter-spacing.
Used typography scales to maintain visual hierarchy.

Layout Structure
Employed CSS Flexbox and Grid for layouts.
Desktop version structured with multi-column grids for product display.
CSS properties used: display, grid-template-areas, justify-content, align-items.

Visual Styles
Styled using color, background-color, border, and box-shadow.
Added interactive elements with pseudo-classes (:hover, :focus, :active).
Responsive Design

Breakpoints
Media queries defined for desktop (≥1024px), tablet (768px–1023px), and mobile (≤767px).
Multi-column grids collapse into single-column layouts on smaller screens.

Relative Units
Used em and rem for scalable font sizes.
Applied % for responsive width and height adjustments.

Responsive Images
Implemented srcset and sizes attributes for images.
Used the picture element for optimized loading across devices.

Testing and Iteration
Browser developer tools used for multi-device testing.
Screenshots of desktop, tablet, and mobile versions included in documentation.
Iterative improvements applied to ensure accessibility and responsiveness.

Explanation of key features.

CSS Styling (Part 2 Enhancements)
Colours: Green and earthy tones for a fresh grocery store look.
Layout: Flexbox & Grid used for responsiveness.
Typography: Clean and readable fonts, with headings highlighted in green.
Hover effects: Buttons and navigation links change colour on hover.

Responsive design:
Desktop  Wide layout with grids.
Tablet  Navigation and content stack neatly.
Mobile  Single column, images resize automatically.
Purpose: ensures the site works across laptops, tablets, and phones.

User Journey Example
A customer visits the Home page to learn about the store.
Customer click on Products to see available organic groceries.
They go to the About page to learn about the store’s values.
They view the Team page to see who runs the business.
Finally, Customer go to Contact to ask about a delivery option and check the location on the map.



Sitemap
<img width="1639" height="1282" alt="image" src="https://github.com/user-attachments/assets/25762c1c-8899-43f4-9322-d06bf8b99214" />


Changelog

(Part 1)
- Project plan, goals, and structure created.
- Folder structure finalized.
- Color scheme and typography chosen.
- Timeline and milestones drafted.
- Used feedbacks from part 1 and added sitemaps for Part 1 and 2
- Included css and js folders.
- Explained what is happening in the code.
- Extended website goals.

(Part 2)
- Implemented external CSS stylesheet (style.css).
- Established base styling across all pages.
- Applied typography, grid layouts, and Flexbox.
- Added visual styles (colors, borders, hover effects).
- Introduced responsive breakpoints for desktop, tablet, and mobile.
- Optimized images using srcset and responsive techniques.
- Conducted device testing and debugging.
- Used feedbacks from part 1 and added sitemaps for Part 1 and 2.
- Removed all the inline css from all the html pages and moved it to styles.css page.
- Updated fonts and css styling to meet typography requirements.
- Updated readme.md as per feedbacks from part 1.
- Updated file and folder structure.
- Multiple commits with descriptive comments.
- Added website goals and objectives, change log and all the resources used.

References:

W3C (2023). HTML & CSS Standards. Available at: https://www.w3.org/ (Accessed: 27 August 2025).

MDN Web Docs (2024). HTML: HyperText Markup Language. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML (Accessed: 27 August 2025).

MDN Web Docs (2024). CSS: Cascading Style Sheets. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 27 August 2025).

Mozilla Developer Network (MDN). 2023. HTML: HyperText Markup Language. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML
 [Accessed 20 September 2025].
 
Mozilla Developer Network (MDN). 2023. CSS: Cascading Style Sheets. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS
 [Accessed 20 September 2025].
 
W3Schools. 2024. Responsive Web Design Tutorial. Available at: https://www.w3schools.com/css/css_rwd_intro.asp
 [Accessed 20 September 2025].

Netlify Docs. 2024. Getting Started with Deployment. Available at: https://docs.netlify.com
 [Accessed 21 September 2025].

The Independent Institute of Education (IIE). 2025. Module Guide: Web Development Project. Johannesburg: IIE.

