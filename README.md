# Profile Card UI Design



## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot
![Profile Card UI Design](images/FinalShot.png)

### None

### Links

- Solution URL: (https://github.com/DMKALALA/Profile-Card-UI-Design-main)
- Live Site URL: (https://dmkalala.github.io/Profile-Card-UI-Design-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid


### What I learned

What i learned today was how transitions work and also how we include icons without using images.

```html
<div class="media-buttons">
            <a href="#" style="background: #4267b2;" class="link">
                <i class='bx bxl-facebook'></i>
            </a>
            <a href="#" style="background: #1da1f2" class="link">
                <i class='bx bxl-twitter'></i>
            </a>
            <a href="#" style="background: #e1306c;" class="link">
                <i class='bx bxl-instagram'></i>
            </a>
            <a href="#" style="background: #ff0000;" class="link">
                <i class='bx bxl-youtube'></i>
            </a>
        </div>
```
```css
    .profile-card .media-buttons{
    display: flex;
    align-items: center;
    margin-top: 15px;
}

.media-buttons .link{
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    font-size: 18px;
    height: 34px;
    width: 34px;
    border-radius: 50%;
    border-radius: 50%;
    margin: 0 8px;
    background-color: #4070f4;
    text-decoration: none;
}

.profile-card .buttons{
    display: flex;
    align-items: center;
    margin-top: 25px;
    /
}

.buttons .button{
    color: #fff;
    font-size: 14px;
    font-weight: 400;
    width: 120px;
    border: none;
    border-radius: 24px;
    margin: 0 10px;
    padding: 8px 24px;
    background-color: #4070f4;
    cursor: pointer;
    transition: all 0.3s ease;
}

.buttons .button:hover{
    background-color: #0e4bf1;

}

.profile-card .analytics{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 25px;
}


```

### Continued development

I would like to make more template cards  so this could be used as a default template and possibly one day use it for a quiz game.



### Useful resources

- [Boxicons](https://boxicons.com/usage) - This helped me to understand better how to use boxicons.

- [CodingLabs](https://www.youtube.com/watch?v=np3L1lb-Uvs) This was the main resource used to fill any gaps in my knowledge.

## Author

- Denis Kalala 

## Acknowledgments
- [CodingLabs](https://www.youtube.com/watch?v=np3L1lb-Uvs) This was the main resource used to fill any gaps in my knowledge.
