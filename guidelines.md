#Guidelines

topics: 

1. Meetings
2. Trello
3. Documents to be worked on (github)
4. Descriptive documents (gdrive)


##1. Meetings
- if not decided otherwise meetings are scheduled for Wednesdays and Fridays
- until we agree on a fixed time, the time is decided on doodle (Thomas)
- the scheduled meetings are listed on the Trello board "Meetings and Conference Calls" with according cards
- the cards contain a checklist "agenda suggestion"
- after the meeting the minutes are linked to the card via a github-link in the comment section (Thomas)

##2. Trello
- everyone is promted to track their own tasks, create according boards, cards and checklists and if necessary assign 
them to other users and provide them with due dates 

##3. Documents to be worked on (github)
- minutes, proposals, pitches and visions should be stored on github (https://github.com/yeehaa123/erc)
- documents should be saved as markdown (.md) 
- save the documents in the appropriate folders (KIEM, minutes, pitches, vision etc.)
- you can create new files directly on github (do not forget to add the ".md" to the filename) or push them from your 
local repository onto github:

- git init
- git add <filename>
- git commit -m "First Commit – Added Document X"
- git push origin master

- Information on .md can be found at:
	- [http://daringfireball.net/projects/markdown/syntax](http://daringfireball.net/projects/markdown/syntax)
	- [http://blog.lib.umn.edu/crosb002/leadership/Markdown_Cheat_Sheet.pdf](http://blog.lib.umn.edu/crosb002/leadership/Markdown_Cheat_Sheet.pdf)
- .md documents can be created in any text editor, e.g.:
	- [http://www.sublimetext.com/](http://www.sublimetext.com/) 
- pandoc is a useful program to convert .md files into html, docx or ODT and many other formats 	
	- [http://johnmacfarlane.net/pandoc/](http://johnmacfarlane.net/pandoc/)
	- e.g. use your console to navigate into the folder with a file you want to convert from .md into .html
	- enter: pandoc filename.md -f markdown -t html -s -o filename.html

##4. Descriptive documents (gdrive)
- if relevant, calls for funding proposals should be stored on gdrive in the folder *funding/name*
- calls for papers and presentations should be stored in the folder *papers_and_presentations/year-month-date_name*
- information about private parters should be saved in the folder *private_partners/name*
- each private partner folder should contain a fact sheet (?)
