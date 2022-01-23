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


<!--
### R1Dx: January x, xday
**Today's Progress**: Coming soon

**Thoughts**: Coming soon

**Link(s) to work**: [coming soon](http://www.example.com)
-->
