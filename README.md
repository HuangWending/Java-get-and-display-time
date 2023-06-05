# Java-get-and-display-time
Java获取并显示当前时间的程序
import java.util.Date;: 导入java.util包中的Date类，这个类用于表示日期和时间。
public class CurrentTimeExample: 定义了一个名为CurrentTimeExample的公共类，这个类包含了main方法。
public static void main(String[] args): 这是程序的主方法，它是Java程序的入口点。程序从这里开始执行。
Date currentTime = new Date();: 创建一个Date对象并将其赋值给currentTime变量。这个对象表示当前的日期和时间。
System.out.println("当前时间: " + currentTime);: 使用System.out.println方法打印输出当前时间。+操作符用于连接字符串和变量。
