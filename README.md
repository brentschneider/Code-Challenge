

#Code challenge excepted!


First UI Challenge, Contact List 
[repo](https://github.com/ff0000/skills-assessment)

[raw image](https://github.com/ff0000/skills-assessment/blob/master/contactListUpdated.jpg)

##List Data: [Some fake people data](listData.md)


###Dev Notes:

[my code example](http://www.milkshakeinteractive.com/code/FF0000challenge/ContactList.html)


####Development progress report

On your mark.. get set... code!

Set up environment and templates 
**[time: 40 min]**

Approached process building out the list [total time: 1.2 hours]
- Started the list using ul class="nav nav-pills", didn't seem to scale well 
- Moved to a list-group with dropdowns using data-toggle="dropdown" function.
**[total time: 1.2 hours, into project]**

Panel devvelopment and list item
- Added the container panel, issue bug: Address border colors
- Added a show status style/metod. (moveed from div to css /* li:before {} */ )
- Added fade to bottom of list
- In progress: hover model style/method
**[total time: 3 hours, into project]**

Cross browser bug testing
 - FF bug; ::first-letter CSS pseudo-element selector
 - Chrome bug; dropdown list margin alignment
**[total time: 5 hours, into project]**

Finishing visual style
- Develop: alt row and divider styles

Adding jquery functionality
- Added swap content method per dropdown selection

**[total time: 8 hours, into project]**

####Todo:

- Bug list:
  -- model darken background on item list hover
  -- last list item hover cuts off

###Test 
- Mac Safari 8
- Mac Firefox 34
- Mac chrome 40
- PC IE 7
- PC FF 35



####UI Settings

```
Width: 280px

height: 398px

Border radious: 12px;

border: 4d4d4d / #4c4c4c - #292929 / 262626


Header: 
    #3d3d3d to #252525
    height 50px
    Note: fade just Inside above footer fade up: #111111

Footer:
    bar: #202020

Rows:
    row: #212121  // slate
    alt #1a1a1a   // dark
    seperator #131313

    StatusOn: #00fe2c   // green
    StatusOff: #ff0207  // Red
    StatusAway: #c1bb1b // yellew

    textRow1: #FFFFFF
    textRow2: #585858
    TextRow2 Hover: #fcfcfc
    Note: Model effect

Item hover: #484848 // background gray
Item link: 08e7e2 // Blue
```
