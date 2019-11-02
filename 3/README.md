# Java 的基本程序设计结构

## 数据类型
- 整型
  - int - 32位
  - short - 16位
  - long - 64位
  - byte - 8位
- 浮点类型
  - float - 32位
  - double - 64位
- char - 单个字符

- 格式化输出
```java
System.out.printf("Hello, %s, Next year, you'll be %d", name, age);
```

- 文件输入与输出
```java
// 读取文件
Scanner in = new Scanner(Path.get("myfile.ext"), "UTF-8");

// 写入文件
PrintWriter out = new PrintWritter("myfile.ext", "UTF-8");
```

- 块级作用域
  - 与 ES6 表现基本一致；

- 大数值
  - Math.BigInteger: 实现了任意精度的整数运算；
  - Math.BigDecimal: 实现了任意精度的浮点数运算；

- 数组拷贝
  - `int[] copiedLuckyNumbers = Arrays.copyOf(luckyNumbers, luckyNumbers.length)`;

- 二维数组
  - `double[][] balances = new double[NYEARS][NRATES]`;