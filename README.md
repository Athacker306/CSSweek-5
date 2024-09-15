#Amazon_Clone_by_Geekster

![Screenshot 2024-09-15 181036](https://github.com/user-attachments/assets/660eadf1-094e-4792-b205-d6c74fbd3b57)

![Screenshot 2024-09-15 200059](https://github.com/user-attachments/assets/e3417c71-d72d-45f8-9fa1-301e566d9001)

![Screenshot 2024-09-15 200146](https://github.com/user-attachments/assets/b6a2b3a4-d0a4-43b6-b8eb-659361a15b1b)


A navigation bar is crafted within the "navbar" class, featuring various divisions:

The "nav-logo" division contains a logo image ("logo.png") linked to "#".
In the "address" division, a "Deliver" link is placed, alongside a map-icon division encompassing a location_on icon. The "India" link corresponds to the icon.
The "nav-search" division encompasses a select dropdown with options ("All," "All Categories," "Amazon Devices"), a search input field, and a search icon.
The "sign-in" division showcases a "Hello, sign in" link, supplemented by "Account & Lists."
The "returns" division hosts a "Returns" link succeeded by "Orders."
Lastly, the "cart" division introduces a shopping_cart icon, a "Cart" text, and a link to the cart.
The "banner" division encapsulates banner content, featuring a "panel" division:

Inside the "panel" division, a menu icon is accompanied by an "All" link.
The "links" division presents an unordered list with links for "Today's Deals," "Customer Service," "Registry," "Gift Cards," and "Sell."
The "deals" division showcases a link to "Shop deals in Electronics."
This HTML code establishes a comprehensive header structure encompassing various navigation elements, a logo, search functionality, account-related links, and a banner section containing menu options and pertinent links. This setup is designed to enhance user experience and facilitate navigation on the webpage.

![Screenshot 2024-09-15 201956](https://github.com/user-attachments/assets/e156bcbd-fc10-4998-8038-84ecc6da6fba)

![Screenshot 2024-09-15 202008](https://github.com/user-attachments/assets/6d0cb840-ae71-4ed9-94c6-1d6a1252d45d)

![Screenshot 2024-09-15 202309](https://github.com/user-attachments/assets/679729e4-500a-47ad-a95f-f5842b76d14f)

![Screenshot 2024-09-15 202343](https://github.com/user-attachments/assets/4b0f4734-c4fe-4a93-bc80-8a79f2154009)

![Screenshot 2024-09-15 202419](https://github.com/user-attachments/assets/fb876233-61cf-4e85-b5b3-c7d8088092af)


The header element:

Spans 100% width.
Has a background color of #0f1111.
The .navbar class:

Has a height of 60px.
Uses flex layout with center alignment and space-between distribution.
Sets cursor to pointer and text color to #fff.
Sets a maximum width of 1280px and centers horizontally with margin: 0 auto.
The .nav-logo class (within .navbar):

Adjusts margin-top to 10px.
Sets width to 128px.
The .address .deliver selector:

Adds a margin of 20px to the left.
Sets font size to 0.75rem.
Sets text color to #ccc.
The .address .map-icon selector:

Uses flex layout with align-items center.
The .nav-search class:

Utilizes flex layout with space-evenly distribution.
Sets a maximum width of 620px and 100% width.
Applies a border radius of 4px.
The .select-search class:

Sets background to #f3f3f3.
Sets width to 50px.
Aligns text center.
Sets border radius for the left side.
The .search-input class:

Sets a maximum width of 600px and 100% width.
Sets font size to 1rem.
Removes borders and outlines.
Adds padding to the left.
The .search-icon class:

Sets a maximum width of 45px and 100% width.
Utilizes flex layout with center alignment.
Sets font size to 1.2rem.
Sets background color to #febd68 and text color to #000.
Adds cursor pointer and border radius for the right side.
The .sign-in p and .returns p selectors:

Sets font size to 0.75rem.
The .sign-in and .returns span selectors:

Sets font size to 0.875rem and font weight to 600.
The .cart class:

Uses flex layout.
The .cart .cart-icon selector:

Sets font size to 2.5rem.
The .cart p selector:

Adds margin-top of 20px and sets font weight to 500.
The .banner class:

Adds padding of 10px vertically and 20px horizontally.
Sets background to #222f3d and text color to #fff.
Sets font size to 0.875rem.
The .banner-content class:

Centers content horizontally with max-width of 1280px.
Uses flex layout with space-between distribution.
The .panel class:

Sets max-width to 1280px and uses flex layout.
Aligns items center with a gap of 5px.
Sets cursor to pointer.
The .panel span selector:

Adds margin-right of 7px.
The .links class:

Uses flex layout with center alignment.
Sets list-style to none and a gap of 15px.
Flex-grow is set to 1 and margin-left to 15px.
The .links a selector:

Adds padding of 10px vertically.
The .deals a selector:

Sets font size to 0.9rem and font weight to 500.
Sets white-space to nowrap to prevent text wrapping.
These styles contribute to the appearance and layout of various elements within the header section of the webpage. The use of flex layout and consistent styling enhances the visual design and user experience.
![Screenshot 2024-09-15 203655](https://github.com/user-attachments/assets/8f62a188-5df8-4357-bb35-d65f2b1aff40)

[hero]![hero-img](https://github.com/user-attachments/assets/f5f935c4-fdb0-481b-996f-f25a391a3770)

The given HTML code represents a "section" element bearing the class "hero-section." This section, devoid of immediate content, serves as a structural component for webpage organization. It can function as a placeholder for upcoming content or dynamic elements, often incorporated using CSS 

![Screenshot 2024-09-15 203519](https://github.com/user-attachments/assets/cf107afb-ceda-4e16-b391-a398ca486823)

The .hero-section class:
Sets the height of the section to 400 pixels.
Uses a background image specified by the URL "./hero.jpeg".
Positions the background image at the center of the section.
Adjusts the size of the background image to cover the entire section, ensuring it fills the available space while maintaining its aspect ratio.

[cards]![15 09 2024_19 01 19_REC](https://github.com/user-attachments/assets/14bb3fc5-377e-49e3-9e89-630bd016abae)

![Screenshot 2024-09-15 211254](https://github.com/user-attachments/assets/b3e8e740-b53c-444f-bd55-8c95fb8641e7)

The provided HTML code defines a "section" with the class "shop-section." This section is designed for showcasing various product categories through a visually appealing grid layout. The "shop-images" division contains a set of "shop-link" divisions, each representing a product category. These divisions feature animation effects using the AOS (Animate On Scroll) library, causing a flip-left animation with varying durations as the user scrolls.

Within each "shop-link" division:

An "h3" heading introduces the product category.
An image ("img-1.png," "img-2.png," etc.) corresponds to the respective product.
An anchor ("a") tag labeled "Shop now" links to the relevant shopping page.
The layout is geared towards engaging users with a selection of shopping options. Each product category is visually represented, with the AOS animation adding an interactive element. This HTML structure creates a dynamic and visually appealing section for highlighting different product categories and encouraging users to explore further.

![Screenshot 2024-09-15 211424](https://github.com/user-attachments/assets/207bcec6-bc20-4210-a907-5dc1601709a6)

![Screenshot 2024-09-15 211538](https://github.com/user-attachments/assets/5029a940-2bde-4542-bf48-81fddbff7eeb)

The .shop-section class:

Uses flex layout to vertically align items.
Sets the flex direction to column.
Sets the background color to #f3f3f3.
Adds padding of 50px vertically and 0 horizontally to the section.
The .shop-images class:

Uses grid layout for the images.
Specifies that columns should automatically fit the available space while having a minimum width of 250px.
Sets a gap of 40px between grid items.
Sets a maximum width of 1280px and 100% width.
Applies an overflow property to hide any overflow from grid items.
The .shop-link class:

Sets background color to #fff.
Adds padding of 30px.
Uses flex layout in column direction for alignment.
Sets cursor to pointer.
Sets white-space to nowrap to prevent text from wrapping.
Sets an initial scale of 1.
Adds a transition effect on the scale property with ease-in-out timing.
Hover state for .shop-link:

Increases the scale to 1.1 on hover, creating a slight zoom-in effect.
The .shop-link img selector:

Sets width to 100%.
Sets height to 280px.
Applies object-fit property to cover the container while maintaining aspect ratio.
Adds a margin of 10px to the bottom.
The .shop-link h3 selector:

Adds margin of 10px to the bottom.
The .shop-link a selector:

Displays as an inline-block.
Adds margin of 10px to the top.
Sets font size to 0.9rem.
Sets text color to blue.
Sets font weight to 500.
Adds a transition effect on the color property with ease timing.
Hover state for .shop-link a:

Changes the text color to #c7511f and adds an underline to the text on hover.
These styles contribute to the appearance and layout of a shop section on the webpage, with responsive grid-based images and interactive effects on hover for a visually appealing and user-friendly design.

[footer]
![15 09 2024_19 01 19_REC](https://github.com/user-attachments/assets/cfa6f2a7-94bd-4e3f-8d3c-6cda06149fff)

![Screenshot 2024-09-15 211704](https://github.com/user-attachments/assets/805e235b-3c3e-45a2-8568-cb32bead4e0b)

![Screenshot 2024-09-15 211722](https://github.com/user-attachments/assets/000039f5-5968-412a-a877-d56cc65659cf)

Within the "footer" section:

An anchor ("a") tag with the class "footer-title" serves as a "Back to top" link, which allows users to quickly navigate to the top of the page.

The "footer-items" division groups multiple unordered lists ("ul"), each containing a series of links categorized into different sections:

The first "ul" section includes links related to "Get to Know Us," including "About us," "Careers," "Press Release," and "Amazon Science."

The second "ul" section consists of links to social media platforms, enabling users to "Connect with Us" through "Facebook," "Twitter," and "Instagram."

The third "ul" section focuses on ways to "Make Money with Us" on Amazon, featuring links such as "Sell on Amazon," "Sell under Amazon Accelerator," "Protect and Build Your Brand," and more.

The fourth "ul" section offers links to assist users with various tasks, under the theme of "Let Us Help You." This includes links like "COVID-19 and Amazon," "Your Account," "Return Centre," "100% Purchase Protection," "Amazon App Download," and "Help."

Overall, this HTML code constructs a comprehensive footer section containing various links for navigation, social media engagement, and accessing important resources related to Amazon services. The structured layout enhances user experience by providing organized access to relevant information and options.

![Screenshot 2024-09-15 212140](https://github.com/user-attachments/assets/f276e24c-a935-467a-931f-1010dcd43a83)

![Screenshot 2024-09-15 212205](https://github.com/user-attachments/assets/4986c335-9160-4d9d-bbaf-130952ffc2bb)

The .footer-title class:

Uses flex layout to center items both vertically and horizontally.
Sets background color to #37475a and text color to #fff.
Sets font size to 0.875rem and font weight to 600.
Sets the height of the title to 60px.
The .footer-items class:

Uses flex layout to evenly distribute items horizontally.
Spans 100% width and centers horizontally with margin: 0 auto.
Sets background color to #232f3e.
The .footer-items h3 selector:

Sets font size to 1rem and font weight to 500.
Sets text color to #fff.
Adds margin of 20px at the top and 10px at the bottom, and 0 on the left and right.
The .footer-items ul selector:

Removes the default list-style and adds some margin at the bottom for spacing.
The .footer-items li a selector:

Sets text color to #ddd and font size to 0.875rem.
Hover state for .footer-items li a:

Adds an underline to the text on hover.
