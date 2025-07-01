# Assessment 1. Portfolio
## DEV1001 - Introduction to Web Development

## Summary

This assessment was both challenging and incredibly rewarding. I genuinely loved creating this portfolio, hyper-fixating and diving deep into all the possibilities that HTML and CSS bring to the table. It was equally exciting (and satisfying) when my code actually worked!

The challenge mostly stemmed from my limited experience, knowledge, and skill set. Having never built a website from scratch before, this project pushed me in the best way. It gave me countless opportunities to learn, troubleshoot, lose my mind a little bit, and build on the foundations we're learning in bootcamp.

I originally started working on my portfolio before the preprocessor class. After learning about SASS, I decided to switch my existing CSS into a SASS structure. I created a new branch in my repo and began converting my CSS into SASS, using partial files for better organisation. However, with my limited experience, I quickly became overwhelmed and realised my time would be better spent finishing a cohesive portfolio. I decided to set that plan aside for now. In future projects, I’ll definitely start with SASS and partials from the beginning.

Being able to organise my code in a clean, easy-to-navigate format helped simplify the entire design process. From finalising design elements to fixing responsiveness and layout adjustments.

My CSS is organised with comments and grouped into the following sections:
1. Root Styles
2. Website Styles
3. Page Styles
4. Media Queries (Tablet and Mobile Screen Responsiveness)

## Wireframe & Moodboard

I roughly followed my wireframes submission from Assessment 1, ISK1001 - Industry Skills I. Minor adjustments were made due to skill level, only utilising HTML and CSS (no JavaScript). Changes included:
- No hamburger menu on mobile. Instead opted to decrease font size and wrap via flexwrap.
- No sliders, all content was displayed on the page. If content was extensive (e.g. project page) then anchor links were created to jump to different sections of the page.
- No modal image slider on prjects page. Just displayed one hero image per project.

## Wesbite Attributes
- Background Image Annimation
    - Same across the website.
    - Created from two original images designed in procreate. Animated with keyframes.
- Font sizing and typography
    - Typography is the same across the website to create visual cohesion.
    - Font size adjusts to media screen size.
- Navigation Bar
    - Inside header
    - 0.5 opacity to not visually cut off background image
    - Flexbox CSS styling, adjusts evenly to all screen sizes
    - Easy to read and navigate across website
- Fixed Footer
    - Copyright info
    - Social meida links

## Webpage Attributes
1. Index/Home Page
    - Name animated with glowing effect and scale 1.5 on hover.
2. About Page
    - Container changes ``flex-direction`` depednign on screen size; ``flex-direction: row;`` for desktop; ``flex-direction: column-reverse;`` for tablet and mobile. 
3. Skills Page
4. Projects Page
5. Contact Page
6. Testimonial Page

    Header tag didnt use nav because used div to make a container for flex box to allow for screen responsiveness and keep everything aligned center until it is 600px. Then mobile menu activates and menu is in hamburger icon.

    50px for height of nav bar to look chunkier and give text space around top and bottom.

    Colour themes the yellow really stands out against the black. easy to read and not plain like white text. this was done by selecting only link elements in external css sheet.

    hamburger menu icon is widely known and accepted as a navigation icon. clean and simple design. allows for landing page to be simple and not lots of nav content when viewing on mobile. visual trigger to click and explore website content.

    Editied a menu icon from flaticon to allow me to match colour of desktop menu.
    
    
    and added links for every html page needed
    css - center and space evenly with black background - mobile frendly

- Footer
    - Copyright info
    - Social link icons

- Main content:

- Padding around main content same for each page.

- Extra padding on top of text to push down the page - same across website.

    1. Home
        - Animated name center of all screens. Change size on mobile view.
        - Background design covers whole page (exc header and footer)
    
    2. About
        - Circle image - radius 50%
        - Page title (left align)
        - Bio info (left align)
        - Font size smaller on mobile (max width)
        - Image smaller on mobile (max width) @media
        - Flexbox direction for "image id" "text id" column until desktop - row reverse.

    3. Skills
        - Icons in an icon folder. Table and contain it in a class to then adjust @media max width and chage px of icons to smaller.
        - Smaller on mobile screen
        - Table, can space evenly and contain on the page.
        - Text align left and responsive to screen size.

    4. Projects
        - Text title and content aligned left
        - image aligned right of text
        - links from list jump to projects on the page
        - add back to top button at bottom of the page
        - add links in text of projects to direct viewer to actual project if online
    5. Contact
        - text title and cotent align left
        - smaller on mobile

    6. Testimonials
