# Java项目需要远程调用共享打印机打印

## 实验环境：
JDK17
IDEA

## MAVEN环境
一般打印都生成PDF然后打印，PDF常用API有两个，pdfbox和itextpdf，依赖如下
pdfbox依赖
```xml
        <dependency>
            <groupId>org.apache.pdfbox</groupId>
            <artifactId>pdfbox</artifactId>
            <version>3.0.2</version>
        </dependency>
```
itextpdf依赖
```xml
        <dependency>
            <groupId>com.itextpdf</groupId>
            <artifactId>itextpdf</artifactId>
            <version>5.5.13.3</version>
        </dependency>
        <dependency>
            <groupId>com.itextpdf</groupId>
            <artifactId>itext-asian</artifactId>
            <version>5.2.0</version>
        </dependency>
```