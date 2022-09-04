# Book-Club-UI
High-fidelity prototype redesigning a book club website including a registration form which was coded in HTML, CSS and JavaScript. I have demonstrated common design principles and taken web accessibility into consideration. 

* Used css selector names for custom color and custom background colour. 
* Used a button to trigger the registration form modal. 
* Used Gestalt principles: Common Fate, Proximity, Colour, Balance, Emphasis, Unity, Colour
* Included a logo.

![Book-Club-UI](Book-Club-UI.png)

## Report
### Quality of User Experience
- I have redesigned the original homepage of the book club website to look more professional, clean, and minimalistic. 
- I have made the design much more accessible, easy to digest the information visually, and simple to use.
- A user should be able to view the home page of the website and fill in the form to register a new book group. 

### User Experience: 
**Accessibility**
- Colour contrast: I have based my UI around a featured colour #26252d which is a dark purple, almost near black. I decided to use this colour as a background to give a sense of a “dark theme”, which in contrast to the text, which is a brighter white colour, gives a very high contrast ratio of 15.16:1 foreground to background. Since this contrast ratio is higher than the recommended 4.5:1 for normal text, this means that the foreground is very easy and clear to see against the background through a variety of text sizes, from small, normal to large, and inclusive of graphical objects and user interface components such as form input fields.
- The colours chosen should not have a drastic impact for the colour blind.
- Images: I have included alt texts for each of my images. This gives accessibility to the visually impaired through the use of text-to-speech. Also if the image is broken, the alt text would still be displayed giving a description of what the image is.
- Text: The text size I have chosen are a good size as the text is not too small and not too large to read.
- The background image also scales depending on the size of the screen, so it can adapt to different screen sizes such as desktop, laptop, tablets.
- Forms: each form field has an associated label.
- All the buttons are able to be accessed via a keyboard.
- Page has a suitable title and also a favicon using the logo placeholder. 

## Gestalt Principles
**Common Fate**
- The only element that has been programmed to “move” is the modal for the form. This is because once a user clicks the “Register” button, the modal pops up, and the user can also exit the form by clicking on the “x” at the top right corner of the modal box which returns the user to the page they were previously on. The separate elements in the form: The User Details, Addresses and Contacts all share the same fate: that they both have the same beginning, and the same end. 

**Proximity**
- This is shown through the links to different pages at the top of the page being right next to each other so that they are grouped together to make the navigation bar. These links all are the same font size, and styled the same
way.
- The logo placeholder is also right next to the name of the website so together they represent the image of the website at first glance.
- The main content of the home page: the BDP header, the short description of what BDP is and the register button are also in close proximity, so they are grouped together.
- In the form, proximity is shown through the grouping of the User Details, Addresses and Contacts, which are separated by their corresponding headers. 

**Balance**

I have achieved a sense of balance through the minimalistic look of my website.
- Symmetry:
  - The main contents of the home page have been positioned to be in the centre of the page. The text has been aligned to the center, the “Register” button is centered.
  - There is an even amount of padding on each side of the buttons.
  - The register form is also positioned to be centered on the screen, with the input fields spanning an even and symmetrical amount of space on the form. 
- Asymmetry:
  - The design of the form has some slight asymmetry as the text and labels of each input field is to the top left of each input field. This is because the eye naturally reads text from top to bottom, left to right.
  - The navigation bar is also asymmetric with uneven weighting of text and elements on the left compared to the right. 

**Emphasis**

There are multiple elements I have chosen to emphasise, these can be narrowed down to:
- Contrast:
  - The contrast between the dark assigned colour to the white text, makes the text stand out a lot, putting emphasis on the text.
  - The green accent colour to highlight “actions” or buttons that the user can click.
  - When a user hovers over the navigation bar options, the background colour of the tab changes colour from #26252d our given colour, to white. This drastic change is a huge contrast and makes it recognisable as something the user can click. 
- Placement:
  - I have placed emphasis mainly to the center of the home page because that is where I put most of the information and that there is a large header of the name of the organisation. This is because the eye will look at larger, central objects first. 
- Isolation:
  - The home page content is isolated to be only in the center of the page. This makes it easy to allocate and look at on initial glance. 
  
**Unity**
- This principle has been supported through the use of a cohesive colour scheme.
- I have also used the same font throughout the entire website.
- The buttons and form input fields also have consistent formatting through the use of CSS so everything looks good and in unity. 

**Colour Scheme for Main Page and Form**
- Using my given colour #26252d, a very dark purple, I contrasted it with white, and an accent colour of a mid-tone green. I chose green because it near opposite (complementary) to the colour wheel of purple which gives good contrast but also goes well together.
- These three colours together, along with the accompanying background image of a gorgeous architecture of a library building filled with books, gives a certain aesthetic and a “dark academia” vibe to the website. The colours green, dark purple and white are also present in the background image, which cohesively ties in the colour scheme of the page. I have also used the assigned colour as a text drop shadow colour, giving the text more depth and contrast from the background.
- The colour scheme has also been used in the logo, which is a simple design representation of a book, with the book being the assigned colour and the background the green to match the website’s accent colour.
- For the form, I used the background colour #26252d to emphasise the use of the assigned colour as a background, which is in contrast to the white text and input field boxes. The submit button is the green accent colour. This is an example of carrying through the “dark” theme, which is also present in the top navigation bar.
- The assigned colour has been used throughout the webpage through the CSS class selector. 

## References:
Bookshelf image:
https://cdn.pixabay.com/photo/2020/05/15/16/32/trinity-college-library-5174182_1280.jpg

Code adapted from W3schools website (CSS, JS, HTML)
https://www.w3schools.com/

Font from Google Fonts: Mate SC
https://fonts.googleapis.com/css?family=Mate+SC
