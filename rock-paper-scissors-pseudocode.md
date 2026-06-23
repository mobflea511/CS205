## Pseudocode – Rock Paper Scissors Game

START

SET userChoice
SET computerChoice

GENERATE random number between 1 and 3
IF number = 1 THEN computerChoice = rock
IF number = 2 THEN computerChoice = paper
IF number = 3 THEN computerChoice = scissors

DISPLAY "Enter rock, paper, or scissors"
GET userChoice

DISPLAY computerChoice

IF userChoice = computerChoice THEN
 DISPLAY "Tie"
ELSE IF userChoice = rock AND computerChoice = scissors THEN
 DISPLAY "User wins"
ELSE IF userChoice = paper AND computerChoice = rock THEN
 DISPLAY "User wins"
ELSE IF userChoice = scissors AND computerChoice = paper THEN
 DISPLAY "User wins"
ELSE
 DISPLAY "Computer wins"

ASK "Play again?"
IF yes, repeat
ELSE END

END
