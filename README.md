# favorite-cmd-commands

## less — view the contents of a text file
    The less command allows you to view files without opening an editor. It’s faster to use, and there’s no chance of you inadvertently modifying the file.
       Syntax: less file_name

## locate — Locate a specific file or directory
    is by far the simplest way to find a file or directory. You can keep your search broad if you don’t know what exactly it is you’re looking for, or you can narrow the scope by using wildcards or regular expressions.
     Syntax: locate [option(s)] file_name(s)

## head — Read the start of a file
    By default, the head command displays the first 10 lines of a file. There are times when you may need to quickly look at a few lines in a file and head allows you to do that. A typical example of when you’d want to use head is when you need to analyze logs or text files that change frequently.
     Syntax: head [option(s)] file(s)

## chmod — Sets the file permissions flag on a file or folder
    There are situations that you’ll come across where you or a colleague will try to upload a file or modify a document and you receive an error because you don’t have access. The quick fix for this is to use chmod. Permissions can be set with either alphanumeric characters (u, g, o) and can be assigned their access with w, r, x. Conversely, you can also use octal numbers (0-7) to change the permissions. For example, chmod 777 my_file will give access to everyone.
      Syntax: chmod [option(s)] permissions file_name

## exit — Exit out of a directory
    The exit command will close a terminal window, end the execution of a shell script, or log you out of an SSH remote access session.
      Syntax: exit

