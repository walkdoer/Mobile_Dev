移动端WebAapp开发资料
=============================

### 资料

#### 性能优化

+ [针对V8引擎进行优化JS](https://github.com/petkaantonov/bluebird/wiki/Optimization-killers)
+ [Rendering: repaint, reflow/relayout, restyle](http://www.phpied.com/rendering-repaint-reflowrelayout-restyle/)
+ [7 steps to better JavaScript](http://www.creativebloq.com/netmag/7-steps-better-javascript-51411781?utm_source=javascriptweekly&utm_medium=email)


### 工具

#### 测试工具

- 跨浏览器测试
    + [BrowserStack](http://www.browserstack.com/)
    + [sauce labs](https://saucelabs.com/)
    + [code swarm](http://codeswarm.com/) (可以和Github结合起来用)

#### 代码度量工具
- [istanbul](http://gotwarlost.github.io/istanbul/) A Javascript code coverage tool written in JS
- [plato](https://github.com/es-analysis/plato) JavaScript source code visualization, static analysis, and complexity tool



### 常见问题

1. 如何去掉点击元素之后的蓝色矩形层？
```css
/*
使用-webkit-tap-highlight-color:rgba(255, 0, 0, 0.5);
*/
/*去除页面所有元素的点击后出现的蓝色矩形*/
html *{-webkit-tap-highlight-color:rgba(255, 0, 0, 0.5);}
```

