# 函数与极限

## 集合

+ a属于集合A表示为：a∈A
+ a属于集合A表示为：a∉A
+ 集合表示方法
  + 列举法：{1,2,3,4,5}
  + 描述法：{a|a的特征}
+ 集合A包含于集合B表示为：A⊂B
+ 如果A⊂B且B⊂A，则A=B
+ 并集：两个集合得总和；表示为A∪B
+ 交集：两个集合共有部分；表示为A∩B
+ 全集：所有研究对象；表示为Ω（读作欧米伽）
+ 补集：全集中去掉集合A的部分称为集合A的补集；表示为Ā
+ 运算：
  + A∩(B∪C) = (A∩B)∪(A∩C)
  + A∪(B∩C) = (A∪B)∩(A∪C)
  + A∪B的补集 = A的补集 ∩ B的补集
  + A∩B的补集 = A的补集 ∪ B的补集

## 函数

+ 周期函数

  + 如果f(x+T) = f(x)，则f(x)为周期函数

  + 如果f(x)的周期为T，则f(ax+b)的周期为T/a

    系数a不会扩大纵坐标的值，只会拉伸或压缩横坐标

## 极限

### 运算法则

> 前提：
>
> + 极限内函数为有限个
> + 每个函数的极限是存在的

+ 若`limit f(x) = a`，`limit g(x) = b`，则
  + `limit (f(x) + g(x))` = `limit f(x) + limit g(x)` = a + b
  + `limit (f(x) - g(x))` = `limit f(x) - limit g(x)` = a - b
  + `limit (f(x) * g(x))` = `limit f(x) * limit g(x)` = a * b
  + `limit (f(x) / g(x))` = `limit f(x) / limit g(x)` = a / b
+ `limit C * f(x)` = `C * limit f(x)`
+ `limit f(x)^n` = `(limit f(x))^n`

### 求极限技巧

+ x趋近于∞时

  + 分子分母同次，极限为最高次系数之比

    <img src="README.assets/image-20230314150254468.png" alt="image-20230314150254468" style="zoom:67%;" /> 

    x趋近于∞时，划掉的项都等于0

  + 分母次数高，极限为0

    <img src="README.assets/image-20230314163002597.png" alt="image-20230314163002597" style="zoom: 67%;" /> 

  + 分子次数高，极限为∞

    <img src="README.assets/image-20230314163404883.png" alt="image-20230314163404883" style="zoom:67%;" /> 

+ 多项式求极限时，目标是将分子或者分母简化为常数或者趋近于0的项，常用方法如：

  + 同时除以最高次项（参见上面）

+ 如果x极限值代入后分子分母同时为0，则需要重新约分，让其中一项不为0

  <img src="README.assets/image-20230314164541996.png" alt="image-20230314164541996" style="zoom:50%;" /> 

+ 分母趋于0时，如果极限为常数，则表名分子必然为0

  > 如果分子不为0，极限必然为∞

  <img src="README.assets/image-20230314213412830.png" alt="image-20230314213412830" style="zoom: 67%;" /> 

### 极限存在法则

+ 夹逼定理

  + 定义

    函数f(x),g(x),h(x)，均满足在x0的去心邻域内，g(x)≤f(x)≤h(x)，并且x趋近于x0时，g(x)和h(x)均趋近于a，则f(x)也趋近于a

  + 例题

    + 求n->∞时，(2^n)/n! 的极限

    + 解

      ![image-20230314221247893](README.assets/image-20230314221247893.png) 

      这里需要保留1个n项，来保留趋势

+ 单调有界的数列必有极限

### 重要极限

+ x->0时，sinx/x的极限 = 1
+ x->0时，tanx/x的极限 = 1
+ x->∞时，(1+1/n)^n的极限等于e
+ 





