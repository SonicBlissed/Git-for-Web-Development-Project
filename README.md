# Git-Flow-Practice

This project is designed for one to practice the Git/Github workflow here at Lambda School. You will be able to follow along with [this pre-class video](https://youtu.be/4fLr6ah82bE) and use this assignment to demonstrate your ability to work within this flow. Watch this video, then follow the instructions listed below to complete the assignment

## Directions to complete this assignment

- [X] Create your own version of this repo - Fork
- [X] Add your PM as a collaborator
- [X] Clone this repo
- [X] Create a branch `git checkout -b 'firstName-lastName'`
  - [X] Add your name to the list of names below.
  - [X] Run your usual git commands or adding/commiting and pushing **Be sure to push to your branch**
- [X] Create a Pull-Request to submit your work
  - [X] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [X] Add your PM as a reviewer on the Pull-Request
- [X] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## ADD your name here
- Dustin Brinkman
- Steve Rogers
- Ryan Hamblin

Link to my code pen https://codepen.io/SonicBliss/pen/eYZavbm?editors=1100

 Questions and their answers:

Copy the questions below into the first-lastname.txt file on your github repo - answer each question and then push your changes. 

    1. What is Semantic HTML - 
    A semantic html is a literal tag or word that means what it does, an example being <div></div>

    2. What is HTML used for? - 
    HTML is used for building the foundations of a website and labeling sections of your website to easily reference later.

    3. What is an attribute and where do we put it? - 
    attributes provide additional information about a tag. It's put at the start of the tag, never the end. href is an example of an attribute

    4. What is the h1 tag used for? How many times should I use it on a page? -
    h1 is used to display titles or the most important thing on the page. It should only be used once.

    5. Name two tags that have required attributes -
    <a><img>

    6. What do we put in the head of our HTML document? -
    Titles, and important information. Things that should show-up as soon as a user open your page.

    7. What is an id? -
    id is an identification or a label added to tags that are repeated often so your computer can see the difference when you reference them later. 

    8. What elements can I add an id to? -
    Header, Footer, Title
    unique elements

    9. How many times can I use the same id on a page? -
    one time

    10. What is a class? -
    class is a label that is used by CSS

    11. What elements can I add a class to? -
    All of them

    12. How many times can I use the same class on a page? -
    Multiple

    13. How do I get my link to open in a new tab? -
    use the attribute target="_blank"

    14. What is the alt attribute in the image tag used for? -
    google, and disabled people when they're using readers

    15. How do I reference an id? -
    use a hashtag and the id's name

    16. What is the difference between a section and a div? -
    section defines a group of content and relates to a single theme, while div doesn't convey and meaning and simply indicates an area

    17. What is CSS used for? -
    Styling your already functional website

    18. How to we select an element? Example - every h2 on the page
    h2{

    }
    19. What is the difference between a class and an id? - Give me an example of when I might use each one -
    id is used for things like <header> that are unique and id's can only be used once
    class is used for things like <section> or <div> and can be used multiple times

    20. How do we select classes in CSS? -
    .className{

    }
    21. How do we select a p element with a single class of “human”? -
    p .human{

    }
    22. What is a parent child selector? When would this be useful? -
    parent is the tag and child is the class or tag within what you are selecting examples being:
    header p{

    }
    or
    div .bananas{

    }
    23. How do you select all links within a div with the class of sidebar? -
    div .sidebar{

    }

    24. What is a pseudo selector? -
    a pseudo selection is essentially adding an attribute to a class... for example
    div .bananas:hover{

    }

    25. What do we use the change the spacing between lines? -
    padding: 999%;

    26. What do we use to change the spacing between letters? -

    letter-spacing: 3,000,000,000px;

    27. What do we use to to change everything to CAPITALS? lowercase?
    Capitalize? -
    text-transform:

    28. How do I add a 1px border around my div that is dotted and black? -
    border: 1px dotted #000000;

    29. How do I select everything on the page? -
    body{

    }

    30. How do I write a comment in CSS? -
    /* bananas */

    31. How do I find out what file I am in, when I am using the command line? -
    ls

    32. Using the command line - how do I see a list of files/folders in my current folder? -
    ls

    33. How do I remove a file via the command line? Why do I have to be careful with this? -
    rm "name" it doesn't confirm if you want to delete it.

    34. Why should I use version control? -
    it allows you to rollback changes or identify what you did to break your code

    35. How often should I commit to github? -
    Once when you're done

    36. What is the command we would use to push our repo up to github? -
    git push -u origin "name"
  
    37. Walk me through Lambda's git flow. - 
    Fork-> Clone-> cd the folder-> Branch -> code .

    After changes

    git add .-> git commit -m "message on changes made"->
    Push-> git add .

    In Github
    Go to your branch, make pull request, change base REPO to you, add comments and submit
