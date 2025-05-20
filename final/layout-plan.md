# Layout Plan

## Header
- Small and up: 
  - Reduce margins and padding for `h1`, `nav` elements to kill wasted space
- Medium + Large: 
  - Increase `h1`, `h2`, `li` font sizes for better readability

## Main Content
### First `article`:
- Mobile/Small:
  - Page center all content including unordered list and table 
- Large: 
  - Increase `h2` font size
  - Put image and unordered list into a two column grid layout

### Second `article`:
- Large: 
  - Increase `h2` font size
  - Put image and table into a two column grid layout

### Third `article`:
- Large: 
  - Increase `h2` font size
  - Put image and a section into a two column grid layout

## Footer
- Mobile and Small:
  - vertically stack each link/copyright
- Medium/Large:
  - horizontally align links

## Standard I will follow
**Common Media Query breakpoints:**
* < 481px -> Mobile devices
* 481px — 768px -> iPads, Tablets
* 769px — 1024px -> Small screens, laptops
* 1025px — 1200px -> Desktops, large screens
* 1201px and greater -> Extra large screens, TV

## My Responsiveness using Media Queries
### Header (Flexbox)
- < 481px (Mobile devices)
  - Header title at top  
  - Navigation becomes a vertical list below the “Menu” title  
  - Tap targets enlarged for touch  
  - Simple stacking layout

- 481px – 768px (iPads, Tablets)
  - "Menu" and nav links stack below the header title  
  - Center-align nav links with more spacing

- 769px – 1024px (Small screens, laptops)
  - "Menu" title on the left, nav links on the right in a horizontal line  
  - Reduced padding and font size adjustments for balanced fit on mid-sized screens
  - Flexbox applied only to the second article section as per current allowed scope

- 1025px – 1200px (Desktops, large screens)
  - Full horizontal layout with left-aligned "Menu" and right-aligned nav links  
  - Header title remains at top, spanning full width

- ≥ 1201px (Extra large screens, TVs)
  - More spacing/padding added  
  - Font sizes slightly larger for readability on large screens

### Main Content (Grid Layout)
#### Article 1
- < 481px
  - Fully stacked layout: Image → Caption → Article Text  
  - Adjusted font and margin for mobile reading

- 481px – 768px
  - Image and caption stack above text  
  - One-column layout

- 769px – 1024px
  - Two-column layout introduced: Left = Image + Caption, Right = Text  
  - Adjusted proportions for mid-size screens

- 1025px – 1200px
  - Balanced 2-column layout  
  - Clearer grid spacing and improved alignment

- ≥ 1201px
  - Increased spacing between columns  
  - Larger image and font sizes for big screens

#### Article 2
- < 481px
  - Stacked layout: Text → Table → Right-column Text  
  - Table may scroll horizontally if needed

- 481px – 768px
  - Table still below text on left  
  - Then full right column content below that

- 769px – 1024px
  - Two-column layout  
  - Left: Text + Table | Right: Additional Content  
  - Spacing and width scale up

- 1025px – 1200px
  - Enhanced two-column layout with clean alignment  
  - Table styled to fit within column

- ≥ 1201px
  - More space between columns  
  - Font size and padding increased

#### Article 3
- < 481px
  - Stacked: Image → Tips → Text → Address  
  - Clear sectioning and vertical flow

- 481px – 768px
  - Image above workout tips  
  - Right-side content (text + address) follows underneath

- 769px – 1024px
  - Two-column grid: Left = Image + Tips, Right = Text + Address

- 1025px – 1200px
  - Balanced two-column layout  
  - Better alignment and spacing

- ≥ 1201px
  - Full spacious layout  
  - Roomy tips, larger text, cleaner visuals

### Footer (Flexbox)
- < 481px
  - Fully stacked items: AI Links → Copyright →
    Sitemap  
  - “Back to Top” remains fixed and thumb-friendly

- 481px – 768px
  - Still vertical stacking  
  - Slight spacing between items for touch clarity

- 769px – 1024px
  - Flex layout for horizontal spacing if space allows  
  - Back to Top fixed in corner

- 1025px – 1200px
  - Horizontal footer layout restored  
  - Even padding and alignment

- ≥ 1201px
  - Expanded footer spacing and font sizes  
  - “Back to Top” remains easily accessible