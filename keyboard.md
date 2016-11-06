# OS/X
[Canonical Apple Keyboard Reference](https://support.apple.com/en-ca/HT201236)
control-F3 shows all windows in the current application, use cursor key to cycle between them
command-space brings up searchlight --- suggestion is to replace it with Alfred

# Bash
[Bash Keyboard Shortcuts](http://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)

Ctrl + A  Go to the beginning of the line you are currently typing on
Ctrl + E  Go to the end of the line you are currently typing on
Ctrl + L  Clears the Screen, similar to the clear command
Ctrl + U  Clears the line before the cursor position. If you are at the end of the line, clears the entire line.
Ctrl + H  Same as backspace
Ctrl + R  Let’s you search through previously used commands
Ctrl + C  Kill whatever you are running
Ctrl + D  Exit the current shell
Ctrl + Z  Puts whatever you are running into a suspended background process. fg restores it.
Ctrl + W  Delete the word before the cursor
Ctrl + K  Clear the line after the cursor
Ctrl + T  Swap the last two characters before the cursor
Esc + T Swap the last two words before the cursor
Alt + F Move cursor forward one word on the current line
Alt + B Move cursor backward one word on the current line
Tab Auto-complete files and folder names

# Sublime (ST3)
[Reference](http://docs.sublimetext.info/en/latest/reference/keyboard_shortcuts_osx.html)
command-n moves between tabs
control-tab cycles between tabs in 'recently used' order
command-` toggles between windows
command-shift-f search all files
command-option-arrows move left and right through tabs
command-T, command-P GOTO anywhere (great for opening files)

Multiple selection:
command-D select word, repeat
command-control-G select all occurances of current word!
command-L select the line (repeat as necessary)
command-U deselect last selection
(you can also use find)

Search:
command-F regular find
command-I incremental find
shift-command-F search all files

Column selection!
With mouse using option key

More on selecting.
[A very good primer](http://brettterpstra.com/2014/07/23/sublime-text-selections/)
Key things I learned:
- you can command-click on any point to create a new curser;
- command-shift-J expand to scope is useful to selecting the content of the strings then expanding that selection to include
the quotation marks and that sort of thing

Installed this package to expand selections to a function:
[Expand to function (javascript)](https://github.com/gillibrand/expand-selection-to-function-js)
Works beautifully with option up-arrow

## Plug-ins
[10 best for full stack developers]https://www.sitepoint.com/10-essential-sublime-text-plugins-full-stack-developer/
Git-gutter seems more useful than running all the git commands from within sublime.
[Git-gutter](https://github.com/jisaacks/GitGutter)

[Javascript snippets for javascript and nodejs](https://github.com/zenorocha/sublime-javascript-snippets)