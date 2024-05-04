# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Screenshot

![](./screenshot.jpg)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

With this challenge I learned how to use the srcset property of an IMG to display different images depending on the device.

```html
      <img  
        class="image-product"
        srcset="./images/image-product-mobile.jpg 686w,
                ./images/image-product-desktop.jpg 600w"
        sizes="(max-width: 375px) 380px, 600px"
        src="./images/image-product-mobile.jpg"
        alt="Image of Product" />
```
## Author

- Frontend Mentor - [@osenprema](https://www.frontendmentor.io/profile/osenprema)