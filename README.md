
# Butter & Bloom 
# Project Summary

![Butter & Bloom Mockup on all devices](/readme-assets/all-devices-home-page.png)
A multi‑device preview of the Butter & Bloom homepage showcasing its fully responsive design.



Butter & Bloom is a fully responsive, multi‑page bakery website designed to showcase artisanal baked goods through elegant branding, high‑quality imagery, and intuitive user experience. Built using HTML, CSS, and Bootstrap, the site guides visitors through browsing products, exploring curated gallery collections, and submitting custom order enquiries.

The project combines UX research, wireframing, visual design, and front‑end development to create a professional, trustworthy digital presence for a boutique bakery. Every page is crafted with a mobile‑first approach, supported by Swiper.js carousels, structured content hierarchy, and accessible design principles.

Extensive testing — including manual functional checks, responsive device testing, Lighthouse audits, and W3C validation — ensures strong performance, clean code, and a smooth user experience across browsers and screen sizes. The site is deployed via GitHub Pages for easy access, assessment, and portfolio presentation.

---

# README Navigation
Use the links below to jump to any section of this documentation:

* [Project Summary](#project-summary)

* [Website Screenshots](#website-screenshots)

* [1) UX](#1-ux)
    * [1.1 Strategy & Goals](#11-strategy--goals)
    * [1.2 Research & Requirements](#12-research--requirements)
        * [User Stories](#user-stories)
    * [1.3 MVP Definition](#13-mvp-definition)
    * [1.4 Information Architecture](#14-information-architecture)
    * [1.5 Feedback Design](#15-interaction-design)
    * [1.6 Visual Design](#16-visual-design)

* [2) Features](#2-features)
    * [2.1 Existing Features](#21-existing-features)
    * [2.2 Features Left to Implement](#21-features-left-to-implement)

* [3) Technologies Used](#3-technologies-used)
    * [3.1 Core Web Technologies](#31-core-web-technologies)
    * [3.2 Libraries & External Resources](#32-libraries--external-resources)
    * [3.3 Design & Prototyping Tools ](#33-design--prototyping-tools)
    * [3.4 Branding & Asset Creation Tools](#34-branding--asset-creation-tools)
    * [3.5 Image Preparation & Optimisation](#35-image-preparation--optimisation)
    * [3.6 Accessibility Tools](#36-accessibility-tools)
    * [3.7 Testing & Debugging Tools](#37-testing--debugging-tools)
    * [3.8 Deployment](#38-deployment)
    * [3.9 Project Management & Version Control](#39-project-management--version-control)

* [4) Testing ](#4-testing)
    * [4.1 Manual Testing](#41-manual-testing)
    * [4.2 User Story Acceptance Testing](#42-user-story-acceptance-testing)
    * [4.3 Validators](#43-validators)

* [5) Deployment](#5-deployment)
    * [5.1 How to Run This Project Locally](#51-how-to-run-this-project-locall)
    * [5.2 Deployment with GitHub Pages](#52-deployment-with-github-pages)

* [6) Credits](#6-credits)
    * [6.1 Contents](#61-contents) 
    * [6.2 Media](#62-media)
    * [6.3 Code](#63-code)
    * [6.4 Acknowledgements](#64-acknowledgements) 

---

# Website Screenshots

Below are full‑page screenshots demonstrating Butter & Bloom’s responsive layout across mobile, tablet, and desktop breakpoints.

## Mobile

<details>
<summary>Home Page</summary>

![Full Screen Size Home Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_index.html_mobile.jpg)

</details>


<details>
<summary>Menu Page</summary>

![Full Screen Size Menu Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_menu.html_mobile.jpg)

</details>

<details>
<summary>Gallery Page</summary>

![Full Screen Size Gallery Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_gallery.html_mobile.jpg)

</details>

<details>
<summary>Order Page</summary>


![Full Screen Size Order  Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_order.html_mobile.jpg)

</details>

---

## Tablet

<details>
<summary>Home Page</summary>

![Full Screen Size Home Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_index.html_tablet.jpg)

</details>


<details>
<summary>Menu Page</summary>

![Full Screen Size Menu Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_menu.html_tablet.jpg)

</details>

<details>
<summary>Gallery Page</summary>

![Full Screen Size Gallery Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_gallery.html_tablet.jpg)

</details>

<details>
<summary>Order Page</summary>

![Full Screen Size Order  Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_order.html_tablet.jpg)

</details>

---

## Desktop

<details>
<summary>Home Page</summary>

![Full Screen Size Home Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_index.html_laptop.jpg)

</details>


<details>
<summary>Menu Page</summary>

![Full Screen Size Menu Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_menu.html_laptop.jpg)

</details>

<details>
<summary>Gallery Page</summary>

![Full Screen Size Gallery Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_gallery.html_laptop.jpg)

</details>

<details>
<summary>Order Page</summary>


![Full Screen Size Order  Page Screenshot](/readme-assets/destinygeorge.github.io_butter-and-bloom_order.html_laptop.jpg)

</details>

---

# 1) UX

## 1.1 Strategy & Goals

### Project Goals

Butter & Bloom aims to provide a visually appealing, trustworthy, and easy‑to‑navigate bakery website that: 

*   Clearly showcases the range and quality of products 
    
*   Communicates key information such as hours, location, and allergens 
    
*   Builds trust through brand storytelling, imagery, and social proof 
    
*   **Encourages users to submit an order enquiry through clear and accessible calls-to-action.** 
    

The **primary purpose** of the website, and the destination most CTAs point to, is to guide users toward submitting a **custom order or general order enquiry**, so the bakery can begin a conversation, confirm details, and convert interest into real orders.

### Business Goals

**Site Owner’s Primary Goal (Business):** 

*   To showcase baked goods and encourage customers to contact the bakery for custom orders and visits. 
    

**Site Owner Goals (Bakery Owner)** 

What the bakery wants from the website: 
    
*   Showcase baked goods attractively 
    
*   Build brand trust and professionalism 
    
*   Encourage custom order inquiries 
    
*   Reduce back-and-forth by collecting clear order details 
    
*   Attract new customers 
    
*   Provide essential info (hours, location) 
    
*   Promote specialties or signature items

### User Goals

**External User’s Primary Goal (Customer):** 

*   To easily browse the bakery’s products and submit a custom order or inquiry for baked goods. 
    

**External User Goals (Visitors / Customers)** 

What a user wants when they visit the bakery site: 
    
*   View available baked goods 
    
*   See prices or product descriptions 
    
*   Decide if the bakery fits their taste/style 
    
*   Request a custom order (cake, pastries) 
    
*   Find bakery location and opening hours 
    
*   Contact the bakery easily 
    
*   Get inspired by visuals of baked goods

### Competitor Analysis


## 1.2 Research & Requirements

### User Need Analysis

**User Need Classification** 

_(What users say they need vs. what they actually need vs. what they don’t realize they need)_ 


**What Users Say They Need** 

Explicit, conscious requests users expect from a bakery website. 

*   Product / menu page with categories 
    
*   Business hours 
    
*   Contact information 
    
*   \*\*Image gallery of baked goods 
    
*   Custom order request form 
    
*   Allergen information 
    


**What Users Actually Need** 

Requirements necessary for usability, even if not verbalized. 

*   Clear navigation structure 
    
*   Mobile-first responsive layout 
    
*   Logical content hierarchy 
    
*   Readable typography and spacing 
    
*   Simple, short forms 
    
*   Clear calls-to-action (Order, Contact, Subscribe) 
    


**What Users Didn’t Know They Needed** 
Unexpected features that improve trust and engagement. 

*   Seasonal highlights section 
    
*   Email subscription with discount incentive 
    
*   Upsell add-ons (candles, toppers) 
    
*   Featured items on home page 
    
*   Trust-building “About Us” section


### Prioritisation Table

**Tradeoffs** Bakery Website – Strategy Plane Decision Table

| **#** | **Opportunity / Problem** | **Feature / Content Decision** | **Importance** | **Feasibility** |
| --- | --- | --- | --- | --- |
| 1 | Users need to understand what the bakery offers immediately | Home page with bakery intro and featured items | 5 | 5 |
| 2 | Users want to browse available products easily | Menu/Product page with categorized items (cakes, pastries, bread) | 5 | 5 |
| 3 | Customers want to see product quality before ordering | Image gallery of baked goods | 5 | 5 |
| 4 | Customers want to request custom cakes/orders | Custom order request form | 5 | 4 |
| 5 | Users need to know when the bakery is open | Business hours displayed on home page | 4 | 5 |
| 6 | Customers need to know how to contact the bakery | Contact section with phone, email, location | 4 | 5 |
| 7 | Users may want to leave feedback or comments | Customer comments/testimonial form (non‑functional) | 3 | 4 |
| 8 | Users want easy navigation between sections | Navigation bar with anchor links or separate pages | 5 | 5 |
| 9 | Users want reassurance the bakery is professional and trustworthy | “About Us” short section | 3 | 5 |
| 10 | Users may want to quickly book for events | Simple booking inquiry form | 4 | 3 |
| 11 | Users want discounts and updates without creating an account | Email subscription signup with discount incentive | 4 | 4 |

Total Importance: 47 

Total Feasibility: 50 


**MoSCoW Prioritisation Outcome**

Following the importance and feasibility analysis, features were categorised using the MoSCoW prioritisation method to determine which features should be included within the MVP.

| **Feature** | **Priority** |
| --- | --- |
| Homepage intro & navigation | Must‑Have |
| Product categories | Must‑Have |
| Product images | Must‑Have |
| Allergen information | Must‑Have |
| Custom order form | Must‑Have |
| Opening hours & contact | Must‑Have |
| Seasonal items | Should‑Have |
| Email signup | Should‑Have |
| Testimonials | Could‑Have |
| Add‑ons | Could‑Have |
| Mobile‑friendly design | Must‑Have |



### User Stories

---

**1. User-Friendly Navigation and Homepage Introduction**

**User Story**  

As a First-Time Visitor, I want clear navigation and an introductory homepage, so I can quickly understand what the bakery offers and move around the site easily.

**Acceptance Criteria**

- The homepage clearly introduces the bakery and its offerings  
- Featured items are visible without excessive scrolling  
- Navigation is intuitive and accessible from all pages  
- Layout is responsive across screen sizes  

**Tasks**

- Create homepage layout  
- Add bakery introduction text  
- Add featured items section  
- Implement navigation bar  

---

**2. Categorised Menu Page**

 **User Story**  

As a Casual Customer, I want to browse bakery products by category, so I can easily find items I’m interested in.

**Acceptance Criteria**

- Products are grouped into clear categories  
- Each product displays a name and short description  
- The menu page is responsive and usable on mobile devices  

**Tasks**

- Create menu page or section  
- Create cards for each product category  
- Style product cards using responsive Bootstrap breakpoints  

---

**3. Product Image Gallery**

**User Story**  

As a First-Time Customer, I want to see high-quality images of baked goods, so I can assess their quality before making an enquiry.

**Acceptance Criteria**

- Images are clear, high quality, and consistently styled  
- Images load correctly on mobile and desktop  
- The gallery layout is easy to navigate  

**Tasks**

- Create image gallery layout  
- Add image assets  
- Optimise image sizing using CSS  

---

**4. Allergen Information Section**


 **User Story**  

As a Customer with dietary requirements, I want to view clear allergen information, so I understand how allergens are handled before placing an enquiry.


**Acceptance Criteria**

- A dedicated allergen information section is displayed at the bottom of the menu page  
- The content explains that products are custom-made and allergens should be specified in the enquiry form  
- The section is easy to read and responsive  


**Tasks**

- Write allergen information content  
- Add allergen section to menu page  
- Style section for clarity and readability  

---

**5. Custom Order Enquiry Form**

**User Story**  

As a Customer planning an event or special order, I want to submit a custom order enquiry, so I can discuss options, availability, and dietary requirements.

**Acceptance Criteria**

- The enquiry form is easy to find  
- The form includes name, contact method, and request details  
- Users can state allergen or dietary concerns in the message field  
- All required fields must be completed before submission  

**Tasks**

- Design enquiry form layout  
- Add input fields and labels  
- Add helper text explaining enquiry purpose  

---

**6. Opening Hours and Contact Information**

**User Story**  

As a Returning Customer, I want to quickly find opening hours and contact details, so I can plan my visit efficiently.

**Acceptance Criteria**

- Opening hours are clearly displayed  
- Contact information is easy to find  
- Information is accessible from the homepage  

**Tasks**

- Add opening hours section  
- Add contact details section  
- Style content for readability  

---

**7. Seasonal Highlights Section**

**User Story**  

As a Regular Customer, I want to see seasonal or limited-time items, so I don’t miss special offerings.

**Acceptance Criteria**

- Seasonal items are visually distinct from the main menu  
- The section is easy to update  
- The content does not overwhelm the core menu  

**Tasks**

- Create seasonal highlights section  
- Add example seasonal items  
- Style section to stand out subtly  

---

**8. Newsletter and Offers Sign-Up Form**

**User Story**  

As a Price-Conscious Customer, I want to sign up for updates and offers, so I can receive discounts and promotions.

**Acceptance Criteria**

- The sign-up form only requires an email address  
- The benefit of signing up is clearly stated  

**Tasks**

- Create newsletter sign-up form  
- Add promotional copy  

---

**9. Optional Add-Ons for Special Occasions**

**User Story**  

As a Customer ordering for a celebration, I want to view optional add-ons, so I can plan everything in one place.

**Acceptance Criteria**

- Add-ons are clearly presented as optional  
- Visual elements make add-ons easy to understand  
- No pricing calculations are required  

**Tasks**

- Create add-ons section  
- Add visual cards or checkboxes  
- Style for clarity  

---

**10. Responsive Design Across Devices**

**User Story**  

As a Mobile and Tablet User, I want the website to adapt to my screen size, so I can browse the bakery comfortably on any device.

**Acceptance Criteria**

- Layout adapts correctly to mobile, tablet, and desktop screen sizes  
- Text remains readable without zooming  
- Images scale appropriately without distortion  
- Navigation remains usable on smaller screens  

**Tasks**

- Implement mobile-first CSS  
- Add media queries for common breakpoints  
- Test layout across multiple screen sizes  

---

**11. Customer Testimonials Section**

**User Story**

As a Prospective Customer, I want to read testimonials from previous customers, so I can feel more confident about the quality of the bakery and its products.

**Acceptance Criteria**

- A dedicated testimonials section is included on the website  
- Testimonials are clearly readable and visually separated from other content  
- The layout is consistent with the site’s overall design  
- Testimonials are static and clearly presented  

**Tasks**

- Create a testimonials section layout  
- Add sample customer testimonials  
- Style the section for readability and visual consistency  

---


### Requirements

**Objective Requirements** 

What the user wants to accomplish. 

*   Browse bakery products 
    
*   Decide what to order 
    
*   Request a custom cake 
    
*   Check hours and location 
    
*   Ensure food safety (allergens) 
    
*   Get discounts or updates 
    
*   Contact the bakery 
    

**Functional Requirements** 

What the user must be able to do. 

*   Navigate between Home, Menu, Gallery, and Order sections 
    
*   View categorized product listings 
    
*   View product images 
    
*   Submit a custom order request form 
    
*   Submit an order inquiry form 
    
*   Subscribe via email form 
    
*   Read allergen labels 
    
*   View seasonal offerings 
    
*   View upsell add-ons as selectable options 
    

Even if forms are non-functional, they still count because the interaction exists. 

**Non**‑**Functional Requirements** 

Constraints the site must operate within. 

*   Static HTML and CSS only (no backend) 
    
*   Mobile-first responsive design 
    
*   Fast load time 
    
*   Cross-browser compatibility 
    
*   Accessible color contrast and font sizes 
    
*   Forms do not store or submit real data 
    
*   Content is informational and demonstrative


## 1.3 MVP Definition

### 1\. Core Pages

*   **Home Page** — intro, featured items, business hours, CTA to order 
  
*   **Menu / Products Page** — categorised product listings 
    
*   **Gallery Page** — curated dessert imagery 
    
*   **Custom Orders Page** — order enquiry form (non‑functional but fully designed) 
    
*   (Contact details in Footer) 
    

**Home Page** 

*   Hero section 
    
*   Featured items 
    
*   Seasonal highlight 
    
*   Short About preview 
    
*   Opening times section 
    
*   CTA to Order page 
    
*   Footer contact details 
    
*   Footer quick links 
    

**Menu / Products Page** 

*   Categorised product listings 
    
*   Pricing guidance (starting prices, portion sizes) 
    
*   Allergen information 
    
*   CTA to Order page 
    

**Gallery Page** 

*   Curated dessert imagery 
    

**Order Page** 

*   Custom order enquiry form  
    

These four pages form the minimum structure needed for users to browse, trust, and enquire. 

### 2\. Essential User Interactions

*   Navigation bar linking all core pages 
    
*   Clear CTAs  
    
*   Simple, short custom order form 
    
*   Mobile‑first responsive layout 
    
*   High‑quality, colour‑cohesive imagery 
    
*   Allergen information 
    
*   Seasonal highlight section (lightweight, optional but recommended) 
    

### 3\. Essential Content

*   Brand introduction 
    
*   Featured items 
    
*   Business hours 
    
*   Contact details 
    
*   Product categories 
    
*   Gallery images 
    
*   Basic pricing guidance (starting prices) 
    

### What Is Not Included in the MVP 

These features are intentionally excluded until later sprints: 

*   Full About page 
    
*   Full Allergen page 
    
*   Seasonal Specials page 
    
*   Instagram embed 
    
*   Upsell add‑ons 
    
*   Subscription pop‑up 
    
*   Multi‑step custom order form 
    
*   Interactive flavour menus 
    
*   Map embed 
    
*   Testimonials section 
    
*   Advanced animations 
    

These are valuable enhancements but not required for the core user journey. 

### MVP Success Criteria

The MVP is considered successful if: 

*   Users can understand the bakery’s offerings within seconds 
    
*   Users can browse products without confusion 
    
*   Users can view high‑quality images 
    
*   Users can find essential information easily 
    
*   Users can reach the Custom Order Enquiry page through clear CTAs


## 1.4 Information Architecture

### Site Map

**Visual Site Map**

![Butter & Bloom Site Map](/readme-assets/butter-and-bloom-site-map.png)


### Navigation Model

This site uses a **primary global navigation model** with **supplementary contextual links**. 

**Primary navigation type** 

**Flat, global navigation (hub-and-spoke)** 

*   All 4 main pages are **peers**  
    
*   Every page is accessible from every other page via the navbar  
    
*   No hierarchy among the main pages  
    

This is sometimes described as: 

*   **Flat site structure**  
    
*   **Global persistent navigation**  
    
*   **Non-linear navigation**  
    

**Secondary navigation types present** 

*   **Contextual navigation**  
    
*   Buttons on Home → Orders  
    
*   Buttons on Menu → Orders 
    
*   In-line text link on Menu → Allergen Section 
    
*   Quick Links on Footer   
    

*   **Utility navigation**  
    
*   404 page  
    
*   Confirmation page  
    

These are _not_ part of the primary navigation model . 


### Page Architecture

**Possible Pages** 

Total Number of Pages 4 core pages: 

*   Home 
    
*   Menu / Products 
    
*   Gallery 
    
*   Custom Orders 

---

Optional (recommended later): 

*   About 
    
*   Allergen 
    
*   Seasonal Specials 
    

For MVP the main 4 pages are enough. 

---

Feature Distribution 

**Features Assigned to Each Page** 

**Home Page**
    

*   Hero section 
    
*   About Us (short version) 
    
*   Featured items 
    
*   Business hours 
    
*   Seasonal highlights 
    
*   Testimonials 
    
*   Subscription pop‑up  
    


**Menu / Products Page** 
    

*   Categorised product list (cakes, cupcakes, pastries, seasonal) 
    
*   Upsell add‑ons (candles, toppers, etc.) 
    
*   Allergen information 
    
*   Seasonal menu section 
    

**Gallery Page** 
    

*   Image gallery — curated, high‑quality photos 
    
*   Optional: Instagram embed for social proof 
    


**Orders Page**

*   Custom order form 
    
---

**Optional Pages (Add in Later Sprints)**

**Contact Page**
    

*   Contact details — phone, email, location 
    
*   Optional: map embed 
    
*   Optional: quick enquiry form 
    

**About Page**
    

*   Full brand story 
    
*   Values, mission, bakery background 
    

**Allergens Page**
    

*   Full allergen breakdown 
    
*   Cross‑contamination disclaimer 
    

**Seasonal Specials Page**
    

*   Seasonal menu 
    
*   Limited‑time offers


## 1.5 Interaction Design

### Feedback Design

**Hover & focus states** 

*   Button colour change on hover 
    

**Active navigation indicator** 

*   Underline or highlight the current page in the navbar 
    
*   Bootstrap’s .active class for nav links 
    

**Form validation feedback** 

Using **HTML5 built**‑**in validation** + Bootstrap styling: 

*   Required field warnings 
    
*   Invalid input borders (red) 
    
*   Valid input borders (green) 
    
*   Error messages like “Please enter a valid email” 
    

**Success confirmation page** 

*   A simple “Thank you, your form has been submitted” page 
    

**Error page** 

*   A friendly 404 or general error page 
    
*   Helps users recover when something goes wrong

## 1.6 Visual Design

### Design Choices

**Overall Brand Identity** 

Butter & Bloom was designed to combine the warmth of an artisan bakery with elegant floral aesthetics. The brand uses a custom colour palette based on the **60**‑**30**‑**10 principle**: 

*   **60% warm golden browns** — representing baked goods (_Butter_) 
    
*   **30% botanical greens** — representing plants and florals (_Bloom_) 
    
*   **10% cherry red accents** — inspired by berry fillings and floral details 
    

Low‑opacity background tints were used throughout the site to maintain softness while keeping imagery and content as the focal point. This supports strong **visual hierarchy** and readability. 

**Brand Assets**

Logo

![Butter & Bloom Logo Variations](/readme-assets/butter-and-bloom-logo-variations-2.png)

| **Original Palette** | **Final Palette** |
| --- | --- |
| ![Initial colour exploration during brand development](/readme-assets/butter-and-bloom-colour-palette.png) | ![Colours implemented in the Butter & Bloom website ](/readme-assets/butter-and-bloom-website-colours-2.png) |


**Typography** 

Typography reinforces the brand identity: 

*   **Playfair Display** provides an elegant, premium feel for headings and body text. 
    
*   **Great Vibes** is used for the brand name to evoke handcrafted quality and a boutique aesthetic. 
    

This pairing creates contrast while maintaining consistency across all pages. 

**Home Page** 

The homepage introduces the brand and guides users naturally through the content. A full‑screen hero image establishes the aesthetic immediately, while a semi‑transparent content container improves readability without obscuring the photography. 

Alternating background colours (white, botanical green, golden brown) create clear section separation and support **cognitive load reduction**. 

Swiper carousels were used for featured products, seasonal highlights, and testimonials to create an engaging browsing experience. Carousels adapt responsively: 

*   1 image on mobile 
    
*   2 on tablets 
    
*   3 on desktop 
    

This ensures images remain prominent while making effective use of larger screens. 

**Menu Page** 

The menu page presents a large amount of information in a clean, organised format. A mini navigation bar allows users to jump directly to any of the nine product categories, reducing scrolling and improving **information architecture**. 

Each category uses consistent Bootstrap cards containing imagery, descriptions, pricing, and a clear call‑to‑action button. Equal‑height cards and consistent button placement create a balanced layout. The responsive grid displays: 

*   1 card per row on mobile 
    
*   2 on tablets 
    
*   3 on desktop 
    

This maintains readability and visual consistency across devices. 

**Gallery Page** 

The gallery is divided into six themed categories rather than one large collection, making browsing more intuitive. Each category uses a responsive Swiper carousel to reduce page length while showcasing multiple images. 

The layout alternates between **title → carousel** and **carousel → title** to create visual variety and guide users down the page. Background colours alternate between botanical green, white, and golden brown overlays to reinforce the brand palette and create clear separation between sections. 

Carousels display: 

*   1 image on mobile/tablet 
    
*   2 images on desktop 
    

This ensures optimal use of screen space. 

**Order Page** 

The order page transforms a detailed enquiry form into a structured, approachable experience. Instead of one long form, fields are grouped into logical sections: 

*   customer details 
    
*   order type 
    
*   event details 
    
*   product details 
    
*   budget 
    
*   allergens 
    

This mirrors the natural ordering process and reduces cognitive load. On larger screens, related fields are placed side by side to reduce scrolling, while smaller screens use full‑width inputs for readability and ease of interaction. 

**Navigation and Footer** 

The navigation bar provides simple, consistent access to the site’s four main pages and collapses into a mobile‑friendly hamburger menu on smaller devices. 

The footer complements the navigation with quick links, contact information, and social media icons in a responsive three‑column layout. Together, these components reinforce the brand identity through typography, colour palette, and subtle hover effects, ensuring a cohesive user experience across the entire site.

### Wireframes

<a href="/readme-assets/Butter & Bloom Wireframes.pdf" target="_blank">Butter & Bloom Full Wireframe PDF</a>

Home Page Wireframe 

![Home Page Wireframe](/readme-assets/butter-and-bloom-home-page-wireframe.png)

Menu Page Wireframe

![Menu Page Wireframe](/readme-assets/butter-and-bloom-menu-page-wireframe.png)


Gallery Page Wireframe

![Gallery Page Wireframe](/readme-assets/butter-and-bloom-gallery-page-wireframe.png)

Order Page Wireframe

![Order Page Wireframe](/readme-assets/butter-and-bloom-order-page-wireframe.png)


# 2) Features

## 2.1 Existing Features

**Responsive Navigation** 

*   A responsive **Bootstrap navigation bar** appears on every page. 
    
*   The navigation collapses into a hamburger menu on smaller devices, ensuring easy browsing across mobile, tablet, and desktop. 
    

**Homepage** 

*   A full‑screen hero banner introduces the Butter & Bloom brand with a clear call‑to‑action. 
    
*   An About Us section provides visitors with an overview of the bakery. 
    
*   Featured Items and Seasonal Highlights use responsive **Swiper carousels** to showcase products without overcrowding the page. 
    
*   Opening times are clearly displayed to help customers plan their visit. 
    
*   A testimonials carousel provides social proof and builds trust. 
    
*   A newsletter sign‑up modal allows visitors to subscribe using only their email address. 
    

**Menu** 

*   Products are organised into nine clearly labelled categories for easy browsing. 
    
*   Each category uses consistent **Bootstrap cards** containing an image, description, options, pricing, and an enquiry button. 
    
*   A mini navigation bar enables users to jump directly to any product category. 
    
*   A dedicated allergen information section reminds customers to include dietary requirements when submitting an enquiry. 
    

**Gallery** 

*   Products are organised into themed categories for intuitive browsing. 
    
*   Each category uses a responsive Swiper carousel to showcase multiple images while keeping the page compact. 
    
*   Alternating layouts and background colours improve visual interest and clearly separate each gallery section. 
    

**Order Enquiry Form** 

*   A structured enquiry form allows customers to submit bespoke order requests. 
    
*   The form is divided into logical sections to reduce cognitive load. 
    
*   **HTML5 validation** and required fields ensure enquiries contain essential information. 
    
*   Customers can specify event details, design requirements, budgets, and allergen information. 
    

**Footer** 

*   A consistent footer appears on every page. 
    
*   It provides contact information, opening hours, social media links, and quick navigation links. 
    

**Responsive Design** 

*   The website follows a mobile‑first approach using **Bootstrap’s responsive grid**. 
    
*   Navigation, layouts, carousels, cards, and forms adapt seamlessly across mobile, tablet, and desktop devices. 
    

**Swiper Carousels** 

*   Interactive **Swiper carousels** are used across the Homepage (Featured Items, Seasonal Highlights, and Testimonials) and the Gallery sections. 
    
*   **Homepage carousels** display: 
    
    *   1 item on mobile 
        
    *   2 items on tablets 
        
    *   3 items on desktop 
    
*   **Gallery carousels** display: 
    
    *   1 image on mobile and tablet 
        
    *   2 images on desktop This is because, from tablet size upwards, the gallery titles shift beside the carousel, using the horizontal space where a second image would normally appear. 
        
*   Carousels reduce page length and present content in an engaging, interactive format.

## 2.2 Features Left to Implement

**User Interaction Enhancements** 

*   **Button press feedback** (pressed states, micro‑animations). 
    
*   **Image hover effects** (zoom‑in, soft shadow, overlay). 
    
*   **Toast notifications** for actions such as form submission or favourites. 
    
*   **Loading indicators** for carousels or form submission. 
    

**Form Improvements** 

*   **Real**‑**time form validation** with instant feedback. 
    
*   **Multi**‑**step enquiry form** with a progress indicator. 
    
*   **Interactive product modals** showing ingredients, allergens, and serving sizes. 
    

**Search & Filtering** 

*   **Live product search** to help users quickly locate items. 
    
*   **Category filtering** for faster browsing. 
    

**Accessibility Enhancements** 

*   **ARIA live regions** for screen‑reader announcements. 
    
*   **Improved keyboard navigation** and focus states.


# 3) Technologies used

**Technologies Used**

This project was built using a combination of front‑end technologies, design tools, libraries, and image‑optimisation workflows to create a fast, responsive, and visually cohesive bakery website. 


## 3.1 Core Web Technologies

* **HTML5** — used to structure all pages, semantic sections, and content hierarchy. 

* **CSS3** — used for custom styling, layout control, spacing, colours, typography, and responsive behaviour. 

* **Bootstrap 5** — used for the grid system, responsive containers, rows/columns, navbar structure, cards, and form layout. All components were custom‑styled to match the Butter & Bloom brand. 


## 3.2 Libraries & External Resources

**Swiper.js** 

Used to create the interactive sliders on the Home page and Testimonials section. Custom styling added includes: 

*   Soft transitions (ease-in-out) 
    
*   Custom pagination bullet colours 
    
*   Custom navigation arrow colours 
    
*   Square image crops using CSS (aspect-ratio: 1/1) 
    

Swiper provides smooth, mobile‑friendly carousel behaviour that fits the brand’s premium aesthetic. 

**Google Fonts** 

Imported two fonts: 

*   **Great Vibes** — used for logo and H1 headings 
    
*   **Playfair Display** — used for body text and section headings 
    

These fonts reinforce the handcrafted, botanical patisserie identity. 

**Font Awesome** 

Used for icons in the footer’s contact section: 

*   Phone icon 
    
*   Location icon 
    
*   Email icon 
    
*   Social media icons

## 3.3 Design & Prototyping Tools 

**Figma**

Used to design wireframes and plan the layout structure before development. The final wireframe document was exported as a PDF and linked in the README. 

## 3.4 Branding & Asset Creation Tools 

**Canva** 

Used to design the Butter & Bloom logo: 

*   Script lettering 
    
*   Serif subtext 
    
*   Floral cake illustration 
    
*   Gold colour palette 
    

Canva allowed precise control over typography and decorative elements to match the brand aesthetic. 

**AI Image Generation** 

Used Copilot and ChatGPT to generate: 

*   Hero images 
    
*   Featured dessert images 
    
*   Seasonal dessert concepts 
    
*   Botanical‑themed dessert compositions 
    

These images were then cropped, refined, and optimised to match the brand’s reduced‑saturation aesthetic. 

**favicon.io** 

Used to generate the site’s favicon: 

*   Based on the Butter & Bloom monogram 
    
*   Exported as a .ico file 
    
*   Ensured clarity at small sizes 
    

**Stock Image Sources** 

Most photography came from: 

*   Unsplash — majority of gallery and menu images 
    
*   Pixabay — additional dessert and botanical images 
    

All images were credited in the README.

## 3.5 Image Preparation & Optimisation 

**Manual Square Cropping** 

Every image was manually cropped to a perfect square using the laptop’s built‑in image editor. This ensured consistency across: 

*   Gallery 
    
*   Menu cards 
    
*   Swiper slides 
    

**Squoosh** 

Used to resize and compress all images after cropping. Optimisation included: 

*   MozJPEG / BrowserJPEG compression 
    
*   Reduced file sizes while maintaining clarity 
    
*   Faster load times across all devices 
    

**CSS Image Rules** 

Applied consistently: 

*   aspect-ratio: 1/1 
    
*   object-fit: cover 
    
*   object-position: center 
    

These ensure perfect framing and visual consistency.

## 3.6 Accessibility Tools 

* **Tailwind Alt Text Generator** — used to generate descriptive alt text for images based on prompts. 

*  **AltText.ai** — used to generate and refine alt text for gallery and menu images to improve accessibility. 

## 3.7 Testing & Debugging Tools

**HTML Validation** 

The website’s HTML was tested using the [**W3C HTML Validator**](https://validator.w3.org/) to ensure correct structure, semantic accuracy, and standards of compliance. 

**CSS Validation** 

All custom CSS was checked using the [**W3C CSS Validator**](https://jigsaw.w3.org/css-validator/) to confirm valid syntax and identify potential errors. 

**Lighthouse Testing (Chrome DevTools)** 

Lighthouse in Chrome DevTools was used to test: 

*   performance 
    
*   accessibility 
    
*   best practices 
    

Chrome DevTools was also used for layout debugging and responsive testing. Temporary grid‑visualisation CSS was applied during development to inspect container and column alignment.

## 3.8 Deployment

**GitHub Pages**

Used to deploy the website publicly. GitHub Pages hosts the project directly from the repository, allowing: 

* Automatic deployment from the main branch 

* Fast static hosting 

* Easy sharing for assessment and portfolio use 

This makes the project accessible online without needing external hosting services.

## 3.9 Project Management & Version Control

**Git** 

Used for version control throughout development. 

**GitHub**  

Used to host the repository, manage commits, and store all project files. 

**GitHub Projects** 

A dedicated GitHub Project board was created and linked directly to the repository to manage all user stories and development tasks. This board acted as a Kanban system with three workflow columns: 

*   **To Do** 
    
*   **In Progress** 
    
*   **Done** 
    

Each user story was added as a task card and moved between columns as development progressed. 

**MoSCoW Prioritisation Labels** were also used to ensured clear prioritisation and helped maintain focus on the MVP scope. 

**Task Tracking** 

*   Checked off subtasks as they were completed 
    
*   Used labels to indicate priority and status 
    
*   Ensured transparency and traceability throughout development 
    
*   Linked tasks directly to commits and pull requests where relevant

# 4) Testing

The Butter & Bloom website underwent extensive testing across functionality, responsiveness, accessibility, performance, and code quality. Testing was performed using **Chrome DevTools**, **physical devices** (iPhone, Android, tablet), **Lighthouse**, and **W3C HTML/CSS validators**. The goal was to ensure a smooth user experience, fast performance, and clean, standards‑compliant code.

## 4.1 Manual Testing 

### Functionality Testing

**Navigation**

| **[Test](ca://s?q=Explain_website_testing)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Navigation links | Click each navbar link | Correct page loads | Pass |
| Footer quick links | Click each footer link | Correct page loads | Pass |
| Active page indicator | Navigate between pages | Active link visually highlighted | Pass |


**Buttons & CTAs**

| **[Test](ca://s?q=Explain_call_to_action_in_UX)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Primary CTAs | Click “Order Now”, “Subscribe” | Correct page loads | Pass |
| Hover states | Hover over all buttons | Colour change + pointer cursor | Pass |

**Forms**

| **[Test](ca://s?q=Explain_HTML5_form_validation)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Required fields | Submit empty form | HTML5 validation prevents submission | Pass |
| Valid submission | Enter valid data | Redirect to confirmation page | Pass |

**Swiper Sliders**

| **[Test](ca://s?q=Explain_Swiper_carousel)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Slide navigation | Click next/prev arrows | Slides move smoothly | Pass |
| Pagination bullets | Click bullet indicators | Correct slide loads | Pass |
| Autoplay (if enabled) | Observe slider | Slides transition automatically | Pass |


**Image Loading**

| **[Test](ca://s?q=Explain_image_optimisation_in_web_design)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Gallery images | Scroll through gallery | All images load correctly | Pass |
| Menu images | View menu cards | Images display in correct aspect ratio | Pass |
| Hero image | Load home page | Hero image displays full‑width | Pass |


### Usability Testing

**Readability**

| **[Test](ca://s?q=Explain_readability_testing)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Text contrast | Check headings, body text, buttons | All text readable against backgrounds | Pass |
| Font sizes | Review across devices | Text remains legible | Pass |

**User Flow**

| **[Test](ca://s?q=Explain_user_flow_in_UX)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Primary user goal | Navigate Home → Menu → Order | Flow is intuitive and friction‑free | Pass |
| CTA placement | Scroll each page | CTAs appear at logical decision points | Pass |
| Form clarity | Complete order form | Fields are clear and grouped logically | Pass |

**Feedback & Interaction**

| **[Test](ca://s?q=Explain_interaction_design_feedback)** | **Procedure** | **Expected Result** | **Outcome** |
| --- | --- | --- | --- |
| Hover feedback | Hover over links/buttons | Colour change or underline appears | Pass |
| Focus states | Navigate using keyboard | Visible focus outline | Pass |
| Error feedback | Submit invalid form | Clear error messages | Pass |


### Responsiveness Testing

Breakpoints Tested
* 320px (small mobile)

* 375px (standard mobile)

* 768px (tablet)

* 992px (small laptop)

* 1200px+ (desktop)

---

**Responsive Design Showcase**

Below are mock‑ups demonstrating Butter & Bloom’s responsive layout across devices.

| Mobile | Tablet | Desktop |
|--------|---------|----------|
| ![Mobile mock‑up](/readme-assets/mockup-mobile-framed.jpg) | ![Tablet mock‑up](/readme-assets/mockup-tablet-framed.jpg) | ![Desktop mock‑up](/readme-assets/mockup-desktop-framed.jpg) |


---

**Layout Behaviour**

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Hero section | View on mobile | Hero container scales correctly | Pass |
| Gallery grid | Resize window | Images remain square and aligned | Pass |
| Menu cards | Resize window | Cards stack on mobile, grid on desktop | Pass |
| Footer layout | Resize window | Columns stack neatly on mobile | Pass |

---

**Responsive Interactions**

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Swiper slider | Test on mobile | Touch swipe works smoothly | Pass |
| Buttons | Test on mobile | Buttons remain large and tappable | Pass |
| Navigation | Test on mobile | Navbar remains readable and usable | Pass |

---

**Browser Compatibility Testing**

Browsers tested:

- Chrome  
- Safari  
- Edge  

All pages, images, sliders, forms, and layout elements behaved consistently across browsers.

---

**Known Issues / Fixes**

| **Issue** | **Cause** | **Fix** |
|----------------|------------------------|------------------------------|
| Minor spacing inconsistencies | Default Bootstrap spacing | Added custom CSS spacing rules |
| Some images initially loaded slowly | Large file sizes | Cropped + compressed using Squoosh |



## 4.2 User Story Acceptance Testing

This section documents manual acceptance tests designed and executed to verify each user story’s success criteria. Tests were performed on desktop, tablet, and mobile devices using Chrome DevTools and physical devices.

---

### **1. Homepage Navigation & Introduction**

**User:** First‑Time Visitor  
**Goal:** Understand bakery offerings quickly and navigate easily.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Homepage introduction visibility | Load homepage | Intro text visible immediately | Pass |
| Featured items visibility | Scroll homepage | Featured items appear without excessive scrolling | Pass |
| Navigation accessibility | Click navbar links | Navigation works from all pages | Pass |
| Responsive layout | Resize window / test on mobile | Homepage adapts correctly | Pass |

---

### **2. Categorised Menu Page**

**User:** Casual Customer  
**Goal:** Browse products by category.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Category grouping | View menu page | Products grouped under clear headings | Pass |
| Product card content | Inspect each card | Name + short description visible | Pass |
| Responsive behaviour | Test on mobile/tablet | Cards stack neatly and remain readable | Pass |

---

###  **3. Product Image Gallery**

**User:** First‑Time Customer  
**Goal:** View high‑quality images to assess product quality.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Image clarity | Inspect gallery images | Images are high‑quality and consistent | Pass |
| Image loading | Scroll gallery | All images load correctly | Pass |
| Gallery navigation | Scroll and tap images | Layout easy to navigate | Pass |
| Responsive scaling | Resize window | Images remain square and undistorted | Pass |

---

### **4. Allergen Information Section**

**User:** Customer with dietary requirements  
**Goal:** Understand allergen handling before enquiry.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Section visibility | Scroll to bottom of menu page | Allergen section clearly displayed | Pass |
| Content clarity | Read allergen text | Explanation is clear and easy to understand | Pass |
| Responsiveness | Test on mobile/tablet | Section remains readable | Pass |

---

### **5. Custom Order Enquiry Form**

**User:** Customer planning an event  
**Goal:** Submit a custom order enquiry.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Form visibility | Navigate to Order page | Form easy to find | Pass |
| Required fields | Attempt submission without filling | HTML5 validation prevents submission | Pass |
| Contact method | Enter email/phone | Accepted correctly | Pass |
| Allergen concerns | Enter dietary notes | Field accepts text | Pass |
| Successful submission | Complete all fields | Form submits successfully | Pass |

---

### **6. Opening Hours & Contact Information**

**User:** Returning Customer  
**Goal:** Quickly find opening hours and contact details.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Opening hours visibility | Scroll homepage | Hours clearly displayed | Pass |
| Contact info visibility | Scroll homepage/footer | Contact details easy to find | Pass |
| Icon clarity | Inspect footer icons | Icons readable and intuitive | Pass |

---

###  **7. Seasonal Highlights Section**

**User:** Regular Customer  
**Goal:** See seasonal or limited‑time items.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Section visibility | Scroll homepage | Seasonal items clearly separated | Pass |
| Visual distinction | Compare with main menu | Seasonal items stand out | Pass |
| Update flexibility | Replace seasonal items | Section easy to update | Pass |

---

### **8. Newsletter & Offers Sign‑Up**

**User:** Price‑Conscious Customer  
**Goal:** Sign up for updates and offers.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Email‑only requirement | Inspect form | Only email field required | Pass |
| Benefit clarity | Read promotional text | Benefit of signing up clearly stated | Pass |
| Submission | Enter valid email | Form accepts submission | Pass |

---

### **9. Optional Add‑Ons Section**

**User:** Celebration Customer  
**Goal:** View optional add‑ons.

This feature is **not implemented** and is documented as a **future enhancement**.

---

### **10. Responsive Design Across Devices**

**User:** Mobile & Tablet User  
**Goal:** Browse comfortably on any device.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Mobile layout | Test at 320–480px | Layout adapts correctly | Pass |
| Tablet layout | Test at 768px | Layout adapts correctly | Pass |
| Desktop layout | Test at 1200px+ | Layout adapts correctly | Pass |
| Text readability | Check all pages | No zooming required | Pass |
| Image scaling | Resize window | Images scale without distortion | Pass |
| Navigation usability | Test navbar on mobile | Links remain tappable | Pass |

---

### **11. Customer Testimonials Section**

**User:** Prospective Customer  
**Goal:** Read testimonials to build trust.

| **Test** | **Procedure** | **Expected Result** | **Outcome** |
|-----------|-------------|----------------------|-------------|
| Section visibility | Scroll homepage | Testimonials clearly visible | Pass |
| Readability | Inspect text | Testimonials easy to read | Pass |
| Visual separation | Compare with other sections | Testimonials visually distinct | Pass |
| Layout consistency | Inspect card styling | Matches site’s overall design | Pass |

---

## 4.3 Validators 

### CSS Validaton 

CSS Stylesheet Results

![CSS Stylesheet Results](/readme-assets/butter-and-bloom-css-validator-result.png)

 

### HTML Validaton

**Home HTML Validation**


<details>
<summary>Initial Errors</summary>

![Home HTML Validation Errors](/readme-assets/butter-and-bloom-home-html-validator-errors.png)

</details>


<details>
<summary>End Result</summary>

![Home HTML Validation Results](/readme-assets/butter-and-bloom-gallery-html-validator-results.png)

</details>
---

**Menu HTML Validation**


<details>
<summary>Initial Errors</summary>

![Menu HTML Validation Errors](/readme-assets/butter-and-bloom-menu-html-validator-errors.png)
</details>


<details>
<summary>End Result</summary>

![Menu HTML Validation Results](/readme-assets/butter-and-bloom-menu-html-validator-results.png)

</details>
---

**Gallery HTML Validation**


<details>
<summary>Initial Errors</summary>

![Gallery HTML Validation Errors](/readme-assets/butter-and-bloom-gallery-html-validator-errors.png)

</details>


<details>
<summary>End Result</summary>

![Gallery HTML Validation Results](/readme-assets/butter-and-bloom-gallery-html-validator-results.png)
 
</details>

---

**Order HTML Validation**


<details>
<summary>Initial Errors</summary>

![Order HTML Validation Errors](/readme-assets/butter-and-bloom-order-html-validator-errors.png)

</details>


<details>
<summary>End Result</summary>

![Order HTML Validation Results](/readme-assets/butter-and-bloom-order-html-validator-results.png)

</details>

---

**Form Submission Confirmation Page HTML Validation**


<details>
<summary>Initial Errors</summary>

![Form Submission Confirmation Page HTML Validation Errors](/readme-assets/butter-and-bloom-success-html-validator-errors.png)

</details>


<details>
<summary>End Result</summary>


![Form Submission Confirmation Page HTML Validation Results](/readme-assets/butter-and-bloom-success-html-validator-results.png)

</details>
 
---

**Error Page HTML Validation**

<details>
<summary>Initial Errors</summary>

![Error Page HTML Validation Errors](/readme-assets/butter-and-bloom-error-html-validator-errors.png)

</details>


<details>
<summary>End Result</summary>

![Error Page HTML Validation Results](/readme-assets/butter-and-bloom-error-html-validator-results.png)
 
</details>

---

### Lighthouse 

**Home Page Lighthouse Results**

<details>
<summary>Results</summary>

![Home Page Lighthouse Results](/readme-assets/butter-and-bloom-home-lighthouse-result.png)

</details>


**Menu Page Lighthouse Results**

<details>
<summary>Results</summary>

![Menu Page Lighthouse Results](/readme-assets/butter-and-bloom-menu-lighthouse-result.png)

</details>


**Gallery Page Lighthouse Results**

<details>
<summary>Results</summary>

![Gallery Page Lighthouse Results](/readme-assets/butter-and-bloom-gallery-lighthouse-result.png)

</details>


**Order Page Lighthouse Results**

<details>
<summary>Results</summary>

![Order Page Lighthouse Results](/readme-assets/butter-and-bloom-order-lighthouse-result.png)

</details>


**Form Submission Confirmation Page Lighthouse Results**

<details>
<summary>Results</summary>

![Form Submission Confirmation Page Lighthouse Results](/readme-assets/butter-and-bloom-success-lighthouse-result.png)

</details>

**Error Page Lighthouse Results**

<details>
<summary>Results</summary>

![Error Page Lighthouse Results](/readme-assets/butter-and-bloom-error-lighthouse-result.png)

</details>

**Overall Lighthouse Summary (All Pages)** 

Across all pages of the site, Lighthouse scores were consistently high, ranging from **90–100 for Performance**, **92–96 for Accessibility**, and mostly **100 for Best Practices**. These results show that the site is fast, well‑structured, and technically robust. 

Lighthouse identified several recurring performance improvement opportunities. These were reviewed and intentionally not implemented due to low impact, design considerations, or time constraints: 

*   **Efficient cache lifetimes** — Lighthouse recommended extending cache durations for static assets. This requires server‑level configuration and was outside the scope of the project. 
    
*   **Image delivery** — Suggested converting images to next‑gen formats (WebP/AVIF). While this could reduce file sizes, the site already performs well, and re‑exporting all images would have required significant additional time. 
    
*   **Render**‑**blocking resources** — External CSS/JS libraries such as Bootstrap and Swiper were flagged. These are essential for layout and functionality, and removing them would break the design. 
    
*   **Font display** — Lighthouse recommended adding font-display: swap. This is a minor optimisation with negligible real‑world impact. 
    
*   **Document request latency** — Small potential savings across pages (4–16 KiB). These were not meaningful enough to justify restructuring. 
    

Accessibility flagged two issues: 

*   **Colour contrast** — The navigation bar and footer use a light golden‑brown background with white text. Lighthouse flagged this combination as having insufficient contrast. The original design plan involved a darker golden‑brown text on a low‑saturation golden‑brown background, but due to time constraints and the need to maintain consistency across components already implemented, the colour scheme was not revised. 
    
*   **Touch target size** —   This primarily affected carousel pagination controls on pages using Swiper (e.g., the Gallery). Increasing their size would require custom overrides to the library’s default styling, which was not feasible within the project timeline. 
    

Overall, the site performs extremely well. The remaining suggestions were evaluated and intentionally not implemented due to low impact or time constraints, demonstrating an informed and practical approach to optimisation.

## 4.4 Bug Fixes

A few of the bugs discovered during development are listed below, along with their causes and the fixes applied to resolve them.


| **Bug** | **Cause** | **Fix** |
| --- | --- | --- |
| **Hero Content Not Centering Vertically** | The hero content container was absolutely positioned, removing it from normal flow. Flexbox centering cannot work on an element that is absolutely positioned. | Separated the background wrapper (absolutely positioned) from the content wrapper (flexbox centered). Background is positioned freely; content centers correctly inside it. |

<details>
<summary> Bug </summary>

![Hero Content Not Centering Vertically Bug](/readme-assets/bugs/positioning-hero-content-bug.jpg)
</details>

<details>
<summary> Cause </summary>

![Hero Content Not Centering Vertically Bug HTML](/readme-assets/bugs/positioning-hero-content-bug-cause-1.png)

![Hero Content Not Centering Vertically Bug CSS](/readme-assets/bugs/positioning-hero-content-bug-cause-2.png)
</details>

<details>
<summary> Fix </summary>

![Hero Content Not Centering Vertically Bug HTML](/readme-assets/bugs/positioning-hero-content-bug-fixed.jpg)

![Hero Content Not Centering Vertically Bug HTML](/readme-assets/bugs/positioning-hero-content-bug-solution-1.png)

![Hero Content Not Centering Vertically Bug HTML](/readme-assets/bugs/positioning-hero-content-bug-solution-2.png)

</details>

---

| **Bug** | **Cause** | **Fix** |
| --- | --- | --- |
| Background colours not stretching full width | Each section was wrapped in a Bootstrap ``.container``, which adds left/right padding and prevents full‑width backgrounds. | Moved background colour to the full‑width ``<section>`` and placed the ``.container`` *inside* it to preserve grid layout while allowing full‑width backgrounds. |

<details>
<summary> Bug </summary>

![Background colours not stretching full width Bug](/readme-assets/bugs/background-colour-width-bug.png)
</details>

<details>
<summary> Cause </summary>

![Background colours not stretching full width Bug](/readme-assets/bugs/background-colour-width-bug-cause.png)

</details>

<details>
<summary> Fix </summary>

![Background colours not stretching full width Bug](/readme-assets/bugs/background-colour-width-bug-fixed.png)

![Background colours not stretching full width Bug](/readme-assets/bugs/background-colour-width-bug-solution.png)

</details>

---


| **Bug** | **Cause** | **Fix** |
| --- | --- | --- |
| Expanding Carousel (Bootstrap) | Bootstrap slides *pages*, not *items*, causing duplicated images and broken last slide. | Replaced Bootstrap carousel with Swiper.js for item‑based sliding. |
| Seasonal Highlights Carousel Buttons Missing | New Swiper initialisation used a different button class, losing default styling. | Used the same Swiper initialisation as Featured Items. |
| Order Form Spacing Breaking Grid | .section div placed between ``.row`` and ``.col-*``, breaking Bootstrap grid rules. | Made each form section its own ``.row.`` |
| **Testimonials Overflowing Container** | The ``.container`` was accidentally closed immediately (``</div>``), leaving the entire testimonial slider outside the container. This removed padding and caused cards to overflow. | Removed the stray closing tag so the ``.container`` properly wraps the testimonial row and Swiper slider. |
| **Modal Body Padding Appearing Incorrect** | The close button was placed inside ``.modal-body``, consuming the top padding and making the paragraph + form appear unpadded. | Moved the close button into ``.modal-header`` (Bootstrap‑correct placement), restoring even padding inside ``.modal-body``. |
| **Testimonial Cards Not Matching in Height** | Swiper slides do not auto‑equalize height. Each ``.swiper-slide`` and ``.testimonial-card`` lacked flex rules needed for consistent vertical sizing. | Applied flexbox to ``.swiper-slide`` and ``.testimonial-card``, and added ``flex: ``1`` to ``.testimonial-text`` to equalize card height across all breakpoints. |




# 5) Deployment

## 5.1 How to Run This Project Locally



To run Butter & Bloom on your local machine:

---

### **1. Clone the Repository**

Open your terminal and run:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Or download the project manually via:

- **Code → Download ZIP** on GitHub

---

### **2. Open the Project Folder**

Navigate into the folder you cloned or extracted.

---

### **3. Open the Project in Your Editor**

You can use any editor, such as **VS Code**.

---

### **4. Run the Site Locally**

Because this is a static HTML/CSS/JS project, you can run it in several ways:

---

**Option A — Open `index.html` Directly**

- Double‑click `index.html`  
- It will open in your browser

---

**Option B — VS Code Live Server**

If using VS Code:

1. Install the **Live Server** extension  
2. Right‑click `index.html`  
3. Select **Open with Live Server**

This provides:

- automatic reload  
- correct relative paths  
- a more realistic development environment  

---

**Option C — Python HTTP Server** *(recommended)*

This is the method used during development.

Open a terminal inside the project folder and run:

```bash
python -m http.server --bind 127.0.0.1
```

Then open your browser and visit:

```
http://127.0.0.1:8000
```

This provides a lightweight local server and ensures correct handling of relative paths.

---

### **5. View the Site**

Your browser will open the homepage, and you can navigate through all pages normally.



## 5.2 Deployment with GitHub Pages 


This project is deployed using **GitHub Pages**.  
Below are the steps followed to deploy the website and how you can redeploy it from the repository.

---

**Deploying from the Main Branch**

### **1. Push Code to GitHub**

- Clone or create the repository on GitHub  
- Add your project files  
- Commit them to the **main** (or **master**) branch

```bash
git clone https://github.com/your-username/your-repo-name.git
```

---

### **2. Open GitHub Pages Settings**

- Go to your repository  
- Click **Settings**  
- Scroll down to **Pages**

---

### **3. Select the Deployment Source**

Under **Source**, choose:

- **Branch:** main (or master)  
- **Folder:** `/root` (or `/docs` if used)

Click **Save**.

---

### **4. Wait for GitHub Pages to Build**

GitHub will build and deploy the site.  
A deployment URL will appear in the **Pages** section.

---

### **5. Access the Live Site**

Visit the URL shown, for example:

```
https://username.github.io/repository-name
```

The deployed version of the site should now be visible.

---

### **Redeploying After Updates**

- Make changes locally  
- Commit and push to the same branch  
- GitHub Pages will automatically rebuild  
- Refresh the deployed URL to see the latest version



# 6) Credits

## 6.1 Contents

**Website Content** 

All written content displayed on the website (e.g., About Us, menu descriptions, seasonal highlights, allergen information) was generated using Microsoft Copilot based on my prompts and brand direction. I reviewed, edited, and approved all content before adding it to the site. 

**Documentation Content**  

All project notes and explanations were written by me. Microsoft Copilot supported me by refining the clarity, structure, and phrasing of my documentation for the README. 

 

## 6.2 Media 

### General

| **File Name** | **[Source](ca://s?q=Explain_asset_sourcing)** | **Author** |
| --- | --- | --- |
| Favicon folder / ``favicon.ico`` | Generated by Copilot → converted using Favicon.io | Destiny |
| ``logo-white.PNG`` | Created in Canva | Destiny |

### Home

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``hero-image.jpg`` | AI‑generated Image (ChatGPT) | Destiny |
| ``featured-items-cake.jpg`` | AI‑generated Image (ChatGPT) | Destiny |
| ``featured-items-cheesecake.jpg`` | Unsplash – [Image by Julia Peretiatko](https://unsplash.com/photos/sliced-bread-with-sliced-strawberries-on-brown-wooden-chopping-board-oXfOK1ymtPU) | Julia Peretiatko (@julie_peretiatko) |
| ``featured-items-cookies.jpg`` | AI‑generated Image (Copilot) | Destiny |
| ``seasonal-highlights-blondies.jpg`` | AI‑generated Image (Copilot) | Destiny |
| ``seasonal-highlights-cake.jpg`` | Unsplash – [Image by Kateryna Hliznitsova](https://unsplash.com/photos/brown-and-white-doughnut-on-brown-wooden-tray-1GjSVRpd-oE) | Kateryna Hliznitsova (@kate_gliz) |
| ``seasonal-highlights-raspberry-cheesecake.jpg`` | AI‑generated Image (Copilot) | Destiny |

### Menu

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``cake.jpg`` | Unsplash – [Image by Jasmine Bartel](https://unsplash.com/photos/baked-strawberry-cake-8LtrMQfeDkQ) | Jasmine Bartel (@jasminesky) |
| ``cheesecake.jpg`` | Unsplash – [Image by Alexandra Khudyntseva](https://unsplash.com/photos/strawberry-cake-on-white-ceramic-plate-hXqbSgOPjSI) | Alexandra Khudyntseva (@sannka) |
| ``cookies.jpg`` | Unsplash – [Image by Eva Creative](https://unsplash.com/photos/assorted-design-baked-biscuits-lVf3t9JWS0E) | Eva Creative (@evacreative) |
| ``cupcake1.jpg`` | Unsplash – [Image by Deva Williamson](https://unsplash.com/photos/selective-focus-photography-of-cupcakes-with-icings-0hnqS3Stj0w) | Deva Williamson (@biglaughkitchen) |
| ``cupcake2.jpg`` | Unsplash – [Image by Deva Williamson](https://unsplash.com/photos/baked-cupcake-S2jw81lfrG0) | Deva Williamson (@biglaughkitchen) |
| ``giftbox.jpg`` | AI‑generated Image (Copilot) | Destiny |
| ``loaf.jpg`` | Unsplash – [Image by Deborah Rainford](https://unsplash.com/photos/brown-bread-on-white-ceramic-tray-lk63vqjc1nA) | Deborah Rainford (@debsrainford) |
| ``scone-iced-cropped.jpg`` | Unsplash – [Image by AnaCristina Smith](https://unsplash.com/photos/a-close-up-of-a-pastry-with-icing-and-raspberries-kALSTzyq6jE) | AnaCristina Smith (@anacristinacanana) |
| ``scones-jam-cream.jpg`` | Unsplash – [Image by Vicky Ng](https://unsplash.com/photos/brown-cookies-on-brown-wooden-tray-hlslhvvfw9w) | Vicky Ng (@vickyng) |
| ``seasonal-berry-cheesecake.jpg`` | Unsplash – [Image by Vera Davidova](https://unsplash.com/photos/a-cake-with-berries-on-top-Sp3KyrXeOzY) | Vera Davidova (@veradavidovaphotography) |
| ``traybake.jpg`` | Unsplash – [Image by Irene Kredenets](https://unsplash.com/photos/brown-and-white-bread-on-tray-50xbDSNARpw) | Irene Kredenets (@ikredenets) |

### Gallery

**Celebration Cakes**

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``cake-chcolate-flower.jpg`` | Unsplash – [Image by Serghey Savchuk](https://unsplash.com/photos/a-chocolate-cake-with-chocolate-icing-and-chocolate-swirls-H2t7or5XgPs) | Serghey Savchuk (@savchuks) |
| ``cake-choco-bday.jpg`` | Unsplash – [Image by Karina Kungla](https://unsplash.com/photos/a-chocolate-cake-decorated-with-chocolate-candies-and-marshmallows-yu9JZAW_TgE) | Karina Kungla (@pixelperfectmom) |
| ``cake-choco-deco.jpg`` | Unsplash – [Image by parastoo jk](https://unsplash.com/photos/chocolate-topped-cake-P68yv6bC2pI) | parastoo jk (@parastoojk) |
| ``cake-gold-cherries.jpg`` | Unsplash – [Image by Karina Kungla](https://unsplash.com/photos/a-white-cake-with-gold-decorations-on-top-of-it-Cso77lQBrZQ) | Karina Kungla (@pixelperfectmom) |
| ``cake-pink-rose.jpg`` | Unsplash – [Image by David Holifield](https://unsplash.com/photos/pink-and-white-floral-cake-N5LQeJFX5pU) | David Holifield (@davidholifield) |
| ``cake-purple-flower.jpg`` | Unsplash – [Image by Deva Williamson](https://unsplash.com/photos/five-cupcakes-beside-cake-pZZJwwNPy2k) | Deva Williamson (@biglaughkitchen) |
| ``cake-strawberry-white-choco.jpg`` | Unsplash – [Image by Joshua Glass](https://unsplash.com/photos/a-pink-cake-with-white-frosting-and-strawberries-on-top-0KpfliRVLJs) | Joshua Glass (@joshuaglass) |

**Tiered & Wedding Cakes**

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``blue-purple-tiered-cake.jpg`` | Unsplash – [Image by Deva Williamson](https://unsplash.com/photos/multicolored-2-tier-cake-on-white-stand-Dd8_frJOHco) | Deva Williamson (@biglaughkitchen) |
| ``blue-tiered-cake.jpg`` | Unsplash – [Image by Eight Creative Media](https://unsplash.com/photos/3-tier-cake--uZNyLofoPw) | Eight Creative Media (@eightcreativemedia) |
| ``pink-gold-tiered-cake.jpg`` | Unsplash – [Image by Hermes Rivera](https://unsplash.com/photos/pink-and-white-roses-in-white-ceramic-vase-pQSs6HXrr3Y) | Hermes Rivera (@hermez777) |
| ``pink-red-tiered-cake.jpg`` | Unsplash – [Image by Ryan Sepulveda](https://unsplash.com/photos/pink-and-white-roses-on-white-table-J10RI2uDhM0) | Ryan Sepulveda (@ryanjs08) |
| ``red-white-tiered-cake.jpg`` | Unsplash – [Image by Scott Osborn](https://unsplash.com/photos/white-4-tier-cake-TAtTPzM95nk) | Scott Osborn (@scottosbornphoto) |
| ``tieredcake.jpg`` | Unsplash – [Image by Photos by Lanty](https://unsplash.com/photos/3-layer-cake-with-flowers-accent-22JxStzTxwo) | Photos by Lanty (@photos_by_lanty) |

**Cupcake Designs**

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``cupcake-pink-flower.jpg`` | Unsplash – [Image by Ivan Yeo](https://unsplash.com/photos/a-cupcake-with-a-flower-design-on-it-Pl99dx-pR3c) | Ivan Yeo (@ivanyeors) |
| ``cupcakes-multicoloured-flowers.jpg`` | Unsplash – [Image by Ana Tavares](https://unsplash.com/photos/flower-cupcakes-on-white-surface-uUtQTi-UNRE) | Ana Tavares (@ana_tavares) |
| ``cupcakes-peach-blue-flowers.jpg`` | Unsplash – [Image by Vy Huynh](https://unsplash.com/photos/pink-and-yellow-flower-bouquet-8yuLwtkpB3w) | Vy Huynh (@thanhvy14) |
| ``cupcakes-purple-yellow-flowers.jpg`` | Unsplash – [Image by Caitlyn de Wild](https://unsplash.com/photos/two-cupcakes-on-white-ceramic-tray-nV5qdHPop3o) | Caitlyn de Wild (@caities_cakes_amsterdam) |
| ``cupcakes-white-pink-flowers.jpg`` | Unsplash – [Image by M. W](https://unsplash.com/photos/pink-and-white-flower-bouquet-on-white-ceramic-plate-vL6XDSdvmec) | M. W (@mmw189) |
| ``cupcakes-yellow-flower.jpg`` | Unsplash – [Image by Anita Austvika](https://unsplash.com/photos/a-plate-of-cupcakes-with-white-frosting-and-yellow-flowers-ZvbT343ee8U) | Anita Austvika (@anitaaustvika) |

**Cheesecakes**

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``cheesecake-choco-marshmallow-berry.jpg`` | Unsplash – [Image by Karina Kungla](https://unsplash.com/photos/a-cake-with-raspberries-on-top-of-it-C-NGt8PUHzE) | Karina Kungla (@pixelperfectmom) |
| ``cheesecake-cinnamon.jpg`` | Pixabay – [Image by Pexels](https://pixabay.com/photos/cake-cheesecake-cinnamon-sticks-1869227/) | Pexels (pexels-2286921) |
| ``cheesecake-ganache-whitechoco-apricot.jpg`` | Pixabay – [Image by PixelPerfectMom](https://pixabay.com/photos/white-chocolate-ganache-cake-8252803/) | PixelPerfectMom (pixelperfectmom-39067011) |
| ``cheesecake-macaron-pistachio.jpg`` | Unsplash – [Image by Jovan Vasiljević](https://unsplash.com/photos/a-colorful-cake-decorated-with-macarons-and-flowers-q-TT-UpsKKc) | Jovan Vasiljević (@jovanvasiljevic) |
| ``cheesecake-pink-berry.jpg`` | Unsplash – [Image by Karina Kungla](https://unsplash.com/photos/a-cake-on-a-table-with-a-glass-of-water-4Zis4Qe7AH8) | Karina Kungla (@pixelperfectmom) |
| ``cheesecake-strawberry.jpg`` | Pixabay – [Image by Tikovka1355](https://pixabay.com/photos/cake-dessert-cheesecake-food-6406440/) | Tikovka1355 (tikovka1355-16935155) |

**Traybakes**

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``tray-bake-choco-flowers.jpg`` | Unsplash – [Image by Jonathan Borba](https://unsplash.com/photos/a-table-topped-with-chocolate-desserts-covered-in-pink-flowers-mN5Neg1_dnk) | Jonathan Borba (@jonathanborba) |
| ``traybake-brownies.jpg`` | Unsplash – [Image by Pushpak Dsilva](https://unsplash.com/photos/chocolate-cake-on-white-paper-Le7eYWBIvio) | Pushpak Dsilva (@pushpak88) |
| ``traybake-nut-cho-bars.jpg`` | Unsplash – [Image by Brigitta Baranyi](https://unsplash.com/photos/chocolate-cake-on-black-round-plate-1lj9mDFaG2Q) | Brigitta Baranyi (@bribrnyi) |
| ``traybake-pink-flowers.jpg`` | Unsplash – [Image by Corryn Burtenshaw](https://unsplash.com/photos/a-cake-with-flowers-on-it-60hrPHoo1HQ) | Corryn Burtenshaw (@indigo365) |
| ``traybake-purple.jpg`` | Unsplash – [Image by Wallace Wang](https://unsplash.com/photos/a-close-up-of-a-plate-of-desserts-with-whipped-cream-RNtQ7zHu--Y) | Wallace Wang (@kwanace) |
| ``traybake-shortbread-bars.jpg`` | Unsplash – [Image by sheri silver](https://unsplash.com/photos/a-white-plate-topped-with-cut-up-flowers-next-to-a-cooling-rack-Mpc6nqvwbbc) | sheri silver (@sheri_silver) |

**Seasonal Creations**

| **File Name** | **[Source](ca://s?q=Explain_image_sourcing)** | **Author** |
| --- | --- | --- |
| ``seasonal-flower-cake.jpg`` | Unsplash – [Image by Karina Kungla](https://unsplash.com/photos/a-close-up-of-a-cake-on-a-table-sxhu7gmKsZ4) | Karina Kungla (@pixelperfectmom) |
| ``seasonal-berry-cake.jpg`` | Unsplash – [Image by micheile henderson](https://unsplash.com/photos/fruit-salad-on-white-ceramic-bowl-MYAGZpr2cik) | micheile henderson (@micheile) |
| ``seasonal-lemon-berry-tart.jpg`` | Unsplash – [Image by Frosty Ilze](https://unsplash.com/photos/sliced-lemon-and-strawberry-on-white-ceramic-plate-lD0JFJDXBfQ) | Frosty Ilze (@frostyilze) |
| ``seasonal-lemon-tarts-small.jpg`` | Unsplash – [Image by Kim Daniels](https://unsplash.com/photos/blueberries-on-bowls-OrkEasJeY74) | Kim Daniels (@kimbroughdaniels) |
| ``seasonal-loaves-lemon.jpg`` | Unsplash – [Image by Sharon GM](https://unsplash.com/photos/a-couple-of-pies-sitting-on-top-of-a-wooden-cutting-board-_gmBYXGwZmU) | Sharon GM (@sharon_gm) |
| ``seasonal-tiered-cake.jpg`` | Unsplash – [Image by Melissa Walker Horn](https://unsplash.com/photos/a-three-tiered-cake-with-figs-on-top-of-it-4on47p0-bk4) | Melissa Walker Horn (@sugercoatit) |



## 6.3 Code 

**Code References** 

The following resources were referenced during development: 

*   **Instructor Walkthrough Project** — used as a structural reference for page layout, Bootstrap usage, and responsive design patterns. 
    
*   **Bootstrap Documentation** — referenced for grid layout, spacing utilities, breakpoints, and responsive components. 
    
*   **Swiper.js Documentation** — referenced for slider initialization, pagination, and navigation settings. 
    
*   **Font Awesome Documentation** — referenced for icon usage and class naming. 
    
*   **GitHub Pages Documentation** — referenced for deployment setup and configuration. 
    
*   **Microsoft Copilot** — provided code explanations and refinement suggestions which I adapted into my own implementation. 
    

All custom HTML, CSS, and JavaScript was written by me.


## 6.4 Acknowledgements


I would like to acknowledge the tools, platforms, and individuals who supported the development of **Butter & Bloom**:

- **Microsoft Copilot** — for assisting with refining my written notes into clear, structured documentation suitable for my README. I wrote all notes myself, and Copilot helped improve clarity, phrasing, and organisation. Copilot also supported me with image generation, favicon concept refinement, testing documentation, and **alt text creation** for gallery images to ensure accessibility.

- **ChatGPT** — for generating additional dessert imagery and helping refine descriptive content.

- **favicon.io** — for converting my AI‑generated logo concept into a functional favicon.

- **Squoosh** — for enabling efficient image compression and optimisation across the site.

- **Unsplash and Pixabay** — for providing high‑quality stock photography used throughout the gallery and menu.
- **MockupFrame** — for generating responsive device mock‑ups used to present the Butter & Bloom website design.

- **Bootstrap**, **Swiper.js**, and **Font Awesome** — for reliable UI components, responsive layouts, and iconography.

- **Course instructors and programme staff** — for guidance, feedback, and support throughout the project.

- **Friends and family** — for testing the site on different devices and providing usability feedback.

