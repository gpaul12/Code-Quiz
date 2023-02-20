# Code Quiz

This project was designed as a Chakkenge for UNC coding bootcamp. 

This is a quiz application using HTML, CSS, and Javascript. This application emphasizes the use of Javascript to provide quiz questions and collect user data to determine whether the answers to a question are correct, this then generates a score and appends a final page of results from the user data. 

This project has been deployed to GitHub Pages. To get this project up and running, you can follow the deployment link. Or, download the sources files to use this as a template.

* [GitHub Repository](https://github.com/gpaul12/UNC-VIRT-FSF-PT-01-2023-U-LOLC-MTTH-Mod4-Challenge/)

### Summary
* HTML and CSS and Javascript documents create a quiz with multiple choice questions with Javascript trivia
* This project emphasizes the use of using Javascript to make dynamic changes to an HMTL document
* This project utilizes the use of appending HTML pages 

### This project has the following features: 
* A Start Quiz button 
    * This starts a timer for the user
    * Each question averages 15 seconds each for a total time of 75 seconds + 1. 


* A HTML page that features questions, and multiple choice answers
    * If questions are answered incorrectly, 5 seconds are deducted off remaining time
    * Answers are recording using an event listener, "click" and tracks correct answers

* A HTML page that features: 
    * Final score which is calculated using time remaining
    * A Summary of how many questions answered correctly 
    * Input area to record initials
    * A Submit button
    * Submit buttom saves initials and score to local storage

* A Highscores HTML
    * This a list summary of intials and final scores
    * Clear button resets the page and local storage
    * Go back button travels to the start of the quiz


### This project has script features of:
* Questions contained in an array variable with objects
* Variable declaration area 
* An event listener (onclick) that generates time interval
* A function to render the questions and choices on the page using a for loop
* An event listener on all list choices 
* A comparison statement to compare correct answers to choices
* An appended page showing the final stats of the individual user with input area for initials, captures local storage
* Highscores retreived local storage

### Features: 
* Two HTML Pages
    * Index.html 
        * Contains landing page to start timer
        * Appends two new pages 
* Highscores 
        * Retreives local data from previous page
* One CSS Page
    * Styles.css
        * Contains centering and styling for html list features
        * Contains media queries
* Two Javascript Page
        * Contains: 
        * Variables, including arrays with object
        * Event listeners
        * if/else if statements
        * For Loops
        * Functions 
        * Local Storage set and get 

## Authors

* **Gerry Paul** 
