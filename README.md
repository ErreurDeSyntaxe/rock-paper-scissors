# rock-paper-scissors
An in-browser console game of paper, scissors, stone

# First Entry: Thinking like a programmer

My objective at this stage is to follow the guidelines
explained in the problem solving lesson: understand the 
objectives, plan from the interface to the input and output 
and algorithms, write pseudocode, and divide tasks. 

The goal is to create a game played through a browser's
console. The game is Rock paper scissors. Rock beats scissors.
Scissors beat paper. Paper beats rock. The players plays
against the computer. The computer randomly selects a hand.
The user writes their own choice into the console. The computer
determines the result of the round and the console displays 
the result of the round: win, loss, draw. The computer offers 
to play once more. 

Some difficulties that I predict will arise are the validation
of the user's input. Typos and voluntarily wrong input could
trip up the process. 

The algorithm checks the input and compares it to its own
randomly determined hand. It displays one of three possible 
messages. It starts a new game.

# Second Entry: Final Push

I forgot to journal my experience writing this program, but I
didn't forget to commit often. That's still a lesson learned
from the first project: the recipe page. 

The whole project was way easier than some Redditors made me
believe. It took about 3 to 4 hours of dedicated work to 
complete. I met all objectives and added one or two that I
thought would be an appropriate challenge for my level.

# Third Entry: Not wanting to move on

I enjoyed coding this project from idea to reality. It was
fun to see it take shape and think about ways to achieve each
small objective. I don't really want to read the next lesson's
content because projects are much more engaging. Lessons can 
seem boring after a project. Such is life. 

I came back for two reasons, then. First was to procrastinate.
Second was to clean up the code because the lesson right after
the project was about writing clean code. I learned some things
and wanted to apply them. Notably, the length of some lines of
code was beyond what is considered good practice. There was also
score display during the game, which felt wrong. Now the game
displays the score at the end of each round.

Looking at other people's code, I am impressed by the brevity of
some functions. It's excellent work on their part. I have much 
to learn, that much is clear. I'll look at more than just one, now
that I think about that. I just saw the number 1 liked.

I am now surprised that most people compared the strings of both
the player's and the computer's selection. They checked
if(playerSelection == "scissors" && computerSelection == "paper").
I seem alone to have compared the array position. Maybe it was
foolish to do so. When we come back to this project, it could be
a good exercise to start from scratch and use a different approach
to solving it.

# Fourth Entry: Back in Black

I struggled with arrows functions and callbacks (I still do) for
a few days, but made it to the lesson which brings students back
to the RPS game to build an interface. Let's go!

First question: should I build the UI in html? My instinct is to
do so because it is cleaner to add the page elements that must 
be present in the html. But the past lessons have all been about 
creating stuff in the .js file. I want to check other students' 
projects, but I don't want to shoot myself in the foot doing so.

What must be there? What should be added dynamically? Should I
review my flexbox knowledge and build a clean but simple layout? 
Poser la question, c'est y répondre. I'll start by making a page.
html and CSS, here I come.

# Fifth Entry: Flexbox Nightmares

It's been a week since I touched flexbox, and it feels like I forgot
everything I knew. Everything is so hard! I need to practice, but I
also need to make headway in TOP, so there's no time to lose on
a single skill. Still, the disappointment of powerlessness stings.

# Sixth Entry: Layout and Inner Workings

The page layout is simple, but it does the job. The footer is at the
bottom, the body takes the whole page. It was tough, but it happened.
The game now computes through buttons instead of prompt. It was tricky
to refactor the code, but that's what happens when a newbie writes
code; the code sucks.

I'll move on to targeting the DOM to display the score instead of
using the console. It shouldn't be too difficult, but then again,
the page layout was supposed to be simple too. Let's commit first.