# 电子书

如果想自己写一点营养的内容，该工具提供电子书模板。

## 环境要求

* macosx
* MacTex
* pandoc
* cookiecutter

初始化步骤：

1. `brew install mactex`
2. `brew install pandoc`
3. `brew install cookiecutter`

## 使用步骤

1. `cookiecutter https://github.com/lanen/ebook.git`
2. `cd ebook && make singlehtml`

电子书的目录如下：


```
├── Makefile
├── common
│   ├── author.html
│   ├── css
│   │   └── vendor.css
│   ├── head.html
│   ├── img
│   │   ├── cover.jpg
│   │   └── favicon.ico
│   ├── metadata.xml
│   ├── share.html
│   ├── stats.html
│   └── style.css
└── src
    └── 01intro.md
```
