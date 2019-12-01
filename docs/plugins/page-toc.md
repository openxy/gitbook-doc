---

showToc: true 

---

# page-toc

https://github.com/aleung/gitbook-plugin-page-toc

## 说明

本插件可以在Gitbook中的每一个页面上生成一个目录（TOC）。在默认情况下，每个页面都将生成一个目录。用户可以自行配置需要显示目录的页面。



## 用法

在`book.json`文件中加入以下代码：

```
{  
	"plugins": [ "page-toc" ], 
	"pluginsConfig": {   
    	"page-toc": {  	
        	"selector": ".markdown-section h1, .markdown-section h2, .markdown-sectionh3, .markdown-section h4",     
            "position": "before-first", 
            "showByDefault": true    
        }
     }
 }
```

之后运行`gitbook install`。

#### 配置

- `position`：目录的位置
  - 允许的值为：
    - `before-first`（默认）：在第一个标题之前。
    - top：在页面的顶部。
- `showByDefault`：是否在每个页面都显示目录。
  - 默认：true

如果在`book.json`中设置了每张页面都显示目录，但是在某个页面不需要目录，则可以在该页面的Markdown的最前面添加以下文字：

```
---
showToc: false
---
```

反之则添加：

```
---
showToc: true
---
```



该插件使用后的效果见本页。