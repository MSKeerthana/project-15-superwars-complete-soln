# Superwars Complete Solution

## Milestone #5: Select players to clash, from the clash result calculate score and announce winners if exists.

1. Create a class for `Player` such that it contains fields like id, name, strength, image url, type and methods like `getRandomStrength()`, `view()`.
    * Use default `strength` as any number.  
    * `image` can be sequential i.e. "images/super-"+(i+1)+".png"  
    * `type` of player can alternating between hero and villain or your own logic
    ```javascript
    [
        {
            id:1,
            name:"Super Man",
            strength:100,
            img:"images/hero-1.png",
            type:"hero|villain",
            selected:false,
            wins:0
        }
    ]
    ```
    * In `getRandomStrength()`, return a random strength from 1 to 100.
    * In `view()`, accumulate HTML template as below and return it.
    ```JS
    <div class="player" data-id="${players[i].id}">
        <img src="${players[i].image}">
        <div class="name">${players[i].name}</div>
        <div class="strength">${players[i].strength}</div>
    </div>
    ```

2. In class `Superwars`, loop through passed constant and  create `Player` Objects, it also has the following methods.
    * In `viewPlayers()`, display players in HTML.
    * In `buildPlayers()`, build players fragment.
    * In `handleSelection()`, handle player clicks.
    * In `isFight()` , check for clash.
    * In `fight()` , make fight.
    * In `calculateScore()`, calculate the total score of teams.
    * In `checkWin()`, check whether there is a win.
    * In `totalStrength()`, find total strength of a team.
    * In `announceWinner()`, announce the winner.
     