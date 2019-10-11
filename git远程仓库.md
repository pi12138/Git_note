# git 远程仓库

## 生成ssh密钥

- `ssh-keygen`
- `ssh-keygen -t rsa -C "your_email@example.com"`
- 根据生成密钥的提示，复制生成文件里的密钥
- 在githhub --> settings -->SSH and GPG keys中设置

## `git push`

- `git push github使用仓库网址 branch_name`

- 用户将本地文件上传到github的仓库中

## `git pull`

- `git pull github使用仓库网址 branch_name`
- 本地用户下载仓库文件

## `git clone`

- `git clone github使用仓库网址 branch_name`
- 其他用户克隆仓库文件

## github上的仓库

- 创建github账号
- 创建仓库
- clone 仓库到本地
- 本地 push到仓库
- pull 代码到本地
- ignoring files
  - 可以忽略一些不想被追踪的文件
- fork and pull request