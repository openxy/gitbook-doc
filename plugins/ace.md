# ace(代码编辑器)
# 说明
用于将代码段插入书中，语法高亮显示支持约110种编程语言
#demo
https://github.com/manchiyiu/gitbook-plugin-ace   
{%ace edit=true, lang='c_cpp'%}
// This is a hello world program for C.
#include <stdio.h>

int main(){
  printf("Hello World!");
  return 1;
}
{%endace%}