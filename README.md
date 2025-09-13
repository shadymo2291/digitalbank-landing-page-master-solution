## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL: https://github.com/shadymo2291/digitalbank-landing-page-master-solution

### Built with

- Semantic HTML5 markup
- CSS custom properties
- grid
- flexbox
- position
- pseudo-elements
- hover effect

### What I learned

In this project, I used some CSS properties to help with responsive font size, such as @media
and pseudo-elements and hover effect

To see how you can add code snippets, see below:

.first_section {
  background-color: #f3f5f7;
  padding: 80px 0;
  margin-top: -100px;
}
.first_section .first_section_sevices {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 40px;
  margin-top: 60px;
}
.first_section_intro {
  width: 550px;
}
.first_section_intro h2 {
  font-size: 30px;
  margin-bottom: 30px;
}
  .first_section_intro > p {
  font-size: 15px;
  margin-bottom: 30px;
}
.first_section .first_section_sevices > div {
  display: flex;
  flex-direction: column;
  gap: 30px;
}
.first_section .first_section_sevices h3 {
  font-size: 20px;
}
.first_section .first_section_sevices p {
  font-size: 14px;
  line-height: 1.7;
}
.first_section .first_section_sevices img {
  display: block;
  width: 60px;
}

@media (max-width: 992px) {
  .first_section {
    margin-top: 0px;
  }
  .first_section .first_section_sevices {
    gap: 20px;
  }
  .first_section_intro {
    width: auto;
  }
  .first_section .first_section_sevices > div {
    align-items: center;
    text-align: center;
  }
  .first_section_intro {
    text-align: center;
  }
  .first_section_intro h2 {
    font-size: 35px;
  }
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements and hover effect

### Useful resources

- [w3schools] https://www.w3schools.com/cssref/sel_hover.php
- [w3schools] https://www.w3schools.com/css/css_pseudo_elements.asp

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
