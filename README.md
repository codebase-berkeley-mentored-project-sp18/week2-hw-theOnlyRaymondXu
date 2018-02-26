# Mentored Project Week 2 Homework - Frontend Web Development

## Instructions

### Submitting the Homework

Your submissions will be done through git. There is no autograder for this assignment. To commit and push your work to GitHub, do

```
git add -A
git commit -m "<YOUR COMMIT MESSAGE HERE>"
git push
```

## Homework Questions

This week's homework is to test your knowledge of the DOM (questions 1 and 2) and CSS (question 3).

## Question 1 - Query Selectors

Reading: [Document Object Model (DOM)](https://theandrewchan.gitbooks.io/javascript-crash-course/content/6-the-document-object-model-dom.html)

This question is the same exercise from lecture; implement the functionality of  [`document.getElementsByClassName`](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementsByClassName), which takes as input a string class (you may assume that there is only one class) and returns an array of all elements in the page that have that class. You may


## Question 2 - Tic Tac Toe

Reading: [DOM Events](https://theandrewchan.gitbooks.io/javascript-crash-course/content/7-dom-events-and-interactivity.html)

Seeing that you already did the hard part, I provided plenty of starter code. I've given you all of the variables, a function to check if someone won, and a function to switch players. You are free to delete all of this and start from scratch if you don't feel like reading through starter code. If you do want to read through the starter, here is what you need to do:

1. Add an event listener to every "spot" on the board. Hint: these are all td elements and they all have the class spot.  
2. Get the ID of the spot on the board that was selected, and put it in a variable called ID  
3. Complete the getRow and getCol functions at the bottom (this isn't DOM interaction). Hint: lookup how to parse strings into integers in js.  
4. Once the game is won, remove the event listener from each "spot." If you don't do this, even when the game is won, players will be able to keep selecting pieces.  
5. Fill in the addMessage function. This function takes in strings m and c representing a message and a class. The function should change the paragraph with ID message (at the top of the page) to have the message passed in and it will add the class to that paragraph element.

When you're done, your game should function like mine: <https://bdeleonardis1.github.io>

## Question 3 - Google

Reading: See [slides](https://docs.google.com/presentation/d/1DFmJxiWmBHeVpdofiF1FiVeQVaqoexdKcuJe1tgbjmw/edit) - CSS section.

Now you know enough to make Google! The home page that is... I gave you some starter HTML code, again feel free to delete it if you want. Please do not just google how to do this directly or use the inspector to steal google's, you will not get anything out of this assignment. I only included some of the elements from the homepage in the starter HTML (the required ones), but feel free to add the others as per: <http://google.com>. There is also a starter picture of what Google looked like when I was making this.
