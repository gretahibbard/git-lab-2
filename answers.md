Answer 1: 
    git version 2.32.1 (Apple Git-133)
    
Answer 2: 
    credential.helper=osxkeychain
    user.name=Greta Hibbard
    user.email=gh945020@ohio.edu

Answer 3:
    The output of git --help is: (information, "help" menu)
    usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
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
    
Answer 4: two untracked files
    On branch master

    No commits yet

    Untracked files:
  (use "git add <file>..." to include in what will be committed)
    README.md
    answers.md

    nothing added to commit but untracked files present (use "git add" to track)
    
Answer 5: one tracked and one untracked file
    On branch master

    No commits yet

    Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
    new file:   README.md

    Untracked files:
  (use "git add <file>..." to include in what will be committed)
    answers.md
Answer 6:
    n branch master
    Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
    new file:   answers.md
    new file: README.md



Answer 7:
    On branch master
    nothing to commit, working tree clean
    
Answer 8:
    commit dae81c8ee12e4301fc89931a492fc40a233a1194 (HEAD -> master)
 Author: Greta Hibbard <gh945020@ohio.edu>
 Date:   Wed Sep 7 16:33:42 2022 -0400

    Initial commit

Answer 9:
    On branch main
    Your branch is up to date with 'origin/main'.

    Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
    
Answer 10: it is not the most updated version because it has not been pulled 
    (base) gretahibbard@MacBook-Pro-31 git-lab % more README.md
    Name: Greta Hibbard
Git username: gretahibbard 

    Email address: gh945020@ohio.edu
    My answers are located in file answers.md
    README.md (END)


Answer 11: it was rejected because there are two conflicting versions
    ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:gretahibbard/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: After pulling from the online directory, the updates have been made in the local directory
    Git username: gretahibbard 

    Email address: gh945020@ohio.edu
    My answers are located in file answers.md

CS 2400, Section 102

Answer 13:
base) gretahibbard@MacBook-Pro-31 git-lab-2 % ls -a
.        ..        .git        .gitignore    README.md


