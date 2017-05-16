## 说明

此博客 fork 自 [cnfeat](https://github.com/cnfeat/cnfeat.github.io)，非常感谢!
* 增加了用MathJax在浏览器端渲染LaTeX语句的功能，方法是在layout文件夹里的default.html开头增加了解析MathJax的代码段：
```
<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```
* 洗去原博主的信息，增添自己的信息，调整页面的视觉效果
* MathJax CDN shutting down on April 30, 2017. 需要重新修改default.html、head.html、post.html三个文件
  * [MathJax CDN shutting down on April 30, 2017. <br> Alternatives available.](https://www.mathjax.org/cdn-shutting-down/)
  * [[IMPORTANT] cdn.mathjax.org end-of-life April 30, 2017 | Basic redirect in place | Alternatives available · Issue #1725 · mathjax/MathJax](https://github.com/mathjax/MathJax/issues/1725)
  * [数学公式和Markdown的结合 | 泽强的工作台](http://www.huangzeqiang.tech/2017/05/%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F%E5%92%8CMarkdown%E7%9A%84%E7%BB%93%E5%90%88/)
