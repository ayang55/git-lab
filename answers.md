Answer 1: git version 2.28.0.windows.1
Answer 2: diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
user.name=Andrew Yang
Answer 3:PS C:\Users\muyia\Documents\cs2400\git-lab>  git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
Answer 4:PS C:\Users\muyia\Documents\cs2400\git-lab> git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
Answer 5:PS C:\Users\muyia\Documents\cs2400\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
Answer 6:On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
Answer 7:*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'muyia@LAPTOP-6LOJ8DR1.(none)')
PS C:\Users\muyia\Documents\cs2400\git-lab> git config --global user.email "ay764920@ohio.edu"
PS C:\Users\muyia\Documents\cs2400\git-lab> git config --global user.name "Andrew Yang"
PS C:\Users\muyia\Documents\cs2400\git-lab> git commit -m "Initial commit"
[master (root-commit) 4f7130d] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
Answer 8:commit 4f7130d46c9de26e223727eef9b9bc593a831473 (HEAD -> master)
Author: Andrew Yang <ay764920@ohio.edu>
Date:   Tue Sep 1 18:16:37 2020 -0400

    Initial commit
Answer 9: Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 226 bytes | 226.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ayang55/git-lab.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
Answer 10: No
Answer 11: ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/ayang55/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Answer 12:YESSSSSSSSSSSSSSSSSSSSSS
Answer 13:Directory: C:\Users\muyia\Documents\cs2400\git-lab-2


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----         9/1/2020   7:47 PM            302 .gitignore
-a----         9/1/2020   7:47 PM             11 README.md