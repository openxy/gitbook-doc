#klipse(代码交互)

#说明
Klipse允许您的gitbook中的代码段是实时和交互式的。在您键入或按时对代码进行评估

#demo
[参考网站](https://github.com/brian-dawn/gitbook-plugin-klipse)

#例子

```eval-python
def factorial(n):                                   
  if n == 0:                          
    return 1                              
  else:
    return n * factorial(n - 1)           

print(factorial(5))
```