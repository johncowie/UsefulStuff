#Vim

[Based on this page](http://rtorruellas.com/vim-cheat-sheet/)

##Cursor

###Characters
- ```h``` Move left
- ```j``` Move down
- ```k``` Move up
- ```l``` Move right

###Words
- ```w``` Jump forwards to the start of a word
- ```W``` Jump forwards to the start of a word (words can contain punctuation)
- ```e``` Jump forwards to the end of a word
- ```E``` Jump forwards to the end of a word (words can contain punctuation)
- ```b``` Jump backwards to the start of a word
- ```B``` Jump backwards to the start of a word (words can contain punctuation)

###Lines
- ```O``` Jump to the start of the line
- ```^``` Jump to the first non-blank character of the line
- ```$``` Jump to the end of the line
- ```G``` Go to the last line of the document
- ```5G``` Go to line 5

```
Prefix a cursor movement command with a number to repeat it.  
E.g. 4h would move the cursor 4 characters to the left
```

##Cut and paste
- ```yy``` yank (copy) a line
- ```2yy``` yank (copy) 2 lines
- ```yw``` yank (copy) word
- ```y$``` yank to end of line
- ```p``` put (paste) the clipboard after cursor
- ```P``` put (paste) before the cursor
- ```dd``` delete (cut) a line
- ```2dd``` delete (cut) 2 lines
- ```dw``` delete (cut) word
