# 基础语法
## 模板字符创
## let const - 块级作用域
## 函数参数
### 剩余参数 
``` js
function multiMax(first, ...remains) {
    /*...*/
}
multiMax(2,3,4,5)
// first: 2
// remains: [3,4,5]
```
### 函数默认参数
```js
function do (a, b = 'qianqian') {
    return `${a} b`
}
do('hello') // hello qianqian
```
### 扩展语法
```js
[...items, 3,4,5]
```
## 生成器
