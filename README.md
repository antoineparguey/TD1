Git interative rebase
<re your work with others.
In this section, you’ll see how to accomplish these tasks so that you can make your commit history look the way you want before you share it with others.
Changing Multiple Commit Messages
To modify a commit that is farther back in your history, you must move to more complex tools. Git doesn’t have a modify-history tool, but you can use the rebase tool to rebase a series of commits onto the HEAD that they were originally based on instead of moving them to another one. With the interactive rebase tool, you can then stop after each commit you want to modify and change the message, add files, or do whatever you wish. You can run rebase interactively by adding the -i option to git rebase. You must indicate how far back you want to rewrite commits by telling the command which commit to rebase onto.
Edouard MINIAU
