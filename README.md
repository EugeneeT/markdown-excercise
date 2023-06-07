# Markdown Exercise 

this is some content for V1 


[dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git status 
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git commit -am "edit README"
[master a4ef3ea] edit README
 1 file changed, 2 insertions(+)
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git log
commit a4ef3ea084abd7d286fa30ea6751f6609fdeee0c (HEAD -> master)
Author: EugeneeT <vina.botanic@gmail.com>
Date:   Wed Jun 7 11:51:01 2023 +0200

    edit README

commit a450b9a18d1e966f9223c29856a51caf83267a21 (origin/master)
Author: EugeneeT <vina.botanic@gmail.com>
Date:   Wed Jun 7 11:32:26 2023 +0200

    initial commit
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 302 bytes | 302.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:EugeneeT/markdown-excercise.git
   a450b9a..a4ef3ea  master -> master
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git branch 
* master
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git branch contentV1
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git branch 
  contentV1
* master
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git checkout contentV1 
Switched to branch 'contentV1'
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git commit -am "first content README"
[contentV1 caae537] first content README
 1 file changed, 1 insertion(+)
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git push 
fatal: The current branch contentV1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin contentV1

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ git push --set-upstream origin contentV1 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'contentV1' on GitHub by visiting:
remote:      https://github.com/EugeneeT/markdown-excercise/pull/new/contentV1
remote: 
To github.com:EugeneeT/markdown-excercise.git
 * [new branch]      contentV1 -> contentV1
branch 'contentV1' set up to track 'origin/contentV1'.
dci-student@dcistudent-ThinkPad-L15-Gen-1:~/Desktop/DCI/BDL/markdown-exercise$ ]