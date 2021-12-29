# learning-git

This repo was created using Learning Git - YouTube tutorial by Amigoscode

Last login: Tue Dec 28 17:42:02 on ttys000
 ✝  ~  git --version
git version 2.34.1
 ✝  ~  ls
Adlm                       Java-1-1221                Projects                   go
Applications               Library                    Public                     node_modules
Applications (Parallels)   Mar_2020                   PycharmProjects            objc.scan
Creative Cloud Files       Movies                     Qt                         package-lock.json
Desktop                    Music                      RiderProjects              plugin-verify
Documents                  PS                         Virtual Machines.localized z.sh
Downloads                  Pictures                   VirtualBox VMs
Feb_2020                   Postman                    booking-app
 ✝  ~  cd Projects
 ✝  ~/Projects  ls
Blueberry                  DevOps                     ReactiveUI                 stripetab
BluetoothPrinter           DevOpsDemo                 TimeTracker                uberdriver
BudgetApp                  GithubFlyoutApp            TimeTrackerTutorial-master uberrider
ControlTemplateDemo        JetBrains                  Twilio
 ✝  ~/Projects  cd ..
 ✝  ~  ls
Adlm                       Java-1-1221                Projects                   go
Applications               Library                    Public                     node_modules
Applications (Parallels)   Mar_2020                   PycharmProjects            objc.scan
Creative Cloud Files       Movies                     Qt                         package-lock.json
Desktop                    Music                      RiderProjects              plugin-verify
Documents                  PS                         Virtual Machines.localized z.sh
Downloads                  Pictures                   VirtualBox VMs
Feb_2020                   Postman                    booking-app
 ✝  ~ 
 ✝  ~  git config --global user.name "jeanchar530"
 ✝  ~  git config --global user.email "joseph.jeancharles@outlook.com"
 ✝  ~  git config --global color.ui auto
 ✝  ~ 
 ✝  ~  git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <>         value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry

 ✘ ✝  ~ 
 ✘ ✝  ~  git config -l
 ✝  ~  ls
Adlm                       Java-1-1221                Projects                   go
Applications               Library                    Public                     node_modules
Applications (Parallels)   Mar_2020                   PycharmProjects            objc.scan
Creative Cloud Files       Movies                     Qt                         package-lock.json
Desktop                    Music                      RiderProjects              plugin-verify
Documents                  PS                         Virtual Machines.localized z.sh
Downloads                  Pictures                   VirtualBox VMs
Feb_2020                   Postman                    booking-app
 ✝  ~  mkdir learning-git
 ✝  ~  ls
Adlm                       Java-1-1221                Projects                   go
Applications               Library                    Public                     learning-git
Applications (Parallels)   Mar_2020                   PycharmProjects            node_modules
Creative Cloud Files       Movies                     Qt                         objc.scan
Desktop                    Music                      RiderProjects              package-lock.json
Documents                  PS                         Virtual Machines.localized plugin-verify
Downloads                  Pictures                   VirtualBox VMs             z.sh
Feb_2020                   Postman                    booking-app
 ✝  ~  cd learning-git
 ✝  ~/learning-git  ls
 ✝  ~/learning-git   git init .
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: 	git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/josephjean-charles/learning-git/.git/
 ✝  ~/learning-git   master  git config --global init.defaultBranch main
 ✝  ~/learning-git   master  git branch -m main
 ✝  ~/learning-git   main  git checkout master
error: pathspec 'master' did not match any file(s) known to git
 ✘ ✝  ~/learning-git   main  git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
 ✝  ~/learning-git   main  git ls
git: 'ls' is not a git command. See 'git --help'.

The most similar command is
	log
 ✘ ✝  ~/learning-git   main  git checkout master
error: pathspec 'master' did not match any file(s) known to git
 ✘ ✝  ~/learning-git   main 
 ✘ ✝  ~/learning-git   main  ls
 ✝  ~/learning-git   main  dir
zsh: command not found: dir
 ✘ ✝  ~/learning-git   main  ls -a
.    ..   .git
 ✝  ~/learning-git   main  rm -f .git
rm: .git: is a directory
 ✘ ✝  ~/learning-git   main 
 ✘ ✝  ~/learning-git   main  git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
 ✝  ~/learning-git   main 
 ✝  ~/learning-git   main  git init .
Reinitialized existing Git repository in /Users/josephjean-charles/learning-git/.git/
 ✝  ~/learning-git   main  git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
 ✝  ~/learning-git   main   touch index.html
 ✝  ~/learning-git   main±   touch index.js
 ✝  ~/learning-git   main±   touch main.css
 ✝  ~/learning-git   main±  ls
