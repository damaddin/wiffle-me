# Wiffle - online Notepad with offline storage

The idea is simple: have a nodepad for quick copy-paste operations, temporary storage and some editing directly in the browser. Nothing fancy, in the end basically just a large empty text area.

Inspired by {{https://editpad.org}} I wanted to add editor tabs and save to local storage so browser crashes don't lose my data. 

There is no backend connection whatsoever, no login, no nothing. You can only see what you typed it yourself.

# Usage

When you enter the page, a new hash is generated and shown in grey (not saved since there is no content). Just start typing in the text field to save the hash. Use the r button to rename and the x to delete it. The rest of the page is a large text area for you to use for what you want. Remember this is stored locally in your browser and thus only you can see it yourself.

Have fun!

# Roadmap

Here is my roadmap for this coffee-break project:

* a bit of nice styling could happen
* create new tabs not only through the hash but in the page
* sort tabs
* syntax highlighting
* (regex) replace tool for patternbased reformatting
* json formatter / pretty printer
* json syntax checker
* collapsible sections (maybe different types of content areas)
* todo list / scheduling addon

Feel free to suggest things or submit pull requests. 

