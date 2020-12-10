# 算命的科学

![screenshot](https://github.com/cp110/Fortunetell/blob/main/img/screenshot.jpg)

## 原理揭秘

### 1、十进制与二进制

首先，我们需要了解一些进制相关的知识。一般生活中我们使用的都是十进制数，十进制数是指由`0~9`组成的数字，而二进制就是由`0~1`组成的数字。

### 2、进制的转换

接下来，我们需要了解一些进制转换的知识。比如十进制数2可以转换成二进制数10（`1*2^1 + 0*2^0 = 1*2 + 0*1 = 2`）。

### 3、算日期

1~31日十进制数最多用5位的二进制数即可表示（`2^5 = 32 > 31`）。

| 十进制 | 二进制 |
| :----: | :----: |
|   1    | 00001  |
|   2    | 00010  |
|   3    | 00011  |
|  ...   |  ...   |
|   19   | 10011  |
|  ...   |  ...   |
|   31   | 11111  |

因此我们可以将每个十进制数对应二进制数划分成5个部分，即二进数表示为`b5b4b3b2b1`。

我们可以画5张表格，如果某个二进制数的bk位为1，那么该数就画在表格k中。比如3用二进制表示是`00011`，那么3就应该出现在表格1和表格2中，而表格3、4、5中没有3。

当我们选择每张表格中有或无我们想的数字时，相当于告诉算命先生`b5b4b3b2b1`，即`00011`。当算命先生拿到完整的二进制数后，将其转换成十进制数，即可得到答案3。

### 4、算姓氏

原理和算日期一样，我们仅需将百家姓按顺序变成`1~503`个数字，2^9 > 503，所以我们需要9张表格才能算出姓氏。最后我们算出的数字转换成对应的姓氏即可得到答案。

### 5、......

### 6、附算日期的5张表格

表格1
|  1   |  3   |  5   |  7   |
| :--: | :--: | :--: | :--: |
|  9   |  11  |  13  |  15  |
|  17  |  19  |  21  |  23  |
|  25  |  27  |  29  |  31  |

表格2
|  2   |  3   |  6   |  7   |
| :--: | :--: | :--: | :--: |
|  10  |  11  |  14  |  15  |
|  18  |  19  |  22  |  23  |
|  26  |  27  |  30  |  31  |

表格3
|  4   |  5   |  6   |  7   |
| :--: | :--: | :--: | :--: |
|  12  |  13  |  14  |  15  |
|  20  |  21  |  22  |  23  |
|  28  |  29  |  30  |  31  |

表格4
|  8   |  9   |  10  |  11  |
| :--: | :--: | :--: | :--: |
|  12  |  13  |  14  |  15  |
|  24  |  25  |  26  |  27  |
|  28  |  29  |  30  |  31  |

表格5
|  16  |  17  |  18  |  19  |
| :--: | :--: | :--: | :--: |
|  20  |  21  |  22  |  23  |
|  24  |  25  |  26  |  27  |
|  28  |  29  |  30  |  31  |
