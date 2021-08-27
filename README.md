# Frontend Mentor - Profile card component

![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

### What I learned

If you are also usign hsl color in your projects than this will be helpful.

During this challenge, I learned the new way of defining hsl color with css variables.

To see how I used hsl color in this project, see below:

```css
:root {
	--clr-dark-cyan: 185 75% 39%;
	--clr-dark-blue: 229 23% 23%;
	--clr-grayish-blue: 227 10% 46%;
	--clr-dark-gray: 0 0% 59%;
}

h1 {
	font-size: 18px;
	color: hsl(var(--clr-dark-blue));
}
```
This way you have control over color opacity. You don't have to define 'opacity' property to your background in css. To control the background-color opacity put '/' and opacity value. As you can see below:

```css
h1 {
	font-size: 18px;
	color: hsl(var(--clr-dark-blue) / .5);
}
```


# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Dark cyan: hsl(185, 75%, 39%)
Very dark desaturated blue: hsl(229, 23%, 23%)
Dark grayish blue: hsl(227, 10%, 46%)

### Neutral

Dark gray: hsl(0, 0%, 59%)

## Typography

### Body Copy

- Font size (name and stats): 18px

### Font

- Family: [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)
- Weights: 400, 700