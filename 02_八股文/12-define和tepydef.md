1. define是一个预处理指令，typedef是关键字
2. define不会做正确性检查，直接进行替换，typedef会进行正确性检查
3. define没有作用域的限制，typedef有作用域的限制
4. 对指针的操作不同


```c
#define b a
typedef b a;
typedef char uint8_t; //重命名为uint8_t类型
```