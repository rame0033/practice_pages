# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot/Screenshot%202024-05-14%20151834.png)

### Links

- [Solution](https://github.com/rame0033/practice_pages/tree/main/front-end_mentor_p8)
- [Live Site](https://rame0033.github.io/practice_pages/front-end_mentor_p8/)

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- Flexbox
- CSS Grid

### What I learned

I learned how to do the progress bar by using div, and span to put the fill in the bar

To see how you can add code snippets, see below:

### HTML
      <!-- Progress bar -->
      <div class="progress_bar">

        <!-- Bar Fill -->
        <span class="fill"></span>
      </div>

### CSS
To be able to do the circle indicator inside the progress bar, I used the pseudo-code `::after`.

I included the code snippet of the value for the `span::after`.



        /* Add the indicator to progress bar fill */
        .progress_bar span::after{
            content:'';
            background-color:var(--PaleBlue);
            height:inherit;
            width:1rem;
            right: 20%;
            position:absolute;
            border-radius: 50%;
}



### Continued development

Adding the tip to the quota box is a bit challenging for me so I did use for now a CSS polygon generator. I tend to practice in doing the polygon so I will be able to do it by myself in the future

### Useful resources

- [CSS Clip Path Generator](https://www.cssportal.com/css-clip-path-generator/) - This helped me for making the tip of the quota box.

- [Box-Shadow CSS](https://cssgenerator.org/box-shadow-css-generator.html) - This is a tool I use to easily manipulate box-shadow for elements.

## Author

- Frontend Mentor - [@rame0033](https://www.frontendmentor.io/profile/rame0033)