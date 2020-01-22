---
refresh: 6000
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
  # :100: Days of code, Day ${daysIn}: ${today}
  :rocket: 
  :thought_balloon: 
  :link: 
  #100DaysOfCode
links:
  - pack: fab # Can be fab or fas https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
    icon: twitter # The font-awesome icon to use 
    title: Tweet this card
    href: https://twitter.com/intent/tweet?text=${encodedText}%0ATweeted%20with%20@imdoneio
---

# 100 Days Of Code - Log
<!-- 
#NOTE:0 # :100: Days of code: Day ${daysIn} expand:1 refresh:300000
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

###  [# :100: Days of code: Day 2](#DONE:30)
#100DaysOfCode
- imdone: Added new card template in frontMatter for 100DaysOfCode

### [# :100: Days of code: Day 3](#DONE:10)
#100DaysOfCode
- Added tweet button from log.md frontMatter to easily tweet progress

### [# :100: Days of code: Day 3](#DONE:20)
#100DaysOfCode
- Added frontMatter variables to imdone to automatically show day's progress

### [# :100: Days of code, Day 3: Sat Dec 28 2019](#DONE:2.5)
**Today's Progress:** Added the standard log.md entry as task template  
**Thoughts:** Looking good so far, hopefully release by monday!  
**Link to work:** [imdone.io](http://imdone.io)
#100DaysOfCode

### [# :100: Days of code, Day 4: Sun Dec 29 2019](#DONE:1.25)
**Today's Progress:** Implemented YAML config for imdone  
**Thoughts:** Much cleaner layout and consistent with use of frontMatter  
**Link to work:** [imdone](https://imdone.io)
#100DaysOfCode

### [# :100: Days of code, Day 5: Mon Dec 30 2019](#DONE:0.625)
**Today's Progress:**
- Added maxLines config setting for imdone
- Fixed bug allowing cards with no title  
<!-- -->
**Thoughts:**
Day job is keeping me from releasing imdone templates today
<!-- -->
**Link to work:**
#100DaysOfCode

### [# :100: Days of code, Day 6: Tue Dec 31 2019](#DONE:0.3125)
**Today's Progress:**
- Worked on imdone release 1.4.4
<!-- -->
**Thoughts:**
- Still not ready to release 100DaysOfCode template, but getting close
<!-- -->
**Link to work:** imdone.io
#100DaysOfCode

### [# :100: Days of code, Day 7: Wed Jan 01 2020](#DONE:0.15625)
**Today's Progress:**
:hankey: Added much needed restartWorker() to imdone.  
**Thoughts:**
:hankey: Woke up to find my imdoneboard wasn't working due to the proces dying overnite.  
**Link to work:**
imdone.io
#100DaysOfCode #EatYourOwnDogfood

### [# :100: Days of code, Day 8: Thu Jan 02 2020](#DONE:0.078125)
**Today's Progress:**
:rocket: Made imdone journal respect single file in config for 100-days-of-code template  
**Thoughts:** Now on to adding new projects from templates  
**Link to work:** imdone.io  
#100DaysOfCode

### [# :100: Days of code, Day 8: Thu Jan 02 2020](#DONE:0.0390625)
:rocket: **Progress:** imdone is now pulling in github:imdone/templates readme  
:thought_balloon: **Thoughts:** Trying to make it easy for community template creation  
:link: **Links to work:** https://github.com/imdone/templates  
#100DaysOfCode


### [# :100: Days of code, Day 10: Sat Jan 04 2020](#DONE:0.01953125)
:rocket: **Progress:** Finished ability to add projects from template in imdone.  
:thought_balloon: **Thoughts:** Continue working on pre-populated board for people new to coding.  
:link: **Links to work:** https://github.com/imdone/templates  
#100DaysOfCode


### [# :100: Days of code, Day 11: Sun Jan 05 2020](#DONE:0.009765625)
:rocket: **Progress:** Finished up some cosmetics around templates  
:thought_balloon: **Thoughts:** Documentation updates are next  
:link: **Links to work:** imdone.io  
#100DaysOfCode


### [# :100: Days of code, Day 12: Mon Jan 06 2020](#DONE:0.0048828125)
:rocket: Added "Add Project From Template" button to quick start modal  
:thought_balloon: Imdone 1.4.5 will be released tomorrow with 100-days-of-code template!    
:link: https://github.com/imdone/templates
#100DaysOfCode


### [# :100: Days of code, Day 13: Tue Jan 07 2020](#DONE:0.00244140625)
:rocket: 100 Days of code template is here!  
:thought_balloon: Plan your challenge with imdone kanban!  
:link: [Templates](https://imdone.io/docs/#/templates)  
#100DaysOfCode


### [# :100: Days of code, Day 14: Wed Jan 08 2020](#DONE:0.001220703125)
:rocket: Added setting for new card syntax MARKDOWN or HASHTAG  
:thought_balloon: Should make markdown rendering easier to read  
:link: imdone.io  
#100DaysOfCode


### [# :100: Days of code, Day 15: Thu Jan 09 2020](#DONE:0.0006103515625)
:rocket: Fixed MARKDOWN syntax in imdone 1.4.6!  
:thought_balloon: Makes card syntax render cleanly with markdown  
:link: imdone.io  
#100DaysOfCode


### [# :100: Days of code, Day 16: Fri Jan 10 2020](#DONE:0.00030517578125)
:rocket: Added a refresh property in front-matter and card metadata
:thought_balloon: Looking at adding functions for dynamic cards
:link: imdone.io
#100DaysOfCode

### [# :100: Days of code, Day 17: Sat Jan 11 2020](#DONE:0.000152587890625)
:rocket: Updated imdone.io/docs
:thought_balloon: Made card syntax easier to understand (feedback welcome) :tomato:
:link: [imdone.io/docs](imdone.io/docs)
#100DaysOfCode


### [# :100: Days of code, Day 18: Sun Jan 12 2020](#DONE:0.0000762939453125)
:rocket: :boom: Add due dates using due metadata and natural language processing for imdone 1.4.7
:thought_balloon: Next will be a column dedicated to what due today or past due
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 19: Mon Jan 13 2020](#DONE:0.00003814697265625)
:rocket: Implemented filtered list for cards due today
:thought_balloon: We can't allow filtered lists to be modified by dragging cards
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 20: Tue Jan 14 2020](#DONE:0.000019073486328125)
:rocket: Filtered list is now static and can't be modified. Also has a filter link in the header.
:thought_balloon: Gotta add a configurable refresh rate for date sensitive filters
:link: imdone.io 
#100DaysOfCode


### [# :100: Days of code, Day 21: Wed Jan 15 2020](#DONE:0.0000095367431640625)
:rocket: Added refresh rate for filtered lists and started "Due in..." display for cards
:thought_balloon: Tomorrow add filtered lists to board settings
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 22: Thu Jan 16 2020](#DONE:0.00000476837158203125)
:rocket: Added filtered lists to board settings
:thought_balloon: Almost ready for release 1.4.7!!!
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 23: Fri Jan 17 2020](#DONE:0.000002384185791015625)
:rocket: Added tabs to board settings
:thought_balloon: Testing all weekend for release on Monday!!!
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 24: Sat Jan 18 2020](#DONE:0.0000011920928955078125)
:rocket: Cleaned up board settings and quick start.
:rocket: Tested default project and quick start.
:thought_balloon: Docs and examples are next.  Examples will be included as a template.
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 25: Sun Jan 19 2020](#DONE:5.960464477539062e-7)
:rocket: Added save button to board settings
:thought_balloon: Tonight, keep testing and writing documentation for R1.4.7 
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 26: Mon Jan 20 2020](#DONE:2.980232238769531e-7)
:rocket: Start and stop every minute refresh on main window focus and blur
:rocket: Ignore tasks in filtered lists when deleting filtered cards
:thought_balloon: Finish docs and prepare for release
:link: imdone.io
#100DaysOfCode


### [# :100: Days of code, Day 27: Tue Jan 21 2020](#DONE:0)
:rocket: docs, docs, docs, docs
:thought_balloon: docs, docs, docs, docs
:link: imdone.io
#100DaysOfCode

