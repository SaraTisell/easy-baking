# Easy Baking

Easy baking's website provides its users with delicious baking recipes that are well structured and easy to follow. Easy Baking is highlighting the Swedish concept of "fika" and gives a broad insight in its meaning - gathering to enjoy pastry and coffee/tea. The site is targeting anyone who has the desire to bake and want some inspiration.
[Here](https://saratisell.github.io/easy-baking/) can you view the site.

![Mockup](document/images_readme/easy-baking-mock-up.png)

## Design

### Color scheme

![Colorscheme](document/images_readme/easy-baking-color-scheme.png)

### Typography

Sans-serif fonts were imported from Google Fonts
The choosen fonts will give advantage for the site due to its clean look due and its accessibility.
<br>

* Voltaire - Headings and Menu
* Signika - Paragraps

### Wireframes

![Wireframe](document/images_readme/easy-baking-wireframe.png)

## Features

### Site Wide

#### Navigation

The header will contain the sites main navigation for an good user experience

* Logo will be clickable and linked to the home page.
* Menu will contain links to Home page, Recipes page and Contact page.
* This will give the user easy navigation thorug all pages.

![Header](document/images_readme/header.png)

#### Footer

* Will contain links to social media websites that will be displayed with icons, and provided with aria labels in order to increase accessibility.
* All links will be opened in a new tab, to avoid users leaving the site.

![Footer](document/images_readme/footer.png)

#### Favicon

* A favicon with the same cupcake-design that shows in the logotype will be added to increase the users experience and make it easier to recognise the site if they have several tabs open.

![Favicon](document/images_readme/favicon.png)

#### 404 Page

* A 404 page will be implemented and designed to match the genral design of the site.
* If a user navigates to a broken link will the 404 page appear and give the user easy access back to the home page.

![404](document/images_readme/404.png)

#### The Home Page

* Will contain a short and consist description what the user can expect from the site.
* The user will find some tips for their baking, regarding flavour combinations and they will be able to read about the 'Fika' concept.

![Home](document/images_readme/landing-page.png)
![Fika](document/images_readme/about.easybaking.png)

#### The Recipes Page

* Will contain six different recipes with proper description for ingredients and a detailed description how to make it.
* The goal of the varierity is to gain an opportunity to offer something for every user.

![Recipes](document/images_readme/recipe.png)

#### The Contact Page

Will contain a contact form that allowes users to contact Easy Baking regarding any questions or thoughts they may have. <br>
 The form will include the following fields:

* First Name
* Last Name
* Email Address
* Message

* All fields will be required.
* When the contact form have been succesfully submitted the user will be navigated to thanks.html that shows a 'Thank you message'
* A meta tag will be implemented on thanks.html to atomatically send the user back to home page after 10 secunds.

![Contact](document/images_readme/contact-form.png)
![Thanks](document/images_readme/thank-you.png)

#### Features

##### Existing

* Responsive design
* Easy navigation and well structured
* 6 well described recipes
* Contact form and Thank you page

##### Future

* Reduce the visible content for 'How To' on recipes to let the user decide when to show and hide a section.
* Add more recipes.
* Add videos showing how to make the recepies in favour to the users that may need more instructions than just text.
* Implement a chat forum for the visitors to use to interact with eachother
  * A session based chat, no need for sign up
  * Where ideas and thoughts can be exchanged
  
## Technologies Used

* HTML
  * The main language to develope the structure of the website
* CSS
  * All styling for the website was written with custom CSS in style.css
* Codeanywhere
  * IDE used to develope the website  
* GitHub
  * To source code and deploy using Git Pages
* Git
  * Used to commit and push code from IDE during the development
* Balsamiq
* <https://balsamiq.com/wireframes/desktop/#> Used to design wireframes
* Canva
  * <https://www.canva.com/> Used to design logo, favicon and resize images
* Favicon.io
  * <https://favicon.io/favicon-converter/>  Used to create favicon files  
* Freeconverter.com
  * <https://www.freeconvert.com/png-to-webp> Used to convert png images to webp
* Pixelied.com
  * <https://pixelied.com/convert/png-converter/png-to-webp> Used to convert png images to webp
* Font Awesome
  * <https://fontawesome.com/> Used to implement icons
* Google Fonts
  * <https://fonts.google.com/> Used to import fonts

### Languages

* HTML
  * To develope website structure
* CSS
  * To give the website custom styling

## Testing

This website was tested on these browsers:

* Chrome
* Firefox
* Microsoft Edge

No issues was found.

* Responsive throug all pages
* Navigation work, NO broken links
* Contact form works
  * Navigation to thanks.html when successful submission
  * Required attribut works
* Font sizes and colors were correct and easy to read

### Lighthouse Testing

![Lighthouse-desktop](document/images_readme/test.desktop.2.png)
<br>
![Lighthouse-mobile](document/images_readme/testing-mobile.png)

### W3C HTML Validator

Html Validator showed no error

![html.index](document/images_readme/html.index.png)
![html.recipes](document/images_readme/html.recipes.png)
![html.contact](document/images_readme/html.contact.png)
![html.thanks](document/images_readme/html.thanks.png)
![html.404](document/images_readme/html-404.png)

### W3C CSS Validator (Jigsaw)

Css Validator showed no error

![css.index](document/images_readme/css.index.png)
![css.recipes](document/images_readme/css.-recipes.png)
![css.contact](document/images_readme/css-contact.png)
![css.thanks](document/images_readme/css-thanks.png)
![css.404](document/images_readme/css-404.png)

### WAVE

Wave accessibility evaluation tool showed 1 error on contact.html

![wave.index](document/images_readme/wave.index.png)
![wave.recipes](document/images_readme/wave.recipe.png)
![wave.contact](document/images_readme/wave.contact.png)
![wave.thanks](document/images_readme/wave.thanks.png)
![wave.404](document/images_readme/wave.404.png)

### Unfixed Bugs

WAVE <https://wave.webaim.org/> showed one contrast error on button for contact form in contact.html.
The color for button were changed from #ffffff to #40393A without any success to fix the error for contrast.

## Deployment

  The site was deployed to GitHub pages. The steps to deploy are as follows:

* In the GitHub repository, navigate to the Settings tab
* From the menu on left select 'Pages'
* From the source section drop-down menu, select the Main Branch
* Click 'Save'
* A live link to the live website will be displayed

The live link can be found here - <https://saratisell.github.io/easy-baking/>

## Credits

### Code

* <https://codepen.io/sarus/pen/PJGPmy>
  * Code borrowed from this page to put images in a row.

* <https://stackoverflow.com/questions/38903300/how-to-i-have-text-partially-overlay-my-image>
  * Code borrowed to display text over image by using flex-box and relativ position.

* Love Running Project
  * HTML - How to add a favicon
  * HTML - Social Network links
  * CSS - Asterisk wildcard selector to override default styles added from the browser

### Content

* <https://www.allrecipes.com>
  * Recipes were borrowed from this site

### Media

Images for content were borrowed from these sites

* <https://www.pexels.com>

* <https://unsplash.com>

* <https://www.canva.com/>
