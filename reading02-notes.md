# **Choosing a Text Editor**


In a developer's line of work, choosing the right text editor for you can be a very vital step in the developing process. In short, a text editor is a piece of software (accessed either by downloading onto your device or online) that allows you to write and manage text. Every computer will come with its own built-in text editor, however they are typically bare-bones and as simple as it can get, offering very litle in the way of additional features. While most text editors are the same apart from some minor differences in features, it is important to understand that the best editor for you will be up to your own personal preference and experience. In general, you want to find an editor that you enjoy using and can successfully complete the tasks you are asking of it. With that being said, here are some key features you want to look out for:

1. ***Code Completion***
    - Code completion offers suggestions based on the text you are inputting, saving you time by providing auto-completed choices rather than typing out the full text or command.
    - Some code completion includes the closing of tags or brackets when you open them.
    - You can utilize the shorthand language ***Emmet*** to write your HTML and CSS code more efficiently.

2. ***Syntax Highlighting***
    - Takes the text you input and makes it more noticeable by colorizing it, which makes finding an error in your text much easier.
    - Attributes will be a different color than elements, and elements will be a different color than copy.

3. ***Theme Selection***
    - Themes allow you to do a number of things, from changing the background color of your text editor to changing the series of colors in your text.
    - Find a theme that reduces eye fatigue and strain, most developers opt for a dark background and light text combination.

4. ***Extensions***
    - Extensions are like plugins for your text editor.
    - A text editor with a good selection of extensions will give you the ability to add functionality as needed.


# **The Terminal**


### ***What is a Command Line?***

A command line, or terminal, is a text-based interface to the system where you are able to enter commands and receive visual feedback in the form of text.
- Typically presents you with a prompt and the text you input will be displayed after it.
- Normally, you will be issuing commands

### ***The Shell***

The shell is located within the terminal and is a part of the OS that defines how the terminal will behave and look after running/executing commands.
- You can use the `echo` command to confrim you are working in the correct shell.
- Text on screen should end with the correct shell name


# **Navigation in the Terminal**


- Alot of commands in the terminal are named as an abbreivation of a words or words describing them.
- Most commands in the terminal will rely on you being in the correct location.
- Whenever you refer to a file or directory on the command line, you are reffering to a **path**.
    - A path is a means to get to a particular file or directory.
- There are two types of paths, **absolute** and **relative**, both can be used to get to the same destination.
    - An **absolute path** will specify the location in relation to the root directory and will always begin with a forward slash.
    - A **relative path** will specify the location in relation to where you are currently located in the system and does not begin with a slash.
- The **`cd`** command is used to change the directory and can be run with or without a specified location, but is generally ran with a single command line argument which is the location you are changing to.


# **About Files**


- In the terminal, everything is a file.
- A **file extension** is normally a set of 2-4 characters at the end of a file that denotes what type of file it is.
    - **`.exe`** is an executable file or program.
    - **`.txt`** is a plain text file.
    - **`.png`**, **`.gif`**, **`.jpg`** are image files
- Some systems are case-sensitive while others are not. Case-sensitive files will see files with the same name as completely seperate files if one has a difference in casing.
    - The command line can also be case-sensitive.
- You can use spaces in your file names by wrapping the text in either single or double quotations.
- Some files in the terminal are hidden and you can create these files by putting a period before the name.

*************

# *Terminal Cheat Sheet*

- **`echo $shell`** is used to confirm which shell you are working in.
- **`pwd`** is used to find which file or directory you are located in.
- **`ls`** is used to see what is in a specific file or directory.
- In the command **`ls [options] [location]`**, the items in the square brackets are optional and the command can be run with or without them.
- **`~`** is a shortcut for your home directory.
- **`.text`** is a reference to your current directory.
- **`..`** is a reference to the parent directory.
- **`cd`** or **`cd [location]`** is used to move around the terminal.
- Hitting the **tab key** invokes an auto-completion when typing a path.
- **`/var/log`** stores log files for various system programs.
- **`/bin`** shows the location of several commonly used programs.
- **`/usr/bin`** shows another location for commonly used programs.
- **`file [path]`** will tell you the type of file the specified path is.
- **`ls -a`** shows hidden files or directories.

**************

### ***Repository Directory***

- [Growth Mindset](https://burban7.github.io/Reading-Notes)
- [Learning Markdown](https://burban7.github.io/Reading-Notes/reading01-notes)
- [Revisions and the Cloud](https://burban7.github.io/Reading-Notes/reading03-notes)
- [Structuring Web Pages with HTML](https://burban7.github.io/Reading-Notes/reading04-notes)
- [Design Web Pages with CSS](https://burban7.github.io/Reading-Notes/reading05-notes)
