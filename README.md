# README #

Multi-project simplifies the switching between different projects by
providing support for creating, deleting, and searching between projects.
Multi-project supports interactively finding a file within a project or
automatically switching the TAGS file for symbol lookup.

Add the lines below in your .emacs file to use multi-project:

```elisp
(require 'multi-project)
(multi-project-mode)
```

## Using multi-project ##

1. Type C-x p n to create a new project.
2. Provide the name of the project, project directory, and the initial cursor position within the project. For example, a src directory could be used for the initial cursor position.
3. C-x p j to jump to the newly created project. Typing 's' will allow you to type a string to filter the list of projects. 
4. C-x p c creates a compilation command for building the project.
5. C-x p g will grep the current project.

## Switching Projects ##

The image below shows the selection of a project from the project window and
then using the multi-project find-file to filter the project files.

![Multi-project-recording.gif](https://github.com/ellisvelo/multi-project/blob/main/Multi-project-recording.gif)

## Searching Across Multiple Projects

Multi-project has the ability to search for a file across multiple projects.

1. Type C-x p j to list the projects to jump to
2. Type g to specify the projects to run grep on
3. Type x to execute the search
4. Specify what you are looking for and the file pattern.
5. The results will be displayed in separate buffers

