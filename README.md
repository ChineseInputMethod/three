windows 8.1 windows 10 windows 11系统，[下载安装](https://github.com/ChineseInputMethod/three/releases)

[macOS安装说明](https://www.shurufa.org/docs/download-macos-install/)

[Linux安装说明](https://www.shurufa.org/docs/download-linux-install/)

[学习教程](https://www.shurufa.org/docs/course-initial-guide//)

如果用户文件夹中，没有`default.custom.yaml`文件，可以拷贝custom文件夹中的`default.custom.yaml`文件到用户文件夹。

如果用户文件夹中，已有`default.custom.yaml`文件，添加以下代码到文件末尾。

```yaml
patch:
  "schema_list/@0":
    schema: three
```

