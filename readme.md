## Table of contents

- [Overview]
  - The challenge is to build out this interactive turist guide page and get it looking as close to the design as possible.
- My process: It took me 5 days to build this.
  - Built with: HTML5 and CSS3.
  - What I learned: I learn a lot about flex-box container and your properties, how to use animations, I have also learned more how to built a responsive page.
  - Continued development: I have to continue practice how to use the responsive page, animations on css, flex-box and javascript. 
- Author: Natali Marinho. 
- Acknowledgments: css and html.
- Deploy's link: https://natsmarinho.github.io/flex-turismo/


### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size 
- See hover states and animations for all interactive elements on the page

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned


```css
#first-img{
transform: translateX(50px);
animation-name: slide;     
animation-duration: .5s;
animation-fill-mode: forwards;
animation-timing-function: ease;
}

#sec-img{
    transform: translate(-50px);
    animation-name: slide;
    animation-duration: .5s;
    animation-fill-mode: forwards;
    animation-timing-function: ease;
}

@keyframes slide{
    from{
        opacity: 0;
   
       }
    to{
     opacity: 1;
     transform: translateX(0);
    }
}
```
```css
@media(max-width: 992px){
    .flex-container{
        flex-direction: column;
    }
```
### Continued development

I want to learn more about flex-box, animations and javascript.

### Useful resources

- [Css animation - mini tutorial (canal Origamid)](https://youtu.be/zWmaohjrkRw) - This helped with the animation of the image. 

## Author

- Twitter: [@friidakhlo](https://www.twitter.com/friidakhalo)
- Instagram: [@natsmarinho](https://www.instagram.com/natsmarinho) 
- Linkedin: [@natsmarinho](https://www.linkedin.com/in/natsmarinho/)

## Acknowledgments

In this project I would like to thank at Digital innovation one, because the let us study more and get more knowledge, and I would like to thank you at Karen Santos for bring us so much knowledge. 
