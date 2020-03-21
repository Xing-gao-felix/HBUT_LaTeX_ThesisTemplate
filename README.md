# HBUT_LaTeX_ThesisTemplate
 湖北工业大学LaTeX本科论文模板
--- 
注释写的很详细,把所有文件放在一个文件夹中,再用xelatex编译即可
---
**注意!**
字体调用的是Windows字体库,Mac和Linux编译时需重新设定字体,后期回进行改进.
---
文献引用需要对文献格式文件(bst文件,texlive2019中文件名为 gbt7714-unsrt.bst)进行调整 'show.missing.address.publisher #1 出版项缺失时显示“出版者不详” '
将 #1 改为 #0 关闭此功能

详细信息参见:[gbt7714宏包文档](http://ctan.math.illinois.edu/biblio/bibtex/contrib/gbt7714/gbt7714.pdf)
