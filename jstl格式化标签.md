## jstl格式化标签

#### 1.fmt:formatNumber﻿

```
<fmt:formatNumber>标签用于格式化数字，百分比，货币。
<fmt:formatNumber
  value="<string>"
  type="<string>"
  pattern="<string>"
  currencyCode="<string>"
  currencySymbol="<string>"
  groupingUsed="<string>"
  maxIntegerDigits="<string>"
  minIntegerDigits="<string>"
  maxFractionDigits="<string>"
  minFractionDigits="<string>"
  var="<string>"
  scope="<string>"/>
```

#### 2.属性

| 属性             | 描述                          | 是否必要 | 默认值     |
| -------------- | --------------------------- | ---- | ------- |
| value          | 要显示的数字                      | 是    | 无       |
| type           | NUMBER，CURRENCY，或 PERCENT类型 | 否    | Number  |
| pattern        | 指定一个自定义的格式化模式用与输出           | 否    | 无       |
| currencyCode   | 货币码（当type="currency"时）      | 否    | 取决于默认区域 |
| currencySymbol | 货币符号 (当 type="currency"时)   | 否    | 取决于默认区域 |
| groupingUsed   | 是否对数字分组    (TRUE 或 FALSE)   | 否    | true    |
|        maxIntegerDigits        |       整型数最大的位数                      |    否  |      无   |
|      minIntegerDigits          |   整型数最小的位数                          |    否  |       无  |
|     maxFractionDigits           |   小数点后最大的位数                          |   否   |     无    |
|     minFractionDigits           |     小数点后最小的位数                        |   否   |     |     minFractionDigits           |     小数点后最小的位数                        |   否   |      无   |
    |
|                |                             |      |         |
|                |                             |      |         |


​			
​			
​			
​			
​	 		
			
			
			
			
var	存储格式化数字的变量	否	Print to page
scope	var属性的作用域	否	page

#### 3.commit 

#### 4.push

