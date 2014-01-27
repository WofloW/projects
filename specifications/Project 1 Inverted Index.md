Project 1 Inverted Index
=================================================

For this project, you will write a Java program that recursively processes all text files in a directory and builds an inverted index to store the mapping from words to the documents (and position within those documents) where those words were found. For example, suppose we have the following mapping stored in our inverted index:

```
capybara
"mammals.txt", 11

platypus
"mammals.txt", 3, 8
"venomous.txt", 2
```

This indicates that the word `capybara` is found in the file `mammals.txt` in position 11. The word `platypus` is found in two files, `mammals.txt` and `venomous.txt`. In the file `mammals.txt`, the word `platypus` appears twice in positions 3 and 8. In file `venomous.txt`, the word `platypus` is in position 2 in the file.

## Functionality ##

Pending.

## Execution ##

Your `main` method must be placed in a class named `Driver`. The `Driver` class should accept the following command-line arguments:

- `-d directory` where `-d` indicates the next argument is a directory, and `directory` is the directory of text files that must be processed

- `-i indexpath` where `-i` is an *optional* flag that indicates the next argument is a file path, and `indexpath` is the path to the file to use for the inverted index output file. If the `indexpath` argument is not provided, use `index.txt` as the default output filename. If the `-i` flag is not provided, do not produce an output file.

The `Driver` class should be the only file that is not generalized and specific to the project. If the proper command-line arguments are not provided, the `Driver` class should output a user-friendly error message to the console and exit gracefully.

## Output ##

The output of your program should be a file that contains the contents of your inverted index in alphabetically sorted order using the following output format:

```
capybara
"/absolute/path/to/mammals.txt", 11

platypus
"/absolute/path/to/mammals.txt", 3, 8
"/absolute/path/to/venomous.txt", 2
```

where the word is listed alone on a single line, followed by lines with the absolute file path, and a comma-separated list of locations. An empty line should separate entries. The words should be output in sorted order, and the files should be sorted by the absolute path name.

## Submission ##

You must commit your project to your SVN repository using Eclipse at:

```
https://www.cs.usfca.edu/svn/username/cs212/project1
```

where `username` should be replaced with your CS username. Verify that your repository includes the `src` directory with all of the `*.java` files necessary to compile your program.

:bulb: See the **Project Submission** guide for additional details on testing, submission, and code review.


