---
tags:
  - coding
props:
  startDate: 12-26-2019
computed:
  daysIn: Math.ceil(((new Date()).getTime() - (new Date('${startDate}')).getTime()) / (1000 * 3600 * 24))
  daysToGo: 100 - Number(${daysIn})
  startDay: (new Date('${startDate}')).toDateString()
  today: (new Date()).toDateString()
  now: (new Date()).getTime()
template: |
  :100: Days of code, Day ${daysIn}: ${today}
  :rocket:  
  :thought_balloon:  
  :link:  
  #100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger
links:
  - pack: fab # Can be fab or fas https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
    icon: fa-twitter # The font-awesome icon to use 
    title: Tweet this card
    href: https://twitter.com/intent/tweet?text=${encodedText}%0A@imdoneio
---

# 100 Days Of Code - Log
<!-- 
#NOTE:0 # :100: Days of code: Day ${daysIn} expand:1
**Days to go: ${daysToGo}**
**Started on: ${startDay}**
- [Rules](rules.md)
- [Log - click here to see my progress](log.md)
- [FAQ](FAQ.md)
- [Resources](resources.md)
- [#100DaysOfCode Official Website](https://www.100daysofcode.com/)
- [#100DaysOfCode on Twitter](https://twitter.com/search?q=%23100DaysOfCode)
- [Edit My 100 Days of Code log](log.md:0:1)

[# Keyboard shortcuts expand:1](#NOTE:10)
| Action                        | Shortcut                                |
|-------------------------------|-----------------------------------------|
| Navigate Selected Card        | :arrow_up: :arrow_down: :arrow_left: :arrow_right:|
| Move Selected Card Up         | shift+:arrow_up:                        |
| Move Selected Card Down       | shift+:arrow_down:                      |
| Move Selected Card Left       | shift+:arrow_left:                      |
| Move Selected Card Right      | shift+:arrow_right:                     |
| Move Selected Card To Top     | cmd+:arrow_up: or ctrl+:arrow_up:       |
| Move Selected Card To Bottom  | cmd+:arrow_down: or ctrl+:arrow_down:   |
| Edit Selected Card            | return or enter                         |
| Open file of Selected Card    | cmd+o or ctrl+o                         |
| Delete Selected Card          | delete or backspace                     |
| Add a Card                    | space                                   |
| Save Card Edits               | cmd+s or ctrl+s                         |
| Filter                        | cmd+f or ctrl+f                         |
| Clear Filter                  | esc                                     |
| Open Journal                  | cmd+shift+j or ctrl+shift+j (Global)    |
| Cycle through tabs            | ctrl+tab                                |
| Add a board                   | cmd+n or ctrl+n                         |
| Board Settings                | cmd+/ or ctrl+/                         |
| Zoom in                       | cmd+shift+[+]                           |
| Zoom out                      | cmd+[-]                                 |
| Zoom reset                    | cmd+0                                   |

-->

###  [:100: Days of code: Day 2](#DONE:30)
<!-- completed:2020-02-19T17:41:02.250Z -->
#100DaysOfCode
- imdone: Added new card template in frontMatter for 100DaysOfCode

### [:100: Days of code: Day 3](#DONE:10)
<!-- completed:2020-02-19T17:41:02.252Z -->
#100DaysOfCode
- Added tweet button from log.md frontMatter to easily tweet progress

### [:100: Days of code: Day 3](#DONE:20)
<!-- completed:2020-02-19T17:41:02.253Z -->
#100DaysOfCode
- Added frontMatter variables to imdone to automatically show day's progress

### [:100: Days of code, Day 3: Sat Dec 28 2019](#DONE:2.5)
<!-- completed:2020-02-19T17:41:02.253Z -->
**Today's Progress:** Added the standard log.md entry as task template
**Thoughts:** Looking good so far, hopefully release by monday!
**Link to work:** [imdone.io](http://imdone.io)
#100DaysOfCode

### [:100: Days of code, Day 4: Sun Dec 29 2019](#DONE:1.25)
<!-- completed:2020-02-19T17:41:02.254Z -->
**Today's Progress:** Implemented YAML config for imdone
**Thoughts:** Much cleaner layout and consistent with use of frontMatter
**Link to work:** [imdone](https://imdone.io)
#100DaysOfCode

### [:100: Days of code, Day 5: Mon Dec 30 2019](#DONE:0.625)
<!-- completed:2020-02-19T17:41:02.254Z -->
**Today's Progress:**
- Added maxLines config setting for imdone
- Fixed bug allowing cards with no title  
<!-- -->
**Thoughts:**
Day job is keeping me from releasing imdone templates today
<!-- -->
**Link to work:**
#100DaysOfCode

### [:100: Days of code, Day 6: Tue Dec 31 2019](#DONE:0.3125)
<!-- completed:2020-02-19T17:41:02.255Z -->
**Today's Progress:**
- Worked on imdone release 1.4.4
<!-- -->
**Thoughts:**
- Still not ready to release 100DaysOfCode template, but getting close
<!-- -->
**Link to work:** imdone.io
#100DaysOfCode

### [:100: Days of code, Day 7: Wed Jan 01 2020](#DONE:0.15625)
<!-- completed:2020-02-19T17:41:02.280Z -->
**Today's Progress:**
:hankey: Added much needed restartWorker() to imdone.  
**Thoughts:**  
:hankey: Woke up to find my imdoneboard wasn't working due to the proces dying overnite.  
**Link to work:**  
imdone.io  
#100DaysOfCode #EatYourOwnDogfood

### [:100: Days of code, Day 8: Thu Jan 02 2020](#DONE:0.0390625)
<!-- completed:2020-02-19T17:41:02.281Z -->
:rocket: **Progress:** imdone is now pulling in github:imdone/templates readme  
:thought_balloon: **Thoughts:** Trying to make it easy for community template creation  
:link: **Links to work:** https://github.com/imdone/templates  
#100DaysOfCode

### [:100: Days of code, Day 8: Thu Jan 02 2020](#DONE:0.0390625)
<!-- completed:2020-02-19T17:41:02.388Z -->
:rocket: **Progress:** imdone is now pulling in github:imdone/templates readme  
:thought_balloon: **Thoughts:** Trying to make it easy for community template creation  
:link: **Links to work:** https://github.com/imdone/templates  
#100DaysOfCode


### [:100: Days of code, Day 10: Sat Jan 04 2020](#DONE:0.01953125)
<!-- completed:2020-02-19T17:41:02.281Z -->
:rocket: **Progress:** Finished ability to add projects from template in imdone.  
:thought_balloon: **Thoughts:** Continue working on pre-populated board for people new to coding.  
:link: **Links to work:** https://github.com/imdone/templates  
#100DaysOfCode


### [:100: Days of code, Day 11: Sun Jan 05 2020](#DONE:0.009765625)
<!-- completed:2020-02-19T17:41:02.282Z -->
:rocket: **Progress:** Finished up some cosmetics around templates  
:thought_balloon: **Thoughts:** Documentation updates are next  
:link: **Links to work:** imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 12: Mon Jan 06 2020](#DONE:0.0048828125)
<!-- completed:2020-02-19T17:41:02.283Z -->
:rocket: Added "Add Project From Template" button to quick start modal  
:thought_balloon: Imdone 1.4.5 will be released tomorrow with 100-days-of-code template!  
:link: https://github.com/imdone/templates  
#100DaysOfCode


### [:100: Days of code, Day 13: Tue Jan 07 2020](#DONE:0.00244140625)
<!-- completed:2020-02-19T17:41:02.283Z -->
:rocket: 100 Days of code template is here!  
:thought_balloon: Plan your challenge with imdone kanban!  
:link: [Templates](https://imdone.io/docs/#/templates)  
#100DaysOfCode


### [:100: Days of code, Day 14: Wed Jan 08 2020](#DONE:0.001220703125)
<!-- completed:2020-02-19T17:41:02.284Z -->
:rocket: Added setting for new card syntax MARKDOWN or HASHTAG  
:thought_balloon: Should make markdown rendering easier to read  
:link: imdone.io
#100DaysOfCode


### [:100: Days of code, Day 15: Thu Jan 09 2020](#DONE:0.0006103515625)
<!-- completed:2020-02-19T17:41:02.285Z -->
:rocket: Fixed MARKDOWN syntax in imdone 1.4.6!  
:thought_balloon: Makes card syntax render cleanly with markdown  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 16: Fri Jan 10 2020](#DONE:0.00030517578125)
<!-- completed:2020-02-19T17:41:02.285Z -->
:rocket: Added a refresh property in front-matter and card metadata  
:thought_balloon: Looking at adding functions for dynamic cards  
:link: imdone.io  
#100DaysOfCode

### [:100: Days of code, Day 17: Sat Jan 11 2020](#DONE:0.000152587890625)
<!-- completed:2020-02-19T17:41:02.286Z -->
:rocket: Updated imdone.io/docs  
:thought_balloon: Made card syntax easier to understand (feedback welcome) :tomato:  
:link: [imdone.io/docs](imdone.io/docs)  
#100DaysOfCode


### [:100: Days of code, Day 18: Sun Jan 12 2020](#DONE:0.0000762939453125)
<!-- completed:2020-02-19T17:41:02.294Z -->
:rocket: :boom: Add due dates using due metadata and natural language processing for imdone 1.4.7  
:thought_balloon: Next will be a column dedicated to what due today or past due  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 19: Mon Jan 13 2020](#DONE:0.00003814697265625)
<!-- completed:2020-02-19T17:41:02.295Z -->
:rocket: Implemented filtered list for cards due today  
:thought_balloon: We can't allow filtered lists to be modified by dragging cards  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 20: Tue Jan 14 2020](#DONE:0.000019073486328125)
<!-- completed:2020-02-19T17:41:02.296Z -->
:rocket: Filtered list is now static and can't be modified. Also has a filter link in the header.  
:thought_balloon: Gotta add a configurable refresh rate for date sensitive filters  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 21: Wed Jan 15 2020](#DONE:0.0000095367431640625)
<!-- completed:2020-02-19T17:41:02.296Z -->
:rocket: Added refresh rate for filtered lists and started "Due in..." display for cards  
:thought_balloon: Tomorrow add filtered lists to board settings  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 22: Thu Jan 16 2020](#DONE:0.00000476837158203125)
<!-- completed:2020-02-19T17:41:02.297Z -->
:rocket: Added filtered lists to board settings  
:thought_balloon: Almost ready for release 1.4.7!!!  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 23: Fri Jan 17 2020](#DONE:0.000002384185791015625)
<!-- completed:2020-02-19T17:41:02.297Z -->
:rocket: Added tabs to board settings  
:thought_balloon: Testing all weekend for release on Monday!!!  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 24: Sat Jan 18 2020](#DONE:0.0000011920928955078125)
<!-- completed:2020-02-19T17:41:02.298Z -->
:rocket: Cleaned up board settings and quick start.  
:rocket: Tested default project and quick start.  
:thought_balloon: Docs and examples are next.  Examples will be included as a template.  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 25: Sun Jan 19 2020](#DONE:5.960464477539062e-7)
<!-- completed:2020-02-19T17:41:02.299Z -->
:rocket: Added save button to board settings  
:thought_balloon: Tonight, keep testing and writing documentation for R1.4.7  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 26: Mon Jan 20 2020](#DONE:2.980232238769531e-7)
<!-- completed:2020-02-19T17:41:02.299Z -->
:rocket: Start and stop every minute refresh on main window focus and blur  
:rocket: Ignore tasks in filtered lists when deleting filtered cards  
:thought_balloon: Finish docs and prepare for release  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 27: Tue Jan 21 2020](#DONE:1.4901161193847656e-7)
<!-- completed:2020-02-19T17:41:02.300Z -->
:rocket: docs, docs, docs, docs  
:thought_balloon: docs, docs, docs, docs  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 29: Thu Jan 23 2020](#DONE:7.450580596923828e-8)
<!-- completed:2020-02-19T17:41:02.301Z -->
:rocket: Released imdone 1.4.7 yesterday  
:thought_balloon: Today - Create and share a short video explaining due dates and filtered lists  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 31: Sat Jan 25 2020](#DONE:3.725290298461914e-8)
<!-- completed:2020-02-19T17:41:02.301Z -->
:rocket: Worked on allowing tags and metadata on any line  
:rocket: Keep markdown from start of line when using MARKDOWN link style  
:thought_balloon: Relase 1.4.8 on Monday?  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 32: Sun Jan 26 2020](#DONE:1.862645149230957e-8)
<!-- completed:2020-02-19T17:41:02.302Z -->
:rocket: Implemented Mustache style interpolation for cards  
:rocket: Worked on documentation for imdone 1.4.8  
:thought_balloon: Maybe an article about the importance of great customers???  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 33: Mon Jan 27 2020](#DONE:9.313225746154785e-9)
<!-- completed:2020-02-19T17:41:02.303Z -->
:rocket: Fixed issue with nested bullet spacing  
:rocket: Updated templates to take advantage of latest imdone features  
:thought_balloon: Make some videos!  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 34: Tue Jan 28 2020](#DONE:4.6566128730773926e-9)
<!-- completed:2020-02-19T17:41:02.304Z -->
:rocket: Make MARKDOWN default card format and default prefix `#`  
:rocket: Fix http protocol for forgot password  
:thought_balloon: Add social cred to home page  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 35: Wed Jan 29 2020](#DONE:2.3283064365386963e-9)
<!-- completed:2020-02-19T17:41:02.305Z -->
:rocket: Keep white space except blank lines in card content
:rocket: Customer outreach email resulted in 2 new customers!
:thought_balloon: Implement auto completed metadata `@cmonterroza`
:link: imdone.io
#100DaysOfCode


### [:100: Days of code, Day 36: Thu Jan 30 2020](#DONE:1.1641532182693481e-9)
<!-- completed:2020-02-19T17:41:02.305Z -->
:rocket: :thinking:  
:thought_balloon: :thinking:  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 38: Sat Feb 01 2020](#DONE:2.9103830456733704e-10)
<!-- completed:2020-02-19T17:41:02.306Z -->
:rocket: Fix bulleted list nested in checkbox  
:thought_balloon: Social cred on site  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 37: Fri Jan 31 2020](#DONE:5.820766091346741e-10)
<!-- completed:2020-02-19T17:41:02.307Z -->
:rocket: Keep blank spaces. It doesn't hurt :)  
:thinking: :thought_balloon: Prep for htofix release   
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 39: Sun Feb 02 2020](#DONE:1.4551915228366852e-10)
<!-- completed:2020-02-19T17:41:02.307Z -->
:rocket: Fix deleting of filtered list  
:rocket: Clean up docs  
:thought_balloon: Social cred on website.  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 40: Mon Feb 03 2020](#DONE:7.275957614183426e-11)
<!-- completed:2020-02-19T17:41:02.308Z -->
:rocket: Released imdone 1.4.12 with change in defaults to MARKDOWN and # as task prefix.  
:thought_balloon: Two minor bugs need fixing for 1.4.13  
:link: imdone.io  
#100DaysOfCode



### [:100: Days of code, Day 43: Thu Feb 06 2020](#DONE:3.637978807091713e-11)
<!-- completed:2020-02-19T17:41:02.309Z -->
:rocket: Added issue templates to https://github.com/imdone/imdone to track bugs and feature requests for imdone  
:thought_balloon: Get started on expand metadata bug  
:link: https://github.com/imdone/imdone/issues/3  
#100DaysOfCode



### [:100: Days of code, Day 44: Fri Feb 07 2020](#DONE:1.8189894035458565e-11)
<!-- completed:2020-02-19T17:41:02.310Z -->
:rocket: Fixed expand meta.
:rocket: Update homepage.  
:thought_balloon: Create a new markdown file for each new card.  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 45: Sat Feb 08 2020](#DONE:9.094947017729282e-12)
<!-- completed:2020-02-19T17:41:02.310Z -->
:rocket: Publish homepage updates.  
:thought_balloon: Fix Board Settings Bug  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 46: Sun Feb 09 2020](#DONE:4.547473508864641e-12)
<!-- completed:2020-02-19T17:41:02.312Z -->
:rocket: Fix image link click to open file  
:thought_balloon: Do actions like @draftsapp ?  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 47: Mon Feb 10 2020](#DONE:2.2737367544323206e-12)
<!-- completed:2020-02-19T17:41:02.313Z -->
:rocket: Bugs fixed in imdone 1.4.13
:hammer: After adding `expand:1` to a card the card should immediately be expanded.  
:hammer: Board settings warns that it's changed when it's not.
:hammer: Links to local images don't open in system editor.  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 48: Tue Feb 11 2020](#DONE:1.1368683772161603e-12)
<!-- completed:2020-02-19T17:41:02.314Z -->
:rocket: Fixed deleting of filtered lists  
:thought_balloon: Add completed dates when card is moved to configured list  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 50: Thu Feb 13 2020](#DONE:5.684341886080801e-13)
<!-- completed:2020-02-19T17:41:02.315Z -->
:rocket: Deployed fix for deleting filtered lists  
:thought_balloon: Completed dates for cards moved to a list configured by user  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 53: Sun Feb 16 2020](#DONE:1.4210854715202004e-13)
<!-- completed:2020-02-19T17:41:02.316Z -->
:rocket: Fixed: Look for links to files and images relative to file folder then root folder  
:thought_balloon: Setting to create a new markdown file for each new card  
:thought_balloon: Completed dates  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 53: Sun Feb 16 2020](#DONE:2.8421709430404007e-13)
<!-- completed:2020-02-19T17:41:44.571Z -->
:rocket: Added a Journal Type called "New File" that creates a new file for each card.  
:thought_balloon: Add completed dates to cards when they are moved to a configured list.  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 56: Wed Feb 19 2020](#DONE:7.105427357601002e-14)
<!-- completed:2020-02-20T15:05:37.947Z -->
:rocket: Add completed date to cards and replace due tag with completed tag  
:rocket: Make completed tag red if past due date, green if on time  
:thought_balloon: Consolidate settings in one view  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 57: Thu Feb 20 2020](#DONE:3.552713678800501e-14)
<!-- completed:2020-02-20T22:09:28.703Z -->
:rocket: Syntax highlighting in cards  
:thought_balloon: Looks so nice!  
:link: imdone.io  
#100DaysOfCode
```scss
.grid {
  display: grid;
  @media (min-width: 576px) {
    grid-template-columns: 1fr 1fr;
  }
```
```js
function jesse () {
  console.log('jesse')
}
```


### [:100: Days of code, Day 58: Fri Feb 21 2020](#DONE:1.7763568394002505e-14)
<!-- completed:2020-02-21T21:13:24.552Z -->
:rocket: Working on copy button for code blocks in cards.  
:thought_balloon: This would be awesome for organizing frequently used code snippets!  
:link: imdone.io  
#100DaysOfCode

### [:100: Days of code, Day 61: Mon Feb 24 2020](#DONE:8.881784197001252e-15)
<!-- completed:2020-02-25T19:30:52.147Z -->
:rocket: Fix journal path default bug  
:thought_balloon: Finish copy code to clipboard  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 65: Fri Feb 28 2020](#DONE:4.440892098500626e-15)
<!-- completed:2020-02-28T19:12:33.847Z -->
:rocket: Added markdown image size plugin 'markdown-it-imsize'  
:nerd_face: `![](logo/imdone-logo-small.png =24x)`  
:thought_balloon: Warn user to save changes if they leave card editor  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 68: Mon Mar 02 2020](#DONE:2.220446049250313e-15)
<!-- completed:2020-03-02T17:18:25.461Z -->
:rocket: Warn user to save changes if they leave editor  
:thought_balloon: Dcoument and release 1.4.20  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 68: Mon Mar 02 2020](#DONE:1.1102230246251565e-15)
<!-- completed:2020-03-03T16:35:51.444Z -->
:rocket: More product docs for...  
:heavy_check_mark: journal and card templates  
:heavy_check_mark: String interpolation with javascript expressions  
:thought_balloon: Update changelog and send email for 1.4.20  
:link: imdone.io  
#100DaysOfCode


### [:100: Days of code, Day 70: Wed Mar 04 2020](#DONE:5.551115123125783e-16)
<!-- completed:2020-03-06T20:33:52.413Z -->
:rocket: Put the finishing touches on imdone 1.4.20 documentation  
:rocket: Released imdone 1.4.20  
:thought_balloon: Review bugs and feature requests for next release  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 72: Fri Mar 06 2020](#DONE:2.7755575615628914e-16)
<!-- completed:2020-03-06T20:37:39.913Z -->
:rocket: Created a nice little javascript terminal interface for sax effects with ChucK  
:thought_balloon: Use spork to combine effects  
:link: https://chuck.cs.princeton.edu/  
#100DaysOfCode


### [:100: Days of code, Day 73: Sat Mar 07 2020](#DONE:2.0816681711721685e-16)
<!-- completed:2020-03-07T19:13:09.796Z -->
:rocket: Move Lists to kebab menu for 1.4.20 release  
:thought_balloon: Don't touch files if they haven't changed  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 73: Sat Mar 07 2020](#DONE:1.0408340855860843e-16)
<!-- completed:2020-03-08T17:34:44.895Z -->
:rocket: Add progress property to cards for easy progress bar  
:thought_balloon: Give focus to card editor on continue editing  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 75: Mon Mar 09 2020](#DONE:5.204170427930421e-17)
<!-- completed:2020-03-09T17:51:49.123Z -->
:rocket: Fixed checkbox alignment
:rocket: Progress bar that can be added to any card
:thought_balloon: Look at bugs and features for next release  
:link: imdone.io
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 82: Mon Mar 16 2020](#DONE:2.6020852139652106e-17)
<!-- completed:2020-03-16T22:14:05.793Z -->
:rocket: Ask for journalType when new project is added  
:rocket: Fix tabbing and untabbing selection  
:rocket: Add replaceSpaceWith setting for "New File" journalType  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 87: Sat Mar 21 2020](#DONE:1.3010426069826053e-17)
<!-- completed:2020-03-21T22:52:45.031Z -->
:rocket: Getting docs ready for imdone 1.4.21  
:thought_balloon: Releasing tonight!  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 87: Sat Mar 21 2020](#DONE:6.5052130349130266e-18)
<!-- completed:2020-03-21T23:03:24.581Z -->
:rocket: Imdone does javascript expression interpolation!!!  
:rocket: 1.4.21 is out!!!  
:link: https://imdone.io/docs/#/cards?id=string-interpolation  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 88: Sun Mar 22 2020](#DONE:3.2526065174565133e-18)
<!-- completed:2020-03-22T14:50:21.236Z -->
:rocket: Added toggleComment for imdone 1.4.22  
:thought_balloon: Getting started video is next!  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 89: Mon Mar 23 2020](#DONE:1.6263032587282567e-18)
:rocket: Markdown/HTML comment hot keys!  
:rocket: Wrap a line or selection in an HTML comment by pressing cmd or ctrl + / in the card editor.  
:thought_balloon: Record a getting started video.  
:link: imdone.io  
<!--[#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger]-->
<!-- completed:2020-03-23T17:11:11.881Z -->


### [:100: Days of code, Day 92: Thu Mar 26 2020](#DONE:8.131516293641283e-19)
<!-- completed:2020-03-27T16:25:09.115Z -->
:rocket: Added card editor themes and option to add getting started cards to new projects  
:thought_balloon: keep working on videos  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 93: Fri Mar 27 2020](#DONE:4.0657581468206416e-19)
<!-- completed:2020-03-27T18:15:52.471Z -->
:rocket: Recorded my first getting started video for imdone  
:thought_balloon: Record the "Using Due Dates" video  
:link: https://vimeo.com/401397987  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger


### [:100: Days of code, Day 95: Sun Mar 29 2020 <!-- completed:2020-03-29T21:05:06.580Z -->](#DONE:0)
:rocket: Allow cards to be part of a markdown list and end at the next item  
:thought_balloon: Available Monday AM in imdone 1.4.24!  
:link: imdone.io  
#100daysofcode #programmer #developer #hacking #markdown #Productivity #codinglife #indiehackers #blogger

