# zhjs
中文编程，zh来自zh_CN

## 目的
1、更好的使用中文进行编程，方便初学者入门
2、现有typescript，coffeescript等技术，为啥还要搞这，就是喜欢中文
3、不喜欢程序中的{},;等符号

## 编译技术nodejs

## 关键字

数值     number
真       true
假       false
字符串   string
字节     buffer
类       class
枚举     enum
如果     if
再如     else if
否则     else
选择     switch
若       case
其他     default
中断     break
W循环    while
C循环    for
异步遍历 foreach

## 命令行
1、在package.json中加入
```
"bin": {
    "zhjs": "./bin/zhjs.js"
  },
```
2、根目录下`npm link`
3、命令行即可使用 zhjs命令
