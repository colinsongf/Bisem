# 栢森（Bisem）中文语义纠错系统
##程序由三部分构成：</br>
【已完成】第一部分是构建语义语料库，其中包含了构建名词动词搭配语料库和构建知网义原语料库；</br>
数据来源：</br>
1.[GoogleBooksNgramViewer](http://storage.googleapis.com/books/ngrams/books/datasetsv2.html) </br>
2.[旧版知网义原语料库](http://download.csdn.net/detail/firparks/9814417)</br>
【已完成】第二部分是构建语义级纠错模块，其主要是利用知网义原语料库进行语义依存分析，判断名词动词之间的义项是否存在义原搭配关系，并给出待纠错的位置；</br>
【未完成】第三部分是构建分布式系统，其主要是利用hadoop这一分布式架构实现MapReduce的设计思路，使服务器集群能够对大规模语料进行训练任务和纠错任务。</br>
