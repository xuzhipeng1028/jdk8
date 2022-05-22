# jdk8
## 1、将本项目下载下来直接导入idea中；
## 2、配置以下设置：
![](image/1653231469788.jpg)
### 1）配置sdk:
![](image/1653231520467.jpg)
![](image/1653231572857.jpg)
![](image/1653231700065.jpg)
![](image/1653231732540.jpg)
### 2）配置项目：
![](image/1653231857279.jpg)
![](image/1653231928533.jpg)
![](image/1653231948530.jpg)
![](image/1653231969677.jpg)
## 3、将src目录设置为Sources Root
![](image/1653232251619.jpg)
## 4、增大编译时的内存
![](image/1653232554722.jpg)
## 5、设置VM参数（让我们编译的代码要跑在jre/lib/rt.jar前面）
-Xbootclasspath/p:/Users/xuzhipeng/soft/jdk/jdk8/target/production/jdk8,
/Users/xuzhipeng/soft/jdk/jdk8/target/production/jdk8是本项目class文件的路径。
![](image/1653232646407.jpg)
![](image/1653232697596.jpg)
## 6、设置debug的时候可以跳进jdk源码，将java.*和javax.*前面的对勾去掉
![](image/1653232762397.jpg)