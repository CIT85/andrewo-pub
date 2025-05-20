# ThriveCircle

## Why I Chose This Topic
ThriveCircle is a place where users can connect with each other about self-improvement topics like healthy meal recipes, new active hobbies, discovered gym routines, etc. I want to create a new place for people to come together to embrace character and/or physical development. With busy schedules, people can have support and participate in conversations that inspire them to keep going. 

## AI Prompts & Content Samples

### To ChatGPT: 'I want to create a website that connects users who can talk about self-improvement through healthy eating, active hobbies, gym routines, etc. I would like you to give me a name of this website as well as a description.'

ChatGPT: 'That sounds like an awesome community idea! Here’s a name and description to get you started:

**Website Name:** **ThriveCircle**

**Description:**  
*ThriveCircle is a supportive online community where people come together to share their journeys in self-improvement—through healthy eating, active lifestyles, and fitness routines. Whether you're into plant-based cooking, trail running, gym gains, or mindful movement, ThriveCircle is your space to connect, inspire, and grow alongside others pursuing their best selves. Discover tips, swap routines, and stay motivated in a circle that thrives together.*'

I think these different subtopics for ThriveCircle can be easily split into different subpages for the Menu/Website. 

## Menu
* Eating
* Activities
* Workouts
* Community

## Typography Enhancements
- implemented `font-size: 16px;` as a normal consistent font size for the body content.
- `text-align: justify;` to make the page cleaner.
- styled `h1` to have the biggest font of the three headings at `font-size: 3em;` with `text-transform: uppercase;` and `letter-spacing: 3px;`. I also used `text-align: center;` so it sits better at the top of the page.
- `h2` has `font-size: 1.75em;`, `text-transform: uppercase;` and `text-align: center;` to keep that consistency of h1 but just a little smaller.
- `h3` is the smallest with `font-size: 1.15em;` and also differnt than the previous two with `text-align: left;`. It also does not have a `text-transform`.
- I took away the underline effect for `a`, and only applied it to `a:hover` or `a:focus`. I also used different colors for all of them and added a background color for `a:focus`. 

## Decorative or Positional Enhancements
* added a `position:sticky` to `h2` elements to show which article the user is in, since all three articles has a single h2 each. 
* applied `position: fixed` to the "Back to Top" link from the footer
* Added a blockquote next to my first picture and made it `position: absolute` to stand out.

## Phase 3 Overview
* I used Flexbox and Grid to improve the layout of my site. Flexbox was applied as a structure within articles. This allowed for better alignment and spacing between sections. I applied Grid to certain articles (like the Routine article) to organize content side by side.

## New Subpage
* My new subpage "The Mental Battle" is a page that can help with tips and suggestions when trying to overcome the mental warfare that goes on when trying something new and difficult. It is a bit separate then the rest of the other pages, in that its about mental rather than physical. 

## Image Optimization
* The 100% width is responsive to different screen sizes, and fills the space all the way. Although I set the width and height attributes to the images, and used height:auto for responsiveness, I think I may be missing an aspect-ratio in the CSS. When large, the images are very pixelated. 

## Accessibility
* “Skip to main content” link at the very top of the page for keyboard users.
* Better keyboard `:focus` styles to make sure my CSS clearly highlights interactive elements (like links) when using the keyboard.
* I want to use a contrast checker to ensure all of my text/background color combos are readable for users with low vision.
* Consistent heading levels: Some of my <h3> tags (visually-hidden headers)jump around sometimes. I want to make sure I'm not skipping any <h2>'s.

## Hero Image Design
* I chose this image because I feel it is a good representation of "thriving" and "circle". It seems social, and also like taking figurative (and physical)steps towards a better version of yourself/themselves. It appears on the home page, the index.html, since that is where the big opening greeting is. They kind of go good together. I felt the 80vh was a decent size, and not too huge. And I like the little bit of background shading to the h2 content that sits on the image. You can still see the image, and it helps 'pop' the text out for readability. 