index.html index.js   main.css
 ✝  ~/learning-git   main± 
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html
	index.js
	main.css

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git   main±   git add index.html
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.js
	main.css

 ✝  ~/learning-git   main±  git rm --cached index.html
rm 'index.html'
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html
	index.js
	main.css

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git   main± 
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html
	index.js
	main.css

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git   main±  git add index.html
 ✝  ~/learning-git   main±  git add index.js
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html
	new file:   index.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	main.css

 ✝  ~/learning-git   main±  git add .
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html
	new file:   index.js
	new file:   main.css

 ✝  ~/learning-git   main±  git rm --cached .
fatal: not removing '.' recursively without -r
 ✘ ✝  ~/learning-git   main±  git -rm -r --cached .
unknown option: -rm
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]
 ✘ ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html
	new file:   index.js
	new file:   main.css

 ✝  ~/learning-git   main±  git rm cached -rm .
error: unknown switch `m'
usage: git rm [<options>] [--] <file>...

    -n, --dry-run         dry run
    -q, --quiet           do not list removed files
    --cached              only remove from the index
    -f, --force           override the up-to-date check
    -r                    allow recursive removal
    --ignore-unmatch      exit with a zero status even if nothing matched
    --sparse              allow updating entries outside of the sparse-checkout cone
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character

 ✘ ✝  ~/learning-git   main±  git rm -r --cached .
rm 'index.html'
rm 'index.js'
rm 'main.css'
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html
	index.js
	main.css

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git   main±  git add .
 ✝  ~/learning-git   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html
	new file:   index.js
	new file:   main.css

 ✝  ~/learning-git   main± 
 ✝  ~/learning-git   main±  git rm -r --cached .
rm 'index.html'
rm 'index.js'
rm 'main.css'
 ✝  ~/learning-git   main±  mkdir test
 ✝  ~/learning-git   main±  cd test
 ✝  ~/learning-git/test   main±  touch test.js
 ✝  ~/learning-git/test   main±  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	../index.html
	../index.js
	../main.css
	./

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git/test   main±  ls
test.js
 ✝  ~/learning-git/test   main±  git add .
 ✝  ~/learning-git/test   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   test.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	../index.html
	../index.js
	../main.css

 ✝  ~/learning-git/test   main±  git add -A
 ✝  ~/learning-git/test   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   ../index.html
	new file:   ../index.js
	new file:   ../main.css
	new file:   test.js

 ✝  ~/learning-git/test   main± 
  1 console.log("hellow git!");
  1
 ✝  ~/learning-git/test   main±  git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   ../index.html
	new file:   ../index.js
	new file:   ../main.css
	new file:   test.js

 ESC^?...skipping...
 ✝  ~/learning-git/test   main±  cd ..
 ✝  ~/learning-git   main±  git commit -m "bootstrap project"
[main (root-commit) 1084cca] bootstrap project
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 index.js
 create mode 100644 main.css
 create mode 100644 test/test.js
 ✝  ~/learning-git   main  git status
On branch main
nothing to commit, working tree clean
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main  git show 1084cca7a0c4a02a0ea9666431d68f05b2fbf4d1
 ✝  ~/learning-git   main   code index.js
 ✝  ~/learning-git   main  vi index.js
 ✝  ~/learning-git   main±  cat index.js
console.log("hellow git!");
 ✝  ~/learning-git   main±  git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.js

no changes added to commit (use "git add" and/or "git commit -a")
 ✝  ~/learning-git   main±  git diff
 ✝  ~/learning-git   main±  git add .
 ✝  ~/learning-git   main±  git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.js

 ✝  ~/learning-git   main±  git commit -m "add console.log"
[main adfedc8] add console.log
 1 file changed, 1 insertion(+)
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main  git show adfedc8ad07235a456bcc9528fbcb5c65242da9f
 ✝  ~/learning-git   main  vi index.js
 ✝  ~/learning-git   main±  git diff
 ✝  ~/learning-git   main±  git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.js

no changes added to commit (use "git add" and/or "git commit -a")
 ✝  ~/learning-git   main±  git restore index.js
 ✝  ~/learning-git   main  git status
On branch main
nothing to commit, working tree clean
 ✝  ~/learning-git   main  git diff
 ✝  ~/learning-git   main 
  1 body
  1 func main(){}
 ✝  ~/learning-git   main  ls
index.html index.js   main.css   test
 ✝  ~/learning-git   main  vi main.css
 ✝  ~/learning-git   main±  git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   main.css

no changes added to commit (use "git add" and/or "git commit -a")
 ✝  ~/learning-git   main±  git add .
 ✝  ~/learning-git   main±  git commit -m "just added"
[main a631b52] just added
 1 file changed, 3 insertions(+)
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main  git commit --amend -m "Updated body{} in main.css"
[main 07f9922] Updated body{} in main.css
 Date: Tue Dec 28 19:09:23 2021 -0500
 1 file changed, 3 insertions(+)
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main    git remote add origin https://github.com/jeanchar530/learning-git.git
 ✝  ~/learning-git   main  git branch
 ✝  ~/learning-git   main  git push -u origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (10/10), 805 bytes | 805.00 KiB/s, done.
Total 10 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/jeanchar530/learning-git.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
 ✝  ~/learning-git   main  vi main.go
 ✝  ~/learning-git   main±  git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	main.go

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git   main±  git add .
 ✝  ~/learning-git   main±  git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   main.go

 ✝  ~/learning-git   main±  git commit -m "add main.go with empty main func"
[main ebcc90e] add main.go with empty main func
 1 file changed, 1 insertion(+)
 create mode 100644 main.go
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main  git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jeanchar530/learning-git.git
   07f9922..ebcc90e  main -> main
 ✝  ~/learning-git   main 
  1 //TODO Implemt utils
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main  ls
index.html index.js   main.css   main.go    test
 ✝  ~/learning-git   main  git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 731 bytes | 243.00 KiB/s, done.
From https://github.com/jeanchar530/learning-git
   ebcc90e..36ac2a6  main       -> origin/main
Updating ebcc90e..36ac2a6
Fast-forward
 README.md | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 README.md
 ✝  ~/learning-git   main  ls
README.md  index.html index.js   main.css   main.go    test
 ✝  ~/learning-git   main  cat main.go
func main(){}
 ✝  ~/learning-git   main  git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 661 bytes | 220.00 KiB/s, done.
From https://github.com/jeanchar530/learning-git
   36ac2a6..be84bad  main       -> origin/main
Updating 36ac2a6..be84bad
Fast-forward
 main.go | 2 ++
 1 file changed, 2 insertions(+)
 ✝  ~/learning-git   main  cat main.go
package main

func main(){}
 ✝  ~/learning-git   main  git branch
 ✝  ~/learning-git   main  git branch -r
 ✝  ~/learning-git   main  git branch -a
 ✝  ~/learning-git   main  git branch feature-a
 ✝  ~/learning-git   main  git branch
 ✝  ~/learning-git   main  git branch -a
 ✝  ~/learning-git   main  git checkout feature-a
Switched to branch 'feature-a'
 ✝  ~/learning-git   feature-a  git checkout -
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 ✝  ~/learning-git   main  git checkout -
Switched to branch 'feature-a'
 ✝  ~/learning-git   feature-a  vi utils.js
 ✝  ~/learning-git   feature-a±  git status
On branch feature-a
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	utils.js

nothing added to commit but untracked files present (use "git add" to track)
 ✝  ~/learning-git   feature-a±  git add .
 ✝  ~/learning-git   feature-a±  git commit -m "util.js with with todo"
[feature-a 66e8422] util.js with with todo
 1 file changed, 1 insertion(+)
 create mode 100644 utils.js
 ✝  ~/learning-git   feature-a 
 ✝  ~/learning-git   feature-a  git log
 ✝  ~/learning-git   feature-a  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 ✝  ~/learning-git   main  git log
 ✝  ~/learning-git   main  git checkout -
Switched to branch 'feature-a'
 ✝  ~/learning-git   feature-a  git push
fatal: The current branch feature-a has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature-a

 ✘ ✝  ~/learning-git   feature-a  git push -u origin feature-a
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'feature-a' on GitHub by visiting:
remote:      https://github.com/jeanchar530/learning-git/pull/new/feature-a
remote:
To https://github.com/jeanchar530/learning-git.git
 * [new branch]      feature-a -> feature-a
Branch 'feature-a' set up to track remote branch 'feature-a' from 'origin'.
 ✝  ~/learning-git   feature-a  git checkout -
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 ✝  ~/learning-git   main  git checkout -b to-delete
Switched to a new branch 'to-delete'
 ✝  ~/learning-git   to-delete  git branch -a
 ✝  ~/learning-git   to-delete  git checkout -
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 ✝  ~/learning-git   main  git branch -d to-delete
Deleted branch to-delete (was be84bad).
 ✝  ~/learning-git   main  git branch
 ✝  ~/learning-git   main 













