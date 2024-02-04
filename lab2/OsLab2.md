# OsLab2

#  Task 1:

## Create new file

In order to create new file in linux terminal you have to write **touch file_Name.Extention**

![loading](images\1.png)

![loading](images\4.png)

![](images\2.png)

To enter content in the file you have to write **nano fileName** after writing content in the file, to save you have to press **Ctrl+S** , to exit from the editor you have to press **Ctrl+X**. Also to see the content in the file you have to write **cat fileName**.



## Merge content of one file to another

In order to merge the content of one file to another file you have to write command **cat firstFileName >> SecondFileName**. It will append content of one file to the other.

![loading](images\7.png)

##  Redirect the output to another file

If you want to create a new file after merging the content of two files you should write **cat firstFileName SecondFileName > newFileName**. This will create a new file after appending content of one file to another file write it into another file.

![loading](images\9.png)

## Display first two lines of a file content

To display only first two lines of a file you have to write **head -n fileName** here **n** is number of lines you want to display.

![loading](images\10.png)

## Display last two lines of a file content

To display only last two lines of a file you have to write **head -n fileName** here **n** is number of lines you want to display.

![loading](images\11.png)

## Find text in file

For finding a text in file write command **grep "Text you want to find" fileName**.

![loading](images\12.png)

## Grant the permission to file or a folder

To grant execution permission to file or folder you have to write command **chmod g+x fileOrFolderName**. In command replace **u,g**   are for **user and group** respectively. Replace **x,r,w** for **execution, read and write** permission respectively

![loading](images\13.png) 

## Remove the permission to file or a folder

To grant execution permission to file or folder you have to write command **chmod u-x fileOrFolderName**. In command replace **u,g**   are for **user and group** respectively. Replace **x,r,w** for **execution, read and write** permission respectively. **ls -l fileOrFolderName** to see the present permission to a file or folder.

![loading](images\13.png) 

## Present Directory

In order to see at which directory you are working in present. give command **pwd** in terminal.

## List/See files present in specific location

For locating files in a specific path or directory(Folder) you should write **ls path**

![loading](images\15.png)

## Create a new Folder or Directory

If you want to create a folder or directory present working directory the command is **mkdir directoryName**.

![loading](images\16.png)

## Display current time

Current time is given by command **date**

![loading](images\17.png)

## Display any text on terminal

For showing some text on the terminal write **echo textYouWantToShow**

# Task 2:

## Change permissions of file with number code

To change permissions of file or folder with the help of number or code you have to write command **chmod numberCode fileOrFolderName**. 

![loading](images\19.png)

![loading](images\permissionCode.png)

## Append content of command to File

In order to append the result of command to a file you have to write **command >> fileName** like in the figure.

![loading](images\20.png)