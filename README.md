# ToDoList

Simple List Web App
I created a web app that can create a list of items that are added in a central section of the site, this web app allows you to write down things to do during the day in order to better organize your time and be more efficient in your days.
The site consists of three files: one that determines the DOM in HTML, one that determines styling in CSS, and one that allows you to manipulate the DOM in JavaScript.
the site is made up of a Body block which makes up the entire site, a "main" block which contains two blocks: a block identified with the "Bodygroup" class relating to the section on the site which contains the upper part, i.e. the title, the input bar and the "Add Item" button which adds the client's input into the block below, the block with the id of "bottom_side", with a listener handler which checks the text input received, if nothing is entered it is sent to screen an error message, otherwise if the input contains at least one letter it can be added to the list of "things to do".
If the input is accepted then elements are added to a list consisting of a text and three buttons with different functions. A "done" button which with the javascript script assigns a new class named "sbarrtext" which bars the word, meaning that our note has been completed.
An "edit" button that does two things, the first is to put the text of the item in the list in the input insertion bar to be edited again and delete the item to avoid duplicates.
The last button allows you to "remove" eliminates the element from the list.
I have also inserted a function which consists of an addEventListener of a keyboard input, i.e. for each input entered, if it is equal to the "enter" key on the keyboard, the input is loaded into the to-do lis
