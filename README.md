# [Blooket](https://www.blooket.com) Cafe Bot


## This is probably the simplest thing I have ever made. All it does is farm coins on Blooket.

**How it works**: it uses [Pyautogui](https://pypi.org/project/PyAutoGUI) - a [Python](https://www.python.org) package that can controll your mouse and keyboard - to spam left click and space. Once the blooket is over, I force quit the script via Task Manager.

**Why it works**: Blooket calculates coins based off how many questions you get right, not how much you actually play the game. In solo cafe, you can answer as many questions as you can (before time runs out) without playing the game at all. The spam click clicks the right answer (which is all of them - the blooket set has one question and all answers are right), and the spam space goes to the next question. Once the time runs out, the bot has answered enough questions to get the maximum amount of coins per Blooket game (100).

*Have questions? Ask them [here](https://github.com/obvMath/blocket-cafe-bot/issues).*
