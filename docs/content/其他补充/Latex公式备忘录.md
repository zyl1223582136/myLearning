# Latex 语法备忘录

## 操作符

| 符号         | 语法        | 解释 |
| ------------ | ----------- | ---- |
| $$\cdot$$    | \cdot       | 点乘 |
| $$\times$$   | \times      | 叉乘 |
| $$\pm$$      | \pm         |      |
| $$\div$$     | \div        |      |
| ∩            | \cap        |      |
| ∪            | \cup        |      |
| ⊗            | \otimes     |      |
| ⊕            | \oplus      |      |
| $$\sqrt{x}$$ | \sqrt{x}    |      |
|              | \sqrt[n]{x} |      |
| $$\Delta$$   | \Delta      |      |
| $$\Xi$$      | \Xi         |      |

## 关系符

| 符号 | 语法      | 符号 | 语法      |
| ---- | --------- | ---- | --------- |
| ≤    | \le       | ≥    | \ge       |
| ∼    | \sim      | ⊂    | \subset   |
| ⊃    | \supset   |      | \approx   |
|      | \subseteq |      | \supseteq |
| ≡    | \equiv    | ∈    | \in       |
| ∋    | \ni       | \|\| | \parallel |

## 希腊字母

| Symbol | Command  | Symbol | Command     | Symbol | Command |
| ------ | -------- | ------ | ----------- | ------ | ------- |
| $$ \alpha$$      | \alpha   |   $$\beta$$     | \beta       |   $$\gamma$$     | \gamma  |
|   $$\epsilon$$     | \epsilon |    $$\varepsilon$$    | \varepsilon |  $$\zeta$$      | \zeta   |
|   $$\theta $$     | \theta   |  $$\vartheta$$      | \vartheta   |    $$ \iota$$    | \iota   |
|    $$\lambda$$    | \lambda  | $$\mu$$       | \mu         |   $$\nu$$     | \nu     |
|    $$\pi $$    | \pi      |  $$\varpi$$      | \varpi      |  $$\rho $$      | \rho    |
|   $$\sigma$$     | \sigma   |    $$\varsigma$$    | \varsigma   |    $$\chi$$    | \chi    |
|    $$\phi $$    | \phi     |   $$\varphi $$     | \varphi     |  $$\tau $$      | \tau    |
|  $$\omega $$      | \omega   |     $$\delta$$     | \delta         |        $$\eta$$     | \eta     |
|  $$\kappa$$      | \kappa   |  $$\xi$$     | \xi      |  $$\upsilon$$    | \upsilon |
|$$\psi$$      | \psi     |

## 特殊符号

| 符号              | 语法          |
| ----------------- | ------------- |
| $$\infty$$        | \infty        |
| $$\to$$           | \to           |
| $$\int$$          | \int          |
| $$\sum$$          | \sum          |
| $$\exists$$       | \exists       |
| $$\forall$$       | \forall       |
| $$\emptyset$$     | \emptyset     |
| $$\frac{y+x}{2}$$ | \frac{y+x}{2} |
| 空格              | \quad         |
| $$\partial$$      | \partial      |
| $$\ldots$$        | \ldots        |
| $$\vec{v}$$       | \vec{v}       |
|                   |               |

## 矩阵

$$
\left\{
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right\}
$$

```text
$$
 \left\{
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right\} \tag{2}
$$
```


$$
\left[
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right]
$$

```text
$$
 \left[
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right] 
$$
```

$$
\left(
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right) 
$$

```text
$$
 \left(
 \begin{matrix}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   7 & 8 & 9
  \end{matrix}
  \right) 
$$
```

$$
\left\{
 \begin{matrix}
 1      & 2        & \cdots & 5        \\
 6      & 7        & \cdots & 10       \\
 \vdots & \vdots   & \ddots & \vdots   \\
 \alpha & \alpha+1 & \cdots & \alpha+4 
 \end{matrix}
 \right\}
$$

```text
$$
 \left\{
 \begin{matrix}
 1      & 2        & \cdots & 5        \\
 6      & 7        & \cdots & 10       \\
 \vdots & \vdots   & \ddots & \vdots   \\
 \alpha & \alpha+1 & \cdots & \alpha+4 
 \end{matrix}
 \right\}
$$
```

$$
\begin{aligned}
a &= b + c \\
  &= d + e + f
\end{aligned}
$$

```text
$$
\begin{aligned}
a &= b + c \\
  &= d + e + f
\end{aligned}
$$
```

$$
\begin{cases}
3x + 5y +  z \\
7x - 2y + 4z \\
-6x + 3y + 2z
\end{cases}
$$

```text
$$
\begin{cases}
3x + 5y +  z \\
7x - 2y + 4z \\
-6x + 3y + 2z
\end{cases}
$$
```

$$
f(n) =
\begin{cases} 
n/2,  & \text{if }n\text{ is even} \\
3n+1, & \text{if }n\text{ is odd}
\end{cases}
$$

```text
$$
f(n) =
\begin{cases} 
n/2,  & \text{if }n\text{ is even} \\
3n+1, & \text{if }n\text{ is odd}
\end{cases}
$$
```