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

- Solution URL: [Add solution URL here](https://github.com/rame0033/practice_pages/tree/main/front-end_mentor_p8)
- Live Site URL: [Add live site URL here](https://rame0033.github.io/practice_pages/front-end_mentor_p8/)

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- Flexbox
- CSS Grid

### What I learned

I learned how to do the progress bar by using div, and span to put the fill in the bar

To see how you can add code snippets, see below:

***HTML
'
<!-- Progress bar -->
      <div class="progress_bar">

        <!-- Bar Fill -->
        <span class="fill"></span>
      </div>

`

To be able to do the circle indicator inside the progress bar, I used the pseudo-code '::after'.

I included the code snippet of the value for the 'span::after'

'
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
`

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
