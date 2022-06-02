#Title
FDN Programming 110 Assignment 07

Jason Johanneck
2022-May-31
IT FDN Programming 110
Module07 Assignment07

## Introduction
In Assignment07 we were asked to apply our knowledge of pickling data and basic error exception handling. For this assignment, I used assignment06 as a template and stuck with menu processing logic to manage a Task List.  I changed the selections from a numeric choice to an alpha character and included an option to display the current Task list.

Here is an example of my menu options:
        Menu of Options
        (l) Load Task list from file
        (a) Add a new Task
        (i) Display current Task list
        (r) Remove an existing Task
        (s) Save Task list to file
        (x) Exit Program

![Figure1](/docs/Figure1.png "Figure1 - Assignment07 Code Listing")

Similar to Assignment06, the Python code was broken out into three sections:

### Section one: A function class for Data Processing was defined that included two functions:

![Figure2](/docs/Figure2.png "Figure 2- Processor Class with four functions")


### Section two: File Processing with two functions for reading and writing data.

Both the read_file and write_file functions used pickling.

![Figure3](/docs/Figure3.png "Figure 3- File Processing Functions")


### Section three: I/O Processing:

This section includes functions to print the menu, retrieve a user choice, display the current task list and to prompt the user for an task to remove.

![Figure4](/docs/Figure4.png "Figure 4 - Main Script section for Menu Processing Logic")


### Section Four: Main Script – code segment to check for TaskList.txt file size and existence.

This section starts with checking for the existence of the file, and will display a message if the file does not exist.
Or if the file exists but is empty, that is noted as well.  Exception handling is used to check for file size and file existence.

![Figure5](/docs/Figure5.png "Figure 5 - Exception Handling to check file size and existence")




Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown

Syntax highlighted code block


# Header 1
## Header 2
### Header 3

- Bulleted
- List
1. Numbered
2. List
**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)

```
For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jjohanne514/FDN_110_Assignment07/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
