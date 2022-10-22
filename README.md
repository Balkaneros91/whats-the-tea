# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^

---
---
---
# What's the Tea?

What's the Tea? is an idea I came up with just exclusivly for this project. The organization is located in Stockholm. The main goal is to spread positivity, care and love and everyone is welcome no matter the gender. The website presents a Home page with an 'About' and 'Contact & Info' section. The Gallery page is built from a bunch of inspirational lgbtq+ photos. And last but not least the Sign Up page contains the events sign up form.

I was inspired by the RuPaul's Drag Race show created by RuPaul Charles who is the ICON of the LGBTQ+ comunity all over the world. The show has grown a lot and as a member of the LGBTQ+ comunity I wanted to celebrate my pride by creating my first project based on this idea. 

---
![amiresponsive](assets/readme/amiresponsive.jpg)

[View live site on Github Pages](https://nicolemne.github.io/project-portfolio-1/)

---

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---

## User Experience (UX)

Visitors looking for a safe place to share their stories and a good laugh should find this website interesting and charming. We are a charitable organization with a goal of sharing information and helping people to get the answers they are looking for or in case  they need even further help pointing them towards the right direction.  

The front page provides the visitor with a short introduction and the events contacts and info. Besides that they can get some more refreshing and inspiring photos in the webites gallery. 

In case you wanna have some fun and share your story proceed to our sign up page. 

The website is viewable from different screen sizes, so every user can browse the site.

### User Stories

For first time viewers I wanted to make the website visually inticing as well as having a clear understanding what the website is about. Together with the hero image and text, side images and introduction text, the first page quickly suggests that this is a music recording studio. 

If the front page has piqued the viewers interest and they would like to learn more about the studio, they can visit the studio gallery, as well as the social media links in the footer, which are both easily accessible. 

## Design

### Colour Scheme

I've generated a color palette based off of the hero image, which I thought would be a well suited color scheme for the full website. 

[Coolors.co](https://coolors.co/) Is the website I've used to generate the colour palette. I've mainly used a black background, white text and #5E4F46 for underlines, and #091B1D as the footer background.

![Colour Palette](assets/readme/color-palette.png)

### Typography

I wanted to go with a sleek typography, and decided to go with Bebas Neue, Pathway Gothic One and Raleway, all of which I thought fitted well together. 
We can see Raleway being used on the hero image "Studio North". Pathway Gothic One is used as paragraph text, and Bebas Neue as lesser headers.

![Typography](assets/readme/google-fonts.png)

### Imagery

As the studio is located in a rural forest area in northern Sweden, I've chosen to use images that gives a warm and earthy feel. 

### Wireframes

The Wireframes I've made was created for desktop and mobile view. The original design I made has changed slightly, and the images below represent the new changes - which I have also tried my best to implement on the live site. 

I ended up not going for the hamburger navigation menu nor the calendar button in the end and settled for just the submit button and the regular navigation menu. I also rearranged the mobile view for the Home page (index.html), showing the picture of the house first, and the about us section second in the column.

![Wireframe Home Page](assets/readme/wireframes-home.png)
![Wireframe Gallery Page](assets/readme/wireframes-gallery.png)
![Wireframe Contact Page](assets/readme/wireframes-contact.png)

## Features

My website contains 3 pages, index.html which is the home page, gallery.html is the gallery page, and contact.html is the contact page. 

### Finished look of the Home page
![Home Page](assets/readme/home-page.jpg)

### Finished look of the Gallery page
Because my screen is a little bit bigger I've had to crop the images to get full view. 
![Gallery Top](assets/readme/gallery-page-1.jpg)
![Gallery Middle](assets/readme/gallery-page-2.jpg)
![Gallery Bottom](assets/readme/gallery-page-3.jpg)

### Finished look of the Contact page
![Contact Pag](assets/readme/contact-page-1.jpg)
## Footer
![Contact Page footer](assets/readme/contact-page-2.jpg)

### General features on each page

The navigation bar and footer is reappearing on all three pages of my website.

### Future Implementations

I would like to add a calendar to the contact page so a visitor can view when the studio is available to rent.

Another page with more detailed information about what hardware and software they have available at the studio, might be something I would like to add in the future too.

### Accessibility

I have tried my best to be mindful of accessibility, and the steps I've taken for this are the following:

- Descriptive information about every image in the gallery page
- Aria labels to the social media links
- Chose a good colour contrast throughout the website
- Semantic HTML

## Technologies Used

### Languages Used

HTML & CSS.

### Frameworks, Libraries & Programs Used

I've used Gitpod for the actual programming, as well as creating a repository for my project in Github. 

Wireframes were created with Balsamic. 

For the iframe I've used https://google-map-generator.com/.

I've converted all images from avif files to jpg with Microsoft Paint. The header image I've also used Canva for adding a colour tint. Original header picture below. 

![Original header image](https://images.unsplash.com/photo-1612344441107-ef12287e4872?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2664&q=80)

Header image with tint and slightly cropped: 
![Header image with tint](assets/images/hero-bg.jpg)

## Deployment & Local Development

### Deployment

[View live site on Github Pages](https://nicolemne.github.io/project-portfolio-1/)

### Local Development

If you wish to clone my project, please see the following steps below:

1. Navigate to Github: https://github.com/nicolemne/project-portfolio-1
2. Select the 'Clone' button 
3. Copy the url or download as ZIP file
4. Use git clone + the url in your terminal, or unpack the ZIP containing the project

## Testing

I have tested all the links, both in the footer and navigation menu to see that all the links are working. All links to websites open up in a new tab. I have also resized the screen size manually to verify that the media queries are working and that the website is responsive to different screen resolutions. 

The mobile phones I have tested resolution with are: 
- Samsung Galaxy 8
- Iphone 12 Pro
- Blackberry Z30
- Nexus 5

### Lighthouse
![Lighthouse](assets/readme/lighthouse.jpg)

### W3C HTML Validator
![W3C HTML Validator](assets/readme/w3c-validator.jpg)

### W3C CSS Validator
![W3C CSS Validator](assets/readme/w3c-css.jpg)

### Known bugs

No known bugs detected

### Solved Bugs

I've encountered several bugs on the journey of making this website, and most of them I've corrected by seeking help online or from my mentor Mitko. 

Some bugs I've encountered and fixed: 

+ Header
  + Description: Hero text placement
  + Expected behaviour: Header text layered on top of the hero image
  + Actual behaviour: Header text hiding under the hero image
  + Fix: Add code transform: translate(1%, -175%);

+ Footer
  + Description: Footer not sticking to bottom of the page
  + Expected behaviour: Footer sticking to the bottom page of the html
  + Actual behaviour: Padding between bottom of page and footer
  + Fix: Add position: relative; and top 50px as well as top: 120px for media query 1500px

+ Div positioning
  + Description: Wrong position on the three divs on index.html & contact.html
  + Expected behaviour: Divs positioned in a row next to each other
  + Actual behaviour: Divs position was on top of each other or to the side
  + Fix: Flexbox

## Credits

The Love Running project has been a design inspiration for my own project.
The help I've used with syntax and formatting, please see links and description below.

### Code Used

- [How to stick footer to bottom of page](https://dev.to/nehalahmadkhan/how-to-make-footer-stick-to-bottom-of-web-page-3i14)
- [How to position text above an image](https://www.w3schools.com/HOWTO/howto_css_image_text.asp)
- [How to style inputs](https://www.w3schools.com/css/css_form.asp)
- [Cursor in the middle of text area](https://stackoverflow.com/questions/9070924/cursor-in-the-middle-of-a-textarea-box)
- [How to center div inbetween two divs](https://stackoverflow.com/questions/3172738/centering-a-div-between-one-thats-floated-right-and-one-thats-floated-left)
- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Date input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date)

### Content

I have written most content on the website. Some code has been borrowed from other authors, please see Code Used.

###  Media

All images are royalty free and has been taken from
[Unsplash](https://unsplash.com/) and
[Pexels](https://www.pexels.com/sv-se/) plus
some private pictures.
  
###  Acknowledgments

And last but not least a big thanks and loads of kudos to those who has in some way helped me so I could complete my first project:  

- Nedicto Entenza Gutierrez, my husband.
- Antonio Rodriguez, my mentor at Code Institute.
- Sawyer, our cooridinator and mental column.
- Gemma our lovely tutor at Code Institute.
- Kera Cudmore, for the README webinar and this README template.
