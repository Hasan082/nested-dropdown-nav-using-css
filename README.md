# 4th Level Dropdown Menu

This is a 4th level dropdown menu implemented using HTML, CSS, and animation. It provides a hierarchical navigation structure with multiple levels of dropdown menus.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Customization](#customization)
- [License](#license)

## Demo

You can see a live demo of the 4th level dropdown menu [here](link-to-demo).

## Features

- Multiple levels of dropdown menus
- Smooth animations on hover
- Easy to customize and integrate into your projects

## Technologies Used

- HTML
- CSS
- Animation

## Usage

To use the 4th level dropdown menu in your project, follow these steps:

1. Copy the HTML markup for the menu structure into your HTML file:

```html

    <div class="nav-wrapper">
        <nav class="main-nav">
            <ul class="mainul">
              <li><a href="#">Home</a></li>
              <li>
                <a href="#">About <span>&dArr;</span></a>
                <ul class="dropdown">
                  <li><a href="#">About 1</a></li>
                  <li>
                    <a href="#">About 2 <span>&rArr;</span></a> 
                    <ul class="dropdown">
                      <li><a href="#">About 2.1</a></li>
                      <li><a href="#">About 2.2</a></li>
                      <li><a href="#">About 2.3</a></li>
                      <li>
                        <a href="#">About 2.4  <span>&rArr;</span></a>
                        <ul class="dropdown">
                          <li><a href="#">About 2.4.1</a></li>
                          <li><a href="#">About 2.4.2</a></li>
                          <li><a href="#">About 2.4.3</a></li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li><a href="#">About 3</a></li>
                </ul>
              </li>
              <li>
                <a href="#">Team <span>&dArr;</span></a>
                <ul class="dropdown">
                  <li><a href="#">Team 1</a></li>
                  <li>
                    <a href="#">Team 2 <span>&rArr;</span></a>
                    <ul class="dropdown">
                      <li><a href="#">Team 2.1</a></li>
                      <li><a href="#">Team 2.2</a></li>
                      <li>
                        <a href="#">Team 2.3 <span>&rArr;</span></a>
                        <ul class="dropdown">
                          <li><a href="#">Team 2.3.1</a></li>
                          <li><a href="#">Team 2.3.2</a></li>
                          <li><a href="#">Team 2.3.3</a></li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li><a href="#">Team 3</a></li>
                </ul>
              </li>
              <li><a href="#">Gallery</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
          </nav>
          
    </div>
```

2. Copy the CSS styles for the menu into your CSS file:

```css
-style.scss
-style.min.css
```

3. Customize the menu as needed by modifying the HTML and CSS code.

4. Link the CSS file to your HTML file using a `<link>` tag:

```html
    <link rel="stylesheet" href="./assets/css/style.min.css">
```

5. You can now use the 4th level dropdown menu in your project.

## Customization

The 4th level dropdown menu can be customized according to your needs. Here are some areas you can customize:

- Colors: Modify the color scheme by changing the background, text, and hover colors in the CSS code.
- Dimensions: Adjust the width, height, and padding of the menu items to match your design requirements.
- Animation: Modify the animation properties such as duration and easing to achieve different visual effects.

Feel free to experiment and make changes to the HTML and CSS code to create your desired look and feel.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/). You are free to use, modify, and distribute this code for both commercial and non-commercial purposes. Please see the [LICENSE](https://opensource.org/license/mit/) file for more details.
