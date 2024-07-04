# Tic Tac Toe Game in React

This is a simple Tic Tac Toe game built using React.

## Features

- Play a game of Tic Tac Toe
- Responsive design
- Reset the game to play again

###steps to create the project 

installation done by using 
npx create-react-app .
=> . to create project in current folder
npm start 
src -> App.js(clear the page)
public -> index.html (rename site title)
src -> Components -> Assets
                  -> TicTakToe -> TicTakToe.jsx convert this file into component using rafc
				                       -> TicTakToe.css and import it into jsx file 
mount the jsx component into App.js(import)
insert assets into Assets folder and import them into component
then form a html page in component only 
for basic css do in index.css of background color 
and other css in TicTakToe.css
create board and rows and boxes
initialise the variables and references
create the functions => toggle , checkWin , won , reset.
