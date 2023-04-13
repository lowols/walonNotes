工具使用

## idea

 查看类结构alt+7  

 浏览窗定位打开的文件 alt+F1 浏览窗右上角也有按钮

 环境参数添加 点击VM-OPTIONS， 填写 -DDOMAIN=test.baiwang-inner.com -Dspring.profiles.active=test     星舰：-Dspring.profiles.active=dkh -DDOMAIN=dkh.baiwang.com

## git

1. 浏览代码
   
   - 查看历史commit，右击->Checkout Revision ,返回最新提交（右击分支->checkout）

2. 撤销操作
   
   - 撤销commit 右击commit->revert
   
   - 撤销文件修改 右击->rollback

3. 常见操作场景
   
   - stash应对紧急需求。stash当前工作内容（开发到一半），去其他分支做紧急需求，然后返回当前分支，unstash前面的修改内容，继续工作
   
   - merge冲突，应用的点双箭头，不要的点X，还有一键全部应用某个分支所有。
   
   - 基分支有更新，需要开发分支从基分支拉取更新，idea中，右击项目目录->git->pull ->选择基分支
