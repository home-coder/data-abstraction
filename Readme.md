## 2018 2 9 17:36
>考虑要反复的磨练前面的线性表存储结构,重复训练

# 数据结构与音频算法的应用
- **将处理pcm数据的方式与数据结构结合**
- **整理pcm中常见的存储方式和处理算法**


### 哈夫曼树的实现与应用
* c 的实现
* 编码实现
* 解码实现
* 模仿360文件压缩解压管理器的实现  

**客户需求：**  
- **做个串口音频数据解压**，蓝牙麦克风将16bit音频数据压缩成4bit，蓝牙主模块接收到将4bit数据，串口接入到开发版，需要开发版在底层解压成16bit PCM音频，保存为wav文件.
-
 - 分析是如何将16bit PCM数据压缩成4bit, 如何还原
 - 使用哈夫曼吗
 - 通过这个需求掌握数据的压缩

扩展阅读：  
[8bit数据 转换为 16bit数据的四种方法](https://www.cnblogs.com/skullboyer/p/8134199.html)  
[哈夫曼树（赫夫曼树、最优树）及C语言实现](http://data.biancheng.net/view/33.html)  
[哈夫曼算法（haffman）实现压缩和解压缩-C语言实现](https://www.cnblogs.com/fuchongjundream/p/5589789.html)  
[哈夫曼编码与解码(C语言实现)](http://touch-2011.iteye.com/blog/1058800)
