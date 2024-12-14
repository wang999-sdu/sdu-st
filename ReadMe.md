### 写作：

参考：
https://ebf-contribute-guide.readthedocs.io/zh-cn/latest/install-sphinx-env/vscode.html


```
make clean
make html
build目录中文件可以删除，使用make html命令生成
```



### 编译部署：

- 上传到github仓库中：

```
$ git add -A
$ git commit -m 'RtD need'
$ git push -u origin main  # 遇到git push失败，网络问题，不稳定，等等再试试
```

- 在ReadtheDocs中编译：
```
登录github账户
https://app.readthedocs.org/projects/sdu-st/builds/26588231/
点击重建 - 查看文档
```

