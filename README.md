QIMR16204-5:~ michaelb$ git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
QIMR16204-5:~ michaelb$ gitconfig --blobal user.name "Michael Breakspear"
-bash: gitconfig: command not found
QIMR16204-5:~ michaelb$ gitconfig --global user.name "Michael Breakspear"
-bash: gitconfig: command not found
QIMR16204-5:~ michaelb$ ls
Applications			Music
Desktop				Pictures
Documents			Public
Downloads			hs_error_pid20456.log
Dropbox				java.log.385
Library				matlab_crash_dump.17525-1
Movies				matlab_crash_dump.24646-1
QIMR16204-5:~ michaelb$ cd ..
QIMR16204-5:Users michaelb$ ls
Shared		administrator	michaelb
aaronm		michaebr	saschaf
QIMR16204-5:Users michaelb$ cd michaelb
QIMR16204-5:~ michaelb$ ls
Applications			Music
Desktop				Pictures
Documents			Public
Downloads			hs_error_pid20456.log
Dropbox				java.log.385
Library				matlab_crash_dump.17525-1
Movies				matlab_crash_dump.24646-1
QIMR16204-5:~ michaelb$ cd ../..
QIMR16204-5:/ michaelb$ ls
Applications			home
EEG				installer.failurerequests
Library				matlab_local
MRI				movies
Network				myproject
System				net
Users				private
Volumes				sbin
bin				tmp
cores				usr
dev				var
etc				wave_movies
QIMR16204-5:/ michaelb$ cd myproject
QIMR16204-5:myproject michaelb$ gitconfig --global user.name "Michael Breakspear"
-bash: gitconfig: command not found
QIMR16204-5:myproject michaelb$ git config --global user.email "mjbreaks@users.noreply.github.com"
QIMR16204-5:myproject michaelb$ git init
Initialized empty Git repository in /myproject/.git/
QIMR16204-5:myproject michaelb$ vi
QIMR16204-5:myproject michaelb$ pico

  GNU nano 2.0.6                            New Buffer                                                    Modified  

hello!
## a sub-heading
goodbye!!

















^G Get Help        ^O WriteOut        ^R Read File       ^Y Prev Page       ^K Cut Text        ^C Cur Pos
^X Exit            ^J Justify         ^W Where Is        ^V Next Page       ^U UnCut Text      ^T To Spell
