# iseries-macros

Greetings,

This repo contains tools that I use for writing IBM iSeries macros.

## User Snippets for VS Code
This is a collection of snippets that makes typing them much faster. Since all of the snippets start with _as_, you can start by typing _as_ to get suggestions from VS Code. 

### How to use?

In VS Code, go to File – Preferences – User Snippets – Visual Basic. Replace contents of the file with _Snippets\vb.json_ of this repo. You will need to associate .mac files with Visual Basic too. Open any macro file and in the bottom right corner click _Plain Text_ and then choose _Configure File Association for ‘.mac’_. Pick _Visual Basic_.

### What snippets are there?

* asgetcursor - get cursor row and column in the terminal
* asgettext - read text at position x, y
* asrefresh - refresh presentation space
* assendkey - method for sending keys
* assetcursor - method for setting cursor at position x,y
* assettext - method for setting text of the box at position x,y
* aswaitcursor - if block that will terminate script if cursor is not at position x,y. Often used when navigating screens
* aswaitinput - method to wait for application and input ready. Often used before sending keys to the terminal
* aswaitwhilecursor - method to wait while cursor is at position x,y
* aswaitx - method to wait X miliseconds



![macro_snippets](https://user-images.githubusercontent.com/87096398/124829653-c63ab700-df70-11eb-8a8a-5ce56210a0db.gif)

## Tutorial Scripts
This is a collection of a few simple scripts for my tutorial. See more at: https://www.kawaicode.com/?p=2178
* 1_first_script.mac - the very first macro that shows a message box
* 2_sending_keys.mac - shows how to send key strokes to the terminal
* 3_text_input.mac - shows how to set text of input boxes
* 4_navigate_screens.mac - shows how to navigate screens
* 5_read_screen.mac - shows how to read text from screen
* 6_excel_integration.mac - shows how to integrate Excel and macro to input information from the spreadsheet to the terminal
