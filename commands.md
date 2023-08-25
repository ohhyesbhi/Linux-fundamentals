#### pwd
This represents what is the current directory we are actually at.

#### mkdir
This helps us to create a new folder

#### touch
Actually creates a new file inside the folder . Ex-: `touch readme.md`

#### cat
Prints the whole content of a file. Ex- `cat readme.md`

#### ls
Here you can print the content of the current directory we are in. All the files and sub-directories will be printed

* `ls -l`: lists down more details about the file such as owner,permissions,date etc.
* `ls -h`: works like `ls -l` but also gives size of the file.
* `ls -a`: also lists  files and folders starting with `.` 

#### cd
cd means change directory , It actually means going inside the directory

#### cd ..
Here .. means that we are going one folder back, so if we want to jump one folder out then we use it

#### cd ../..
Here ../.. means that we are going two folder back, so if we want to jump two folder out then we use it

#### cd ~
Suppose you are 10 folder inside from the home directory and you want come back to home directory then we can use this command

#### cd/Developer/DSA
Using this we can move into internal subdirectories directly by seperating them with the forward salsh s(This forward slash actually means to seperate the sub-directories).

#### ~
This tilda refers to home directory  . `cd ~`

#### /
This slash will lead us to root directory. `cd /`

##### Relative path 
* It describes the location of the file/folder  w.r.t current folder. Whereas in an absolute path we mention the loaction from home directory or root directory.
* When you guve an absolute path of a file or a folder that means you will give the whole path of that file or folder, whereas in relative path you do jumps w.r.t to current folder 

#### clear
clears the working space by actually  moving you to top of the current shell.

#### rm
It actually removes the file. `rm <filename>`

#### rmdir
It will delete an EMPTY folder . `rmdir <foldername>`

#### rm -r
Here -r flag enables rm to recursively delete all the content of the folder and then delete the folder. `rm -r <foldername>`


### Note 
Suppose we want to add content to a file how we can do that , so what happens is linix terminal bydefault gives access to some text editors that are actually available inside the terminal few of them are vim,emax then there is nano etc.
 
## VIM 

`vim <nameOfFile>` -: using this command if there is any file exists with the same name then we can open the file or if there is no such file then the new file would be created. 

note -: To exit out of vim we have to do we have to first of all press escape then press colon and then press q . 
* Let's say now we have craeted a file now if we want to edit or write something we will press "i" ( which is nothing but insert )
* If you want to close the file after saving the changes we can press on escape button and then press ":wq" that's it , it will save our changes
* And if you want to exit a file without making any changes in the file then press escape and then on ":q!"