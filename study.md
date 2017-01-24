# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
  -![wireframe](http://imgur.com/a/UzOUi)

-   The data structure you plan to use.
    - I plan to use array of arrays for my tic tac toe board and in my outside array I have 3 rows and in each one of those rows I have 3 cells.
    - The cells [items] may either be a string or an object depending on if additional information is needed.
-   How you will take the markup of the game board and represent it in JS
    - I think I will use an array of arrays as divs. Each one of my cells will be a div. I will loop through my array of arrays to create divs.
-   How you plan to approach this project.
    - make a board = [row1, row2, row3]: row1,2,3 are arrays.
    - loop through this to make a board using divs in HTML depending on the div, have different borders. example: board[0][0] has no top
    - each div has attribute called piece played which stores x or o.
    - Add event listener to all my divs for when it is clicked it saves the x or o, depending on playerx or playero.
    - write functions to check conditions for when a cell is empty or filled.
    - write function to convert my row of rows to the cells that the data store handles.
    - save results of all games to data store.
-   4-8 user stories for your game project.
    - As a player, I would like to play my turn by clicking a box.
    - As a player, I would like to know when I win so I dont keep playing.
    - As a judge, I would not want two boxes be clicked so the game can be fair.
    - As a competitor, I would like to know the current score so I can see who is winning.
    - As a quitter, I would like to sign out so I can leave.
    - As a player, I would like to know what shape I am, to play the game.
-   How you plan to keep your code modular.
    - I will make seperate files to keep my codes seperate. I will add comments to seperate the code within the file.
-   What creative spin will you add to your project?
    - I will add audio files for when the cell is clicked.
-   How will you use version control to backup / track your project?
    - I will backup my project in git hub and make use of branches to make sure every new feature does not break an old one.
-   Do you plan to attempt any of the bonuses?
    - I do not plan to attempt any bonuses until I am done with my project.  If i have time left over then I will try my best to complete a bonus.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).
