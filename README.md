# external-hub
这是一个远程仓库，用以学习。

问题：
提示：更新被拒绝，因为您当前分支的最新提交落后于其对应的远程分支。
提示：再次推送前，先与远程变更合并（如 'git pull ...'）。详见
提示：'git push --help' 中的 'Note about fast-forwards' 小节。
解决方法：
git fetch origin            //获取远程更新
git merge origin/master     //合并到本地分支
 或者直接加-f 选项强制更新
