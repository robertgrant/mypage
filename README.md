## Note! I no longer use Github. This repo may be out of date.

All my ex-Github repos are now stored and maintained at [my personal website](http://www.robertgrantstats.co.uk/code.html).

Why did I leave Github? Because I consider the compulsory imposition of 2-factor authentication to be inappropriate for people writing software, including cryptography, which can attract severe punishments in certain jurisdictions. We all know that the organisations that hold the 2nd factors (mobile telephony providers, tech companies) are compromised, willingly or otherwise, in their relationships with security agencies, benign or otherwise.

Why not just close it down? Because you might use it programmatically, via http or API, and I don't want to hurt you (by breaking your code) while trying to help you (by raising issues of privacy and confidentiality).





# mypage
Homepage for browser, with time progress bar and to-do list. Like Momentum but private. And basic. SO basic.

### How to use it

1. Clone or download the repository.
1. Either [download d3.v5.min.js](https://d3js.org/d3.v5.min.js) into the same directory as mypage, or change line 53 to point to that address. If you download, mypage will work even when you are offline (I recommend this).
1. Optional: change the title in line 33. This is displayed at the top of your browser and in your history, etc.
1. You _might_ like to change the fonts in lines 38 and 43. I use this on an Apple machine and have Helvetica, but Win***s users probably won't, and it will default to some nasty business like Arial.
1. Change your start time for work on line 62
1. Change your end time on line 63
1. Change to your tasks in lines 67-69. Be careful to have a comma after every task, match opening and closing quotes, leave the first item blank (line 66) and have no comma at the end.
1. I give you my photograph of the South Downs from Ditchling Beacon in full resolution. If you want something different, you can change the file (and path) in line 79
1. Save your changes, and open or refresh it in your browser.
1. Feel calm and focussed. When you have done a task, click it and it will go green and be struck through.

Note! dear reader. This is a privacy-preserving tool. Nothing communicates your tasks to the outside world (of course, if you have snoopware open at the same time, more fool you). And I want to keep it simple (no starting Python web servers), so the fact that you have "done" a task is not saved anywhere. Refresh and they will all go back to being undone. You can just delete them from the mypage.html file at the end of the day.

### I ought to ...

* Have the bar go a different colour when you exceed end time
* Allow tasks to be un-done again
