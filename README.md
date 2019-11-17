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

## Creating a New Project ##

1. Type C-x pn to create a new project.
2. Provide the name of the project, project directory, and the initial cursor position within the project. For example, a src directory could be used for the initial cursor position.
3. C-x pj to jump to the new created project. 

## Switching Projects ##

The image below shows the selection of a project from the project window and
then using the multi-project find-file to filter the project files.

![Multi-project-recording.gif](https://osdn.dl.osdn.net/storage/g/m/mu/multi-project/Multi-Project-recording.gif)

