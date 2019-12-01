# bilibili

https://github.com/open-course/gitbook-plugin-bilibili

## 说明

本插件可以在GitBook中加入bilibili里面的视频。



## 用法

在book.json中加入如下代码：

```
{
    "plugins": ["bilibili"]
}
```

之后在命令行中输入：

```
gitbook install
```



你可以在markdown中加入以下文字来添加bilibili中的视频：

```
{% bilibili %}av56927206{% endbilibili %}
```

生成的电子书效果如下：

{% bilibili %}av56927206{% endbilibili %}

