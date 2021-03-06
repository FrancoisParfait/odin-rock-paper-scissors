# odin-rock-paper-scissors
TOP Project 3 - Rock Paper Scissors game

This is my first JavaScript project! I'm pretty excited to get going on it - honestly, so far the other Odin projects have been a bit boring. Not that they were easy, though. I really struggled on the landing page project in a few different areas. It's just not necessarily what I'm interested in terms of programming, I guess. I don't want to just lay out a webpage, or whatever. I know that that's a huge part of web dev, but I guess maybe I'm just not interested in web dev like I thought. It'll be nice to make something that actually DOES something - even though at first I'm just going to be running this in the console, without a GUI.

So far, I've been using these readme's as a way to catalog my thoughts before and after working on the project. I know that's not necessarily what I'll always be doing with projects I post on here, but right now while I'm in the learning phase I think it's a good idea.

With this project I definitely need to dedicate some time to actually planning it out, using pseudocode and such. I haven't had to do that yet with the webpages, simply since it's just laying things out, not using any sort of functions. With this, I'm going to be writing code that actually needs to run in a certain way, so some planning seems imperative to making this turn out right.

I'd like to be able to debug/problem solve on this all without looking at a user solution, too. Last time I did peek at one when I still had a couple issues with the page. I just felt so stuck that I couldn't handle it anymore, which is pretty antithetical to how a programmer should operate, haha. The core of all development, as far as I have learned, is problem solving. So if I can't learn to do that effectively, then I'm not a programmer.

Anyway, those are my thoughts going into it. Will update with a post-mortem once I finish!



POST-MORTEM-THOUGHTS:

Dang, that was difficult.

Like literally every project/exercise thus far, I thought that this would be fairly simple to start off. And it was, relatively, at the beginning. I understood and wrote the pseudocode for what I think needed to happen to play a round of the game, and I did that. This got me through the first few parts of the assignment, but I had no idea what was in store for me now.

I needed to make 5 rounds of the game, store scores, and output a result at the end saying who won and who lost. For some reason, I just couldn't get the 5 rounds thing down. Any way I seemed to try it, my function call wouldn't repeat - it would only fire the first time and that was it. I realized this was because the user input prompt wasn't stored inside the playRound function, but I couldn't declare it inside of the function because it was a parameter of said function. So, I spent HOURS Googling my everliving butt off, and banging my head on the keyboard, trying to figure out how to fix that problem. I tried reworking the function to not include parameters, but thought I had to because the project page had me start it that way.

Anyway, I did end up browsing through a few solutions (not the ones listed on the project page, mind you) for other versions of rock paper scissors just so I could get my bearings a little. It wasn't at all like copy and pasting code from one project to another. Honestly, it only helped a little because I still wasn't understanding it, I think. 

Eventually, I did figure out how I could change it, and did end up taking the parameters out and declaring the variables inside the playRound function. I also ended up using a loop instead of calling it multiple times - which I looked up and learned how to write - but I want to go back and make a version where I do what I was originally intending to do, which was call the playRound function multiple times. I know there are various other things here that could be much cleaner and simpler, but I'll also be revisitin this later on apparentely, so maybe I'll rework it then.

I'm a little disappointed in myself for not staying away from solutions completely, although in this instance I think that I still learned a ton even though I did. It still required me to understand what was wrong and how I could fix it rather than just copy/paste without any knowledge of why you need to do that specific thing. 

I also think I need to get into asking questions on the discord for Odin, or stack overflow. I did hit a point where I was at my wit's end, and asking a question would've helped, I just didn't know how to phrase it and didn't want to come off the wrong way, I guess. But it definitely could've helped having other eyes on my code to point out obvious or not obvious things that I'm missing. 

Anyway, glad to be done. The game works as intended, and I'm happy to be moving on.



REVISIT:

Okay, so I'm back to this project now after a break with some other lessons. This time, I'm going to attempt to add a UI to the game so that it's not just played inside of the console.

As always, I'm feeling pretty confident at the start that this won't be too difficult. But at the same time, I also know that's probably not true, as it hasn't been with every project, haha.

Again, I'm just going to try to apply the problem-solving skills I've been working on so far to this, and avoid looking up solutions and such before I get it working. We'll see how it goes!


POST-REVISIT:

Alright, that actually went super well!

I actually had to change my original code quite a bit from how it was. This included changing it to including playerSelection as a parameter, since that was necessary for the buttons to work with pre-loaded selections. So that took a bit of time, but I actually was able to do it pretty much all on my own, with Google providing some help here and there. Didn't look up any solutions or copy/paste code, so that was nice!

CSS continues to be a bit annoying, and the styling took a little while. Styling this is also kind of a black hole because you could always make it look nicer, so I opted for a pretty simply design for now. Who knows, maybe I'll come back later and make it look cooler. 

But all in all, the revisit went very well, and I feel like I did a good amount of problem solving on it! On to the next project.