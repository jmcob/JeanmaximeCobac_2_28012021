# Reservia - OpenClassRooms webDev

This is my second project for OpenClassRooms as a student for becoming a web developer. It simulates a booking website.

## Conception

**This webpage is made of pure HTML5 and CSS3 and nothing more, from a mockup.**

This page makes use of the CSS FlexBox and Grid properties. As a result, the "hébergement" and "activités" sections mainly use Flexbox for their structure. Moreover, the "footer", each hotel card, and mobile menu are made with CSS Grid.

Some CSS properties like color variables, media queries for responsive, font awesome icons, google fonts and heavy CSS personnalization are part of this work.

Forms, links and buttons are not functional as this is a single page.

## Checkout the URL to take a look

<http://reservia.jmax.dev/>

## About this work, in details

The purpose of this work is to master CSS main principles, as well as apply part of the HTML tags learnt is the course.

To begin, it's necessary to understand the basics of div and span in html, as well as the attributes id and class that comes with them. Later, divs will be the basic tags for CSS Grid and CSS Flexbox.

### The menu

The desktop menu is made of three divs inside a flexbox. In the mobile version, these divs are part of a grid, because Grid made it easier to display the mobile menu correctly. The other part of the mobilemenu, I talk about the "inscription" button, and the logo, are fixed to an absolute position in CSS.

### Form and filters

The tricky part here, at first, is the HTML. Once HTML is done, every icon here comes from FontAwesome. Customisation of these elements is made from different CSS selectors.

### Hébergements and populaires: accomodations

One big part of this work is taking advantage of CSS Flexbox in this part of the page. Here, a div contains aside (populaires) and section (accomodation). This div is a flexbox container for "populaires" and "hébergements". Flex direction is row and it wraps for the mobile version. (60% / 22 %) is the ratio for the two childs, which are containers too, for the cards they contain. One property, "fill" when used with height, makes the two parts about accomodations end to the same height of the screen in desktop.

### Cards

CSS attributes make the card look like the mockup. Borders, stars from fontawesome, widths, heights, margins and paddings, everything is made to look good in the browser... and in the eye of a developer. Everything is made to be understood and reworked. Inside the cards in the caption, I used a simple CSS Grid for the stars to be aligned as in the mockup.

### activité : activity

These are made of flexboxes too. The tricky part was to make the containers containing two activities behave as the normal ones. These are flexboxes inside flexboxes. Here it's necessary to deal with paddings and margins carefully, as it was in the cards.

### Margins and paddings

Every margin had to be the same in every place of the webpage. 3vw was ok on left and right on the desktop version, 5vw in mobile version.

### Footer

Made of a CSS Grid.

### Responsive

Two major breakpoints : 1024px and 768px. Between the two this is sort of a hybrid.

## Git and GitHub

Obviously, I'm usinig GitHub for this project. Locally I'm using 3 different softwares for git :
* git in the terminal on macOS with the common command lines, easy for important changes, preferably used for merges.
* GitHub Desktop to stage, commit and push files in a second.
* VS Code integrated terminal and simplified command lines in the beginning, but less often now that i know how to use a proper terminal.

I could add GitHub website that is easy to handle some tasks like pull requests, and necessary to delete branches once they are removed locally.
I use GitHub Pages to host the website.

## Visual Studio Code

This is my editor of choice due to extensions like "Live Server", "Prettier", W3C validation tools and other stuff.
Its use for common tasks on git is a great advantage too.
Lots of settings to customize and make it mine.

## Files

*index.html* is the main HTML file.
*styles.css* is the main CSS file.

You can see the original mockup in *Desktop - 1.png* and *iPhone 8 - 1.png*.

Everything else should not be important to you.


Regards, Jean-Maxime
