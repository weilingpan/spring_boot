# spring_boot

## Spring 基本概念

- 由 Rod Johnson 建立的開源框架，並在 2003年6月在 Apache2.0 許可下首次發布
- Spring 框架是 Java 的一個開源全端應用程式框架
- Spring 框架的兩大特性: IoC、AOP
    - IoC: Inverse of Control 控制反轉
    - AOP: Aspect-Oriented Programming、面向切面編程

## 環境準備

- Java 環境
    - JVM (Java Virtual Machine)
    - JRE（Java Runtime Environment；Java執行環境）
         - 用於運行java程序，不包含任何開發工具,如Java編譯器、調試器、JShell等
    - JDK（Java Development Kit；Java開發工具包）: [下載連結](https://www.oracle.com/java/technologies/downloads/#jdk19-windows)
        - 用於開發目的
        - 安裝完成後
        - 新增環境變數: JAVA_HOME=安裝的路徑，在 PATH 新增 %JAVA_HOME%\bin
        - 檢查: javac -version/java -version
- 編譯器
    - Eclipse: [下載連結](https://www.eclipse.org/downloads/packages/)
    
## Hello World
    - 新增專案: File > New > Java Project
    - 輸入 Project Name > Finish
    - 專案底下有兩個資料夾
        - JRE System Library: 引用的 library
        - src: source file 存放位置
    - 新增類別: 專案名稱右鍵 > New > Class
    - 在 New Java Class 視窗中
        - Package: 封裝的名稱
        - Name: 類別的名稱
        - 點選 public static void main
        - Finish
        ![Eclipse 建立類別](doc/Eclipse%20%E5%BB%BA%E7%AB%8B%E9%A1%9E%E5%88%A5.png)
    - 增修程式碼:
        ```java
        package package01;

        public class class01 {

            public static void main(String[] args) {
                // TODO Auto-generated method stub
                System.out.println("Hello World! 回顧如何使用 Eclipse 寫 Java");
            }

        }
        ```
    - 執行: 點選上方 Run 圖示 > Run As > Java Application
        