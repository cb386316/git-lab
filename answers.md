Answer 1: usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

Answer 2:	user.name=Connor Barber
		user.email=cb386316@ohio.edu

Answer 3: It pulls up a list of commands and explains what they do.
		
Answer 4: On branch master

	No commits yet

	Untracked files:
  		(use "git add <file>..." to include in what will be committed)

		README.md
		answers.md

	nothing added to commit but untracked files present (use "git add" to track)

Answer 5: On branch master

	No commits yet

	Changes to be committed:
  		(use "git rm --cached <file>..." to unstage)

		new file:   README.md

	Untracked files:
  		(use "git add <file>..." to include in what will be committed)

		answers.md

Answer 6: On branch master

	No commits yet

	Changes to be committed:
  		(use "git rm --cached <file>..." to unstage)

		new file:   README.md

	Untracked files:
  		(use "git add <file>..." to include in what will be committed)

		answers.md

	cbarber@sp-011:~/2400/git-lab$ git add answers.md
	cbarber@sp-011:~/2400/git-lab$ git status
	On branch master

	No commits yet

	Changes to be committed:
  		(use "git rm --cached <file>..." to unstage)

		new file:   README.md
		new file:   answers.md

Answer 7: On branch master
	Changes not staged for commit:
  		(use "git add <file>..." to update what will be committed)
  		(use "git checkout -- <file>..." to discard changes in working directory)

			modified:   answers.md

	no changes added to commit (use "git add" and/or "git commit -a")
	cbarber@sp-011:~/2400/git-lab$ git commit -m "Initial commit"
	On branch master
	Changes not staged for commit:
			modified:   answers.md

	no changes added to commit
	cbarber@sp-011:~/2400/git-lab$ git status
	On branch master
	Changes not staged for commit:
  		(use "git add <file>..." to update what will be committed)
  		(use "git checkout -- <file>..." to discard changes in working directory)

			modified:   answers.md

	no changes added to commit (use "git add" and/or "git commit -a")

Answer 8: commit c40c4f5b21841c3fad7dcd32767286ce7d9da160 (HEAD -> master)
	Author: Connor Barber <cb386316@ohio.edu>
	Date:   Wed Jan 22 17:02:44 2020 -0500

    	Initial commit

Answer 9: Counting objects: 4, done.
	Delta compression using up to 8 threads.
	Compressing objects: 100% (3/3), done.
	Writing objects: 100% (4/4), 749 bytes | 749.00 KiB/s, done.
	Total 4 (delta 0), reused 0 (delta 0)
	To https://github.com/cb386316/git-lab.git
 	* [new branch]      master -> master
	Branch 'master' set up to track remote branch 'master' from 'origin'.
	cbarber@sp-011:~/2400/git-lab$ git status
	On branch master
	Your branch is up to date with 'origin/master'.

	Changes not staged for commit:
  		(use "git add <file>..." to update what will be committed)
  		(use "git checkout -- <file>..." to discard changes in working directory)

			modified:   answers.md

	no changes added to commit (use "git add" and/or "git commit -a")

Answer 10: No, it did not alter the local copy

Answer 11: It did not alter the README.md file

Answer 12: It appears to have done so, with the addition of some colored text, with arrows
infront of them 

Answer 13: .  ..  .git  .gitignore  README.md








