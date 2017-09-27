![logo](http://oop4q34sz.bkt.clouddn.com/objective-C.png)

# Objective-C

[NSLog](#nslog) 
## NSLog

打印

### 语法
```
%@     对象

%d, %i 整数

%u     无符号整数

%f     浮点/双字

%x, %X 二进制整数

%o     八进制整数

%zu    size_t

%p     指针

%e     浮点/双字 (科学计算)

%g     浮点/双字

%s     C 字符串

%.*s   Pascal字符串

%c     字符

%C     unichar

%lld   64位长整数(long long)

%llu   无符64位长整数

%Lf    64位双字

```

### 实例
``` objective-c
NSLog(@"字符串:%@",string);
NSLog(@"字符:%c",a);
NSLog(@"布尔值:%i",isShow);
NSLog(@"整形:%zi",zi);
NSLog(@"整形:%i",i);
NSLog(@"单精度浮点数： %f",f);
NSLog(@"精度浮点数,且只保留两位小数:%.2f",f);
NSLog(@"科学技术法:%e",f);
NSLog(@"科学技术法(用最简短的方式):%g",f);
NSLog(@"同时打印两个整数：i＝%i,f=%f",i,f);
```

## 参考链接

[http://www.cnblogs.com/qingyuan/p/3524791.html](http://www.cnblogs.com/qingyuan/p/3524791.html)  