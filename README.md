# vulnfind_batch_frameworkie

This is a lightly py code file, use it ,you can make your batch vuln tests more eaiser.
这是个轻量级的 py 代码文档，你可以使你的 批量 漏洞测试 更加容易。

Just replace your vuln test codes in line 39,40  and ,
只需要把你的漏洞测试代码替换 39，40 行即可 并且 ，

These codes run on the py3 flatform. U can make a new address file, put all the address in it, then use:
这些代码运行在 py3 平台， 你可以新建一个地址文档，把所有的地址放进去，然后使用：

```
py -3 vulnfind_batch_frameworkie.py url.txt
```

The vuln address will be displaied in the "results.txt"
然后 有漏洞的地址 将会 通过 “results.txt” 展示出来。

The format in the "url.txt" should be like this, one a address a line :
url.txt 里的格式应该如这样, 一个地址一行

192.168.0.1:88
