## 七月在线机器学习集训营第七期课件库
#### 本仓库内课件仅供第七期学员参考使用，请勿外传，请勿修改master下的任何文件
#### 本仓库内课件搭配mybinder.org共同使用，地址为：https://mybinder.org/v2/gh/julyedu-train/train7/master
#### mybinder.org容器服务使用有时间限制，请随时注意保存您的练习和试卷
#### 同学提交作业和试卷push时，请以自己姓名全拼新建分支，并仅commit变更的文件，请勿覆盖master分支

## 从mybinder.org上新建、切换分支 ，并回推github，实现试卷提交
### 打开binder jupyter notebook上的terminal
### 配置
```$git config --global user.email "jack@hack.com"```
```$git config --global user.name "jack"```
### 新建本地分支
```$git branch jack```
### 查看分支
```$git -branch -a```
### 切换分支
```$git checkout  jack```
### 再查看确认下当前分支
```$git branch```
### 推送分支至github 远程(假定github上没有该分支)
```$git push --set-upstream origin jack```
#### 返回信息
```
Username for 'https://github.com': julyedu-train
Password for 'https://julyedu-train@github.com':
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for ' jack' on GitHub by visiting:
remote:      https://github.com/julyedu-train/train7/pull/new/jack
remote:
To https://github.com/julyedu-train/train7
 * [new branch]      jack -> jack
Branch ' jack' set up to track remote branch ' jack' from 'origin'.
```
### 先add变更的文件，注意不要 add . ,再commit,最后push
```
$git add Python-1.ipynb
$git commit -m 'jack from binder.org'
$git push
$github上查看结果
```


