# Games202Notes
闫令琪的Games101课程，记录学习笔记和作业的代码

+ 课程[主页](https://sites.cs.ucsb.edu/~lingqi/teaching/games202.html)
    + [视频链接（BIlibili）](https://www.bilibili.com/video/BV1YK4y1T7yY?spm_id_from=333.999.0.0&vd_source=ed25f8cd46af3af17726f30e1b36d673)
+ 本文使用数学渲染库：[KaTeK](https://katex.org/)
    + [Supports](https://katex.org/docs/supported.html)
    + 所有涉及数学公式的章节，都有对应的数学公式渲染后PDF版内容，无法渲染数学公式时请阅读PDF版内容——【章节名.pdf】
+ 笔记索引
    + Lecture 1
    + Recap of CG Basics
        + Basic GPU hardware pipeline
        + OpenGL and GLSL
            + Create shader => Compile shader => attack shader to program => Link program => Use program
        + The Rendering Equation
            + $L_o(p, \omega_o) = L_e(p, \omega_o) + \displaystyle\int_{H^2}f_r(p, \omega_i \rightarrow \omega_r)L_i(p, \omega_i)\cos\theta_iV(p, \omega_i)d\omega_i$
            $V(p, \omega_i)$ 是这个方向光的可见性
    + [Real-time Shadows](./Notes/3_Real-time_Shadows/Real-time%20Shadows.md)

****
他人[笔记](https://blog.csdn.net/qq_38065509)，作参考

以下为临时草稿文件：
+ [MD基本要素](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/markdown-basics)
+ 常用数学公式记录
箭头表示向量：$\overrightarrow{a}$
绝对值：$\lVert a \rVert$
式子整体放大+粗体A+行列式：
>$\LARGE{
    { \mathbf{A} }
    = { \begin{pmatrix} x \\ y \end{pmatrix} }
}$

行列式：
>${ \begin{pmatrix} x \\ y \end{pmatrix} }$

式子整体放大+粗体A与A的转置+行列式：
>$\LARGE{
    { \mathbf{A}^\mathrm{T} }
    = { \begin{pmatrix} x , y \end{pmatrix} }
}$

粗体A与A的转置：
>$
    { \mathbf{A} } + { \mathbf{A}^\mathrm{T} }
$

求根${ \sqrt{x^2 + y^2} }$
点乘：$\LARGE{ { \overrightarrow{a} \cdot \overrightarrow{b} } }$
投影：$\overrightarrow{b}_\perp$

叉乘：
>$\LARGE{
    { \lVert a \times b \rVert }
    = { \lVert a \rVert }{ \lVert b \rVert }\sin\theta
}$

矩阵乘法：
>$\LARGE{
    \overrightarrow{a} \times \overrightarrow{b}
    = \mathbf{A}\overrightarrow{b}
    = \begin{pmatrix} 0 & -z_a & y_a \\ z_a & 0 & -x_a \\ -y_a & x_a & 0 \end{pmatrix} \begin{pmatrix} x_b \\ y_b \\ z_b \end{pmatrix}
}$

不等于：
> $M \not = P$

$f:\R^2 \rarr \R^3 \Rightarrow (u, v) \rarr (x, y, z)$

$\eqslantless \eqslantgtr$

$$\begin{equation*} \begin{split}
a 
&=b+c\\
&=e+f
\end{split} \end{equation*}$$

$$\Large L_r(p, \omega_r) = \displaystyle\int_{H^2}f_r(p, \omega_i \rightarrow \omega_r) L_i(p, \omega_i) \cos\theta_i d\omega_i$$