# Learn Bootstrap in 30 Chapters

### After completing this course, we'll build [5 Projects]() with Bootstrap in-sha-Allah.

After completing the 30-chapters module, jump in the [Projects Section](#).

| **Chapter No.** |         **Topics**         | **Video Explanation** |
| :-------------: | :------------------------: | :-------------------: |
|       00        | How The Course is Designed |       Watch Now       |
|       01        |                            |                       |
|       02        |                            |                       |
|       03        |                            |                       |
|       04        |                            |                       |
|       05        |                            |                       |
|       06        |                            |                       |
|       07        |                            |                       |
|       08        |                            |                       |
|       09        |                            |                       |
|       10        |                            |                       |
|       11        |                            |                       |
|       12        |                            |                       |
|       13        |                            |                       |
|       14        |                            |                       |
|       15        |                            |                       |
|       16        |                            |                       |
|       17        |                            |                       |
|       18        |                            |                       |
|       19        |                            |                       |
|       20        |                            |                       |
|       21        |                            |                       |
|       22        |                            |                       |
|       23        |                            |                       |
|       24        |                            |                       |
|       25        |                            |                       |
|       26        |                            |                       |
|       27        |                            |                       |
|       28        |                            |                       |
|       29        |                            |                       |
|       30        |                            |                       |

# 5 Bootstrap Projects

| **Project No.** | **Project Name** | **Video Explanation** | **Live Demo** |
| :-------------: | :--------------: | :-------------------: | :-----------: |
|       01        |                  |       Watch Now       |   Live Link   |
|       02        |                  |                       |               |
|       03        |                  |                       |               |
|       04        |                  |                       |               |
|       05        |                  |                       |               |

# Chapter-00: How The Course is Designed

### কোর্সটি যেভাবে সাজানো হয়েছেঃ

- এই পুরো Article কে একটা বই মনে করতে পারেন। কোর্সটি 60 টি Chapter এ ভাগ করা হয়েছে। প্রতিটি Chapter এ HTML/CSS এর বিভিন্ন Topics নিয়ে আলোচনা করা হয়েছে।
- প্রতিটা Chapter এর Module সাজানো হয়েছে ক্রমানুসারে । উদাহরণস্বরূপ, Chapter-05 এর টপিকসগুলো শিখতে হলে অবশ্যই আপনাকে Chapter-04 শেষ করে আসতে হবে। একইভাবে Chapter-04 শিখতে হলে আপনাকে Chapter-03 শেষ করে আসতে হবে ।
- প্রতিটা Chapter এর Topics এর Written Explanation/Article এর সাথে সাথে Video Explanation-ও দেয়া আছে। যাতে শিক্ষার্থীরা খুব সহজেই টপিকসগুলো আত্মস্থ করতে পারে।

### কোর্সটি কাদের জন্য?

- এই কোর্সটিতে যেকেউ অংশগ্রহণ করতে পারবে। শিখার জন্য মনের ইচ্ছাটাই আসল!
- Course টি মূলত Beginner-friendly. যারা Web Programming এ নতুন তাদেরকে উদ্দেশ্য করেই Course টি সাজানো।

### Prerequisite

- HTML সম্পর্কে অল্প ধারনা থাকলে ভালো, না থাকলেও সমস্যা নেই।

# Chapter-01: Introduction

- [What is HTML?](#what-is-html)
- [HTML Basics](#html-basics)
- [How Web Works?](#how-web-works)

### What is HTML?

The full meaning of HTML is **_Hyper Text Transfer Protocol_**. HTML is a Markup language.  
HTML is used to buld the **_STRUCTURE_** of the web pages.

### HTML Basics

- **`<DOCTYPE html>`** is used to **tell** the browser, this is an HTML5 document.
- **`<html>`** is the **container** of all HTML elements. This tag is used to **indicate** the beginning and end of all HTML elements in an HTML Document.

- **`<head>`** element is used to give **browser and search engine** informations about the page.
- **`<title>`** element specifies a title for the HTML page (which is shown in the browser's title bar and in the page's tab).
- **`<body>`** element is the container for all the visible contents such as headings, paragraphs, images, hyperlinks, tables, lists, etc in the webpage.
- The **`<em>`** element is used to define emphasized text. By default, emphasized text is
  displayed in _italic_.
- The **`<strong>`** element is used to represent important content. Browsers, by default, render strong content in **bold**.
- The **`<i>`** and **`<b>`** elements are considered deprecated because HTML should not be used for styling. That’s the role of CSS.
- Headings are represented using **`<h1>`**, **`<h2>`**, **`<h3>`**, **`<h4>`**, **`<h5>`**, **`<h6>`**. Every web page should have one and only one **`<h1>`** element. Headings should have a natural hierarchy and should not be skipped.
- Entities are used to display special characters such as angle brackets, copyright symbol, etc. The most important entities are: **`&nbsp;`** (non-breaking space), **`&lt;`** (less than sign), **`&gt;`** (greater than sign) and **`&copy;`** (copyright symbol).
- The **`<div>`** and **`<span>`** elements are generic containers used for styling purposes. Divs are block-level elements, spans are inline elements. A block-level element starts on a new line and takes up the entire available horizontal space.
- Semantic elements help us write markup that is more meaningful and descriptive to search engines, screen readers and other software. So, use **`<div>`** and **`<span>`** elements when no other semantic element is appropriate.
- The semantic elements in HTML5 are: **`<header>`, `<footer>`, `<nav>`, `<main>`, `<aside>`, `<article>`, `<section>`, `<figure>`, `<time>` and `<mark>.`**

  **An Example of Basic HTML Boilerplate is**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="keywords"
      content="TravellerAlim, Alim, Travel, AlimTheTraveller"
    />
    <meta
      name="description"
      content="Alim is an passionate traveler who travels around the world and loves to make adventures"
    />
    <title>TravellerAlim</title>
  </head>
  <body></body>
</html>
```

### How Web Works?

Hey, rather wasting some time, I'm gonna provide you some useful resources to learn how the web works!
Here we go:

1. An amazing Video [Explanation](https://youtu.be/zN8YNNHcaZc) on freeCodeCamp.
2. Another Amazing [Explanation](https://github.com/vasanthk/how-web-works) by Vasa.
3. Video [Explanation](https://www.youtube.com/watch?v=hJHvdBlSxug) on Academind.
4. An [Explanation](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) on Mozilla.

[Go to Top](#learn-html-and-css-in-60-chapters)

<div align="right">
    <b><a href="#learn-html-and-css-in-60-chapters">↥ Go to Top</a></b>
</div>

# Project-03: Simple Website Layout with Flexbox

### Difficulty: Easy (2/10)

### You Will Learn

- কিভাবে একটি Website এর Layout তৈরি করতে হয় CSS Flexbox দ্বারা ।
- যদিও এই কাজটা CSS Grid এর সাহায্যে খুব সহজেই তৈরি করা যায়, কারন CSS Flexbox হলো One dimensional Concept, যেখানে CSS Grid এর সাহায্যে খুব সহজেই 2-dimensional Layout তৈরি করা যায়।

### Project Description

এই প্রজেক্টে আমরা একটা Simple Website Layout বানাবো CSS এর Flexbox ব্যবহার করে। যদিও এই কাজটা CSS Grid এর সাহায্যে খুব সহজেই তৈরি করা যায়, কারন CSS Flexbox হলো One dimensional Concept, যেখানে CSS Grid এর সাহায্যে খুব সহজেই 2-dimensional Layout তৈরি করা যায়।

### Project Screenshot

_Click the following image to view Project_
[![Project 2](./project-02-simple-website-layout-with-basic-css/images/layout1.png)]()

### Live Project Link

[Open in CodePen]()

### Video Explanation

Coming Soon...

### Project Source Codes

[Source Codes](./project-03-simple-website-layout-with-flexbox/)

[<h3 align="center">Back to Project Section</h3>](#20-html--css-projects)
