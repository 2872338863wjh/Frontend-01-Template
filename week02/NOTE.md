# 每周总结可以写在这里
BRF表达式
<Number>="0"|"1"|"2"|...|"9"
<DecimalNumber>="0"|(("1"|"2"|...|"9")<Number>*)

<PrimaryExpression>=<DecimalNumber>|
"("<LogicalExpression>")"

<MultiplicativeExpression>=<DecimalNumber>|
<MultiplicativeExpression>"/"<DecimalNumber>|
<MultiplicativeExpression>"*"<DecimalNumber>|

<AdditiveExpression>=<MultiplicativeExpression>|
<AdditiveExpression>"+"<MultiplicativeExpression>|
<AdditiveExpression>"-"<MultiplicativeExpression>|

<LogicalExpression>=<AdditiveExpression>|
<LogicalExpression>"||"<AdditiveExpression>|
<LogicalExpression>"&&"<AdditiveExpression>|

图灵完备性
 命令式----图灵机
   goto
   if 和 while
 声明式
   递归

动态与静态
  动态
   在用户的设备/在线服务器上
   在产品实际运行时
   Runtime
静态
  在程序员的设备上
  产品开发时
  Complietime

类型系统
动态类型系统与静态类型系统
强类型与弱类型
    String + Number
    String+Boolean
复合类型
  结构体
  函数签名
子类型
  逆变/协变

