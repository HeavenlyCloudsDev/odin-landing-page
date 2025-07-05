Project Name: Odin Landing Page
Project Description: This is a landing page project for The Odin Project.
I was given the option to use images that are free to use or create my own. I was also told to have fun with the font.

Images and buttons were created using figma.

Font used: 

About the process of creation: 

July 4th: First Portion Nav and Hero.

Situation: 

Initially I could not get this code to work properly. It was extremely bloated. Flexboxes were showing up as columns instead of rows. I need to build this landing page from scratch and make it nice uniform polished presentation ready.

Task: 
Create the graphics (SVGs), Use the wireframes provided, use a color scheme, find the fonts I would like to use and link them. Also I want to use a favicon in the browser window.


Action: Changed the hero-section to row instead of column to get them horizontally aligned properly, and took the align-items off the parent div (hero-section)


Result: 

Everything is aligned and in flexboxes in the header and the hero section.
The image is the perfect size. Changed it from a small screen to a larger screen and grows perfectly. The image quality is stable because I used SVGs instead of JPEGs or PNGs. So I am going to add this to git first before continuing.

Update 
Situation: The nav bar needs more padding left and right.

Task: Get the navigation bar to be vertically aligned with the main content.

Action: Increased the padding on the left and the right of the div (nav) from 20px to 90px.

Result: It now lines up perfectly even on larger screens. 


Working on the second section called feature and now I am having the same problem as before. I have created a flexbox that will house the 4 images and the 4 images all will have paragraph text. The issue is they are showing up as columns and the text is stretching to the full with of the page. I even added a border that I do not see showing up. Going to do some light research and I will log the resources used to find the answers as well. 

Stackoverflow.com: https://stackoverflow.com/questions/31676623/why-wont-my-div-elements-stay-in-line

So I am going to try to see if changing stuff to inline to see if that helps.
No that just lined them up next to each other. I'm thinking I may need to apply a max-width to the features-info section so they can be set to wrap.

Setting the max-width worked.

Now I am going to add text wrap to the parent so the children can be next to one another. That worked and now they need a gap between them.


Everything looks great so far except the header is on its left and I need it above. So I am going to set that element to be declared a block element so it can have its own line. That didn't work.

Okay What I did appears to be changing a lot. The header for the features section is no longer centered and the font is bigger than intended... Taking a break to think about it and get prepared to see fireworks. 

Situation : The header for the feature section needs to be centered.

Task: Get it in the middle vertically.

Action : Changed it to display block,

Result: 
It is now centered.


Situation: Now that I had to make the header an element on its own, there is a gap between the header and the feature section. 

Task: Remove the gaps on the webpage.

Action: Researched on google and stackoverflow. I've tried using the negative margins like google suggested it did help with taking away the vertical gaps but not the horizontal gaps. Going to try increasing it.

Result: 
Increasing the first negative margin to -25px from -15px fixed the gap.
