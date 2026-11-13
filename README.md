# Parallax Landing Page

A landing page for Mount Zlatibor in Serbia, with a parallax scrolling effect made in **CSS only**: no JavaScript and no libraries.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-none-555)

![The hero section, with the page title over a mountain photo](https://github.com/ThyMo05e/Home-Easy-parallax-effect-with-background-attachment/assets/126653199/bd460041-e48f-43c6-a3d8-15ba5e0f625c)

![Three activity cards over a fixed background photo](https://github.com/ThyMo05e/Home-Easy-parallax-effect-with-background-attachment/assets/126653199/7129d47a-193f-464b-adad-ca3efea44606)

## How the parallax works

Each full-screen section has a background photo with `background-attachment: fixed`. The photo stays still while the page scrolls, and the solid sections between them slide over it, which gives the feeling of depth.

```css
.container {
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
```

Phone browsers either ignore fixed backgrounds or make them stutter, so on screens narrower than 900px the backgrounds scroll normally and the activity cards stack in one column.

## What's on the page

- A hero section with the title, a short intro and a button that scrolls down to the activities
- Cards for rock climbing, caving and parachuting, each with a photo
- Smooth scrolling, switched off for people who prefer reduced motion

## Run it locally

```bash
git clone https://github.com/MuneerMiller/Home-Easy-parallax-effect-with-background-attachment.git
```

Then open `index.html` in your browser.

## Credits

Photos from [Unsplash](https://unsplash.com/), loaded from their servers. Font: [Red Hat Text](https://fonts.google.com/specimen/Red+Hat+Text) from Google Fonts.

Built by **[Muneer Miller](https://github.com/MuneerMiller)** · [muneermiller.github.io](https://muneermiller.github.io/)
