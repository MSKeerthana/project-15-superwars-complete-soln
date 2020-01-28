# ProGrad

## Superwars

Dustin and Lucus are best friends, they spend their weekends watching superhero series and playing superhero games. One Friday in school Mr.Hooper who is their computer science faculty member taught them HTML, CSS, and JavaScript. So what's next? It's Weekend! Lucus and Dustin will be on their laptops. Are they watching series or playing games? Lucus says, No we are building a new game.

Lucus always loves protagonists like most of us. But Dustin is quite crazy he likes antagonists. So now they are collecting a bunch of their favorite Super Heroes and Super-Villains names along with images. Did they tell you about the game that they are building? Uh no. Okay, lemme explain. They are going to facilitate the ultimate war between Super Heroes and Super-Villains. As they are new to these technologies, they need **YOU** to help them build this game. Go to the `src/app.js` file and complete all the unfinished code to propel both of these young champ's dreams.

## What should you do?

- Fork this repo
- Clone this repo
- Practice JavaScript Oops -  _classes, objects, member variables, member functions_

## How do you submit?

- Upon completion, run the following commands:

  ```
  git add .
  git commit -m "prograd ID"
  git push origin master
  ```

- Create a pull request so your teaching mentors can check your work.

## Starter code

The `src/app.js` contains an array of 20 Super Heroes and Super-Villains. We are talking about the array of 20 _strings_ containing each Super Heroes and Super-Villains names. Here is one example of how the data is displayed:

```javascript
[
    "Spiderman"
]
```

### Tests

Ohh yes! We have our beloved tests, and you already know how this works. Open the `SpecRunner.html` file on your browser and start coding to pass the test. Remember to focus on one test at a time and read carefully the instructions to understand what you have to do.

## Trial 1: CLASH OF CLANS !

Brace yourself ! we are in the last legs. Help Dustin and Lucus by filling the logic of `isFight()` method such that it should _return `clash`_ when it satisfies the constraint. Otherwise it should _return `peace`_. The given constraint is that a Super Hero and Super-Villain with strength greter than zero should be there to make a clash.

## Trial 2: CONSISTENCY AFFORD REFUGE !

Dustin and Lucus wants to display the scores of teams. So to get scores add logic to the `calculateScore()` method, use reduce array method to  loop through players, such that it should _return the score_ for the both the teams.

## Trial 3: WINNER WINNER CHICKEN DINNER !

Check whether there is a winner by adding your logic to `checkWin()` method. If winner exists then based on the players type _return `hero`_ or _return `villain`_. If winner dosen't exists then _return `endure`_.

## Trial 4: UNITY IS STRENGTH !

Hurray we're just one step away from the completion ! Add the logic of `totalScore()` method, such that it should _return total strength_ of the team. Where team type is passed as parameter.

## Expected Output

![Superwars](doc/superwars-complete.png)