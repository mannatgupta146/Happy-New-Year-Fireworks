# Happy New Year Fireworks 

A dynamic and colorful fireworks animation created with HTML5 Canvas and JavaScript to celebrate the New Year!

## Features
- Displays the message: **"Happy New Year 2025"** with animated fireworks.
- Fully responsive and adapts to different screen sizes.
- Smooth animations with particle effects.


## How It Works
1. **Initialization**: The JavaScript code initializes a canvas element and sets up essential styles and properties like width and height.
2. **Animation Logic**: The script defines particle and fireworks animations that generate the fireworks effect.
3. **Resizing and Redrawing**: On window resize, the canvas is resized, ensuring the animation remains responsive.
4. **Particle Generation**: For each character of the message, particles are generated to create the explosion effect.
5. **Firework Effects**: The animation loops through different stages like the rocket launch and explosion, creating the fireworks effect.


## Technologies Used
- **HTML5**: For the structure of the page.
- **CSS**: For basic styling and ensuring a clean background.
- **JavaScript**: For the canvas animation logic.


## Project Structure
```
├── index.html # Main HTML file 
├── script.js # JavaScript logic for animation 
├── styles.css # Basic styling for the canvas 
└── README.md # Project documentation
```


## Customize
You can customize the text displayed and animation behavior by editing the `str` array and other variables in the `script.js` file:
```javascript
let str = ['Happy', 'New', 'Year', '2025'];
```

## Contributions
Contributions, issues, and feature requests are welcome! Feel free to check the issues page for more information.

---
Happy Coding and Happy New Year! 🎆
