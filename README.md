![art/-ora logo](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/wireframes/Union.png "Art/-Ora logo")

# ART/-ORA MEDIA WEBSITE

## DESCRIPTION

This is the hypothetical consumer-facing media website. Its purpose is to create a sense of community that allows artists to connect locally. They will have the option to either collaborate or showcase their works of art. 
The website is made up of 5 pages:

-   Landing page: Introduces the main brand and information to the user.
-   Discover page: Showcases existing art projects uploaded by artists in the user's local area.
-   Join page:  Presents the user with a sign-up form.
-   About page: Explains the company’s values and ethos.
-   Coming-soon page: Informs the user that there are more pages to come.

## DEPLOYMENT AND LIVE DEMO

The site has been deployed to GitHub and is accessible on [github pages](https://gerakas.github.io/Art-Ora/).

## CONCEPT

A detailed concept design process was undertaken to oversee the structure/ layout of the site and ensure proper organization of content on both desktop and mobile view.

The final version of each pages concept can be found [here](https://gerakas.github.io/Art-Ora/wireframes/Page-concepts.pdf).

## UX

### Brand and Visual Identity

For this project, a  simple design process was undertaken to come up with a minimalistic yet timely logo that will allow for a memorable and easily recognizable brand. This logo will ensure an overall consistent theme and feel of the website through its basic and modern design. 

The design process started with applying a variety of different font styles to the brand's name in order to create a mixture of options to pick from.

![logo fonts](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/logo_fontsPNG.PNG "Logo Fonts")

Once the top 5 font styles were picked, basic minimalistic shapes were added onto them to complement the style and to create a more finalized feel.

![logo shapes](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/logo_shapes.PNG "Logo Shapes")

The visual identity of the website is represented by 2 main fonts: Montserrat for titles and headers, and Roboto for content. The logo relies on a simple square which in turn engulfs the title text that has an applied font of "Chonburi". The background can be found as either white or black with a large percentage of it making use of negative space for clear recognizability.

### User Experience

The website is responsive across most screen resolutions, adapting its layout and content based on screen-size for ease of use while maintaining a similar structure for brand recognizability.

![landing page screen sizes](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/landing_screens.png "Landing Page Screen Sizes")

![discover page screen sizes](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/discover_screens.png "Discover Page Screen Sizes")

Minimal colours are used throughout the header and footer, providing anchor points for the user to differentiate between the core structure of the page and to the pages' content. The body itself creates a contrast to the header and footer by conveying a colourful and bright aesthetic which in return emphasizes a more creative and vibrant community.

![website header](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/header.PNG "Website Header")

![website footer](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/footer.PNG "Website Footer")

## FEATURES

The site uses numerous features, many of which were pulled from the bootstrap library.

-   Navbar, Nav links & Toggler allow for a simpler and more straight forward navigation system. For both desktop and mobile/tablet view.
-   Search bar (although not functional at this stage) allows users to navigate and lookup existing content.
-   Forms to receive and store data directly inputted by a user.
-   Cards to provide a clear separation between content and a flexible layout that adapts to different screen resolutions.
-   Containers and Bootstraps grid system for fluid-like layouts that respond accordingly to screen size.

## TESTING 

The site has been tested using various platforms to ensure proper display and responsivness.

[W3C Markup Validation Service](https://validator.w3.org/) validated all the html files.
[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) validated the style.css file.
[Pingdom](https://tools.pingdom.com/) tested the website's speed. Which 

### Issues 

-   W3C CSS Validator's results came back with 3 errors regarding the "blur(5px)" value from the "backdrop-filter" property. All 3 errors read as "Property backdrop-filter doesn't exist : blur(5px)", which is incorrect as the value does indeed affect the element it's targeting and therefore exists.

![css validation results](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/css_validation_results.PNG "CSS Validation Results")

-   Pingdom results cambe back as "Performance Grade: B 81"

![pingdom results](https://raw.githubusercontent.com/Gerakas/Art-Ora/master/assets/readme%20file/pingdom_resultsPNG.PNG "Pingdom Results")

### Removed Features

- Initially, the aim was to have something of a hover effect happen over the content cards in the discovery.html page, where when a user decided to hover over a card, the title and description of said card would appear alongside a background blur that would make the background image darker. This hover effect would then disappear once the user hovers off of it, leaving only the background image of each card visible. This feature was dropped as it could not be accomplished without the necessary skills and knowledge acquired outside of the scope of this project.

## SCALABILITY 

-   Add more content in order to create a better sense of community.
-   Implemet a functioning search bar for an efficient naviagtional system throughout the website.
-   Work on the About.html page and the contnet it provides.
-   Create pages for every link provided in the footer section.
-   Implement a default profile page for each user that fills out the sign-up form in the join.html page.

## TECHNOLOGIES

### Languaes and Frameworks

- HTML
- CSS
- BOOTSRAP
- FIGMA

### Tools and  Platforms Used

- [Figma](https://www.figma.com): Used to create web-page concepts and the brand logo.
- [Gitpod](https://www.gitpod.io/): IDE used for creating and editing code.
- [Unsplash](https://unsplash.com/): Used for all the images on the website.
- [Font Awesome](https://fontawesome.com/): Used for all icons throughout the site.
- [Google Fonts](https://fonts.google.com/): Roboto and Montserrat fonts imported from google fonts.
- [Hover.css](https://ianlunn.github.io/Hover/): Used for a hover effect on the landing page "Sign-Up" button.
- Responsive Viewer: Used to test site at different screen resolutions.
- [TinyPNG](https://tinypng.com/): Used to compress images.
- [Favicon Generator](https://www.favicon-generator.org/): Used to generate a favicon icon for the website.
- Adobe Photoshop: Used for editing the background image of the landing page.
- [Pingdom](https://tools.pingdom.com/): Used to test the website's speed.
- [PDFcandy](https://pdfcandy.com/png-to-pdf.html): Used to convert PNG's exported from Figma into a PDF format.
- [W3C Validator](https://validator.w3.org/): used to validate HTML code.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): used to validate CSS code.

## ACKNOWLEDGEMTS 

-   Many thanks to [Felipe Alarcon](https://github.com/felipe-alarcon) for his insightful feedback and advice.
-   Many thanks to [Code Institute](https://codeinstitute.net/) and the slack community for their unmatched support.

