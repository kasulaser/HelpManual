# **激光头不出光如何排查？** {#激光头不出光如何排查？}

1、电话询问客户是某个头不出光了还是所有激光头都不出光了。

2、如果机器上所有激光头都不出光了，首先排查**水保护（水流状态是否通畅）是否出了问题（99%概率是这个原因）。如果没有水流，直接调整下管路，看哪里被挡住了；在**有水流的状态，**找两根电线直接接到主板上（短接水保护线），如果主板有信号，点射出光，则水保护出了问题，需要进一步检测水流是否通畅，水箱温度是否过高等原因，如果点射无光，则水保护没问题，进入到下一步，排查激光电源问题；**

3、如果客户说只有某个头不出光，再询问是点射出光运动不出光，还是点射运动都不出光。如果是点射出光运动不出光，基本就可以确定是软件参数调整或者是主板原因，和激光管激光电源水保护等没有什么关系。首先排查软件里面的图层参数里面是否勾选了是否输出选项，如果勾选了输出，基本可以判断是主板原因。如果是点射运动都不出光，进入到下一步；

a\)首先排查电流表旋钮有没有开，如果开了，进入下一步；

b\)软件控光按钮有没有开，如果开了，调大电流表到80%位置，再测试，因为如果选择了软件控光，电流表位置在70%以下的时候，基本也没有光的；如果没开，进入下一步；

c\)检查激光电源开关是否有开，如果没开，开上，看是否正常，如果仍然不正常，进入下一步；

d\)点射看电流表有无电流通过，如果没有电流，直接检查激光电源。首先将激光电源五根线的那个控制线拔掉，点强制点射，看是否出光，如果出光了，再将控制线插上，再强制点射，如果无光，则是激光电源控制线和电流表可能有问题，将另一个头的控制线对调排查，如果对调后有光，则是电源控制线问题，如果仍然无光，则是电流表有问题，更换电流表。如果强制点射后仍然有光，则**排除激光电源**问题，点射有电流，直接进入下一步；则是电源控制线问题，更换控制线，问题解决。

e\)面板点射时看激光管里面有没有光，如果激光管里面有光，则基本可以确定要调光路和检查几个镜片是否破损了，调整光路，检查镜片，清洁镜片即可。如果都调整完之后，还没解决（极少数情况下发生），则将一反镜片上贴上胶布，看是否有光出来，如果激光管管内有光，但是一反镜片上无光，则需更换激光管。如果有光出来，则一定还是光路没有调整到位。如果激光管里面没有光，则进入下一步；

f\)检查高压线是否有黑点，严重的高压线打火也会引起无光，需要更换整条高压线，如果无打火现象，更换激光管解决。

![](https://kasulaser.gitbooks.io/kasuclientservice/content/assets/%E6%BF%80%E5%85%89%E5%A4%B4%E4%B8%8D%E5%87%BA%E5%85%89%E5%A6%82%E4%BD%95%E6%8E%92%E6%9F%A5.png)
