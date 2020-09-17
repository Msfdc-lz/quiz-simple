# JS 使用和基本编程

## 写代码

请完成以下文件中的编码需求：

- [查看 `clone.js`](./clone.js)
- [查看 `get-host.js`](./get-host.js)
- [查看 `get-sum.js`](./get-sum.js)

## 方法论

如果你有一定的开发经验，并且追求代码的质量。  
那么你一定知道一些实践技巧，简答 3 ～ 10 条即可。

例如：

> 面向对象编程，代码逻辑可以内聚。
> 禁止使用 var，不可变数据用 const 声明，可变数据用 let 声明。

答：
  尽量不使用双等号
  用逻辑或来设置变量的默认值
  条件判断时, 不使用关系运算符, 直接进行判断

## 请问以下代码做了什么事情

```js
const getLoglevel = () => {
  return localStorage.loglevel ?? 'INFO';
};
```

答：给localStorage.loglevel设置默认值: 判断Storage中loglevel值是否为null或undefined, 是则返回默认值; 不是则返回loglevel的值
