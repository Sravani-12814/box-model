# CSS Box Model Project

## Description

This project demonstrates the **CSS Box Model** using HTML and CSS. It is designed to show how different CSS properties work together to create and style a box element.

The project also demonstrates **CSS Variables, Flexbox, Links, Pseudo-classes, and CSS Animation**.

## Features

* CSS Variables using `:root`
* Box Model properties
* Flexbox for alignment
* Google, YouTube, and GitHub links
* Hover effect on links
* Active effect on links
* Focus effect on links
* Visited link styling
* CSS animation using `@keyframes`
* Rounded corners using `border-radius`
* Smooth transitions using `transition`

## Technologies Used

* HTML5
* CSS3

## CSS Concepts Used

### 1. CSS Variables

CSS variables are used to define the width and height of the box.

```css
:root {
    --box-width: 400px;
    --box-height: 200px;
}
```

### 2. Box Model

The project demonstrates the main parts of the CSS Box Model:

* Content
* Padding
* Border
* Margin

### 3. Flexbox

Flexbox is used to center the box and arrange the links horizontally.

```css
display: flex;
justify-content: center;
align-items: center;
```

### 4. Pseudo-classes

The links use different pseudo-classes:

* `:hover`
* `:active`
* `:focus`
* `:visited`

### 5. Animation

The box moves from one position to another using CSS `@keyframes`.

```css
@keyframes moveBox {
    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(300px);
    }
}
```

## Project Structure

```text
CSS-Box-Model
│
└── index.html
```

## How to Run

1. Download or clone this repository.
2. Open the project in **VS Code**.
3. Open `index.html`.
4. Run it using **Live Server**.
5. Click the Google, YouTube, or GitHub links to open them.

## Output

The webpage displays a centered box containing three links:

* Google
* YouTube
* GitHub

The box also has a simple animation and the links have different hover, active, focus, and visited effects.

## Learning Outcome

This project helps beginners understand the **CSS Box Model, CSS Variables, Flexbox, Pseudo-classes, Transitions, and Animations**.
