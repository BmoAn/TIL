docs: What I learned Today

## DONE

### shell command
move to another directory : cd @@@/, cd ..(upper)
make directory : mkdir
location where i am now : pwd

make file : touch 000.00
move file : mv 000.00 @@@/
remove file : rm 000.00
rename file : rm 0000.00 ./0000.XX

remove folder : rm -rf 000/
print inside file : cat 0000.00
write in file : vi 000.00


### vim command
h j k l - left, down, up, right 
i - insert mode 
v - visual mode 
ESC - back to normal mode
d - delete 
dd - delete a line 
y - yank 
yy - yank a line 
p - paste 
u - undo 
a - append 
A - append from end of line 
o - open line(under) 
O - open line(upper) 
H - move to the top of the screen 
L - move to the bottom of the screen

:q - quit 
:q! - quit discarding all changes 
:w - write 
:wq - write and quit 
:{number} - jump to {number}th line.

### What is git?

### why need it?

### how to use git

#### start project with git init
make directory first
mkdir first-repo
cd first-repo
git init
git remote add origin (URL address)
touch file.md
git add file.md
git commit -m "docs: Create README.md"
git push -u origin main
#### start project with git clone

make repo on github
git clone (repo address)
git add
git commit 
git push
