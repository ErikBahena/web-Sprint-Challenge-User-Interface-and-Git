# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.


## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons)

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages (found in the design-files folder):

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions 
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

When you write html, you could just use divs for everything. Not that you should, but it's possible. The problem with that is when you need to find something in your html or screen readers are trying to go through your page. Problems will arrise, semantic HTML gives meaning to your html. For example, the body tag, the img tag, and the link tag. Just by reading these you can undersand what content is going to be inside those elements. The body tag will contain the body, the img tag will contain an image, and the link tag will contain a link. It's best practice to use semantic html to structure your page, allowing future developers to navigate your html with less difficulty, and screen readers to go through your page.

2. Name two big differences between ```display: block;``` and ```display: inline;```.
    
    display block is the default display type for elements like the p tag or h1. This display type means that your element will take up 100% of the availible space of its parent in the horizontle direction. Display inline is the default display type for elements like a or button. This display type means that your element will not take up an entire line or "100% of the availible space of its parent element", instead it will take up as much space as it's content. An example of an inline case would be putting a link inside a paragraph. The link will not break the rest of the paragraph. It will just take up the space it need to fit the name of the link. 

3. What are the 4 areas of the box model?

The four areas of the box model are the content, padding, border, and margin.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

The align-items property works on the relative (to us) verticle axis of the element if the element is using flex-direction: row; If the flex-direction is column, then the align-items property aligns in the horizontal direction


5. Explain why git is valuable to a team of developers.

While develping code as developers do, there may be mistakes or a client did not like how a feature looks. The value of git is that it allows you revert to older versions of your code. It also allows multiple developers to work on different parts of your code base; choosing who can add code to the original codebase based on your criteria, like a code review.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push -u origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**



## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [ ] Build the HTML and CSS to create the missing navigation and header.
* [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box (Note: inline styles are not acceptable. All styles should be written in your index.css file):

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [ ] Copy and paste your home page navigation and header into the about page
* [ ] Update the header image with the about page image
* [ ] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

Note: Please make sure you are using flexbox to layout your website. Floats, inline-block, tables, etc, should not be used for layout. 

## Submission Instructions 
 
Please submit the url to your pull request in Canvas
