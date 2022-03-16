## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Yiyuan-Yang/yiyuan.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

### Markdown

cheat sheet: <https://wordpress.com/support/markdown-quick-reference/>

## character and advantages of Java
- simplism
- object oriented
- protability
- distributed
- dynamic
- multithreading
- security

## introduction to Java
- JDK: Java Development Kit
- JRE: java Runtime Environment
- JVM: Java Virtual Machine

**JRE is included in JDK**

## Java Environment
install JDK from [here](https://www.oracle.com/java/technologies/downloads/#jdk17-windows)
- test JDK environment
  1. open cmd
  2. type command: java -version
- download notepad++ [here](https://notepad-plus-plus.org/downloads/v8.2.1/)

## My first code
- create a new folder to save code
- create a new java file
  - file end as .java
  - eg: Hello.java

```java
public class Hello{
	public static void main(String[] args){
		System.out.print("Hello World!");
	}
}
```
Then open cmd, change path to the location of Hello.java, run command: javac Hello.java.
If no error generated, then run java Hello, the cmd will print "Hello World!" on the screen.

## Install IDEA
[download IDEA](https://www.jetbrains.com/idea/)

### comments:
- Line comment
- Block comment
- Document comment
<img src="https://github.com/Yiyuan-Yang/javalearn.github.io/blob/gh-pages/comment.png" width="50%" height="30%">

**interesting comment**

<img src="https://github.com/Yiyuan-Yang/javalearn.github.io/blob/gh-pages/name_comment.png" width="30%" height="30%">

### Identifier

```java
public class Hello{
	public static void main(String[] args){
	// every identifier should be started at letters (A-Z, a-a), $ or _
	// upper/lower cases sensitive
		String teacher = "Yiyuan";
		String $teacher = "Yiyuan";
		String _teacher = "Yiyuan";
	}
}
```
### data type
- primitive type
	- numeric
		- integer
			- byte(1 byte): -128 ~ 127
			- short(2 bytes): -32768 ~ 32767
			- int(4 bytes): -2147483648 ~ 2147483647
			- long(8 bytes)
		- float
			- float(4 bytes)
			- double(8 bytes)
		- char(2 bytes)
	- boolean(1 byte): only true or false
- reference type
	- class
	- Arrays
	- String, Interface

```java
public class data_type {
    public static void main(String[] args) {
        // 8 kinds of data type
        int num1 = 9;
        byte num2 = 91;
        short num3 = 30;
        long num4 = 30L; // sometimes add L at the end to show as long
        // float
        float num5 = 9.1F;
        double num6 = 3.14159265358;
        //char only one char
        char name1 = 'Z';
        //sting many chars
        String name2 = "abcdefg";
        //boolean
        boolean b1 = true;
        boolean b2 = false;
    }
}
```

**PS**

- bit(b), byte(B)
- 1 B = 8 b
- 1 KB = 1024 B
- 1 M = 1024 KB
- 1 G = 1024 M








