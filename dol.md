
### 一、改完的*.dot截图
> Example1
> ![](https://timgsa.baidu.com/timg?image&quality=80&size=b10000_10000&sec=1477984948&di=0cbf1b3845a656ba0a19c18663c6daab&imgtype=jpg&src=http%3A%2F%2Fc.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2Fd833c895d143ad4b83a2e1168a025aafa50f0653.jpg)
>  Example2
> ![](https://timgsa.baidu.com/timg?image&quality=80%20&size=b10000_10000&sec=1477390439051&di=fb26db13e31724539745487f71f6092a&imgtype=jpg&src=http%3A%2F%2Fmt1.baidu.com%2Ftimg%3Fshitu%26quality%3D100%26sharpen%3D100%26er%3D%26imgtype%3D0%26wh_rate%3Dnull%26size%3D9%26sec%3D1477380264%26di%3D6b628d9d884ef306608fe410447b373f%26cut_x%3D0%26cut_y%3D7%26cut_w%3D508%26cut_h%3D55%26src%3Dhttp%3A%2F%2Fe.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2F08f790529822720ea81e442c73cb0a46f31fab10.jpg)


### 二、修改之处

>2.1 example：
修改square.c中对i的赋值
> ![](https://timgsa.baidu.com/timg?image&quality=80%20&size=b10000_10000&sec=1477390439050&di=9fd8daa97325baf36f72fa29aaf78f9c&imgtype=jpg&src=http%3A%2F%2Fb.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2F34fae6cd7b899e5146d79bc24aa7d933c9950d8e.jpg)
> 实验结果
>![](https://timgsa.baidu.com/timg?image&quality=80%20&size=b10000_10000&sec=1477390622402&di=149d29811896d1fcc51c132a97e40661&imgtype=jpg&src=http%3A%2F%2Fa.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2F7c1ed21b0ef41bd5957f482259da81cb39db3d33.jpg)
>2.2 example2:
修改xml中对value的赋值：
![](https://timgsa.baidu.com/timg?image&quality=80%20&size=b10000_10000&sec=1477390692823&di=ce8c4b02120c68f3aa704a68322492fc&imgtype=jpg&src=http%3A%2F%2Fa.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2F4afbfbedab64034f209862d0a7c379310b551d8a.jpg)
实验结果：
![](https://timgsa.baidu.com/timg?image&quality=80%20&size=b10000_10000&sec=1477390734380&di=b8c55dc78e7eed6e4a8ad56aa8f64a32&imgtype=jpg&src=http%3A%2F%2Fh.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2F0b7b02087bf40ad1e54167355f2c11dfa8eccebb.jpg)




### 三、Experimental experience
>实验感想、实验心得
修改完代码是不能直接运行的，因为第一次配置的时候跑过examples1，已经产生文件，需要将其删除并重新编译（要删掉整个build/bin/main/examples1文件）。删除之后进入dol文件并通过代码ant -f build_zip.xml all编译，若成功会提示build successful。最后进入build/bin/main路径下，通过代码ant -f runexample.xml -Dnumber=1运行即可。
有的时候build/bin/main/examples1文件被锁定，不能直接删除，需要先通过在命令行输入“sudo chown –R 用户名 dol路径”来给予暂时的root权限，才可以删除。





                 

