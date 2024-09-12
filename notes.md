## CSS
### Center items horizontally
- display: block
- must have a width
- margin: auto

### Height vs Line-Height
- when using text-heavy elements and input fields, its netter to use line-height instead of height, it scales batter, better for accessible design, more flexible for resposniveness and great for readability


### Contrast Checker
- check contrast checker online to see how well elements contract from each other

### Defining relative path
- a single slash / used in defining  arelative path means start from the root directory
- ./ means start from current file location

### Web-Safe Fonts
- Arial (sans-serif)
- Verdana (sans-serif)
- Tahoma (sans-serif)
- Trebuchet MS (sans-serif)
- Times New Roman (serif)
- Georgia (serif)
- Garamond (serif)
- Courier New (monospace)
- Brush Script MT (cursive)

### CSS Inheritance
- button dont inherit font family from body
- To inherit, target the button selector and set font-family to 'inherit'; provided you already set it in the body.

### Searching Specific Fonts
- Search 1001fonts.com for fonts you wont normally find online
- download th ttf file of the font. e.g 'Corleone.ttf'
- paste the file inside your project
- create the css as follows and target the selector:

```css
@font-face {
    src: url("Corleone.ttf");
    font-family: Corleone;
}

h1 {
    font-family: Corleone;
}
```

### Animated webp image formats
- visit gify.com for animated webp images 
- use them exactly as you would an image background

### Color Pallet from photo
- you can pich colors from an image to use in your design
- in coolors.com, click on 'more' and chose 'pich pallete from photo', then 'browse image'

### Text Shadows
- set four properties as follows:
1. Horizontal offset (negative values displace the shadow left from the text)
2. Vertical offset (negative values displace the shadow upwards)
3. blur radius
4. colour
- You can also apply multiple shadows by separating them with commas
- Examples:
```css
h1 {
  text-shadow: 2px 4px 3px rgba(0, 0, 0, 0.3);
}
```
- miltiple shadows:
```css
h1 {
  text-shadow: 2px 2px 4px #000, -1px -1px 2px rgba(255, 255, 255, 0.5);
}
```

### Text-Shadow
- set the vertica and horizontal shadow properties to 0 for it not to offset

