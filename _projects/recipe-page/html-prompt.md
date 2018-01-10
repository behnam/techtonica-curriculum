# Project 1 - Recipe Page
### Phase 1 - Create structure with HTML

### Languages
- HTML

### Frameworks
None

### Topics
1. Topic1
2. Topic2
3. Topic3

### Overview
In this project you will create a well-designed webpage that displays one of your favorite recipes. It will include the ingredients, the steps needed to make the dish, links to similar recipes, and at least one photo.

Phase 1 of the project involves coding the structure of your webpage using HTML. This includes the ingredients, the steps needed to make the dish, links to similar recipes, and at least one photo.

Phase 2 of the project involves adding styling and pizazz using CSS. This includes changing the font style, font size, colors, and other qualities that interest you.

Phase 3 of the project involves incorporating Bootstrap. You'll add a navigation bar and several other Bootstrap components of your choosing.

Phase 4 of the project involves incorporating jQuery. You'll add at least one interactive element of your choosing.

### Context
- You've learned the basic structure of an HTML page
- You've learned the proper syntax for many commonly-used HTML elements
- You've learned how to open an HTML file in Chrome
- Let's put all these things together!

### Basic Requirements
1. Create an HTML file
2. Code the basic HTML structure
3. Add the title of the recipe
4. Add a brief background or blurb about the recipe
5. Add an unordered list of ingredients
6. Add an ordered list of the steps required to make the dish
7. Add at least one image
8. Add links to similar recipes you found online
9. Obtain a code review from Techtonica staff once you've fulfilled these requirements

## Setup Instructions
Use the Terminal for navigating around the file system and creating new folders and files. Refer to the lesson on [The Command Line Interface](https://github.com/Techtonica/curriculum/blob/master/command-line/command-line-interface.md) if you need guidance on using the Terminal.

When you get to the steps below that ask you to initialize a git repo and track files using git, refer to the lesson on [Git and Version Control](https://github.com/Techtonica/curriculum/blob/master/git-version-control/lesson-plan.md) if you need guidance.

If you do not yet have a directory called `techtonica-projects` on your Desktop, create one now using the Terminal. Initialize it as a git repository.

1. Navigate to the `techtonica-projects` directory.
2. Run the `git status` command. If you have any changes that need to be added and committed, do so before moving on. Make sure your branch is clean.
3. Create a new directory called `recipe-page` within the `techtonica-projects` directory.  
4. Navigate to the `recipe-page` directory.  

If you have questions, do not disturb your colleagues until you have spent at least 20 minutes troubleshooting on your own. Be sure to format your question using the template we practiced in the [Asking Good Questions](https://github.com/Techtonica/curriculum/blob/master/asking-good-questions/asking-good-questions.md) lesson.

## Lab Instructions

### Starter Code
There is no starter code for this lab exercise.

### Lab Exercise

#### Part 1 - Create an HTML file & open it in Atom

Using the Terminal, ensure you are in the `recipe-page` directory. Create a new file in this directory called `index.html`. Open this file in Atom using the Terminal shortcut to do so.

#### Part 2 - Code the basic HTML structure

Using the [HTML lesson slides](https://docs.google.com/presentation/d/1sqmplQtQw0KfC64VGL8Ur8NWOtyeUvSVYN407lJvjzY/edit?usp=sharing) or another online resource, code only the most essential elements of all HTML pages (the basic structure). Create a reasonable title given the recipe you are going to showcase. Do not include any code within the `<body>` tags yet.

> **PAUSE.** Obtain a code review from Techtonica staff.

#### Part 3 - Add the title of the recipe to the body

Using either the `<h1>` or `<h2>` header tags, create a header within the `<body>` tags that displays the title of your recipe.

Open `index.html` in Chrome to verify that this works.

[Add screenshots or images whenever possible](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository)

#### Part 4 - Add a brief background or blurb about the recipe

Using the `<p>` paragraph tags, write a little blurb or background story about the recipe underneath the title. It doesn't need to be long; a few sentences will do. Don't worry about how the text looks on the webpage. We'll make things more readable when we style the text with CSS in Phase 2 of the project!

Refresh `index.html` in Chrome by pressing `<COMMAND> + r`.

[Add screenshots or images whenever possible](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository).

#### Part 5 - Add an unordered list of ingredients

Using the `<ul>` unordered list tags and the `<li>` list item tags, list the ingredients in the order that they will be used in the recipe. Be sure to include the amount you need of each ingredient! 

Refresh `index.html` in Chrome by pressing `<COMMAND> + r`.

[Add screenshots or images whenever possible](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository).

> **PAUSE.** Obtain a code review from Techtonica staff.

#### Part 6 - Add an ordered list of the steps required to make the dish

Using the `<ol>` ordered list tags and the `<li>` list item tags, list the steps that are involved in creating the dish. 

- If there are distinct parts to the recipe, such as "make frosting" and "make the cupcakes", feel free to use sub-headings and multiple ordered lists to clearly show which steps go with which parts of the recipe.

Refresh `index.html` in Chrome by pressing `<COMMAND> + r`.

[Add screenshots or images whenever possible](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository).

#### Part 7 - Add at least one image

Using the `<img>` image tag, add an image between the blurb and the list of ingredients. 

<pre>
This should be an image you find online. Do a Google search for "(name of dish) image", like "spaghetti image". Click on the "Images" tab in the upper left (it's just to the right of "All"). When you find an image you like, click on it to see a larger version. Then, click on the "View Image" button. Doing this will open a new tab that contains only the image. Copy the URL that appears in the search bar -- this is the URL you can use inside the `src` attribute of your `img` tag!

[Here's a short video that walks you through these steps.](https://youtu.be/lTJWBagWE4c)
</pre>

1. You'll need to use the `src` attribute inside the `<img>` tag in order to specify the URL where the image is hosted.
2. Specify the width of the image to be 600px using the `"width"` attribute.

Underneath the image, include a photo credit that links to the source of the image. Hint: You'll need to use a combination of tags for this!

[Add screenshots or images whenever possible](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository) to clarify what you mean, and so students can verify they've done the task correctly.

#### Part 8 - Add links to similar recipes you found online

**Third step**  
Etiam eleifend est ac auctor pretium. Pellentesque eu quam urna. Morbi mattis purus at iaculis ornare. Sed id felis felis. Etiam euismod ante vel augue dictum, sed finibus arcu iaculis. Suspendisse maximus congue pharetra. Phasellus at sem vel sapien tincidunt porttitor vitae sit amet quam. Praesent sodales nisl elit, id vehicula nulla faucibus vel.

[Add screenshots or images whenever possible](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository) to clarify what you mean, and so students can verify they've done the task correctly.

> **PAUSE.** Obtain a code review from Techtonica staff.

-----

### Questions to Consider
- Ask questions here that connect what is being done in the lab exercise to what was covered in the associated lecture.
- Also ask questions that connect this lab exercise to prior lessons.
- Also ask questions that require the student to put together multiple pieces of knowledge to arrive at an answer or opinion.

### Extensions
- What deliverables can students work on once they have fulfilled the basic requirements for this lab exercise? 
- What do these deliverables add to their understanding of the topic?
- Extensions are designed for students who are moving through the material faster than their classmates. They should reinforce or build on the concepts from this lab exercise. Students should not work ahead in the curriculum by starting on the next lab exercise.