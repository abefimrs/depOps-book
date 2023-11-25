# Git Restore

The `git restore` command is used in Git to restore working tree files or to restore the content of a file to a specific state. It provides a flexible way to discard changes in your working directory or to selectively restore specific files.

## Basic Usage

To discard changes in the working directory for a specific file:

``
git restore <file>
``


To restore a file to a specific commit or branch:

```bash
git restore --source=<commit or branch> <file>



### Options

<file>: Specifies the file or files you want to restore.
--source=<commit or branch>: Specifies the source commit or branch from which to restore the file.


## Examples

### Discard Changes

 Discard changes made to a specific file in the working directory:

 git restore myfile.txt

 > git restore <directory>

 > git restore .


Restore from a Specific Commit

	Restore a file to its state in a specific commit:


git restore --source=abc123 myfile.txt


Restore from a Specific Branch

Restore a file to its state in a specific branch:

git restore --source=feature-branch myfile.txt



