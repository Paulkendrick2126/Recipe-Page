# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot
![Desktop Design](<Screenshot 2024-03-20 at 03-26-05 Frontend Mentor Recipe page.png>)


![Mobile Design](<Screen Shot 2024-03-20 at 03.29.44.png>)




### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)



## My process
I started by mapping out the sub-compoment of the project. Broke it down to the simplest element needed. Started with HTML and then Designed with CSS. Got stuck alot of time and i had to do some research and debugging.

1. Setting Up the Files:

Created three files:

# index.html: This was main webpage file containing the HTML structure.
# style.css: This held all the CSS styles for the website.
# reset.css: provided a baseline style sheet to normalize element appearances across browsers, removed default margins and paddings, and set some core defaults for readability and accessibility.


2. Building the HTML Structure:

Open index.html and add the basic HTML structure
Inside the body section of index.html, started adding the content for the recipe
Used different HTML elements for better organization (e.g. span, divs).

3. Basic Styling with CSS:

Open style.css and add some basic styles: Customization:


Styling individual elements with classes.
Adding navigation elements like a header and footer.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Desktop workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

HTML:

Basic Structure: The code used basic HTML tags like <html>, <head>, <body>, <h1> (headings), <p> (paragraphs), <ul> (unordered lists), <li> (list items), and <img> (images) to structure the content.

Inline Images: The <img> tag is used with a src attribute to specify the source of the image file (likely "pancakes.jpg" in this case).

HTML Non-Semantic Tag (div):

``` HTML
 <div class="prep-time">
        <h3>Preparation time</h3>
        <ul>
          <li><span>Total:</span> Approximately 10 minutes</li>
          <li><span>Preparation:</span> 5 minutes</li>
          <li><span>Cooking:</span> 5 minutes</li>
        </ul>
      </div> 
```

Semantic tag: Table 
``` HTML
   <table>
          <tr>
            <td class="nut">Calories</td>
            <td class="nut-value">277kcal</td>
          </tr>
          <tr>
            <td class="nut">Carbs</td>
            <td class="nut-value">0g</td>
          </tr>
          <tr>
            <td class="nut">Protein</td>
            <td class="nut-value">20g</td>
          </tr>
          <tr>
            <td class="nut">Fat</td>
            <td class="nut-value">22g</td>
          </tr>
        </table>
 ```


```css
main{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```





### Continued development


**I would like to work on my Box Model concept and the following. Responsive design, flexbox and grid. various table designs. Also work on my css styling better**



### Useful resources

- [resource 1](https://github.com/LucianFE/recipe-page-main/blob/main/assets/css/style.css) - This helped me for the table concept and responsive design including the reset css. I really liked this pattern and will use it going forward.

- [ resource 2](https://blog.logrocket.com/css-flexbox-vs-css-grid/) - This is an amazing article that helped me get a grasp of Flexbox. I'd recommend it to anyone still learning this concept.

- [resource-3] https://gemini.google.com/



## Author

- Website - [Paul_kendrick](https://linktr.ee/paul_ad)
- Frontend Mentor - [@Paulkendrick2126](https://www.frontendmentor.io/profile/Paulkendrick2126)
- Twitter - [@littlehomiz_ken](https://twitter.com/littlehomiz_ken)



## Acknowledgments

Special shout out to Jojo, CJPanda and the authors of the articles i read, the users on stackoverflow, and the youtube channels.



