# novel_spider
   大家都知道，在小说网站看小说总是各种广告，想要下载小说然而却要么需要钱，要么需要会员，如此，我们不妨写一个小说爬虫，将网页上的小说内容章节全部抓取下来，整理成为一本完整的txt文件，这样岂不是一件很愉快的事情！

## 说明
   其实没想到大家对于这种爬取小说的还比较感兴趣，那么接下来会对这个爬虫持续优化 -2018-04-23
- 多线程
- 多进程
- 增加常见反爬虫机制绕过
- 错误异常抛出
- 增加程序稳定性
- 完成整个小说网站的download 并 添加到数据库

## 2016-06-21 更新 V1.2
   1. 在1.1版本的基础上增加了异常抛出，更加稳定；
   2. 去掉标题重复抓取的BUG；
   3. 非递归调用，优化程序运行效率，占用内存极小；
   4. 速度明显提升。

[![](https://upload-images.jianshu.io/upload_images/6661013-de747716a71b77ba.png)](https://upload-images.jianshu.io/upload_images/6661013-de747716a71b77ba.png)
