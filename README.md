# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Author](#author)


## Links

- Solution URL: [https://github.com/macdeesh/QR-code-challenge]
- Live Site URL: [https://macdeesh.github.io/QR-code-challenge/]

## My process

## Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


## What I learned

In the beginning i did the Mobile-first workflow, then a media query for desktop but after having some comments from the community in Slack i realized that this challenge doesn't need a media query at all. I start also by making flex-box and grid but couldn't get the result proposed by the challenge, then i tried something more simple so it worked very well. This challenge wasn't difficult at all but my approach to it by trying to apply what i learned changed to something complicated. I learned to make things really simple when it needs to be.  
I learned also about the Fallback color because when i just used the reference of color proposed by the challenge in hsl: **{background-color: hsl(212, 45%, 89%);}** Atom editor showed an error massage saying: **"Fallback background-color (hex or RGB) should precede HSL background-color"**. So i figure out the same color hexadecimal code by using the HTML Color Picker in w3schools.com.
I learned also to not use % for border radius. That will always go strange because percentage height on one axis is bigger than percentage width on the other axis. Also  that i should remove all the % widths i'm adding especially in the media query. But in this case i do not need a media query, all i need is a max width (preferably in rem) on the container.

## Author

- Frontend Mentor - [@macdeesh](https://www.frontendmentor.io/profile/macdeesh)
- Twitter - [@Mac Deesh](https://twitter.com/Macdiish)
