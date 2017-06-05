## 说明

此博客 fork 自 [cnfeat](https://github.com/cnfeat/cnfeat.github.io)，非常感谢!
* 增加了用MathJax在浏览器端渲染LaTeX语句的功能，方法是在_includes文件夹里的head.html开头增加了解析MathJax的代码段：
```
<!-- mathjax config similar to math.stackexchange -->

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>

<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre', 'code']
      }
    });
</script>

<script type="text/x-mathjax-config">
    MathJax.Hub.Queue(function() {
        var all = MathJax.Hub.getAllJax(), i;
        for(i=0; i < all.length; i += 1) {
            all[i].SourceElement().parentNode.className += ' has-jax';
        }
    });
</script>

<script type="text/javascript" async
   src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML">
</script>
```

PS：MathJax CDN shutting down on April 30, 2017，所以改用cdnjs。参考： [MathJax CDN shutting down on April 30, 2017. <br> Alternatives available.](https://www.mathjax.org/cdn-shutting-down/)

* 洗去原博主的信息，增添自己的信息，调整页面的视觉效果