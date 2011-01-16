Somehow, it seems that after cloning a repo and then pushing the very first files to the remote repository, is putting the files somewhere else then when pushing files after that.

On github, files with no branch and with a branch called 'master' seem to be merged into the same view. Which makes this problem less appearant. But on assembla the initial files are displayed on the main source-list, while all future commits are only seen via the page branches->master.

Also, one should first use 'git push origin master', and after that can just use 'git push'.
