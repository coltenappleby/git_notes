# History and Background

### About
excel_file_final_final_finalv3.xlsx is version control - just a terrible way to do it

### History


Source Code Control System (SCCS)
- AT&T released UNIX which was closed source and with it one of the first Version Control Systems 
- came out in 1972
- AT&T gave Unix to colleges which taught there student SCCS and then everyone knew SCCS
- Kept the original file and then all of the changes that occurred after it
- Worked with only one file

Revision Control System (RCS)
- Released in 1982
- It was open sourced
- Worked on PC
- Kept the most recent file, and all the changes to move back in time
- Much faster
- Worked with only one file

Concurrent Versions Systems (CVS)
- 1986-1990
- Open Sourced
- Multiple fies, entire project
- Multi-users repositorires
- taking snapshots of files in a directory
- bad with file name changes

Apache Subversion (SVN)
- 2000 - open source
- Watching files and directories 
- tracking changes to the directories
- Tracked text files and images
- Taking snapshots of a directory

BitKeeper SCM
- 2000 - closed source 
- Distributed Version Control

Git 
- 2005 
- Linus Torvalds (also did Linus)
- Distributed Version Control
- Open-sourced and free software

### Distributed Version Control
- Different users maintain their own repos
- No central repo
- Changes are stored as change sets
    - Tracks changes, not versions
    - Super Huge allows there tto be multiple versions of a file beacuse the system tracks each change independently not the file state
- no single master repo
- many working copies
- each woth their own combination of change sets
- Encourages participation and forking of projects
