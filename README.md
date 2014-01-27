CS 212 Projects
=================================================

This repository contains the project files for CS 212 Software Development at the University of San Francisco. This includes test files, input files, and expected output files.

## Project Specification ##

Please see the **[Project Specification](specifications/)** directory for project specifications, including details on how to verify and submit the projects.

## Project Setup ##

Pending.

## Updating Files ##

The project files may be periodically updated as the semester progresses. An announcement will be posted on the course website whenver these changes occur.

You must make sure you always have the latest version of these files when testing your project. You have several options for obtaining the latest files:

- You may download a zip file of this entire repository and replace your old files. The zip file is located at:

  > https://github.com/cs212/projects/archive/master.zip

- You may use `svn export` to export an individual subdirectory within this repository.

  ```
  svn export https://github.com/cs212/projects/trunk/subdirectory
  ```
  where `subdirectory` is the subdirectory to export. For example, the following will export just the files in the `specifications` subdirectory:

  ```
  svn export https://github.com/cs212/projects/trunk/specifications
  ```

  This method may be used to download single large-sized files as well.

- You may download a single small-sized file by viewing that file on GitHub and clicking the "Raw" button and saving the file through your browser. For larger files, you need to use the `svn export` approach above.

Alternatively, you can use the steps illustrated by the [GitHub Help Pages](https://help.github.com/articles/downloading-files-from-the-command-line) for downloading files. Of course, you can use `git` to update your files as well.

