#《更了不起的 Node 4:将下一代 Web 框架 Koa 进行到底》

## 目录

- 一张图看懂Node.js核心
- 核心变更
- 推荐技术栈
- 为什么要选Koa？Koa特性、性能、生态
- 异步流程控制改进
- Koa vs Express大比拼
- Koa实践
- 总结

## 一张图看懂Node.js核心

![Cover](cover.png)

- node4 + es6
- koa
- 异步流程控制
- 模块

## 核心变更

**es语法支持**

- 使用Node.js 4.x或5.x里的es6特性，如果想玩更高级的，可以使用[babel](babeljs.com)编译支持es7特性
- 合理使用[standard](https://github.com/feross/standard) 代码风格约定
- es6语法，写的一般，比较啰嗦，凑合看吧 http://es6.ruanyifeng.com/ 
- 需要大家重视OO（面向对象）写法的学习和使用，这是es的另一个好处,推荐蔡伟小兄弟的[《JavaScript Patterns》 examples in ECMAScript6](https://github.com/DavidCai1993/JsPatterns-ES6)


相比es语法，其实我本人更喜欢typescript的，不过写Node.js还是推荐跟Node SDK玩才是。

## 推荐技术栈

http://nodeonly.com/stack/

- koa 1.0 && 2.0 （koa2.0刚发布不久，喜欢折腾的可以考虑）
- mongoose（mongodb）
- bluebird（Promise/A+实现）
- jade（视图层模板）
- ava（测试）
- vscode(调试)

推荐生成器（稍后会把ava和bluebird加上）

https://github.com/17koa/koa-generator

## 为什么要选Koa

- Koa核心
  - Context
  - Middleware
  - Generator
  - Router
  - Views
  - Lifecycle
- 性能
- 生态

![Npm](npm.png)

## 异步流程控制改进（generator && co && async）

![Async](async.png)

### generator

### co

### async

### promise


## Koa vs Express大比拼


## Koa实践


## 总结
