# Read Reflection 03 

## Git Tutorials and Comprehensive guide
Before explaining Git, you must first go back and explain **Version Control**. <br>

**_Version Control_** is a system that allows you to revisit various versions of a file or set of files by recording changes or 'snapshots'. 
- Through version control, you can: 
  - revert a project or file to a previous version. 
  - track modifications
  - compare changes

By using a Version Control System, mistakes can easily be revisited and corrected. 
<br><br><br><br>


### Local Version Control Systems 

    Many years ago, programmers created the Local Version Control Systems that utilized one local database to store changes.  

### Cetnralized Version Control Systems

    The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System. CVCS uses a single server to track and store all changes and file versions, can be accessed by various clients, and generally streamlined the process with the doors opened up for collaboration. 

### Distributed Version Control Systems 

    Eliminated the main vulnerability in CVCS of having everything rest on a single server. DVCS allows clients to create mirrored repositories. These data backups can be easily uploaded on the server if needed. DVCS allows for multiple mirrored repositories, which opens dooes for further innovation in joint collaboration. 
<br><br><br><br>

## So... What is Git?

<br>

**_Git is a DVCS_** that stores data in a file system made up of snapshots. 
- Every time you commit, Git creates a snapshot of the file and stores a reference to it. 
  - If a file hasn't changed, git will store a reference to the already stored version of it. 
- Mostly relies on local operations
  - Makes everything faster as history is stored on the local disk. 
  - This allows clients to work offline and or use a VPN. 
- Every change is tracked. Any corruption or lost data will be detected by git. 

### Files in git can reside in three states: 

*commited, modified, and staged.* 

<br><br>
1. **Committed** files are securely stored in a local database. 
1. **Modified** files have been changed but are not committed to the database. 
1. **Staged** files are flagged as 'to be committed' in the next snapshot. 

### Getting Help with Git in terminal
- Commands: 

        man git
        git help   


### Setting up a Git Repository: 

To import an existing project or directory into git...
<br>

1. Switch to project directory
        
        $ cd test


1. Use git init command
        
        $ git init

      - This has created a sub-directory named .git that has all of the repositories. Tracking has not yet commenced. 

1. To start tracking repositories, perform an initial commit with the following commands: 
        
        $ git add *.c
        $ git add LICENSE
        $ git commit -m "insert comment here"


