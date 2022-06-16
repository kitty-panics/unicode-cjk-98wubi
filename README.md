# Unicode-CJK-98Wubi

整理 Unicode CJK 字符的 98 五笔编码。

## 协作整理

由于疏忽、参考资料有误等，码表可能会存在一些错误，
如果你发现了错误请通过 [PR] 或者 [issues] 反馈给我。

+ 如果熟悉 Git 操作可在更正错误后发起 [PR]。
+ 如果不会 Git 操作可在 [issues] 中发起反馈。

[PR]: https://github.com/kitty-panics/unicode-cjk-98wubi/pulls
[issues]: https://github.com/kitty-panics/unicode-cjk-98wubi/issues

## 数据格式

每个文件一行一字，以 Tab (制表符) 进行分割，如果某字存在多个编码时，以
`,`(英文逗号)字符进行分割，例：

```Text
U+4E00	一	ggll
U+4E01	丁	sgh
U+4E11	丑	nhg,nhgg
U+4E1C	东	aii
U+4E24	两	gmww
```

## 文件列表

+ [All.txt]
    + 整合下面 CJK/A/B/C/D/E/F/G/Compatibility/Compatibility-Supplement。
+ [CJK-Unified-Ideographs.txt] (中日韩统一表意文字)
+ [CJK-Unified-Ideographs-Extension-A.txt] (中日韩统一表意文字扩展区 A)
+ [CJK-Unified-Ideographs-Extension-B.txt] (中日韩统一表意文字扩展区 B)
+ [CJK-Unified-Ideographs-Extension-C.txt] (中日韩统一表意文字扩展区 C)
+ [CJK-Unified-Ideographs-Extension-D.txt] (中日韩统一表意文字扩展区 D)
+ [CJK-Unified-Ideographs-Extension-E.txt] (中日韩统一表意文字扩展区 E)
+ [CJK-Unified-Ideographs-Extension-F.txt] (中日韩统一表意文字扩展区 F)
+ [CJK-Unified-Ideographs-Extension-G.txt] (中日韩统一表意文字扩展区 G)
+ [CJK-Compatibility-Ideographs.txt] (中日韩兼容表意文字)
+ [CJK-Compatibility-Ideographs-Supplement.txt] (中日韩兼容表意文字增补)

**注：**

为方便管理，将争议字符 "〇 U+3007" 由 "CJK Symbols and Punctuation (中日韩符号和标点)"
移动到 "CJK Unified Ideographs (中日韩统一表意文字)"，并置于文件开头。

[All.txt]: All.txt
[CJK-Unified-Ideographs.txt]: CJK-Unified-Ideographs.txt
[CJK-Unified-Ideographs-Extension-A.txt]: CJK-Unified-Ideographs-Extension-A.txt
[CJK-Unified-Ideographs-Extension-B.txt]: CJK-Unified-Ideographs-Extension-B.txt
[CJK-Unified-Ideographs-Extension-C.txt]: CJK-Unified-Ideographs-Extension-C.txt
[CJK-Unified-Ideographs-Extension-D.txt]: CJK-Unified-Ideographs-Extension-D.txt
[CJK-Unified-Ideographs-Extension-E.txt]: CJK-Unified-Ideographs-Extension-E.txt
[CJK-Unified-Ideographs-Extension-F.txt]: CJK-Unified-Ideographs-Extension-F.txt
[CJK-Unified-Ideographs-Extension-G.txt]: CJK-Unified-Ideographs-Extension-G.txt
[CJK-Compatibility-Ideographs.txt]: CJK-Compatibility-Ideographs.txt
[CJK-Compatibility-Ideographs-Supplement.txt]: CJK-Compatibility-Ideographs-Supplement.txt

## 参考资料

参考资料可在 [参考资料] 目录下找到。其中非文件类的在线资料将转换成 PDF 快照存放。

+ 2022-06-07 更新的 [RIME-DATA.7z]

[参考资料]: 参考资料
[RIME-DATA.7z]: http://98wb.ysepan.com

## 相关项目

### [unicode-cjk]

整理所有 Unicode CJK 字符。

[unicode-cjk]: https://github.com/kitty-panics/unicode-cjk

### [unicode-cjk-98wubi]

整理 Unicode CJK 字符的 98 五笔编码。

[unicode-cjk-98wubi]: https://github.com/kitty-panics/unicode-cjk-98wubi

### [cn-tables]

整理中国大陆简中、中国台湾繁中的国标汉字表。

[cn-tables]: https://github.com/kitty-panics/cn-tables

### [CNS11643-Unicode-Cangjie]

CNS11643、Unicode、Cangjie 对照表。

[CNS11643-Unicode-Cangjie]: https://github.com/kitty-panics/CNS11643-Unicode-Cangjie

### [unicode-cjk-ids]

备份 "[chise/ids.git]" 仓库。

[unicode-cjk-ids]: https://github.com/kitty-panics/unicode-cjk-ids
[chise/ids.git]: http://git.chise.org/git/chise/ids.git
