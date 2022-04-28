# MOON MEDITATION 
Moon Meditation is a website for anyone curious about meditation techniques. This page will give information to it's users about working with the lunar phases and their energy. 

Welcome to [Moon Meditation](https://delayrider.github.io/moon-meditation.github.io/)!

![Am I Responsive screenshot](/docs/images/am-i-responsive.png)

# User Experience UX
## User stories
   - Users want to understand at first glance what the page is about
   - Users want to learn about moon meditation
   - Users want to know what are lunar phases
   - Users want to understand the properties of each lunar phase
   - Users want to start building a meditation practice
   - Users want to find out more about the topic through external links

# Design
- Hero image
  - The hero image was chosen on [Stockvault](https://www.stockvault.net/)
  - The choice of the hero image was made concidering the content of the website. Purple being associated with mysticism. 
  - The general atmosphere of the image is very calming and goes well with the subject of the page
- Color palette
  - The color palet for this website was chosen by running the hero image through [Color Picker](https://imagecolorpicker.com/en)


# Current Features
 - Navigation bar
   - The navigation bar is the same throughout the all four pages. 
   - The navigation bar elements are styled to highlight when the user hovers over them. This gives the user feedback as to where he can click. 
   - The active page is highlighted to give user feedback as to what page is currently being viewed.
   - The logo is linked to bring the user back to the home page. This does not highlight for esthetical purposes. 

![Navigation bar screenshot](/docs/images/nav-bar.png)

- Hero image and overlay
  - All four pages have the same hero image.
  - The image was chosen to reflect a calm and mystical feeling. The colour purple being associated with mistycism made the image a good fit for the style the page is going for. The clouds surrounding the moon give a nice "this to shall pass" vibe to the page which is very in tune with the main goal of mediation: letting go. 
  - The overlay on the hero image give site specific descriptions to what the page is about.

![Hero image screenshot](/docs/images/hero-image.png)

- Build a practice section
  - Instead of using a list to explain the four key notions of meditation, it was decided to go with four blocks. This makes the page more attractive and fun to look at. 

![Build a practice screenshot](/docs/images/build-a-practice.png)

- Lunar phase collapsible descriptions
  - Describing the eight lunar phases in one block of text separated by heading elements would have overcrowded the page with text thus reducing the overall user experience. 
  - In an effort to make the page more user friendly and interactive, collapsible texts were added for the descriptions of the lunar phases. 

![Lunar phase collapsible screenshot](/docs/images/moon-phase-collapsible.png)

- Lunar phase emojis
  - To illustrate what each lunar phase looks like to the user, emojis were custom made for each phase. 
  - Due to limited time and skill these are imperfect and will not render on small screen. For more information about this please refer to the bugs section. 

![Lunar phase emoji screenshot](/docs/images/moon-phase-emoji.png)

- External links highlight on hover
  - To give the user feedback on where to click to open the external links, the higlight on hover feature was added.

![External links screenshot](/docs/images/external-link.png)

- Guided meditation video 
  - The video was embedded from [youtube](https://www.youtube.com/) to give the user an idea to what lunar meditation is about.
  - The video was give the ```controls``` attribute for it not to play when page is loaded

![Guided meditation video](/docs/images/guided-meditation-video.png)

- Sign up form
  - Users can sign-up to a monthly news letter to recieve a monthly news letter.
  - The gradient used in the form background was used to reflect the hero image.

![Sign up form screenshot](/docs/images/sign-up-form.png)

# Future Features

- Home page text
  - In a future release the main text on the home page will be more alive. Imagery can be used to give the paragraphs life. 

- Lunar phase emojis
  - In a future release the lunar phase emojis will be all styled in a more conform way
  - They will also appear for small screen sizes

- Sign-up form
  - In a future release the sign-up form will be more inviting. A few icons and or images decorating the form could make it more engaging to users.

# Technologies used
- Languages used
  - HTML
  - CSS

- Frameworks and programs
  - [Gitpod](https://gitpod.io/workspaces) for editing.
  - [Github](https://github.com/) for storing and deployment.
  - [Google Fonts¨](https://fonts.google.com/) for sourcing the fonts.
  - [Font Awesome](https://fontawesome.com/search?q=moon&s=solid%2Cbrands) for incons.
  - [ColorPicker](https://imagecolorpicker.com/en) to create the palette of the website.
  - [DevTools](https://developer.chrome.com/docs/devtools/) for testing while developping the site
  - [DevTools Lighthouse](https://developers.google.com/web/tools/lighthouse) to check performance, accessiblity, best practice and SEO ratings.
  - [W3C Validator](https://www.stockvault.net/) to test HTML.
  - [Jigsaw Validator](https://jigsaw.w3.org/css-validator/) to test CSS.
  - [Ezgif](https://ezgif.com/jpg-to-webp) to compress .png hero image to .wepb

# Testing

## Validator testing

- W3C Validator
  - All four HTML pages came back with no errors
- Jigsaw Validator
  - CSS came back with no errors
- Lighthouse score for mobile
  - The original score for performance was 89 because the size of the touch navigation element was not big enough. The score was brough up by making these bigger.

![Lighthouse score mobile](/docs/images/lighthouse-mobile.png) 

- Lighthouse score for desktop
  - The original score for SEO was 79. The score was brought up by adding a description in the meta tags.

![Lighthouse score desktop](/docs/images/lighthouse-desktop.png) 

- [A11y](https://color.a11y.com/Contrast/) was used to test the color contrast for accessibility.

![A11y screenshot](/docs/images/A11y-validator.png)

## Responsive Testing

The DevTools were used during the entire developpement to test responsiveness of the website. All the screen sizes available in DevTools were tested.

## Manual Testing

Manual testing was carried out on the website for all features

- Naivigation bar and logo
  - All internal link led to their respective pages
  - The logo leads user back to the home page
  - The navigation links highlight when hovered over
  - The page currently being visited is highlighed in the navigation bar
  - The navigation bar and logo resize appropriately to the max-width of the display in use

- Hero image and overlay
  - The hero image is large enough not to appear pixelated on large screens
  - The hero image was converted from .png to .webp to make the loading time shorted
  - The overlay shows on each page
  - The overlay gives clear information to user about the content of page
  - The overly is resposive to all screen sizes

- Build a practice
  - The contrast between background text/icons is good
  - The icons load from the Font Awesome script with no issues
  - The layout of the blocks is responsive on all screen sizes

- Lunar phase collapible description
  - All eight collabisble texts can be shown by clicking on their respedtive labels
  - The feature works on all screen sizes
  - Styling is consisten for all screen sizes

- Lunar phase emojis
  - The emojis illustrate the lunar phases accurately
  - The user unserstands the lunar phase as it can be seen in the sky
  - The emojies are as consistent as possible in style 
  - The emjois do not hinder the collapsible text feature
  - The emjois are created within ```<span>```element to maintain valid HTML
  - The emojis are removed for xs screen sizes as they disrupt the collapsible text feature

- External link highlight when hovered
 - The external link highlight when hovered on with a mouse or when tapped with a finger
 - The external link leads to the correct website
 - The external link opens in a new tab

- Guided meditation video
  - The video has controls and is not played automatically when page is loaded




# Bugs

- Gibbous moon phase emoji : current
  - In the gibbous moon phase emojis there seems to be the border of the div still showing after addin the inset box-shadow. This will be resolves in a future release
  - This bug does not hinder the flow and performance of the site and is only an esthetical problem.

![Gibbous moon emoji bug](/docs/images/gibbous-moon-emoji-bug.png)

- Collapsible text bug : fixed
  - In the process of developing the collabsible text feature a bug appeared where not matter what collapsible label was clicked only the first text would unfold.
  - This was solved by giving each label unique ```id``` and ```for``` attributes.

- Navigation bar bug : fixxed
  - In the process of developin the navigation menu a bug appeared when trying to float the list elements to the top left of the screen. The ```li``` elements lost their original order.
  - This was fixed by using ```#menu{ float: right; }``` and ```#menu li { float: left}```

# Deployment 
- This project was developped using Gitpod, then commited to git and pushed to GitHub

The site was deployed to GitHub Pages from the repository by taking the following steps

  1. From GitHub navigate to the main page of the repository
  2. Select the "settings" cog underneath the repository name
  3. In the sidebad, under "code and automation" select "pages"
  4. Once in GitHub Pages select the publishing source from the dropdown menu
  5. Then click save
  6. The deployed site will update automatically with ever push made from Gitpod to GitHub

To run the code locally the following steps need to be taken
  1. From GitHub navigate to the main page of the repository
  2. Select the "code" button above the file list
  3. Choose HTTPS, SSH or GitHub CLI and click the clipboard incon to copy
  4. In your editor open the terminal
  5. Change the current working directory to the location where you want the cloned directory
  6. Type ```git clone``` and paste the URL you just copied
  7. Press "enter" to create you local clone



# Credits

- Tutorials and posts
  - [This](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) absolute gem of a blog post by [Chris Coyier](https://css-tricks.com/author/chriscoyier/) was refered to through the entire project for all questions I had regarding the ```flex-layout```
  - The collapsible feature was only possible to implement thanks to [this](https://www.youtube.com/watch?v=RvpYnUZRquw) tutorial by [Enhance Coding](https://www.youtube.com/channel/UC7Taam_8Qri6Rr_zo3RmKJw)
  - The moon emojis were implemented with the help of [this](https://www.youtube.com/watch?v=kG_x15yhtBQ) tutorial by [SoySudhanshu Codes](https://www.youtube.com/channel/UCX-YPTfZcKPZP7_XAA5zEsg) as well as [this](https://www.codegrepper.com/code-examples/css/how+to+make+semi+half+circle+css) blog post by [JérômeW](https://www.codegrepper.com/profile/jrmew)
  - The Love Running Project from [Code Institute](https://codeinstitute.net/global/) was used to help implement the sing-up.html submit button.
  - The Love Running Project from [Code Institute](https://codeinstitute.net/global/) was also used to help implement the navigation bar. 







