# 标定寻网格线段数目过少 {#标定寻网格线段数目过少}

### 现象： {#现象：}

寻网格出现错误，网格线段数目过少

### 解决方法： {#解决方法：}

1.修改初始偏移值，初始X，初始Y均改为0，再“拍照”测试。

![](https://kasulaser.gitbooks.io/kasuclientservice/content/assets/QQ%E5%9B%BE%E7%89%8720170919140033.png)

2.检查焦距是否合适。拍出来的图片是否模糊，是否失焦。

3.检查相机镜头是否脏。

4.修改Low,High的值。Low改为0.1，High值改为3，再进行测试。

![](https://kasulaser.gitbooks.io/kasuclientservice/content/assets/QQ%E5%9B%BE%E7%89%8720170919140611.png)

