## 检测该手机号是否正确

#### 1.引入

```
    var {
        isPhone
    } = require('wx-tool')
```

#### 2.参数

|  属性   | 类型    | 默认值 | 必填   | 说明            |
| :-------: | :------: | ------ | :--------: | :--------|
|  s  | string  |        | 是 | 所选手机号  |

#### 3.使用

```
    isPhone('15089700000')  // true
    isPhone('15089700')  // false
    isPhone('15089700sdsa')  // false

```