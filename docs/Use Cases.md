User Stories
============
As a teacher, I want to review my lesson to students.

As a student, so that I get credit, I want to join a quiz game.

Informal Use Case
===================

##UC1 : Create Question Pool
gather all questions and answers, arrange and orgainize it into database.

##UC2 : Join a Game
Student enters the game ( or game site ) and identifies himself. Then he selects the game he wants to join. The game adds the user as a contestant.

##UC3 : Find Matches
students can quicky find their competitors if they has no specific competitor or game to join, then move contestants to the picking state where they can choose what question to answer.

##UC4 : Contestant choose Question to answer
After contestant Enters the picking state, a bunch of questions available will be displayed on the screen, seperated by question categories, and its points according to its difficulty. the contestant must select the question in limited time otherwise the game will randomly choose it for the contestant. Then, moves to the answering state.

##UC5 : Contestant Answer a question
A question will be displayed on the screen, a contestant presses a buzz to indicate he can answer it. the contestant  have to fight over each other to press a buzz, whoever press a buzz first will get a chance to answer the chosen question. The moderator or game selects the first contestant who presses his buzz to answer the question. If contestant answer correctly he earns points otherwise he loses points equal to the point value of the question.

##UC6 : Continue to the next question
After the answer is revealed, if the answer is correct, let the contestant choose the question again until there is no more question or the contestant fail his answer, otherwise, let the contestant's opponent choose instead.

##UC7 : End the game and show the winner
when the last question finishes and there's no more question to be answered. show the winner of the game which is calculated by the game point of each team.
