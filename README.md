# 《利用Python进行数据分析·第3版》学习笔记

> 时隔5年，《利用Python进行数据分析》在2022年9月20日推出了最新的第3版。在此次新版“鼹鼠书”中，Wes亲自讲解了最新的1.4版的Pandas。这次，很高兴能受邀翻译第3版的《利用Python进行数据分析》，22年11月底翻译好了本书，还有不到一个月，这本书应该就快能付梓啦。

这5年中，数据分析又发生了很大的变化。尤其是眼见着OpenAI的GPT横扫技术领域，让以往一切模型方法看起来都像“小孩子的游戏”一样。大模型成为了海量信息和有效信息之间的新桥梁，而上一座桥梁是以谷歌的PageRank为代表的搜索算法。幸好，因为数据分析是直接跟数据打交道，并且要根据数据生成决策，这方面是人的强项，暂时不会受到影响。

相比GPT，pandas本身也在快速进步着。实际上，就在二月中旬，[pandas发布了2.0大版本](https://datapythonista.me/blog/pandas-20-and-the-arrow-revolution-part-i)，引入了PyArrow、优化了内存计算方法、优化了索引结构，以后用Pandas进行机器学习和大数据分析工作就更加便捷了。

![](https://upload-images.jianshu.io/upload_images/7178691-8dfb9dd7b75260aa.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/41240)

第三版多了**41**页内容，pandas升级为1.4.0、Python升级为3.10。第三版最大的变化是**紧贴pandas升级，主要是新增了方法和特性的内容**。另外，第三版有作者的[在线开源电子版](https://wesmckinney.com/book/)了，可以从[GitHub地址](https://github.com/wesm/pydata-book)和[Gitee地址](https://gitee.com/wesmckinn/pydata-book)下载本书代码。

第三版目录略有调整，不如第二版和第一版的变化大：
- 第4章NumPy基础新增了生成伪随机数；
- 第7章数据清洗新增了扩展数据类型和分类数据，实际是把第二版中第12章的内容放到新版第7章里了；
- 第11章时间序列新增了分组时间重采样。

曾经不止一次听别人抱怨，pandas的知识点分散、零碎、不便于记忆。在细节上，作者这次在新版中摒弃了许多容易造成记忆混乱的用法。比如，用`axis = "columns"`替代`axis = 1`，简写方式破坏了代码的可读性，作者修改了许多类似的编程细节。新版对初学者更为友好了！

***

> 只用了两个半月的时间，翻译出了第3版，真是太担心有错误了T_T

<div align=center>
    <a href="https://item.jd.com/13255935.html">
        <img src="https://tva1.sinaimg.cn/large/008vxvgGly1h8obmj8oc6j308w08w3z2.jpg" width="200px">
    </a>
</div>
<div align=center>
    <p>我的微信·WeChat，欢迎沟通 ^_^</p>
</div>
