# mcqx（多项选择插件）

#说明  
具有以下功能     
1.提示问题  
2.随机选择问题顺序  
3.允许添加2-8个选项 
4.允许添加答案说明  
5.支持.pdf,.mobi,.epub导出 

<!--sec data-title="Introduction" data-id="intro" ces-->
这个界面是用两个插件来完成的: ```gitbook-plugin-mcqx``` 和```gitbook-plugin-sectionx```.
<!--endsec-->

<!--sec data-title="Example" data-id="q2" data-show=true ces-->


 ```random``` 为该问题启用了该选项，刷新页面时，可能会发现问题的顺序有所不同。

{%mcq ans="o4", random=true%}
{%title%}
以下哪种不是太阳系中的行星?
{%o1%} 冥王星
{%o2%} 地球
{%o3%} 火星
{%o4%} 木星
{%hint%} 可怜的冥王星0.0
{%endmcq%}

The ```random``` option is disabled for the question.

{%mcq ans="o3"%}
{%title%} 点击C来继续
{%o1%} 不要点我 我是A
{%o2%} 不要点我 我是B
{%o3%} Click me.
{%o4%} 不要点我 我是D
{%hint%} 不信你选不出来
{%endmcq%}

可以使用 ```count``` 来仅显示一定数量的选项

{%mcq ans="o4", count=6%}
{%title%} 找到编号```42```然后点击它
{%o1%} ```689```
{%o2%} 30626700^23
{%o3%} 30624770
{%o4%} 42
{%o5%} 1234
{%o6%} 99999
{%o7%} 1
{%o8%} -3
{%hint%}  相信你可以的
{%endmcq%}

可以添加```{%message%}``` 子块，在正确回答问题后才会显示

{%mcq ans="o4", random=true%}
{%title%} 找到编号```42```然后点击它
{%o1%} 31
{%o2%} 13
{%o3%} 689
{%o4%} 42
{%message%} 只有答对的人才能看到这条消息
{%endmcq%}

<!--endsec-->

{%mcq ans="o1", count=2%}
{%title%} 这是个问题吗
{%o1%} First option
{%o2%} Second option
{%o3%} Third option
{%o4%} Fourth option
{%o5%} Fourth option
{%o6%} Fourth option
{%o7%} Fourth option
{%o8%} Fourth option
{%endmcq%}