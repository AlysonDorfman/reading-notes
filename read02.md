[Back to Homepage](https://alysondorfman.github.io/reading-notes/)

# Read: 02 - The Coder's Computer


## Choosing a Text Editor

### Things to look for: 

* Code Completion 
* Shorthand (Emmet for HTML and CSS)
* Syntax Highlighting (Color Coding)
* Themes
* Extensions

There exist text editors that come built into operating systems, but they usually lack some of the robust features we're looking for, so it's wise to choose from a third-party option.

### Third-Party Options

* NotePad++
* TextWrangler: outdated, now folded into BB Edit
* BB Edit
* Visual Studio Code: Free, made by MSFT, available on most machines, has Emmet
* Atom: Made by GitHub
* Brackets: Made by Adobe, only supports HTML, CSS and Java so may be good for beginners. Has live preview.
* Sublime Text: $70

### Text Editors vs. IDEs

IDE: Integrated Development Enviroment

An IDE is a text editor **and**, in addition, a file manager, compiler, and debugger. Just like MSFT Outlook is not just email, it's also a calendar, task manager, etc. It's a whole suite of software.

## The Command Line
Your window into the computer.

The Command Line aka The Terminal mirrors your computer's File Folder. Instead of having a graphical user interface (GUI) where you can click around and see what you're doing easily, it has a Command Line Interface (CLI) that functions with the commands you enter through text.

Within the terminal, there is a prompt, after which you enter your command and any command line arguments or "options," which are simply modifications to your command. 

To open a terminal: Search Terminal in your computer's search bar, and open the application.

Bash is the most common shell, or element responsible for running your commands in the terminal. 

A shortcut: The terminal stores a list of your commands. So if you want to repeat a recent command, type the up arrow to flip through a bunch of your recent commands. 

## Basic Navigation
Let's explore the system

Commands:
 * **pwd**: Print Working Directory, where are we in the system since we can't see it
 * **ls**: List of what's here
 * **/etc**: Instead of listing the directories, list their content. When used like this: ls /etc
 * **cd**: Change Directory
 * **file [path]** What type of file
 * **\\**  nullify special meaning of next character

Paths: Absolute = specifies exactly where, Relative = specifies a file name from your current position in the system and will produce a different outcome depending on that position in the system
Shortcuts: **~** is Home Directory, **.** is Current Directory, **..** is Parent Directory

## More About Files
Kinda boring, but essential knowledge.

Everything is a file: your keyboard, text, an image, etc. 

Extensionless System: Linux doesn't use file extensions like .png, but you can use the command **file [path]** to find that out.

Linux is Case sensitive, Space sensitive and Quote sensitive.

ls -a
List the contents of a directory, including hidden files.



