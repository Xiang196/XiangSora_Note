# 1. 知识
定义：
$$pH=-\lg c(H^{+})$$
于是可以得到以下公式
>$$c(H^+)=a\times10^{-b}mol/L \to pH=b-\lg a$$

注：一般地，lg2=0.3，lg3=0.48

---

# 2. 题型
## 2.1. 单一溶液
以0.004mol/L的Ba(OH)<sub>2</sub>溶液为例

$$c(OH^-)=8\times10^{-3}mol/L$$
$$pOH=3-\lg 8=3-3\times0.3=2.1$$
$$pH=14-pOH=11.9$$
*用pOH反推pH值*
## 2.2. 溶液加水稀释
*加水稀释溶液物质的量不变*
ex.pH=12的NaOH与等体积的水混合
$$pOH=2 \to c(OH^-)=10^{-2}mol/L$$
经过稀释，有$$c'(OH^{-})=5\times10^{-3}mol/L \to pOH'=3-\lg5=2.3 \to pH'=11.7$$
## 2.3. 溶液混合
### 同类混合
如酸加酸 or 碱加碱
先计算出混合后H<sup>+</sup>或OH<sup>-</sup> 物质的量，再计算其浓度算出pH
### 异类混合
即酸+碱
要**先判断溶液酸碱性**，再选定pH或pOH进行计算

ex.常温下将pH=5的盐酸与pH=9的NaOH溶液以体积比11:9混合
$$c(H^+)=10^{-5}mol/L,c(OH^-)=10^{-5}mol/L$$
$$c'(H^+)=\frac{10^{-5}\times11-10^{-5}\times9}{11+9}mol/L=10^{-6}mol/L \to pH=6$$
## 2.4. 给定K<sub>a</sub>，求pH值
ex.求0.5mol/L的CH<sub>3</sub>COOH的溶液pH(Ka=1.8*10^-5)
$$CH_3COOH \Leftrightarrow CH_3COO^-+H^+$$

| CH3COOH | CH3COO- | H+  |
| ------- | ------- | --- |
| 0.5     |         |     |
| -x      | +x      | +x  |
| 0.5-x   | x       | x   |
计算时分母的x可以忽略
$$K_a=\frac{x\times x}{0.5-x}=1.8\times10^{-5} \to x=3\times10^{-3}\to pH=2.52$$
