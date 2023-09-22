# ***HTML***

> HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

[Image](https://internetingishard.netlify.app/becoming-a-web-developer-0530f1.3b5388b5.png)

## Introduction

HTML, CSS, and JS are the languages that run on the web. 

They're very closely related, but they're also designed for very specific tasks.

Understanding how they interact will go a long way towards becoming a web developer.

[Image2](https://internetingishard.netlify.app/html-css-javascript-905348.7c291929.png)

- ### HyperText Markup Language (HTML)

> HTML is for adding meaning to raw content by marking it up.

> Think of HTML as the abstract text and images behind a web page.

Example:

```
<p id = 'paragraph'>This is a paragraph.</p>
```

- ### Cascading Style Sheets (CSS)

> CSS is for formatting that marked up content.

> CSS as the page that actually gets displayed

Example:

```
p {
    font-size: 20px;
    color: blue;
}
```

- ### JavaScript (JS)

> JavaScript is for making that content and formatting interactive.

> JavaScript as the behaviors that can manipulate both HTML and CSS

Example:

```
var p = document.getElementById('paragraph');
p.addEventListener('click', function(event) {
  p.innerHTML = 'You clicked it!';
});
```

> As you can see, HTML, CSS, and JavaScript are totally different languages, but they all refer to one another in some way. Most websites rely on all three, but the appearance of every website is determined by HTML and CSS. That makes this tutorial a great starting point for your web development journey.

## Languages VS Web Development

> Unfortunately, mastering HTML, CSS, and JavaScript is only a prerequisite for becoming a professional web developer. There are a bunch of other practical skills that you need to run a website:

- ### Organizing HTML into reusable templates

- ### Standing up a web server

- ### Moving files from your local computer to your web server

- ### Reverting to a previous version when you screw something up

- ### Pointing a domain name at your server

Dealing with these complexities involves setting up various “environments” to organize your files and handle the building/deploying of your website. 

All of this is orthogonal to the actual HTML, CSS, and JavaScript code that make up a website.

This tutorial focuses entirely on the languages of HTML and CSS—not setting up those underlying environments.

[Image3](https://internetingishard.netlify.app/languages-vs-web-dev-b849db.a1ad228a.png)

---

## Web Publishing

> So, what is it to “learn” HTML and CSS? We like to look at it through a historical lens into the printing industry. 

> Back in the days of the original printing press, printers created documents by arranging metal characters, dipping them in ink, and pressing them onto a piece of paper.

> In a lot of ways, that’s exactly what web developers do, except instead of arranging moveable type, they write HTML and CSS.

> We’re concerned with the same task as they were: conveying content in meaningful ways. We even deal with the same presentational issues they did, like selecting the font to use, setting the size of headings, and determining the space between lines of text.

[Image4](https://internetingishard.netlify.app/web-publishing-cd96b2.87351deb.png)

> Printers used to print a bunch of pages and bind them into a book. Nowadays, we create a bunch of HTML files and link them together into a website. 

> Learning HTML and CSS is a matter of understanding the available HTML markup and CSS rules to make a browser render those files exactly how they’re supposed to.

--- 

## Fundamentals, Not Frameworks

> There’s all sorts of front-end web development frameworks out there (few): 

- ### Bootstrap

- ### ZURB Foundation

- ### Pure CSS

> The goal of every single one of them is to abstract away some of the redundant aspects of creating web pages from scratch.

> These kinds of frameworks are an important part of real-world web development, and they’re definitely worth exploring—but only after mastering the basics with HTML & CSS Is Hard.






