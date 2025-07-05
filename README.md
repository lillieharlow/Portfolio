# Assessment 1: Portfolio
## DEV1001 - Introduction to Web Development

## Summary

This assessment was both challenging and incredibly rewarding. I genuinely loved creating this portfolio, hyper-fixating and diving deep into all the possibilities that HTML and CSS bring to the table. It was equally exciting (and satisfying) when my code actually worked!

Challenges mostly stemmed from my limited experience, knowledge, and skill set. Having never built a website from scratch before, this project pushed me in the best way. It gave me countless opportunities to learn, troubleshoot, lose my mind a little bit, and build on the foundations we're learning in bootcamp.

I originally started working on my portfolio before the preprocessor class. After learning about SASS, I decided to switch my existing CSS into a SASS structure. I created a new branch in my repo and began converting my CSS into SASS, using partial files for better organisation. However, with my limited experience, I quickly became overwhelmed and realised my time would be better spent finishing a cohesive portfolio. In future projects, I’ll definitely start with SASS and partials from the beginning.

Being able to organise my code in a clean, easy-to-navigate format helped simplify the entire design process. From finalising design elements to fixing responsiveness and layout adjustments.

My CSS is organised with comments and grouped into the following sections:
1. Root Styles
2. Website Styles
3. Header & Nav Bar Styles
4. Footer Styles
5. Index/Home Page Styles
6. About Page Styles
7. Skills Page Styles
8. Projects Page & Contact Page Styles
9. Testimonial Page Styles
10. Tablet Screen Responsiveness (max-width: 1030px)
11. Mobile Screen Responsiveness (max-width: 480px)

<hr>

## Wireframe & Moodboard

This project was based on my wireframes submitted for Assessment 1 of ISK1001 – Industry Skills I. While the core structure remained the same, minor adjustments were made due to technical limitations, as this project is built with HTML and CSS (no JavaScript).  

Key changes included:
- Mobile Navigation Bar: The original hamburger menu was removed. Instead, font sizes were reduced and flex-wrap was used to ensure a responsive layout.
- Sliders: Sliders were removed, and all content is displayed directly on the page. For lengthy sections (e.g., Projects Page), anchor links are used to easily navigate between different sections of the page.
- Modal Image Sliders: Each project displays a single hero image instead of a modal slider.

<img src="icons-images/moodboard.png" alt="Moodboard for Portfolio" width="700px">

<hr>

## Website Attributes
- Background Image Animation
    - Consistent background animation across all pages.
    - Created from two original images designed in Procreate.
    - Animated via keyframes in CSS.  

- Font sizing and typography
    - Unified typography across the website for visual cohesion.
    - Font sizes are responsive, adapting to screen size with media queries.  

- Navigation Bar
    - Located in the header.
    - ``var(--opacity)`` to maintain visibility of the background image.
    - Styled using Flexbox for responsiveness across screen sizes.
    - Clear, user-friendly navigation layout.  

- Fixed Footer
    - Consistent across webpages.
    - Includes copyright info and links to social media platforms (LinkedIn, GitHub, Twitter).

<hr>

## Webpage Attributes
1. Index/Home Page
    - Animated name on hover:
        - ``text-shadow`` for a glowing effect
        - ``transform: scale`` for increase of size
        - ``var(--transform)`` used across website animations for smooth transitions. 

2. About Page
    - Responsive layout:
        - ``flex-direction: row`` on desktop
        - ``flex-direction: column-reverse`` on tablet and mobile
    - Portrait image:
        - Rotates 360° infinitely on hover using keyframes ``transform: rotate``. 

3. Skills Page
    - Skill icons:
        - Scale on hover using ``transform: scale``
        - Smooth transitions via ``cubic-bezier`` in ``var(--transform)``. 

4. Projects Page
    - Anchor navigation:
        - Smooth, easy-to-locate individual project sections
        - "Back to Top" link at the end of each project
        - On hover these links animate with ``transform: scale`` and ``box-shadow``. 
        
5. Contact Page
    - Interactive links to:
        - Email
        - LinkedIn
        - GitHub
        - Twitter
    - On hover these links animate with ``transform: scale`` and ``box-shadow``. 

6. Testimonial Page
    - Testimonial cards:
    - Wrap on smaller screens for responsiveness
    - Animate on hover with a ``box-shadow`` and ``translate``.

<hr>

## Reference List
Bruyerre, C. (n.d.) *Charles Bruyerre*, https://itssharl.ee/ee, accessed 16 June 2025.

Chung, W. (2025) *25 web developer portfolio examples to take inspiration from*, https://www.hostinger.com/tutorials/web-developer-portfolio, accessed 14 June 2025.

Dinculescu, M. (n.d.) *Monica Dinculescu*, https://meowni.ca/, accessed 16 June 2025.  

Galvan, M. (n.d.) *20 wireframe examples for web design*, https://www.flux-academy.com/blog/20-wireframe-examples-for-web-design, accessed 16 June 2025.  

McKelvey, K. (2024) *Top 23 web developer portfolio examples to inspire your own*, https://www.wearedevelopers.com/en/magazine/161/web-developer-portfolio-examples, accessed 14 June 2025.

Mozilla. (n.d.) *MDN Web Docs*, https://developer.mozilla.org/en-US/ accessed 29 June 2025.

Sen, T. (n.d.) *Tamal Sen*, https://tamalsen.dev/, accessed 16 June 2025.

W3Schools. (n.d.) *W3Schools Online Web Tutorials*, https://www.w3schools.com, accessed 29 June 2025.