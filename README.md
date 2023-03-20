# 0x01. AirBnB clone - Web static

**HTML CSS Front-end**

> Concepts

*For this project, we expect you to look at these concepts:*

- [HTML/CSS](https://intranet.alxswe.com/concepts/2)
- [The trinity of front-end quality](https://intranet.alxswe.com/concepts/4)

# Background Context

## Web static, what?

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

	- Create simple HTML static pages
	- Style guide
	- Fake contents
	- No Javascript
	- No data loaded from anything

During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

Before starting, please fork or clone the repository AirBnB\_clone from your partner if you were not the owner of the previous project.

# Resources

**Read or watch:**

- [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/) (until “Creating Lists” included)
- [Inline Styles in HTML](https://www.codecademy.com/article/html-inline-styles)
- [Specifics on CSS Specificity](https://css-tricks.com/specifics-on-css-specificity/)
- [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [MDN](https://developer.mozilla.org/en-US/)
- [center boxes](https://css-tricks.com/centering-css-complete-guide/)

# Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/), **without the help of Google:**

## General

- What is HTML
- How to create an HTML page
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- How does the browser load a webpage
- What is CSS
- How to add style to an element
- What is a class
- What is a selector
- How to compute CSS Specificity Value
- What are Box properties in CSS

# Copyright - Plagiarism

- You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
- You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work. 
- You are not allowed to publish any content of this project.
- Any form of plagiarism is strictly forbidden and will result in removal from the program.

# Requirements

## General

- Allowed editors: vi, vim, emacs
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should be W3C compliant and validate with [W3C-Validator](https://github.com/holbertonschool/W3C-Validator)
- All your CSS files should be in styles folder
- All your images should be in images folder
- You are not allowed to use !important and id (#... in the CSS file)
- You are not allowed to use tags img, embed and iframe
- You are not allowed to use Javascript
- Current screenshots have been done on Chrome 56 or more. 
- No cross browsers 
- You have to follow all requirements but some margin/padding are missing - you should try to fit as much as you can to screenshots

# More Info

![server side and client side (fron-end)](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step1.png)

> 0. Inline styling 

Write an HTML page that displays a header and a footer.

Layout:

	- Body: 
		- no margin
		- no padding
	- Header: 
		- color #FF0000 (red)
		- height: 70px
		- width: 100%
	- Footer: 
		- color #00FF00 (green)
		- height: 60px
		- width: 100%
		- text Best School center vertically and horizontally
		- always at the bottom at the page
Requirements:
	- You must use the header and footer tags
	- You are not allowed to import any files
	- You are not allowed to use the style tag in the head tag
	- Use inline styling for all your tags

![](/web_static/img/0-index.png)

**Repo:**

	- GitHub repository: AirBnB_clone
	- Directory: web_static
	- File: 0-index.html

> 1. Head styling 

Write an HTML page that displays a header and a footer by using the style tag in the head tag (same as 0-index.html)

Requirements:

	- You must use the header and footer tags
	- You are not allowed to import any files
	- No inline styling
	- You must use the style tag in the head tag

The layout must be exactly the same as 0-index.html

> 2. CSS files 

Write an HTML page that displays a header and a footer by using CSS files (same as 1-index.html)

Requirements:

	- You must use the header and footer tags
	- No inline styling
	- You must have 3 CSS files: 
		- styles/2-common.css: for global style (i.e. the body style)
		- styles/2-header.css: for header style
		- styles/2-footer.css: for footer style
The layout must be exactly the same as 1-index.html

**Repo:**

	- GitHub repository: AirBnB_clone
	- Directory: web_static
	- File: 2-index.html, styles/2-common.css, styles/2-header.css, styles/2-footer.css

> 3. Zoning done! 

Write an HTML page that displays a header and footer by using CSS files (same as 2-index.html)

Layout:

	- Common:
		- no margin
		- no padding
		- font color: #484848
		- font size: 14px
		- font family: Circular,"Helvetica Neue",Helvetica,Arial,sans-serif;
		- [icon](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon.png) in the browser tab
	- Header: 
		- color: white
		- height: 70px
		- width: 100%
		- border bottom 1px #CCCCCC
		- [logo](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/logo.png) align on left and center vertically (20px space at the left)
	- Footer: 
		- color white
		- height: 60px
		- width: 100%
		- border top 1px #CCCCCC
		- text Best School center vertically and horizontally
		- always at the bottom at the page

Requirements:

	-  No inline style
	- You are not allowed to use the img tag
	- You are not allowed to use the style tag in the head tag
	- All images must be stored in the images folder
	- You must have 3 CSS files: 
		- styles/3-common.css: for the global style (i.e body style)
		- styles/3-header.css: for the header style
		- styles/3-footer.css: for the footer style

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/2be1eda05a0d9097c210f2d3482a59aa858c5711.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230320T070439Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9984a87501a16554b89189b758517424c2bfa2c612b5e45539a8480a009fba69)

**Repo:**

	- GitHub repository: AirBnB_clone
	- Directory: web_static
	- File: 3-index.html, styles/3-common.css, styles/3-header.css, styles/3-footer.css, images/
