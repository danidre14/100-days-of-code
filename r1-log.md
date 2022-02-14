# #100DaysOfCode Log - Round 1 - Danidre

The log of my #100DaysOfCode challenge. Started on [January 8th, Saturday, 2022].

## Log

### R1D1: January 8th, Saturday
**Today's Progress**: Maxed out my stats on freeCodeCamp's Learn To Code RPG in preparation for the [2022 Resolution](https://www.freecodecamp.org/news/2022-become-a-dev-new-years-resolution-challenge/).

**Thoughts**: Technically I did not code, but I mentally prepared myself and read about code, which counts in my book. 

**Link(s) to work**: [Twitter Statement](https://twitter.com/danidre/status/1479853021161009160)


### R1D2: January 9th, Sunday
**Today's Progress**: Learned bash by completing the bash tutorial from freeCodeCamp's Relational Database Certification, as well as created a figma mockup for my game engine editor's landing page and fixed bugs in the flevar editor.

**Thoughts**: Although it is 100DaysOfCode, and the FAQ considered tutorials out of "proper" coding logs, I want to include it daily, since my plan is to complete the 300 hour database certification within the 100 days of code, and all other programming/code secondary. As for the figma mockup, I duplicated a general theme found on figma and went about adding my own resources. It'll be a while of contemplating what stack I should use to actually create it. I want to host it on https://flevar.com soon. As for the FlevaR Editor bug fixes, I discovered those bugs during a [game jam](https://itch.io/jam/toast-2021/rate/1325405) last year, so I went about finding the causes and fixing the bugs today. I want to host the editor on `https://editor.flevar.com` soon. _(Currently it's on `flevar.com`)_

**Link(s) to work**: [Flevar Editor (WIP)](https://flevar.com)


### R1D3: January 11th, Tuesday
**Today's Progress**: Started working on the landing page for the FlevaR Editor

**Thoughts**: I've decided to use Express and TailwindCSS for it. I planned on one hour alone but spent all day trying to figure out why some styles would not show up when building. Turns out I needed to remove the `mode: "jit"` flag and it would show up. :)

**Link(s) to work**: [Twitter](https://twitter.com/danidre/status/1481051874904186886)


### R1D4: January 12th, Wednesday
**Today's Progress**: Started working on FlevaR's landing page.

**Thoughts**: It took a while for me to regain familiarity with tailwind. I started with a preset template and customized it to FlevaR. I have no wifi today to check tailwind's documentations, so fortunately a VSCode extension would give me a suggested class to use depending on my closest guess of what I want. I created the placeholder menus for 'learn', 'about', and 'blog' pages; I will fill them in at a later time. The 'create' link would go to `https://editor.flevar.com/`, which is the main purpose of the landing page currently.

**Link(s) to work**: [FlevaR Editor](https://www.flevar.com)


### R1D5: January 13th, Thursday
**Today's Progress**: Made FlevaR's landing page responsive and ready to be uploaded.

**Thoughts**: Tailwind's media queries were a bit counter intuitive. I had to remind myself: build for small screen, alter for larger screen. It took a while to look satisfactory on all screen sizes, getting the footer and menu correct with the proper spacing even on smaller screens was fun to do. I still do not have wifi to look for fonts, but it is ready to go live.

**Link(s) to work**: [FlevaR Editor](https://www.flevar.com)


### R1D6: January 16, Sunday
**Today's Progress**: Today I completed a Celestial Bodies Database Certification on freeCodeCamp.

**Thoughts**: With requirements of database schemas, it is always important to spend time planning what tables and pieces of data should go where. While you can alter tables for added information, I find it best to plan and know in advance so you can add the constraints and create the tables all at once.

**Link(s) to work**: [Twitter Status](https://twitter.com/danidre/status/1482776360934334466)


### R1D7: January 17, Monday
**Today's Progress**: Today I learnt more bash commands from freeCodeCamp's Database Certification, but ultimately got stuck. 

**Thoughts**: Unlike the previous projects, so far most of the exercises require self research to figure out, which is very tedious. One would expect to be made known what commands to use and later expected to remember it, but I was left to fend for myself. It was very frustrating since I had to start over for every little mistake since I did not know any easier methods, and google resulted in strange commands I have never seen before. For some reason, at one point it idid not seem like I can make future progress, even by finally figuring things out and doing exactly what they asked. In the end, I only went from 3% to 8% progress in one hour. I might actually have to start over tomorrow, but I've given up for today.

**Link(s) to work**: [Twitter Status](https://twitter.com/danidre/status/1483198589308444672)


### R1D8: January 18, Tuesday
**Today's Progress**: Today I made more progress learning bash commands.

**Thoughts**: There are many ways to find options about commands; man (manual) command, help command, command --help...Also a nano command allows much more efficient editing of files without having to use sed, etc to append or alter lines in files. After a little more than an hour, I only completed about 34% of the project, but it is much more progress then yesterday so I feel more positive and motivated about continuing it.

**Link(s) to work**: [Twitter Status](https://twitter.com/danidre/status/1483598605843894279)


### R1D9: January 19, Wednesday
**Today's Progress**: Today I made even more progress with bash and command shell lines and completed another project in the freeCodeCamp Relational Database Certification.

**Thoughts**: Commands like sleep, square bracket or parenthesis if statements, arrays, etc made it fun to create the 5 programs in this project. It's been easier to made progress, as I have gotten more familiar with certain commands and can do them quickly. I may return to this project to practice conditional commands and RegExp expressions again.

**Link(s) to work**: [Twitter Status](https://twitter.com/danidre/status/1483967303976984582)


### R1D10: January 22, Saturday
**Today's Progress**: Today I changed some links on the FlevaR Editor landing page.

**Thoughts**: Rather than have useless links on the site that led to hastag (#) hrefs, I decided to put links to existing pages and additional information related to FlevaR. Unfortunately I missed 2 days due to a physical injury, but I tried to at least get some coding in today, as little as it wash. The changes have been pushed to main and deployed!

**Link(s) to work**: [FlevaR Editor](https://www.flevar.com)


### R1D11: January 23, Sunday
**Today's Progress**: Today I learnt how to run https on localhost, added ruffle to the flash games on my website, and completed another project on freeCodeCamp's Relational Database Certification.

**Thoughts**: I store .swf games on a separate url/server and embed them, so originally I had cross origin errors. I learnt how to run https on local host using certificates generated by mkcert and trusted on the local PC. However, in the end I added the ruffle emulator to the flash server itself. Since my website hosts those flash embeds from the server, it will load the ruffle emulated version and thus work on my website once again. Finally, I created a castle using nano. It looks like this:

![image](https://user-images.githubusercontent.com/10374096/150698812-28d2a5b9-c1ad-40ef-b559-402bdb90f9ea.png)

This project was very simple for me because I had prior experience with nano from the previous freeCodeCamp projects I did. They should have put this project above the others, since it was a more beginner friendly course; rather than me learning nano on my own through google, research, and help from other developers.

**Link(s) to work**: [Danidre Games _(last 4 games are old flash games)_](https://danidre.com/games/)


### R1D12: January 24, Monday
**Today's Progress**: Today I learnt advanced bash by building a kitty ipsum translator! Sed and grep are fun commands, and redirecting outputs and/or piping inputs is quite powerful and useful!

**Thoughts**: The freeCodeCamp project took me about 3 hours to complete today, since I was dedicated to finish it. It refreshed me on commands I knew before (nano, echo, man) and taught me new commands (2>, 1>, |, grep, sed) as well as a few useful regular expressions. In my opinion, this project did a great job at reinforcing what was being taught, and somehow this time doing repeated actions was more fun than tedious, since I had the options of exploring the different flags for different commands and test out what I remembered, before committing them to files. It sure beats copy/pasting, and made it enjoyable.

![image](https://user-images.githubusercontent.com/10374096/150889217-8f64cbc3-6dc1-4ee6-9659-7770fa942239.png)

**Link(s) to work**: [Twitter Status](https://twitter.com/danidre/status/1485775100708331523)


### R1D13: January 26, Wednesday
**Today's Progress**: Today I stress tested my game engine and created a simple way to host/view sample games.

**Thoughts**: I have many optimizations to make on the engine. I learnt that you can send individual html files in express even if it is using the ejs view engine. I had trouble providing the html of the game from the public static folder, so I had to server it to the client using a route.

**Link(s) to work**: [Stress Test: Engine Prefab vs Raw Object](https://flevar.com/sandbox-samples/stress-test-engine-prefab-vs-raw-object.html)


### R1D14: January 27, Thursday
**Today's Progress**: Today I learned a few git commands, including checkout and branch, as well as flags such as --oneline (for git log)

**Thoughts**: So far the git project on freeCodeCamp has been easy to do. It drew upon previous knowledge such as nano and bash commands, which I confidently performed as I am not more proficient in the skill. I did not finish the project within the hour, but I did make significant progress for the day.

**Link(s) to work**: [fCC New Years Resolution](https://www.freecodecamp.org/news/2022-become-a-dev-new-years-resolution-challenge/)


### R1D15: January 28, Friday
**Today's Progress**: Today I learned more git commands, and inevitably had to rebuild the fCC docker project container due to an error on their end.

**Thoughts**: Rebase is a very tricky tool, resolving complex conflicts; and who knew `git stash` existed? 😮 I feel like I'm getting better at the commands from memory (such as git checkout) so although I feel discouraged having to start it over due to lost data, I know that I'll be back up to speed in no time.

**Link(s) to work**: [fCC New Years Resolution](https://www.freecodecamp.org/news/2022-become-a-dev-new-years-resolution-challenge/)


### R1D16: January 29, Saturday
**Today's Progress**: Today I practiced scraping data from a website to present in a more readable format.

**Thoughts**: I learnt that it is convenient to scrape web data for use cases such as scraping open graph meta tags to display rich embeds for links in your webpage. I have not used jQuery before, but Cheer.io boasts to be similar, and it was easy to get the required data necessary.


### R1D17: January 30, Sunday
**Today's Progress**: Today I wrote and tested an API using VSCode's REST API extension.

**Thoughts**: I had the extension on my computer for two years (possibly by following an old tutorial) but never personally used it until now. Files end in `.rest` and you can click them according to their syntax, to make the desired API request. I used this with the express API to test out the web scraping practice I did yesterday.


### R1D18: January 31, Monday
**Today's Progress**: Today I learnt about ArrayLists and the extends keyword in java.

**Thoughts**: When a class extends another, you can call methods of the superclass without creating them in the subclass. Additionally, you can access super variables by declaring them as protected. I have much more experimentation to do.


### R1D19: February 1, Tuesday
**Today's Progress**: Today I landed my first Software Development job!

**Thoughts**: I was able to use the knowledge learnt from freeCodeCamp's bash tutorials to complete assigned tasks adequately.


### R1D20: February 2, Wednesday
**Today's Progress**: Today I confused myself over cors and browsers with fetch requests.

**Thoughts**: You must include the 'content-type' in fetch requests and the API must have cors enabled...but the fetch requests that worked for Chrome, returned Security errors on Firefox. I took a break after an hour of unsuccessful googling on Firefox's possible issue. (it could be blocked cookies on the browser itself, I do not know).


### R1D21: February 5, Saturday
**Today's Progress**: Today I added an internal console to the engine.

**Thoughts**: Rather than crash when third party cookies are blocked (needed for saving/loading), a console warns the player instead.
![image](https://user-images.githubusercontent.com/10374096/152661572-1e06bcb9-95ff-44f2-a377-0dfbff7715ee.png)


**Link(s) to work**: [Mountain Bell Ski](https://danidre.itch.io/mountain-bell-ski) (test in incognito)


### R1D22: February 7, Monday
**Today's Progress**: Today I practiced encrypting data in python using ceasar cipher and OTPs. 

**Thoughts**: The keys and encrypted content was transmitted via sockets on different hosts, and the receiver was able to decrypt the key and message using the OTP. It was a really fun project, as it gave me a deeper understanding of even the basics of security and encryption.


### R1D23: February 8, Tueday
**Today's Progress**: Today I profiled the performance of a stress tested "game" created in my editor, powered by my engine.

**Thoughts**: Code abstractions (getters/proxies) intended to make the developer's life easier resulted in much slower operations at scale. Because of this, it takes 80% of the time to tick, and 20% to render (so rendering isn't even the bottleneck). I've used Firefox, Chrome, and Edge's profilers and thoroughly documented any removals, fixes, changes, optimization or more than I'd need to make. It may involve changing the architecture of the engine, but I believe it can be done with time.

**Link(s) to work**: 
- [Stress Test: Engine Prefab vs Raw Object](https://flevar.com/sandbox-samples/stress-test-engine-prefab-vs-raw-object.html)
- [Twitter Status](https://twitter.com/danidre/status/1491270551351881730)


### R1D24: February 10, Thursday
**Today's Progress**: Today I...read some programming related articles...

**Thoughts**: It's been a really exhausting and draining few days where I'm not even getting time to program. I figured I can at least read something for about 30 minutes, rather than just keep missing days.


### R1D25: February 11, Friday
**Today's Progress**: Today I worked on optimizations in my game engine.

**Thoughts**: Previously, at 1000 flevaclips, each loop took 300ms to perform. I was able to reduce this to 100ms per loop at 1000 flevaclips. However, the countless getters I've created puts a huge bottleneck on the engine, which prevents it from being reduced to the ideal 10ms per loop. The final verdict is now to restructure the architecture of the engine, or re-write the engine.


### R1D26: February 13, Sunday
**Today's Progress**: Today I was able to reduce the tick from 40ms to 3.1ms by using a lookup table instead of a for loop.

**Thoughts**: A slight increase in memory consumption, for an effective increase in performance. 🤩 Instead of looping through hundreds of flevaclips per frame to detect a matching UID (which takes longer the more flevaclips), I simply, upon flevaclips instantiation, add that UID to an object variable as the key, along with the referenced flevaclip as the value. Then, instead of looping each frame, I simply check the object variable for that existing UID and relative flevaclips reference. O(1) instead of O(n).


<!--
### R1Dx: February x, xday
**Today's Progress**: Coming soon

**Thoughts**: Coming soon

**Link(s) to work**: [coming soon](http://www.example.com)
-->
