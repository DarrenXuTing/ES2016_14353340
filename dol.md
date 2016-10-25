
### 一、改完的*.dot截图
> Example1
>![](http://p1.bqimg.com/567571/55664a301dade015.png)
> Example2
>![](http://p1.bqimg.com/567571/a82910fd3f4881ba.png)


### 二、修改之处

>2.1 example：
>修改square.c中对i的赋值
>![](http://p1.bqimg.com/567571/69fa03ccfd73a42b.png)
> 实验结果
>![](http://p1.bqimg.com/567571/b5ac656bb4b4b28c.png)
>2.2 example2:
>修改xml中对value的赋值：
>![](http://p1.bqimg.com/567571/d196b73756dcd300.png)
>实验结果：
>![](http://p1.bqimg.com/567571/b93fdf4546373b2a.png)




### 三、Experimental experience
>实验感想、实验心得
修改完代码是不能直接运行的，因为第一次配置的时候跑过examples1，已经产生文件，需要将其删除并重新编译（要删掉整个build/bin/main/examples1文件）。删除之后进入dol文件并通过代码ant -f build_zip.xml all编译，若成功会提示build successful。最后进入build/bin/main路径下，通过代码ant -f runexample.xml -Dnumber=1运行即可。
有的时候build/bin/main/examples1文件被锁定，不能直接删除，需要先通过在命令行输入“sudo chown –R 用户名 dol路径”来给予暂时的root权限，才可以删除。





                 

