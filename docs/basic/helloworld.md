## Hello World起步

Hello World是我们学习任何一门语言的基石，来吧，一起敲门！  

### 环境准备    
#### 安装JDK  
> 安装的过程比较简单，这里不再赘述，可参考[JDK安装这篇](https://www.cnblogs.com/zll-wyf/p/15095664.html){:target="_blank"}  
#### Eclipse安装过程[请参考这篇](https://www.cnblogs.com/caijiaming/p/10837083.html){:target="_blank"}   
> Intellij idea安装过程请参考[这篇文档](https://blog.csdn.net/weixin_43184774/article/details/100578786){:target="_blank"}    

### 详细步骤  
#### 新建工程  
> 请[参考这篇](url)  

```  
public class People {

    private final String name;

    public People(String name) {
        this.name = name;
    }

    public static void main(String[] args) {
        People people = new People("老张");
        String hello = people.sayHello();
        System.out.println(hello);
    }

    private String sayHello() {
        return this.name + "说：\"你好\"";
    }
}  
```   

### 总结  
#### 使用到的快捷键  
> control + option + o 删除无效的import   
command + option + L 格式化代码  
psvm 快速书写main方法  
sout 快速书写System.out.println()  
option + enter 输入提醒  



### 参考文档（链接）  
JDK下载地址：[https://www.oracle.com/java/technologies/downloads/#java8-windows ](https://www.oracle.com/java/technologies/downloads/#java8-windows){:target="_blank"}  
OpenJDK下载地址：[http://jdk.java.net/java-se-ri/8-MR3](http://jdk.java.net/java-se-ri/8-MR3){:target="_blank"}    
Intellij idea下载地址：[https://www.jetbrains.com/zh-cn/idea/download/#section=mac](https://www.jetbrains.com/zh-cn/idea/download/#section=mac){:target="_blank"}    
Eclipse下载地址：[https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/){:target="_blank"}     

### 常见问题  
### 交作业  
跟上节奏，走向你的人生巅峰 
