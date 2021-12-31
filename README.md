# Quiz-competition

Overview
This is a simple quiz game which supports two players (or teams).

The idea is that teams get questions alternately and if the first one does not give correct answer, the other gets a chance. If neither answers correctly, that’s a tie. Another way to play is to have teams use buzzers of some kind to determine which gets the first try at the question. The way I’ve used the script is by having two asymmetric teams and the smaller one always getting the first chance.


Usage
First of all, you should check print preview and print the web page as it will give you list of questions and answers for each category. If your questions are not too long you should get one-page per category printout. This may be helpful when hosting the game.

Controls of the game itself should be straightforward. As you open the site, a grid shows up with category names at the top and boxes indexed from 100 to 500 for each question in the category. Clicking on a box brings up a question board with the question, an “x” link in top right corner and three links at the bottom: “Team 1”, “Tie” and “Team 2” (the text depends on values of configuration variables in quiz.js file).

Pressing “x” hides the question board in case you’ve clicked it by mistake. “Team 1” and “Team 2” links will hide the question board, add grant appropriate amount of points to given team. The “Tie” button shows the answer to the question and replaces bottom links with a single “Close” link, which disables the question without adding points to either team. Disabling the questions greys corresponding box out and makes it impossible to display the question board again.

Lastly, team scores are displayed on the bottom. If there was any kind of mix-up and scores need to be altered it’s enough to click on the number and a prompt will show up where one can enter new score for given team.

And that’s about it, when it comes to usage – not very complicated.
