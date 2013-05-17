**Note**: this is a work in progress (in case that's not completely obvious)!

##Inspiration
Many of the CLIs for various Ruby applications have a very intuitive interface, e.g. gem, knife, vagrant.  IMHO, the same cannot be said about git.  Don't get me wrong, there are a lot of very good things about git, but the interface is not one of them.

For example (TODO: put some actual output in here):

If you type 'vagrant', you get a list of high level commands.

If you then type 'vagrant box', you get a list of subcommands.
If you then type 'vagrant box add', you then get specific documentation for that command.

It becomes very easy to guess/construct commands, without having to refer to the manpage or google.
It is easy to remember commands because they are formed in a consistent and predictable manner.

[] - optional parameter <br/>
<> - required parameter <br/>

gfh help [command]

##setup repository
init <br/>
clone <br/>

gfh repo init <name> <br/>
gfh repo clone <url> [branch/sha]     


##interact with remote
pull <br/>
fetch <br/>
push <br/>
?describe/info/list <br/>

gfh remote pull         #pull fetches and merges <br/>
gfh remote fetch <name> # fetch updates the local copy of the remote branch, doesn't merge <br/>
gfh remote push <name> <br/>
gfh remote list         # list all remotes <br/>
gfh remote info <name> <br/>


##index/stage

gfh index add <file(s)>         # bash expansion <br/>
gfh index remove <file(s)>      # rm?  more inline with unix command line <br/>
gfh index status [file(s)] <br/>
gfh index move <from> <to>      # mv? <br/>
gfh index commit [file(s)] <br/>
gfh index reset [file(s)]       # index is reset <br/>



##branching

gfh branch create <name> <br/>
gfh branch delete <name> <br/>
gfh branch switch <name> <br/>
gfh branch merge <name> <br/>
gfh branch rebase <name> <br/>


##working copy  
** TODO: is this even a git term, or just svn? **

stash <br/>
pop <br/>

** TODO: is stash/pop just short hand for branching? would it be better to go under that.**



        
##status/interrogation
show <br/>
log <br/>
diff <br/>


##sha related
checkout  <br/>
revert <br/>



### General notes
* what takes a single sha/file, what takes two, and what takes a range?


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
