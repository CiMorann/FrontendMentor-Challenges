# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Screenshot.](./assets/images/Frontend%20Mentor%20-%20Results%20summary%20component.png)

### Links

- Live Site URL: [Live Web](https://64f2154333c4ae044cca0850--summarysite.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I struggled a bit at the beginning after all the time I had without touching VS Code. Even so, after re-watching a couple videos, going over documentation every time I needed it, achieved the goal.

The first version had divs all around the code. I learned that HTML should be more semantic, always there's the possibility to. Swapped <divs> with <uls> and <lis> and reduced the number of written lines by approximately 30 lines. Also, I learned that font shouldn't ever, ever, ever (can't stress this enough) be in pixels, rather REMs.

Then, I had an issue with the height of the body. The body was a flex container, and I hadn't set the align-items: center property, which caused the height to take all the screen instead of what should've been used.

### Useful resources

- [Why you should use REM instead of PX.](https://fedmentor.dev/posts/font-size-px/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@CiMorann](https://www.frontendmentor.io/profile/CiMorann)

## Acknowledgments

Don't be concerned about stopping for some reason at any point. Whatever is in the way, you can always solve it if you put enough patience.

READ THE CODE, always read what you write, review it. Sometimes the solution to the problem is there.
