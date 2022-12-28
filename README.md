# saida-abdelhady
# Landing Page Project

# Project description :

### In this project there are many thinks wanted to do :
1. The HTML file must have at least 4 content sections.
2. Build a dynamic navigation menu.
3. While navigating through the page, the section that is active must have an active class.
4. Clicking on a navigation item should scroll to this section and the animation must be smoothing.
5. The page must be responsive and should be created to use across all devices.

## Steps to do this :
1. Because of the page has 3 sections only, I first add a new section.
2. To build a dynamic nav bar I create (li) elements equals the number of sections in the page and add anchor to each one. I use innerhtml to add anchor and use (scrollIntoViw) to add a smooth behavior and finally use (appedChild) to add (li) element to (ul) element.
3. I use (getBoundingClientRect()) to know the place of the section and add the ("your-active-class") to it. in this step I add the ("active-link") to navigation item.
4. I use @media in css file to make the page responsive.

## Sources :
1. https://www.w3schools.com/
2. https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect
3. http://udacity.github.io/frontend-nanodegree-styleguide/css.html#block-content

