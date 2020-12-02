# 点と直線の垂直距離


<div style="text-align:center;">
    <img src="http://drive.google.com/uc?export=view&id=1KfsOl-CxO3jdcyY-fB21xhweb225ukBe" alt="点と直線の垂直距離" width="300">
</div>
</br>


点 $P_0$ と直線 $ax+by+c=0$  の距離 $d$ は下記である。
$$
\Large
\begin{align}
d &= \frac{|ax_0+by_0+c|}{\sqrt{a^2+b^2}}
\end{align}
$$

</br>

---
### 説明



三角形の面積は、２つの方法で求めることができる。



$$
\begin{align}
A(\triangle) &= \frac{1}{2}lm\\
&= \frac{1}{2} d\sqrt{l^2+m^2}\\
where&\\
\quad l &= \left| \frac{-ax_0-c}{b} - y_0\right| 
= \frac{1}{|b|}\left| ax_0+by_0+c \right|\\
\quad m &= \left| \frac{-by_0-c}{a} - x_0\right| 
= \frac{1}{|a|}\left| ax_0+by_0+c \right|\\
\end{align}
$$



この式は等しいので距離 $d$  は下記のように導かれる。
$$
\begin{align}
\frac{1}{2}lm &=\frac{1}{2} d\sqrt{l^2+m^2}\\
d &= \frac{lm}{\sqrt{l^2+m^2}}\\
&= \frac{(\frac{1}{|b|} |ax_0+by_0+c|)(\frac{1}{|a|} |ax_0+by_0+c|)}{\sqrt{(\frac{1}{|b|} |ax_0+by_0+c|)^2+(\frac{1}{|a|} |ax_0+by_0+c|)^2}}\\
&= \frac{\frac{1}{|a|}\frac{1}{|b|}|ax_0+by_0+c|^2}{\sqrt{(\frac{1}{a^2}+\frac{1}{b^2})(ax_0+by_0+c)^2}}\\
&= \frac{\frac{1}{|a|}\frac{1}{|b|}|ax_0+by_0+c|}{\sqrt{\frac{1}{a^2}+\frac{1}{b^2}}}\\
&= \frac{|ax_0+by_0+c|}{\sqrt{a^2+b^2}}
\end{align}
$$

