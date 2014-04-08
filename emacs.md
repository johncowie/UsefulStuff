#Emacs

[Based on this page](http://www.rgrjr.com/emacs/emacs_cheat.html)

##Cursor Motion

###Characters
- ```C-f``` move forward
- ```C-b``` move backward
- ```C-d``` delete forward
- ```DEL``` delete backward

###Words
- ```M-f``` move forward
- ```M-b``` move backward
- ```M-d``` delete forward
- ```M-DEL``` delete backward

###Lines
- ```C-n``` move forward
- ```C-p``` move backward
- ```C-k``` delete forward
- ```C-SPC C-a C-w``` delete backward

###Sentences
- ```M-a``` move forward
- ```M-e``` move backward
- ```M-k``` delete forward
- ```C-x DEL``` delete backward

###Expressions
- ```C-M-f``` move forward
- ```C-M-b``` move backward
- ```C-M-k``` delete forward
- ```C-M-DEL``` delete backward

###Paragraphs
- ```M-}``` move forward
- ```M-{``` move backward

###End/start of line
- ```C-e``` end of line
- ```C-a``` start of line

###End/start of buffer
- ```M->``` end of buffer
- ```M-<``` start of buffer  

##Cutting and Pasting
- ```C-SPC``` Mark one end of region
- ```C-w``` Cut
- ```M-w``` Copy
- ```C-y``` Yank (paste)
- ```M-y``` Yank next most recently killed

##Files and Buffers
- ```C-x C-f``` Find file (or create if not there)
- ```C-x C-s``` Save file
- ```C-x C-w``` Write file (prompts for new name)
- ```C-x s``` Save modified buffers (asks about each)
- ```C-x b``` Select buffer (prompts for buffer)
- ```C-x C-b``` List buffers

##Scrolling/Windows
- ```C-v``` Scroll down (towards the end of the buffer)
- ```M-v``` Scroll up (towards the beginning of the buffer)
- ```C-M-v``` Scroll other window down
- ```C-x 1``` One window on current buffer
- ```C-x 2``` Split window vertically
- ```C-x 3``` Split window horizontally
- ```C-x ^``` Grow window vertically; prefix is number of lines

##Command-related
- ```C-g``` Stop a command in progress
- ```C-u #``` Prefix numeric arg to next cmd

##Searching/Replacing
- ```C-s``` Incremental search forward
- ```C-r``` Incremental search backward
- ```M-x replace-string RET``` String replace from here to end of buffer; prompts for string and replacement
- ```M-x query-replace RET``` String replace from here to end of buffer, querying for each occurrence

##Getting Help
- ```C-h k``` Show command documentation
- ```C-h a``` Prompts for regex and shows all matching commands
- ```C-h c``` Show command name on message line
- ```C-h f``` Describe function - shows documentation in other window
- ```C-h i``` Info browser, gives access to online documentation

##Miscellaneous
- ```C-_``` or ```C-x u``` Undo/redo
- ```C-q``` Quoted insert (even if it is a control or meta character)
- ```C-x C-c``` Exit emacs
