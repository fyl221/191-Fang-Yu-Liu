# This repository is for basic-commits exercise
# 1. Ouput of git log:
commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (HEAD -> master, origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh

    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
Date:   Wed Dec 4 07:46:31 2019 +0200

    Word ordering

commit 6ccb85882dc12fb0b26acd65bead2fc7da57a187
Author: Frank Theile <ftheile@grundfos.com>
Date:   Wed Nov 27 08:24:29 2019 +0100

    Mention `less` in SHELL-BASICS.md

    Helpful alternative to `cat` for long files.

# 2. Output of git status:
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../3-way-merge/README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.txt
        ../fd
        ../less

no changes added to commit (use "git add" and/or "git commit -a")

# 3. Output of git status:
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../3-way-merge/README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../fd
        ../less

# 4. Output of git status:
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../3-way-merge/README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../fd
        ../less

no changes added to commit (use "git add" and/or "git commit -a")

# 5. Ouput of git status:
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../3-way-merge/README.md
        modified:   test.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../fd
        ../less

no changes added to commit (use "git add" and/or "git commit -a")

# 6. Output of git status:
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   test.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../3-way-merge/README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../fd
        ../less

# 7. Output of git status:
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../3-way-merge/README.md
        modified:   test.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../fd
        ../less

no changes added to commit (use "git add" and/or "git commit -a")

# 8. Output of git log:
commit 94eb6d936e75392d7a074be2bc638c2dea8f9880 (HEAD -> master)
Author: fyl221 <60276685+fyl221@users.noreply.github.com>
Date:   Fri Jan 24 21:29:10 2020 -0800

    Change test.txt

commit d5869911838c12e08aa8016becd753115a28dcf5
Author: fyl221 <60276685+fyl221@users.noreply.github.com>
Date:   Fri Jan 24 21:25:47 2020 -0800

    Add test.txt

commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh

    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
:...skipping...
commit 94eb6d936e75392d7a074be2bc638c2dea8f9880 (HEAD -> master)
Author: fyl221 <60276685+fyl221@users.noreply.github.com>
Date:   Fri Jan 24 21:29:10 2020 -0800

    Change test.txt

commit d5869911838c12e08aa8016becd753115a28dcf5
Author: fyl221 <60276685+fyl221@users.noreply.github.com>
Date:   Fri Jan 24 21:25:47 2020 -0800

    Add test.txt

commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh

    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
Date:   Wed Dec 4 07:46:31 2019 +0200

    Word ordering

commit 6ccb85882dc12fb0b26acd65bead2fc7da57a187
Author: Frank Theile <ftheile@grundfos.com>
Date:   Wed Nov 27 08:24:29 2019 +0100

    Mention `less` in SHELL-BASICS.md

    Helpful alternative to `cat` for long files.

commit f805e2ad3fe14cc8d3a4dcce2da50b50601d0ac7
Author: Mads Jensen <maj@praqma.net>
Date:   Fri Sep 13 13:18:28 2019 +0200

    Added kata for .gitattributes

commit 96690446d090d99146f9daf0497f06169e4e9141
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Nov 25 13:33:47 2019 +0100

    Simplify `git lol` alias

    `--oneline` is is a shorthand for `--pretty=oneline --abbrev-commit`, see git-log(1)

commit 892d64f4ffb1031ff22847ef906d1f0083e7dfe5
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Nov 25 13:58:22 2019 +0100

    Fix link in squashing-README

commit 1f9ead1c32dbf5bdd9a4cc45ae94a0d9fc92298e
Author: Brent Clark <clark@sedsystems.ca>
Date:   Fri Oct 18 16:14:28 2019 -0600

