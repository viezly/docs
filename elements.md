# Elements

We aim to make diagram elements intuitive as much as possible, so most of them should be understood from the first look.  
Nevertheless, we created this page to give you a full overview of all elements you can find in diagrams.

## Files

The files are the core of each diagram. They are displayed as blocks of different colors depending on their status.

A new file is displayed as a green block:  

![added file](_media/elements/added_file.png ':size=200')

------

A changed file is displayed as an orange block:  

![changed file](_media/elements/changed_file.png ':size=200')

------

A removed file is displayed as a red block:  

![removed file](_media/elements/removed_file.png ':size=200')

------

A file without changes is displayed as a gray block:  

> Such file may appear if there are new/removed relations to it from new/changed files

![non-changed file](_media/elements/existing_file.png ':size=200')

------

The file with `tied` files.

> A `tied` file is a file which is highly bound with the original file and won't exist without it. 
> The examples are the unit tests for particular class, styles of particular component in separate file.

Such files are displayed with tags in the bottom-left corner:  

![file with tags](_media/elements/file_with_tags.png ':size=200')

> The colors of the file and the tags might be different e.g. file is changed, but tests are added.


## Relations

The relations between files are represented as the arrows of appropriate color.

> A relation between files is either an import (e.g. JS) or the entity, declared in one file, being used in another file 
(e.g. class declared in one file is used in another file).  

New relation between files:  
![new relation](_media/elements/added_relation.png ':size=200')

Removed relation between files:  
![removed relation](_media/elements/removed_relation.png ':size=200')

Existing relation between files:  
![existing relation](_media/elements/existing_relation.png ':size=200')


## Folders

A folder corresponds to a file-system folder:  
![folder](_media/elements/folder.png ':size=250')
