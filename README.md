# pdf-pdfminer-　　
安装pdfminer可以实现pdf的阅读，提取pdf中的文字信息，检索关键字信息，整理成表，表可以在内存中，也可以存到硬盘上。  
Traceback (most recent call last):　　
  File "pdf_2.py", line 5, in <module>　　
    from pdfminer.pdfdocument import PDFDocument　　
  File "/home/nathan/appStore/anaconda3/lib/python3.7/site-packages/pdfminer/pdfdocument.py", line 26, in <module>　　
    from .pdftypes import PDFObjectNotFound　　
ImportError: cannot import name 'PDFObjectNotFound' from 'pdfminer.pdftypes' (/home/nathan/appStore/anaconda3/lib/python3.7/site-packages/pdfminer/pdftypes.py)　　
## 项目方案  

---------------- 
输入一个txt文档，根据txt文档中内容按照一定的格式，捡出关键的单词，将单词放到有道上面去查询，
根据单词生成汉意，词根，短语，造句等内容，然后将内容写入doc文档之中，实现自动查询单词  
