# CHEAT SHEET


### FOR LOOP 

- Goes through each 


### IF STATEMENT

- check to see

### POWER MOVES

-------

## SUBLIME TEXT
- CMD + N - new tab (new file)
- Cmd + S, SAVE YOUR STUFF
- CMD + SHIFT + [ / ] - cycle left/right
- Ctr + CMD + Space - mac emoji menu
- Cmd + C, Cmd + V, Cmd + X - copy, paste, cut
- Cmd + ~ - cycle through multiple Sublime windows
- Cmd + P - quick open files
- Cmd + F - find in file
- Cmd + Shift + F - find in all files



-------

## GIT COMMANNDS

- git init - initiate a git repo
- git status - checks the status of the repo (any new files? any new changes?)
- git add - add a (or multiple) file(s) changes to the new commit git add testFile.js or git add . (for all files)
- git commit - save that point in time, with a message git commit -m "did some stuff"
- git remote - allow me to communicate with another computer (backup my stuff) (git remote add origin <SOME GITHUB REPO>)
- git push - push local changes to remote! git push origin master
- git pull - pull changes from remote git pull origin master
- git log - list out history of commits

**WARNING: DO NOT MAKE GIT REPOSITORIES WITHIN OTHER REPOSITORIES.**

### FORK AND CLONE

git clone git@gist.github.com:YOUR_FORKS_ID.git lunch

## VIM 

- `H` moves left
- `K` moves up
- `L` moves right
- `J` moves down

### Inserting Text

- Press `i` to begin inserting text at the current cursor position
- Press `a` to begin inserting after the current cursor position.
- hit `escape` to exit editing mode

- `Y` copies a line of text to the buffer.
- `P` pastes it to the cursor's current position.
- `dd` will delete the whole line of text. This will also effectively "cut" a line of text as well. When you delete a line, it's placed in the buffer.
- `yy` copies a whole line of text.

### Saving a File 

While editing a file, its always a good idea to save the text. To do that you would need to do the following

- Make sure you are in command mode. Use escape key to make sure.
- type `:w`

That's it.

### Quit vim

Quit vim
Once you have finished editing you can quit vim in one of the following two ways

- `:wq` - save and quit file(and vim)
- `:q!` - quit and ignore changes made since last file save.


-------

## OPERATORS

`===` compares value *and* type 

`==` compares type aka type coercion 



## FALSY LIST

```
// All of the following are inherently falsey:

False
// False is False. Makes sense, right?

0
// 0 is the only falsey Number

""
// an empty string is falsey

null
// a null, or empty value, is falsey.

undefined
// an object that has not been defined is considered falsey.

NaN
// Not a Number. You'll learn more about NaN as we go on.
```






