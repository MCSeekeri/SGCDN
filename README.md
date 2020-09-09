# 石头门音乐外链服务

鉴于网易云下了石头门相关音乐,所以我又爬出来想解决方案了。

网易云的音乐外链功能确实好使,基本上静态博客都在用w

但是被下架之后就没得听了,隔壁QQ我又没整明白怎么外链（摊手

# 使用方法

点开上面那个[files](https://github.com/MCSeekeri/SGCDN/tree/master/files)文件夹,找到你想外链的音乐,复制链接,完事。

当然...Github在国内的访问速度相当...一言难尽,所以最好套个CDN,方案如下:

把你的链接改成https://cdn.jsdelivr.net/gh/MCSeekeri/SGCDN@master/files/文件名

比如我复制的是https://github.com/MCSeekeri/SGCDN/blob/master/files/Another%20Heaven%20-%20%E3%81%84%E3%81%A8%E3%81%86%E3%81%8B%E3%81%AA%E3%81%93.mp3 

那就要改成https://cdn.jsdelivr.net/gh/MCSeekeri/SGCDN@master/files/Another%20Heaven%20-%20%E3%81%84%E3%81%A8%E3%81%86%E3%81%8B%E3%81%AA%E3%81%93.mp3

这样就OK了!

初次访问可能有点慢,因为没缓存,之后任何时候访问都会直接走缓存力（
