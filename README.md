# Command-Line Text Editor in C++

This project is a simple command-line-based text editor written in C++. It allows basic text editing operations such as inserting, deleting, replacing, and moving lines. It also supports saving to and loading from `.txt` files, along with an undo feature for recent actions.

## Features

- Insert text into any line (including creating blank lines if needed)
- Delete a specific line
- Replace the content of a line
- Move one line's content to another position
- View the full content with page-wise navigation (10 lines per page)
- Save the current text to a `.txt` file
- Open and load content from a `.txt` file
- Undo the most recent changes

## How it works

The editor uses a singly linked list to store each line of text as a node. All editing actions are tracked in a stack to enable undo operations. The user interacts through a menu-based system in the terminal.

## Menu Options

When the program is run, a menu is displayed with options:

1. Insert text into Line N
2. Delete line N
3. Move line N into line M
4. Replace text in Line N
5. Print all
6. Save into a .txt file
7. Undo
8. Open a .txt file
9. Print the next page
10.Print the previous page


## File operations

- To save your text, choose option 6 and provide a filename (without the `.txt` extension). The file will be saved in the same folder as the program.
- To open an existing text file, choose option 8 and enter the name of the file (again, without `.txt`). The contents will be loaded line-by-line into the editor.

## How to compile and run

Make sure you have a C++ compiler (like `g++`) installed. Then run the following commands in the terminal:


