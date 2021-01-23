# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. How would you describe acessibility on the web to someone new to programming?

    Accessibility means that you are building websites that can be easily viewed on multiple devices for all kinds of different people. The goal is to make a site accessible to everyone regardless if they fit the standard model or not. Younger more tech savvy people, as well as older less savvy people. People who have a hard time reading, someone who doesn't have use of their hands, etc. When opening a website on your phone you want it to be just as clean and aesthetic as it would be on a desktop. Because the screen size is smaller this often included modification to the code. 

2. Talk about 3 different things you can do to ensure your website is accessible. 

    The main things that will help to make you website more accessible include using media queries to resize your page to different screen sizes. Using screen readers is another great way to build accessibility. Screen readers are web extensions that help people who wouldn't otherwise be able to read the page. They often read the page aloud or translate it to brail. A screen reader relies on html and is a huge reason why your html must be semantic and easy to a understand. Because many people are colorblind you must also be able to use color in an accessible manner. If you can't turn greyscale onto your page and have it equally understood, rework your website. Color should never the only thing in an item that conveys a message.

3. How would you explain the concept of a variable to someone new to programming?

    Simply put, variables are ways to store data. Most things on the web are variables. In order to store this data you need to declare it using a keyword. The main keywords are let, const, and var. They each serve a different purpose. Variables are important because data is always changing on websites and you need to have a way to keep track, organize, and store all of these parts.

4. What is the purpose of using functions in code?

    functions in code save a lot of time. They allow us to have repeating sections of code without spending time manually doing it ourselves. This at first may not seem like a big deal when dealing with small chucnks of code, but when working with projects that have hundreds of lines of code it is imperitive to not have to go in and manually type out every step several times, when running a function once will do the same thing.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [x] Add a viewport meta tag to the head of your index.html page.
* [x] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Website is responsive at multiple breakpoints and looks good in-between breakpoints because student is using responsive units of measurement where appropriate. Student is using most semantic HTML for each element on page and has included ARIA roles where applicable (More research may be required to impliment ARIA roles)  
* [ ] Student demonstrates and can explain a deep understanding of basic programming concepts, when walking Team Lead through the explaination of their code.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example) - do this seperate from your MVP tasks


## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Please see canvas for cohort specific submission instructions 
