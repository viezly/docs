# Elements

All elements of a diagram can be divided in 3 groups:
- files
- folders
- relations

## Files

A new file is displayed as a green block:  
![added file](_media/elements/added_file.png ':size=150')

A changed file is displayed as an orange block:  
![changed file](_media/elements/changed_file.png ':size=150')

A removed file is displayed as a red block:  
![removed file](_media/elements/removed_file.png ':size=150')

A file without changes is displayed as a gray block:  
> Such file may appear if there are new/removed relations to it from new/changed files

![non-changed file](_media/elements/existing_file.png ':size=150')


## Folders

A folder corresponds to a file-system folder:  
![folder](_media/elements/folder.png ':size=250')

## Relations

The relations between files are represented as the arrows of appropriate color.

> A relation between files is either an import (e.g. JS) or the entity, declared in one file, being used in another file 
(e.g. class declared in one file is used in another file).  

New relation between files:  
![new relation](_media/elements/added_relation.png ':size=150')

Removed relation between files:  
![removed relation](_media/elements/removed_relation.png ':size=150')

Existing relation between files:  
![existing relation](_media/elements/existing_relation.png ':size=150')