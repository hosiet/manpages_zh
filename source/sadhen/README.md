## sadhen的翻译目录

这里存放我的翻译源文件和一些解决方案。

### 说明
这里的翻译以Debian Sid中的man pages为基础。逐步移植cmpp遗留下来的文档。

对于文档中不明白的地方。先不翻译，应当看源代码之后再翻译。

### 翻译流程
每次翻译`sadhen/todo`中的一篇。翻译好之后，移动到`sadhen/migrated`目录。

每次翻译好之后，从cmpp中认领一篇，并且移动到`sadhen/todo`。

翻译好的文件整理到[coreutils-ronn](https://github.com/man-pages-zh/coreutils-ronn)

### 翻译规范
1. man的各节标题（指NAME,DESCRIPTION），以后用程序统一替换
2. 尽可能用全角，因为全角全局替换成半角大多没有损失信息
3. 文档最后最好加上文档信息，翻译指的是原文档的译者，维护指的是当前的维护者。如果只有翻译没有维护，那么表示翻译和维护是同一个人。
