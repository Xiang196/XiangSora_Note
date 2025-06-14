# 1. 希腊字母
小写字母$$\alpha,\beta$$
大写字母$$\Delta,\Lambda$$
一些特别的符号如phi的变体，无穷符号，偏导符号等$$\phi,\varphi,\aleph,\partial,\infty,\ell$$

# 2. 上下标
使用乘方符号和下划线（如果多余一个字符用大括号包裹）
 `\rm` 可以将斜体改成直立体（规范使用）
$$y=x_0^{n+1}$$

# 3. 分式与根式
## 3.1. 分式
用`\frac`表示，后面跟两个大括号
$$\frac{x^2+2x+3}{x+1}$$

## 3.2. 根式
用`\sqrt`表示，后面跟大括号，多次方根时在sqrt后中括号跟角标
$$\sqrt[n+1]{x^2+3x+4}$$

# 4. 运算符
$$\times,\cdot,\div,\pm,\mp,\ge,\le,\gg,\ll,\ne,\approx,\equiv,\rightleftharpoons$$

$$\cup,\cap,\in,\notin ,\subseteq,\subsetneqq,\varnothing$$
$$\forall,\exists,\nexists,\because,\therefore$$
$$\mathbb R,\mathbb C,\mathbb Z_+$$
$$\mathcal F,\mathscr F$$

$$\cdots,\vdots,\ddots$$

$$\sin x,\cos x$$
$$\log_{2}x$$
$$\lim_{x \to 0} \frac{x}{\sin x}$$
# 5. 大运算符号
```
\displaystyle\sum{p_i}+\sum_{i=1}^{n}{p_i}
```

$$\displaystyle\sum{p_i}+\sum_{i=1}^{n}{p_i}$$
```
$$\displaystyle\prod{a_i}+\prod_{i=1}^{n}a_i$$

```
$$\displaystyle\prod{a_i}+\prod_{i=1}^{n}a_i$$
# 6. 方程组
使用 `\begin{cases}` 与 `\end{cases}` 包含，使用 `\\` 进行换行
```
\begin{cases}  
x\equiv a_1\pmod{m_1}\\  
x\equiv a_2\pmod{m_2}\\  
\cdots\\  
x\equiv a_n\pmod{m_n}  
\end{cases}
```
$$
\begin{cases}  
x\equiv a_1\pmod{m_1}\\  
x\equiv a_2\pmod{m_2}\\  
\cdots\\  
x\equiv a_n\pmod{m_n}  
\end{cases}
$$


# 7. 其他
## 7.1. 给化学方程式等号注条件
源代码：`\mathrm{4HCl + O_2 \xlongequal[\text{加热}]{\text{CuCl}_2} 2Cl_2 + 2H_2O}`
$\mathrm{4HCl + O_2 \xlongequal[\text{加热}]{\text{CuCl}_2} 2Cl_2 + 2H_2O}$





