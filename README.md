# vc-configer
voice changer service configer

[server_addr]
addr1=47.57.93.155:31345
addr2=47.57.93.155:31345

## 提交github流程

[参考](https://geek-docs.com/git/git-questions/264_git_how_to_configure_git_with_ssh_keys_on_windows_10.html)

git push前需要创建一个虚拟代理，如下：

```shell
eval $(ssh-agent -s)
ssh-add /c/Users/Administrator/.ssh/github-baikaishui.priv
# 找不到密钥，在 personal-collection-gitee\其他\secrets\github 中找

git add xxx.file
git commit -m "add v0.3.5"
git push origin main
```