** Work in progress

    [] - optional

gfh help [command]

*setup repository
init
clone

gfh repo init <name>
gfh repo clone <url> [branch/sha]     


*interact with remote
pull
fetch
push
?describe/info/list

gfh remote pull         #pull fetches and merges
gfh remote fetch <name> # fetch updates the local copy of the remote branch, doesn't merge
gfh remote push <name>
gfh remote list         # list all remotes


*index/stage

gfh index add <file(s)>         # bash expansion
gfh index remove <file(s)>      # rm?  more inline with unix command line
gfh index status [file(s)]
gfh index move <from> <to>      # mv?
gfh index commit [file(s)]
gfh index reset [file(s)]       # index is reset



* branching

gfh branch create <name>
gfh branch delete <name>
gfh branch switch <name>
gfh branch merge <name>
gfh branch rebase <name>


* working copy
stash
pop
        - is stash/pop just short hand for branching? would it be better to go under that.



        
* status/interrogation
show
log
diff


* sha related
checkout 
revert






# Unclassified git commands.
git-archive(1)
Create an archive of files from a named tree.

git-bisect(1)
Find by binary search the change that introduced a bug.

git-bundle(1)
Move objects and refs by archive.

git-cherry-pick(1)
Apply the changes introduced by some existing commits.

git-citool(1)
Graphical alternative to git-commit.

git-clean(1)
Remove untracked files from the working tree.

git-describe(1)
Show the most recent tag that is reachable from a commit.

git-format-patch(1)
Prepare patches for e-mail submission.

git-gc(1)
Cleanup unnecessary files and optimize the local repository.

git-grep(1)
Print lines matching a pattern.

git-gui(1)
A portable graphical interface to Git.

git-notes(1)
Add or inspect object notes.

git-shortlog(1)
Summarize git log output.

git-submodule(1)
Initialize, update or inspect submodules.

git-tag(1)
Create, list, delete or verify a tag object signed with GPG.

gitk(1)
The git repository browser.
