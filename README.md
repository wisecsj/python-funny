# python-funny

(觉得还可以的，不吝赐个Star吧)

此.py是通过是用来自动完成合工大试题库题库的，**仅供学习交流**。

本人使用的是**py3**。

具体思路代码中的注释已经写明了。

可以使用pyinstaller来将py转换成exe文件，运行在windows上（或者直接通过http://pan.baidu.com/s/1dFClCBn下载）。

转换成exe后，将**试题库的Excel文件放在exe的同级目录下**即可。
------------------------------
# Usage

1. python bru-async.py (py>=3.5)
    需要输入的url为点击下图中红圈后浏览器地址栏的url
    
    
    ![](/images/2.png)

2. 
------------------------------
# Images
![运行输出截图](/images/1.png)

| 第一列        | 第二列           | 第三列  |
| ------------- |:-------------:| -----:|
| 题号    | 提交结果 | 题目答案，或`Not Found` |


     
-----------------------------
# Update (2017-11-12) 

更新的内容(By Dawnspace)：


1. 自动下载试题文件并解压
2. 自动参与两次讨论
3. 免去了手动输入试题URL的麻烦

______________________________

# Update (2017-11-19)
（可以正常刷税法课了~）

1.更新了Excel文件读取逻辑

2.无论是从网页爬取的题目，还是从excel获取的题目都进行**strip()**操作，进行统一

-------------------------------

# Update (2017-11-25)

登录仍然通过requests，爬取和提交采用 asyncio + aiohttp 协程的方式，

在非校园网的网络环境下，极大地提高了运行速度

--------------------------------

# Update (2017-12-20) 

By Ms

改进了云端验证码识别程序，采用Tensorflow

识别率95%左右，识别速度大幅提升