# Problem1.2
题目如下：
![cmd-markdown-logo](http://note.youdao.com/yws/public/resource/6d0f9ed26e7ed3b459f36fd61f5606df/xmlnote/17F3287A4EB34BF5B80C6864E5A4693B/916DA2DC8F944A14A1338FE832EDAD36/31)
 
 解：由泰勒公式可得X(t+∆t)=X(t)+dx/dt*∆t+½×d²x/dt²×(∆t)²+···
                       
                       ≈X(t)+dx/dt*∆t
    
    由（1.9）式可得dx/dt=v
    
    因此可得X(t+∆t)≈X(t)+v∆t
    
    然后我们设时间t和位置x为变量 取初始值x0=0 t0=0
    
    
    运用Euler method input dt和time
    
    得到x与t的函数图象
     
     情况1 令 dt=0.5 time=20
    
     得到[图像1](https://raw.githubusercontent.com/zhangsheng999/1111/master/Figure_1.png)
    
     
     情况2 令 dt=0.1 time=20

     得到[图像2](https://raw.githubusercontent.com/zhangsheng999/1111/master/Figure_2.png)
                       
