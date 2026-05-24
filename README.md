# Photo Editor 

An interactive **CSS-only Photo Editor** built using **HTML5 and CSS3**.
This beginner-friendly project demonstrates how various **CSS filter properties** can be used to create image editing effects without JavaScript.

**Live Demo:**
[https://madhushreerasal.github.io/Photo-Editor/](https://madhushreerasal.github.io/Photo-Editor/)

## Features

* Apply image filters using CSS
* Interactive filter controls using radio buttons and labels
* Pure HTML and CSS implementation
* Responsive filter layout using Flexbox
* Dark-themed interface
* Multiple preset image effects

## CSS Concepts Practiced

This project was created while learning and experimenting with:

* CSS `filter` property
* `brightness()`
* `blur()`
* `contrast()`
* `grayscale()`
* `hue-rotate()`
* `invert()`
* `opacity()`
* `saturate()`
* `sepia()`
* `drop-shadow()`
* Hidden radio inputs with labels
* Sibling selectors (`~`)
* Flexbox
* Grid layout structure
* Form styling using `fieldset` and `legend`

## Technologies Used

* HTML5
* CSS3

## How It Works

Each filter option is connected to a hidden radio button.
When a label is clicked, CSS selectors apply a specific filter effect to the image.

Example:

```css
#blur1:checked ~ .container #img {
    filter: blur(1.5px);
}
```

This creates an interactive image editing experience entirely through CSS.

## Learning Outcome

Through this project, I practiced:

* Creating interactive behavior without JavaScript
* Understanding image manipulation using CSS filters
* Structuring larger CSS projects
* Improving UI organization and responsiveness
* Using advanced CSS selectors for dynamic styling
  
## Note

This is a learning project created for practice purposes while studying CSS filters and interactive frontend design.

Currently:

* The **Save** button is non-functional
* Uploaded images are not previewed yet
* Filters apply one at a time rather than stacking together

Future improvements may include JavaScript-based functionality for image uploads and downloadable edited images.

## Author

**Madhushree Rasal**

GitHub:
[https://github.com/MadhushreeRasal](https://github.com/MadhushreeRasal)
