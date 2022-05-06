# Make 3 tabs

## Steps
- make a div with three buttons tab1, tab2 and tab3
- give backgroud color of div and button same by inherit
- as we want button to be not distinctly visible give no border to button, use padding to expand the button to div size
- create three diff div for content of each button 
- make a class for tab content with border-top as none
- make tab content display as block to hide them
- on tab button give onclick event and call function openTab
- in openTab first make all tab content display none using getElementByClassName using element.style.display and element.className.replace
- also for all tab buttons make backgroud same as background of div
- for tab clicked make background little dark
- for content take tab content id from button event and make display block