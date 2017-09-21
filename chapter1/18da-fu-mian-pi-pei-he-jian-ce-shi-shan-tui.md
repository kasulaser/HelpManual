# 大幅面匹配和检测时闪退 {#大幅面匹配和检测时闪退}

### 现象： {#现象：}

大幅面匹配和检测时闪退

### 解决方法： {#解决方法：}

检测时闪退或者没有响应，需要检查检测参数是否合适。

1.点“恢复默认参数”按钮。用默认参数再进行检测实验。

![](https://kasulaser.gitbooks.io/kasuclientservice/content/assets/QQ%E5%9B%BE%E7%89%8720170919132210.png)

2.检查曲线拟合参数，设置为“无拟合”，再进行测试。

3.检测轮廓筛选参数，将最大值和最小值设置为合适的值。

4.将形态学运算设置为无。

将高级形态学运算中的“形态学方法”设置为无，

将高级形态学运算中的“区域合并”,"区域筛选”打钩去掉。

![](https://kasulaser.gitbooks.io/kasuclientservice/content/assets/QQ%E5%9B%BE%E7%89%8720170919132105.png)

匹配时闪退：

1.点“恢复默认参数”按钮。用默认参数再进行匹配实验。

![](https://kasulaser.gitbooks.io/kasuclientservice/content/assets/QQ%E5%9B%BE%E7%89%8720170919132624.png)

2.修改模板相似度，改为合适的值再进行测试。

3.重新生成模板进行测试。

终极解决方法：

将配置文件（KasuSmartVisionLaser.exe.xml）替换为默认的配置文件再进行测试。

