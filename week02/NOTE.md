# 编程语言通识和 JS 词法--学习总结

## 编程语言通识

- 了解了形式语言和非形式语言
- 了解了什么是产生式：将源程序经过词法分析和语法分析后得到的一系列符合文法规则的语句
- 知道了市面上的那些语言，有强类型和弱类型语言、有动态和静态语言。

## 词法和类型

> 主要理解了 Atom 这种最基本的类型

- whiteSpace
- LineTerminator 换行符
- Comment 注释
- Token 一切有效东西的最小单元
  - Punctuator: 符号 比如 `> = < }`
  - Keywords：比如 `await`、`break`... 不能用作变量名，但像 getter 里的 `get`就是个例外
  - Literal: 直接量
    - Number
      - 存储 Uint8Array、Float64Array
      - 各种进制的写法
        - 二进制 0b
        - 八进制 0o
        - 十进制 0x
    - String
      - Character
      - Code Point
      - Encoding
        - unicode 编码 - utf
          - utf-8 可变长度 （控制位的用处）
      - Grammar
        - `''`、`""`、``` `
    - Boolean
      - `true`
      - `false`
    - Null
    - Undefind