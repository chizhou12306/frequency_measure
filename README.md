## frequency_measure
STM32F29IGT6 frequency measurement


LINK TO:【教程】[使用STM32测量频率和占空比的几种方法](http://www.openedv.com/forum.php?mod=viewthread&tid=82594&highlight=%B2%E2%C1%BF%C6%B5%C2%CA)


*缺陷显而易见，当频率提高，将会频繁进入中断，占用大量时间。*  
_而当频率超过100kHz时，中断程序时间甚至将超过脉冲周期，产生巨大误差。_  
___同时更重要的是，想要测量的占空比由于受到中断程序影响，误差将越来越大。___  
***  
- - -  
> 最外层
> > 第一层嵌套
> > > 第二层嵌套
***
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)  
![RUNOOB 图标](http://www.openedv.com/data/attachment/forum/201608/26/222513whja58hl6cxg07hh.png "RUNOOB")
