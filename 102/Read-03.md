# Revisions and the Cloud

## Version Control
allows you to revisit various versions of a file(s) by recording changes.
you can revert a file/project to a previous version, track modifications, compare changes.
- local VCS - database on hard disk that stores changes to files
- centralised version control - single server storing all changes and file versions which can be accessed by various clients.
- distributed version control - if CVS fails, collaborators cant work together on a file or save changes and new versions - all work lost if no backups/corrupted central database hard disk. DVCS allows clients to create mirrored repositories - data backups can be placed on a server to replace lost information

## Cloning in Git
Git is a DVCS stores dtaa in a file system made up of snapshots. each time you commit, git creates snapshots of file and stores a reference of it. need to add, commit push locally each time you make changes

- $ git clone https://github.com/test

## Command to track and stage files
## Command to take a snapshot of your changed files?
## Command to send your changed files to Github?

git status - add . - commit -m " " - push




