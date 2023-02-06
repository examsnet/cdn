$$
\begin{aligned}
& =\left[\begin{array}{cc}x^{2} & 0 \\x+1 & 1\end{array}\right] \\
& A^{3}=\left[\begin{array}{cc}x^{2} & 0 \\x+1 & 1\end{array}\right]\left[\begin{array}{ll}x & 0 \\1 & 1\end{array}\right] \\
& =\left[\begin{array}{cc}x^{3} & 0 \\x^{2}+x+1 & 1\end{array}\right] \\
& A^{3}=B \Rightarrow\left[\begin{array}{cc}x^{3} & 0 \\x^{2}-x+1 & 1\end{array}\right]=\left[\begin{array}{ll}8 & 0 \\7 & 1\end{array}\right] \\
& \Rightarrow x^{\prime}=8 \\
& \Rightarrow x=2
\end{aligned}
$$

4. (a) We have,

$$
\begin{aligned}
A+B & =\left[\begin{array}{lll}
1 & b & c \\
b & 2 & 3 \\
c & 3 & 4
\end{array}\right]+\left[\begin{array}{ccc}
0 & b & c \\
-b & 0 & 2 \\
-c & -2 & 0
\end{array}\right]=\left[\begin{array}{ccc}
1 & 2 & 2 c \\
0 & 2 & 5 \\
0 & 1 & 4
\end{array}\right] \\
\therefore|A+B|= & \left.\mid \begin{array}{ll}
2 & 5 \\
1 & 4
\end{array}\right]=8-5=3
\end{aligned}
$$

5. (b) Given, $A=\left[\begin{array}{cccc}1 & 2 & 1 & -1 \\ -1 & 2 & 3 & 5 \\ 0 & 1 & k & k\end{array}\right]$.

Applying $R_{2} \rightarrow R_{2}+R_{1}$,

$$
A=\left[\begin{array}{cccc}
1 & 2 & 1 & -1 \\
0 & 4 & 4 & 4 \\
0 & 1 & k & k
\end{array}\right]
$$

Applying $R_{3} \rightarrow R_{3}-\frac{1}{4} R_{2}$

$$
A=\left[\begin{array}{cccc}
1 & 2 & 1 & -1 \\
0 & 4 & 4 & 4 \\
0 & 0 & k-1 & k-1
\end{array}\right]
$$

Rank of matrix $A$ will be 2 if $k-1=0 \Rightarrow k=1$ satisfy the equation $x^{2}+x-2=0$

6. (a) $\left[\begin{array}{ccc}1 & 2 & -3 \\ 2 & -4 & 3 \\ 3 & 6 & -6\end{array}\right]\left[\begin{array}{c}1 / x \\ 1 / y \\ 1 / z\end{array}\right]=\left[\begin{array}{c}1 \\ 1 \\ 4\end{array}\right]$

$$
\begin{aligned}
& \text { Let } A=\left[\begin{array}{ccc}1 & 2 & -3 \\2 & -4 & 3 \\3 & 6 & -6\end{array}\right], X=\left[\begin{array}{l}1 / x \\1 / y \\1 / z\end{array}\right] \text {. } \\
& B=\left[\begin{array}{l}1 \\1 \\4\end{array}\right] \\
& |A|=1(24-18)-2(-12-9)-3(12+12) \\
& =6+42-72 \\
& =-24
\end{aligned}
$$

$$
\begin{aligned}
\operatorname{Adj} A & =\left[\begin{array}{ccc}
6 & 21 & 24 \\
-6 & 3 & 0 \\
-6 & -9 & -8
\end{array}\right] \\
& =\left[\begin{array}{ccc}
6 & -6 & -6 \\
21 & 3 & -9 \\
24 & 0 & -8
\end{array}\right] \\
A^{-1} & =\frac{1}{|A|} \operatorname{adj} A \\
& =\frac{-1}{24}\left[\begin{array}{ccc}
6 & -6 & -6 \\
21 & 3 & -9 \\
24 & 0 & -8
\end{array}\right]
\end{aligned}
$$

$$
\begin{aligned}
& X=A^{\prime} B \\
&=\frac{-1}{24}\left[\begin{array}{ccc}
6 & -6 & -6 \\
21 & 3 & -9 \\
24 & 0 & -8
\end{array}\right]\left[\begin{array}{l}
1 \\
1 \\
4
\end{array}\right] \\
&=\frac{-1}{24}\left[\begin{array}{c}
6-6-24 \\
21+3-36 \\
24-32
\end{array}\right] \\
&=\frac{-1}{24}\left[\begin{array}{c}
-24 \\
-12 \\
-8
\end{array}\right]=\left[\begin{array}{l}
1 \\
1 / 2 \\
1 / 3
\end{array}\right] \\
& \therefore \alpha=1, \beta=2, \gamma=3 \\
& N\left(0 w, \alpha^{2}+\gamma^{2}=1+9\right. \\
&=10=5 \beta
\end{aligned}
$$

7. (c) We have,

$$
\begin{aligned}
& \sum_{k=1}^{6} \sin \left(\frac{2 \pi k}{7}\right)-i \cos \left(\frac{2 \pi k}{7}\right) \\
& \quad=-i\left[\sum_{k=1}^{6} \cos \left(\frac{2 \pi k}{7}\right)+i \sin \left(\frac{2 \pi k}{7}\right)\right]=-i \sum_{k=1}^{6} c^{12 \pi k} \\
& \quad=-i\left[e^{i 2 \pi / 7}+e^{i 4 \pi / 7}+\ldots+e^{i 12 \pi / 7} \mid\right.
\end{aligned}
$$

This forms a GP

$$
\begin{aligned}
& =-i\left[e^{i 2 \pi / 7} \frac{\left(1-\left(e^{i 2 \pi / 7}\right)^{6}\right]}{1-e^{i 2 \pi / 7}}\right] \cdot \\
& =-i\left[\frac{e^{i 2 \pi / 7}-e^{i 14 \pi / 7}}{1-e^{i 2 \pi / 7}}\right] \\
& =-i\left[\frac{e^{i 2 \pi / 7}-1}{1-e^{i 2 \pi / 7}}\right] \quad\left[\because e^{i 14 \pi / 7}=1\right] \\
& =i
\end{aligned}
$$

8. (a) We have,

$$
\begin{aligned}
& (x-i y)^{1 / 3}=a-i b \\
\Rightarrow & x-i y=(a-i b)^{3} \\
\Rightarrow & x-i y=a^{3}-i^{3} b^{3}-3 a^{2} i b+3 x i^{2} t t
\end{aligned}
$$

$\Rightarrow x-i y=a^{3}+i b^{3}-3 a^{2} b i-3 a b^{2}$

Comparing real part and imaginary part on both sides, we get

$$
\begin{gathered}
x=a^{3}-3 a b^{2}, y=3 a^{2} b-b^{3} \\
\text { Now, } \frac{x}{2 a}+\frac{y}{2 b}=\frac{a\left(a^{2}-3 b^{2}\right)}{2 a}+\frac{b\left(3 a^{2}-b^{2}\right)}{2 b} \\
=\frac{a^{2}-3 b^{2}+3 a^{2}-b^{2}}{2}=2\left(a^{2}-b^{2}\right)
\end{gathered}
$$

9. (d) We have,

$$
\begin{aligned}
& \cos 5 \theta=\cos (4 \theta+\theta) \\
& =\cos 4 \theta \cos \theta-\sin 4 \theta \sin \theta \\
& =\left(2 \cos ^{2} 2 \theta-1\right) \cos \theta-2 \sin 2 \theta \cos 2 \theta \sin \theta \\
& =2 \cos \theta\left[2 \cos ^{2} \theta-1\right]^{2}-\cos \theta-2(2 \sin \theta \cos \theta) \\
& =2 \cos \theta\left[4 \cos ^{4} \theta+1-4 \cos ^{2} \theta\right] \\
& \left(2 \cos ^{2} \theta-1\right) \sin \theta \\
& -\cos \theta-4 \sin ^{2} \theta \cos \theta\left(2 \cos ^{2} \theta-1\right) \\
& =8 \cos ^{5} \theta+2 \cos \theta-8 \cos ^{3} \theta-\cos \theta \\
& -\left(8 \cos ^{3} \theta-4 \cos \theta\right) \sin ^{2} \theta \\
& =8 \cos ^{5} \theta+\cos \theta-8 \cos ^{3} \theta \\
& \left.=8 \cos ^{5} \theta+\cos \theta-8 \cos ^{3} \theta-4 \cos \theta\right)\left(1-\cos ^{2} \theta\right) \\
& -8 \cos ^{3} \theta+4 \cos \theta+8 \cos ^{5} \theta-4 \cos ^{3} \theta \\
& =16 \cos ^{5} \theta-20 \cos ^{3} \theta+5 \cos \theta
\end{aligned}
$$

10. (c) We have,

$$
\begin{aligned}
& x=-5+2 \sqrt{-4} \\
& x+5=4 i
\end{aligned}
$$

On squaring both sides,

$$
\begin{aligned}
& x^{2}+10 x+25=-16 \\
\Rightarrow \quad & x^{2}+10 x=-41 \text { or } x^{2}+10 x+41=0 \\
\text { Now, } & x^{4}+9 x^{3}+35 x^{2}-x+4 \\
= & x^{4}+10 x^{3}+41 x^{2}-x^{3}-6 x^{2}-x+4 \\
= & x^{2}\left(x^{2}+10 x+41\right)-x^{3}-10 x^{2}-41 x \\
= & x^{2}(0)-x\left(x^{2}+10 x+41\right)+4\left(x^{2}+10 x\right)+4 \\
= & 4(-41)+4 \\
= & -160
\end{aligned}
$$

11. (d) $\alpha, \beta$ are the roots of $x^{2}-10 x-8=0$

$$
\alpha+\beta=10, \alpha \beta=-8
$$

Also, $\alpha^{2}-10 \alpha-8=0$ or $\alpha^{2}-8=10 \alpha$ and $\beta^{2}-10 \beta-8=0$ or $\beta^{2}-8=10 \beta$

Now, $\frac{a_{10}-8 a_{8}}{5 a_{9}}$

$$
=\frac{\left(\alpha^{10}-\beta^{10}\right)-8\left(\alpha^{8}-\beta^{8}\right)}{5\left(\alpha^{9}-\beta^{9}\right)}
$$

$$
\begin{aligned}
& =\frac{\left(\alpha^{10}-8 \alpha^{8}\right)-\left(\beta^{10}-8 \beta^{8}\right)}{5\left(\alpha^{9}-\beta^{9}\right)} \\
& =\frac{\alpha^{8}\left(\alpha^{2}-8\right)-\beta^{8}\left(\beta^{2}-8\right)}{5\left(\alpha^{9}-\beta^{9}\right)} \\
& =\frac{\alpha^{8} \times 10 \alpha-\beta^{8} \times 10 \beta}{5\left(\alpha^{9}-\beta^{9}\right)} \\
& =\frac{10\left[\alpha^{9}-\beta^{9}\right]}{5\left(\alpha^{9}-\beta^{9}\right)} \\
& =2
\end{aligned}
$$

12. (b) Given, equation is

$$
x^{2}+(2 m+1) x+m=0
$$

As the equation has equal roots, $D=0$

$$
(2 m+1)^{2}-4 m=0
$$

$\Rightarrow 4 m^{2}+4 m+1-4 m=0$

$\Rightarrow 4 m^{2}+1=0$

$m^{2}=\frac{-1}{4}$ (which is not possible)

$\therefore m$ has no real values.

13. (d) We have, $2^{\sqrt{\sin ^{2} x-2 \sin x+5}} \times \frac{1}{4^{\sin ^{2} y}} \leq 1$

$\Rightarrow 2^{\sqrt{\sin ^{2} x-2 \sin x+1+4}} \leq 4^{\sin ^{2} y}$

$\Rightarrow 2^{\sqrt{(\sin x-1)^{2}+4}} \leq 2^{2 \sin ^{2} y}$.

$\Rightarrow \sqrt{(\sin x-1)^{2}+4} \leq 2 \sin ^{2} y$

$$
\sqrt{(\sin x-1)^{2}+4} \in[2,2 \sqrt{2}] \text { and } 2 \sin ^{2} y \in[0,2]
$$

$\therefore \quad(\sin x-1)^{2}+4=2 \sin ^{2} y=2$

$\Rightarrow(\sin x-1)^{2}=0$

$\Rightarrow \sin x=1$

and $2 \sin ^{2} y=2$

$\Rightarrow \sin ^{2} y=1 \Rightarrow|\sin y|=1$

$\Rightarrow \sin x=|\sin y|$

14. (b) $x+y+z=1$

$$
x^{2}+y^{2}+z^{2}=1, x^{3}+y^{3}+z^{3}=1
$$

$\Rightarrow x, y$ and $z$ are positive integers.

There are three solutions, i.e. $(1,0,0)$, $(0,1,0)$ and $(0,0,1)$.

15. (d). There are 5 different green toys, so the
number of ways number of ways that at least one green toy can be selected is $2^{5}-1=31$

There are 4 different blue toys, so the number of $2^{4}-1=15$ There are 3 different red toys and here is no restriction in selecting the toys, so the number of ways of selection red toys is $2^{3}=8$

$\therefore$ The reauired number of ways is $31 \times 15 \times 8$.

16. (a) We have,

$$
{ }^{2 n} C_{3}:{ }^{n} C_{3}=12: 1
$$

$\Rightarrow \frac{2 n !}{3 ! \times(2 n-3) !}: \frac{n !}{(n-3) ! 3 !}=\frac{12}{1}$

$\Rightarrow \frac{(2 n)(2 n-1)(2 n-2)}{n(n-1)(n-2)}=12$.

$\Rightarrow \frac{2 \times 2(2 n-1)}{n-2}=12$

$\Rightarrow \frac{2 n-1}{n-2}=3$

$\Rightarrow \quad 2 n-1=3 n-6$

$\Rightarrow n=5$

17. (d) Number of ways of selecting 4 aranges is $4+1=5$

Number of ways of selecting 5 apples is $5+1=6$

Number of ways of selecting 7 mangoes is $7+1=8$

$\therefore$ The required number of ways

$$
\begin{aligned}
& =5 \times 6 \times 8-1 \\
& =239
\end{aligned}
$$

18. (b) We have,

$$
{ }^{9} C_{3}+{ }^{9} C_{5}={ }^{10} C_{r}
$$

$$
\begin{aligned}
& \frac{9 !}{3 ! 6 !}+\frac{9 !}{5 ! 4 !}=\frac{10 !}{(10-r) ! \times r !}
\end{aligned}
$$

$\Rightarrow \frac{9 !}{5 ! 3 !}\left[\frac{1}{6}+\frac{1}{4}\right]=\frac{10 !}{(10-r) ! r !}$

$\Rightarrow \frac{9 !}{5 ! 3 !} \times \frac{10}{24}=\frac{10 !}{(10-r) ! r !}$

$\Rightarrow \frac{10 !}{6 ! 4 !}=\frac{10 !}{(10-r) ! r !}$

$\Rightarrow r=4$ or 6

19. (b) We have,

$$
\begin{aligned}
& \frac{x^{3}}{(2 x-1)(x+2(x-3)} \\
& =\frac{A(2 x-1)+B}{2 x-1}+\frac{C}{x+2}+\frac{D}{x-3} \\
& \Rightarrow \quad x^{3}=A(2 x-1)(x+2)(x-3) \\
& \quad+B(x+2)(x-3)+C(2 x-1)(x-3) \\
& \quad+D(2 x-1)(x+2) \quad \ldots
\end{aligned}
$$

Substitute $x=3$ in Eq. (i), we get

$$
27=D(5)(5)
$$

$\Rightarrow \quad D=\frac{27}{25}$

Substitute $x=-2$ in Eq. (i), we get

$$
-8=C(-5)(-5)
$$

$\Rightarrow \quad C=\frac{-8}{25}$

Substitute $x=1 / 2$ in Eq. (i),

$\frac{1}{8}=B\left(\frac{1}{2}+2\right)\left(\frac{1}{2}-3\right)$

$\Rightarrow \quad \frac{1}{8}=B\left(\frac{5}{2}\right)\left(\frac{-5}{2}\right)$

$\Rightarrow \quad B=\frac{-1}{50}$

Substitute $x=0$ in Eq. (i), we get

$0=A(-1)(2)(-3)+B(2)(-3)$

$$
+C(-1)(-3)+D(-1)(2)
$$

$\Rightarrow 6 A-6 B+3 C-2 D=0$

$\Rightarrow 6 A+\frac{6}{50}-\frac{24}{25}-\frac{54}{25}=0$

$6 A=\frac{24+54-3}{25}$

$\Rightarrow 6 A=3 \Rightarrow A=\frac{1}{2}$

$\therefore \quad A+B+C=\frac{1}{2}+\left(\frac{-1}{50}\right)+\left(\frac{-8}{25}\right)$

$=\frac{25-1-16}{50}=\frac{4}{25}$

20. (d) Given,

$\cos \theta-\sin \theta=\sqrt{5} \sin \theta$

$\Rightarrow \quad(\cos \theta-\sin \theta)^{2}=5 \sin ^{2} \theta$

$\Rightarrow \cos ^{2} \theta+\sin ^{2} \theta-2 \sin \theta \cos \theta=5 \sin ^{2} \theta$

$\Rightarrow 2 \sin \theta \cos \theta=1-5 \sin ^{2} \theta$

Now, $\cos \theta+4 \sin \theta=\sqrt{(\cos \theta+4 \sin \theta)^{2}}$

$$
\begin{aligned}
& =\sqrt{\cos ^{2} \theta+16 \sin ^{2} \theta+8 \sin \theta \cos \theta} \\
& =\sqrt{\cos ^{2} \theta+16 \sin ^{2} \theta+4-20 \sin ^{2} \theta}
\end{aligned}
$$

[ $\because$ using Eq. (i)]

$$
\begin{aligned}
& =\sqrt{\cos ^{2} \theta-4 \sin ^{2} \theta+4} \\
& =\sqrt{\cos ^{2} \theta-4\left(1-\cos ^{2} \theta\right)+4} \\
& =\sqrt{\cos ^{2} \theta+4 \cos ^{2} \theta} \\
& =\sqrt{5} \cos \theta
\end{aligned}
$$

21. (b) We have,

$$
\begin{aligned}
& \frac{A+B}{2}=\frac{180-C}{2} \\
& \frac{A+B}{2}=90-\frac{C}{2}
\end{aligned}
$$

146 AP EAPCET (Engineering) Online Solved Paper 2022

$\Rightarrow \tan \left(\frac{A}{2}+\frac{B}{2}\right)=\tan \left(90-\frac{C}{2}\right)$

$\Rightarrow \quad \frac{\tan \frac{A}{2}+\tan \frac{B}{2}}{1-\tan \frac{A}{2} \tan \frac{B}{2}}=\cot \frac{C}{2}$

$\Rightarrow \quad \frac{\tan \frac{A}{2}+\tan \frac{B}{2}}{1-\tan \frac{A}{2} \tan \frac{B}{2}}=\frac{1}{\tan \frac{C}{2}}$

$\Rightarrow \quad \tan \frac{A}{2} \tan \frac{C}{2}+\tan \frac{B}{2} \tan \frac{C}{2}$

$=1-\tan \frac{A}{2} \tan \frac{B}{2}$

$\therefore \quad \tan \frac{A}{2} \tan \frac{B}{2}+\tan \frac{B}{2} \tan \frac{C}{2}+\tan \frac{C}{2} \tan \frac{A}{2}=1$

22. (a) $\sec ^{2} x+5 \tan x+5$

$$
\begin{aligned}
& =1+\tan ^{2} x+5 \tan x+5 \\
& =\tan ^{2} x+5 \tan x+6 \\
& =\tan ^{2} x+3 \tan x+2 \tan x+6 \\
& =\tan x(\tan x+3)+2(\tan x+3) \\
& =(\tan x+2)(\tan x+3)
\end{aligned}
$$

23. (b) Given, $\sin \alpha+\sin \beta=\frac{-21}{65}$

and $\cos \alpha+\cos \beta=\frac{-27}{65}$

Squaring and adding both equations

$(\sin \alpha+\sin \beta)^{2}+(\cos \alpha+\cos \beta)^{2}$

$$
=\left(\frac{-21}{65}\right)^{2}+\left(\frac{-27}{65}\right)^{2}
$$

$\Rightarrow \sin ^{2} \alpha+\cos ^{2} \alpha+\sin ^{2} \beta+\cos ^{2} \beta+2 \sin \alpha \sin \beta$

$$
+2 \cos \alpha \cos \beta=\frac{441+729}{4225}
$$

$\Rightarrow 2+2[\cos (\beta-\alpha)]=\frac{1170}{4225}$

$\Rightarrow 2[1+\cos (\beta-\alpha)]=\frac{1170}{4225}$

$\Rightarrow 1+2 \cos ^{2} \frac{(\beta-\alpha)}{2}-1=\frac{585}{4225}$

$\Rightarrow \cdot \cos ^{2} \frac{(\beta-\alpha)}{2}=\frac{9}{130} \Rightarrow \cos \frac{(\beta-\alpha)}{2}=\pm \frac{3}{\sqrt{130}}$

$\Rightarrow \cos \frac{(\beta-\alpha)}{2}=-\frac{3}{\sqrt{130}}$

$[\because \pi<\alpha-\beta<3 \pi]$

24. (d) We have,

$\operatorname{cosech} x=\frac{4}{5}$

$\Rightarrow \quad \sinh x=\frac{5}{4}$

$$
\Rightarrow \quad \begin{aligned}
\cosh x & =\sqrt{1+\sin ^{2} h x} \\
& =\sqrt{1+\frac{25}{16}}=\sqrt{\frac{41}{16}}
\end{aligned}
$$

25. (a) Let $y=\tan ^{-1} \mathrm{~h} x$

$$
\tanh y=x
$$

$$
\begin{aligned}
& \frac{e^{y}-e^{-y}}{e^{y}+e^{-y}}=x .
\end{aligned}
$$

$\Rightarrow \frac{e^{y}-\frac{1}{e^{y}}}{e^{y}+\frac{1}{e^{y}}}=x \Rightarrow \frac{e^{2 y}-1}{e^{2 y}+1}=x$

$\Rightarrow \quad e^{2 y}-1=x e^{2 y}+x \Rightarrow e^{2 y}(1-x)=1+x$

$\Rightarrow \quad e^{2 y}=\frac{1+x}{1-x}$

Taking log on both sides

$$
\begin{aligned}
& \log e^{2 y}=\log \left(\frac{1+x}{1-x}\right) \\
\Rightarrow & 2 y=\log \left(\frac{1+x}{1-x}\right) \\
\Rightarrow & y=\frac{1}{2} \log \left(\frac{1+x}{1-x}\right) . \\
\therefore \quad & \tan { }^{-1} x=\frac{1}{2} \log \left(\frac{1+x}{1-x}\right)
\end{aligned}
$$

26. (b) We have,

$$
s=\frac{4+5+7}{2}=8 \mathrm{~cm}
$$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-04.jpg?height=609&width=669&top_left_y=1806&top_left_x=1075)

27. (a) We have,

$$
\begin{aligned}
s & =\frac{a+b+c}{2} \\
& =\frac{a+5+6}{2} \\
& =\frac{11+a}{2}
\end{aligned}
$$



$$
\begin{aligned}
\Rightarrow \quad s-a & =\frac{11+a}{2}-a \\
& =\frac{11-a}{2}
\end{aligned}
$$

$\Rightarrow \quad s-b=\frac{11+a}{2}-5$

$$
=\frac{a+1}{2}
$$

$\Rightarrow \quad \therefore-c=\frac{11+a}{2}-6=\frac{a-1}{2}$

Now, $\tan \frac{A}{2}=\sqrt{\frac{(s-b)(s-c)}{s(s-a)}}$

$\Rightarrow \frac{1}{\sqrt{2}}=\sqrt{\frac{\left(\frac{a+1}{2}\right)\left(\frac{a-1}{2}\right)}{\left(\frac{11+a}{2}\right)\left(\frac{11-a}{2}\right)}}$

$\Rightarrow \frac{1}{2}=\frac{a^{2}-1}{121-a^{2}} \Rightarrow 121-a^{2}=2 a^{2}-2$

$\Rightarrow 3 a^{2}=123 \Rightarrow a^{2}=41$

$\Rightarrow \quad a=\sqrt{41}$

28. (b) Given,

$$
\begin{aligned}
& s\left[\frac{r_{1}-r}{a}+\frac{r_{2}-r}{b}+\frac{r_{3}-r}{c}\right] \\
& =s\left[\frac{1}{a}\left(\frac{\Delta}{s-a}-\frac{\Delta}{s}\right)+\frac{1}{b}\left(\frac{\Delta}{s-b}-\frac{\Delta}{s}\right)\right. \\
& \left.+\frac{1}{c}\left(\frac{\Delta}{s-c}-\frac{\Delta}{s}\right)\right] \\
& =s\left[\frac{\Delta}{a}\left(\frac{s-s+a}{s(s-a)}\right)+\frac{\Delta}{b}\left(\frac{s-s+b}{s(s-b)}\right)\right. \\
& \left.+\frac{\Delta}{c}\left(\frac{s-s+c)}{s(s-c)}\right)\right] \\
& =\frac{\Delta}{s-a}+\frac{\Delta}{s-b}+\frac{\Delta}{s-c}=r_{1}+r_{2}+r_{3}
\end{aligned}
$$

29. (c) We have,

$\mathbf{A B}=$ Position vector of $B$ - Position vector of $A$

$$
=-6 \hat{i}-2 \hat{j}+3 \hat{k}
$$

$$
\begin{aligned}
& |\mathbf{A B}|=\sqrt{36+4+9}=7
\end{aligned}
$$

$\mathbf{B C}=$ Position vector of $C-$ Position vector of $B$

$=-2 \hat{i}+3 \hat{j}-6 \hat{k}$

$|B C|=\sqrt{4+9+36}=7$

$\mathrm{CD}=6 \hat{i}+2 \hat{j}+\hat{k}$

$|C D|=\sqrt{36+4+1}=\sqrt{41}$

$\mathrm{DA}=2 \hat{i}-3 \hat{j}+2 \hat{k}$

$$
\begin{aligned}
& |\mathrm{DA}|=\sqrt{4+9+4}=\sqrt{17} \\
& \begin{aligned}
\mathbf{A C} & =-8 \hat{i}+\hat{j}-3 \hat{k} \\
& =\mathbf{A B}+\mathbf{B C}
\end{aligned}
\end{aligned}
$$

$\therefore A B C D$ is a quadrilateral which is not a parallelogram.

30. (d) Let positive vector of $A, B, C$ and $D$ are $\mathbf{a}, \mathbf{b}, \mathbf{c}$ and $d$ respectively.

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-05.jpg?height=334&width=425&top_left_y=804&top_left_x=1204)

$$
\begin{aligned}
& \mathbf{A B}= \mathbf{b}-\mathbf{a} \\
& \mathbf{A D}=\mathbf{d}-\mathbf{a} \\
& \mathbf{A C}=\mathbf{A B}+ \mathbf{A D}[\because \text { parallelogram law of vector }] \\
&=\mathbf{b}-\mathbf{a}+\mathbf{d}-\mathbf{a} \\
& \mathbf{c}-\mathbf{a}=\mathbf{b}+\mathbf{d}-2 \mathbf{a} \\
& \mathbf{C}=\mathbf{b}+\mathbf{d}-\mathbf{a} \\
& \mathbf{C}+\mathbf{a}=\mathbf{b}+\mathbf{d} \\
& \text { Position vector of } M=\frac{\mathbf{b}+\mathbf{c}}{2} \\
& \text { and Position vector of } N=\frac{\mathbf{c}+\mathbf{d}}{2} \\
& \mathbf{A M}+\mathbf{A N}=\left(\frac{\mathbf{b}+\mathbf{c}}{2}-\mathbf{a}\right)+\left(\frac{\mathbf{c}+\mathbf{d}}{2}-\mathbf{a}\right) \\
&=\frac{\mathbf{b}+\mathbf{c}-2 \mathbf{a}+\mathbf{c}+\mathbf{d}-2 \mathbf{a}}{2} \\
&=\frac{\mathbf{b}+\mathbf{d}+2 \mathbf{c}-4 \mathbf{a}}{2} \\
&=\frac{\mathbf{c}+\mathbf{a}+2 \mathbf{c}-4 \mathbf{a}}{2} \quad[\because \text { from Eq. (i) }] \\
&=\frac{3 \mathbf{c}-3 \mathbf{a}}{2}=\frac{3}{2}(\mathbf{c}-\mathbf{a})=\frac{3}{2} \mathbf{A C}
\end{aligned}
$$

31. (c) Let 0 , the circum centre of circle be taken as origin.

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-05.jpg?height=396&width=394&top_left_y=2292&top_left_x=1211)

Let $\mathbf{a}, \mathbf{b}$ and $\mathbf{c}$ are the position vector of the vertices $A, B$ and $C$, respectively. 

\section{AP EAPCET (Engineering) Online Solved Paper 2022}

Position vector of $G=\left(\frac{\mathbf{a}+\mathbf{b}+\mathbf{c}}{3}\right)$

Let $B C=a, A B=c$ and $A C=b$

$$
|B C|=a
$$

$\Rightarrow|\mathbf{c}-\mathbf{b}|=a$

$\Rightarrow(\mathbf{c}-\mathbf{b})^{2}=a^{2}$

$\Rightarrow|\mathbf{c}|^{2}+|\mathbf{b}|^{2}-2 \mathbf{b} \cdot \mathbf{c}=a^{2}$

$\Rightarrow R^{2}+R^{2}-2 \mathbf{b} \cdot \mathbf{c}=a^{2}$

$\Rightarrow \quad 2 \mathbf{b} \cdot \mathbf{c}=2 R^{2}-a^{2}$

Similarly, $2 \mathbf{a} \cdot \mathbf{b}=2 R^{2}-c^{2}$

and $2 \mathrm{a} \cdot \mathrm{c}=2 R^{2}-b^{2}$

$\mathbf{O G}=\frac{\mathbf{a}+\mathbf{b}+\mathbf{c}}{3}$

$|O G|^{2}=\frac{(a+b+c)^{2}}{9}$

$=\frac{|\mathbf{a}|^{2}+|\mathbf{b}|^{2}+|\mathbf{c}|^{2}+2 \mathbf{a} \cdot \mathbf{b}+2 \mathbf{b} \cdot \mathbf{c}+2 \mathbf{c} \cdot \mathbf{a}}{9}$

$=\frac{R^{2}+R^{2}+R^{2}+2 R^{2}-a^{2}+2 R^{2}-b^{2}+2 R^{2}-c^{2}}{9}$

$=\frac{9 R^{2}-1\left(a^{2}+b^{2}+c^{2}\right)}{9}$

$=R^{2}-\frac{1}{9}\left(a^{2}+b^{2}+c^{2}\right)$

32. (c) We have,

$\mathbf{a}+\mathbf{b}+\mathbf{c}=0$

$\Rightarrow(\mathbf{a}+\mathbf{b}+\mathbf{c})^{2}=0$

$|\mathbf{a}|^{2}+|\mathbf{b}|^{2}+|\mathbf{c}|^{2}+2(\mathbf{a} \cdot \mathbf{b}+\mathbf{b} \cdot \mathbf{c}+\mathbf{c} \cdot \mathbf{a})=0$

$\therefore \quad \mathbf{a} \cdot \mathbf{b}+\mathbf{b} \cdot \mathbf{c}+\mathbf{c} \cdot \mathbf{a}$

$=\frac{-1}{2}(1+9+16)$

$=-13$

33. (a) The bisector OD of $\angle A O B$

$=\lambda\left(\frac{\mathrm{OA}}{|\mathbf{O A}|}+\frac{\mathrm{OB}}{|\mathrm{OB}|}\right)$

$=\lambda\left(\frac{-4 \hat{i}+3 \hat{k}}{\sqrt{16+9}}+\frac{14 \hat{i}+2 \hat{j}-5 \hat{k}}{\sqrt{196+4+25}}\right)$

$=\lambda\left[\frac{-4 \hat{i}+3 \hat{k}}{5}+\frac{14 \hat{i}+2 \hat{j}-5 \hat{k}}{15}\right]$

$=\lambda\left[\frac{-12 \hat{i}+9 \hat{k}+14 \hat{i}+2 \hat{j}-5 \hat{k}}{15}\right]$

$=\lambda \times \frac{2}{15}[\hat{i}+\hat{j}+2 \hat{k}]$

$\Rightarrow \quad|O D|=\sqrt{6}$

$$
\begin{aligned}
= & \sqrt{\left(\frac{2}{15} \lambda\right)^{2}+\left(\frac{2}{15} \lambda\right)^{2}+\left(\frac{4}{15} \lambda\right)^{2}}=\sqrt{6} \\
= & \frac{4 \lambda^{2}+4 \lambda^{2}+16 \lambda^{2}}{225}=6 \\
= & \lambda^{2}=\frac{225}{4}=\lambda=\frac{+15}{2} \\
\text { OD } & =\pm \frac{15}{2} \times \frac{2}{15}(\hat{i}+\hat{j}+2 \hat{k}) \\
= & \pm(\hat{i}+\hat{j}+2 \hat{k})
\end{aligned}
$$

34. $\left(^{*}\right)$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-06.jpg?height=825&width=962&top_left_y=967&top_left_x=1001)

35. (a) We have, $P(X)=\frac{1}{5}, P(Y)=\frac{1}{4}$,

$$
\begin{aligned}
& P \bar{Z})=\frac{2}{3} \\
& P(Z)=\frac{1}{3}
\end{aligned}
$$

$\therefore P(X Y \bar{Z}+\bar{X} Y Z+X \bar{Y} Z+X Y Z)$

$\frac{1}{5} \times \frac{1}{4} \times \frac{2}{3}+\frac{4}{5} \times \frac{1}{4} \times \frac{1}{3}+\frac{1}{5} \times \frac{3}{4} \times \frac{1}{3}+\frac{1}{5} \times \frac{1}{4} \times \frac{1}{3}$

$=\frac{2+4+3+1}{60}$

$=\frac{10}{60}=\frac{1}{6}$

36. (b) The total number of outcome is 36 .

Favourable outcomes $(1,2),(1,4),(1,6),(2,1)$,

$(2,2),(2,3),(2,4),(2,5),(2,6),(3,2),(3,4),(3$,

$6),(4,1),(4,2),(4,3),(4,4),(4,5),(4,6),(5,2)$,

$(5,4),(5,6),(6,1),(6,2),(6,3),(6,4),(6,5)$,

$(6,6)$.

Number of favourable outcomes is 27 . $P$ (Product of 2 number is even)

$$
\begin{aligned}
& =\frac{27}{36} \\
& =\frac{3}{4}
\end{aligned}
$$

37. (d) Total number of outcomes when 3 cards are drawn $={ }^{52} \mathrm{C}_{3}$

There are 4 ace, 4 queen and 4 jack cards in a deck of 52 cards.

$P$ (ace, jack and queen $)=\frac{{ }^{4} C_{1} \times{ }^{4} C_{1} \times{ }^{4} C_{1}}{{ }^{52} C_{3}}$

$$
\begin{aligned}
& =\frac{4 \times 4 \times 4}{52 \times 51 \times 50} \times 1 \times 2 \times 3 \\
& =\frac{16}{5525}
\end{aligned}
$$

38. (c) The total number of cases of checking in the hotels $=4 \times 4 \times 4=64$ ways

Number of ways of checking the 3 men in different hotels

$$
=4 \times 3 \times 2=24
$$

$P(3$ men checking in different hotels $)=\frac{24}{64}=\frac{3}{8}$

39. (b) $P(X=2)=P(X=3)$

$$
{ }^{n} C_{2} p^{2} q^{n-2}={ }^{n} C_{3} p^{3} \cdot q^{n-3}
$$

$$
\begin{aligned}
& { }^{n} C_{2} q={ }^{n} C_{3} p \\
& { }^{n} C_{2}(1-p)={ }^{n} C_{3} p \\
& { }^{n} C_{2}=\left({ }^{n} C_{2}+{ }^{n} C_{3}\right) p
\end{aligned}
$$

$\frac{n !}{2 !(n-2) !}=\left(\frac{n !}{2 !(n-2) !}+\frac{n !}{3 !(n-3) !}\right) p$

$\Rightarrow \frac{1}{2 !(n-2) !}=\frac{1}{2 !(n-3) !}\left[\frac{1}{n-2}+\frac{1}{3}\right] p$

$\Rightarrow \frac{1}{n-2}=\left(\frac{3+n-2}{3(n-2)}\right) p$

$\Rightarrow \quad 3=(n+) p$

$\Rightarrow \quad 3=n p+p$

$\Rightarrow n p=3-p$

Mean $=n p$

$$
=3-p
$$

40. (c) $P(X=2)+P(X=3)$

$\Rightarrow \frac{e^{-3} \times 3^{2}}{2 !}+\frac{e^{-3} \times 3^{3}}{3 !}$

$\Rightarrow e^{-3}\left[\frac{9}{2}+\frac{27}{6}\right]$

$\Rightarrow 9 e^{-3}$ 41. (c) Let coordinate of $P$ be $(x, y)$.

$(B P)^{2}-(A P)^{2}=121$

$\Rightarrow\left[(5-x)^{2}+(11-y)^{2}\right]-\left[(2-x)^{2}+(5-y)^{2}\right]=121$

$\Rightarrow 25+x^{2}-10 x+121+y^{2}-22 y-4-x^{2}+4 x$

$$
-25-y^{2}+10 y=121
$$

$\Rightarrow-10 x-22 y-4+4 x+10 y=0$

$\Rightarrow \quad-6 x-12 y-4=0$

$\Rightarrow 3 x+6 y+2=0$

Slope of the line is $=-\frac{\text { Coefficient of } x}{\text { Coefficient of } x^{2}}$

$$
=\frac{-3}{6}=\frac{-1}{2}
$$

42. (a) Let the coordinates of a point whose distance from $4 x+3 y=10$ are $(\alpha, \beta)$.

Then,

$$
\begin{aligned}
& \frac{|4 \alpha+3 \beta-10|}{\sqrt{4^{2}+3^{2}}}=1 \\
& \Rightarrow|4 \alpha+3(4-\alpha)-10|=5 \\
& [\because \alpha, \beta \text { lies on line } x+y=4] \\
& \Rightarrow|4 \alpha+12-3 \alpha-10|=5 \\
& \Rightarrow|\alpha+2|=5 \Rightarrow \alpha+2=\pm 5 \\
& \Rightarrow \alpha+2=5 \text { or } \alpha+2=-5 \\
& \alpha=3, \alpha=-7 \\
& \text { If } \alpha=3 \text {, then } \beta=1 \\
& \text { If } \alpha=-7 \text {, then } \beta=11 \\
& d=\sqrt{(3+7)^{2}+(1-11)^{2}}=\sqrt{100+100} \\
& =\sqrt{200}=10 \sqrt{2} \text { units }
\end{aligned}
$$

43. (a) $\sqrt{3} x \pm(y-2)=0$

The intersection point of 2 given lines is $(0,2)$.

$$
y-2=\pm \sqrt{3} x
$$

$\Rightarrow y=\pm \sqrt{3} x+2$ is a line at a distance of 5 units from $(0,2)$

$\Rightarrow \sqrt{(x-0)^{2}+(y-2)^{2}}=5$

$\Rightarrow x^{2}+(y-2)^{2}=25 \Rightarrow x^{2}+3 x^{2}=25$

$\Rightarrow x^{2}=25 / 4$

$\Rightarrow x=\pm \frac{5}{2}$ and $y=2+\frac{5 \sqrt{3}}{2}$

Foot of the perpendicular of $P$ on $Y$-axis is $\left(0,2+\frac{5 \sqrt{3}}{2}\right)$.

Distance from origin to $\left(0,2+\frac{5 \sqrt{3}}{2}\right)$

$$
=2+\frac{5 \sqrt{3}}{2}
$$

44. (b) Slope of $A C=\frac{3+1}{-3-1}=-1$

Slope of $B D=\frac{1+2}{1+2}=1$

Slope of $A C \times$ Slope of $B D=-1$

$\Rightarrow A C$ is perpendicular to $B D$.

$\Rightarrow$ Angle between $A C$ and $B D$ is $\pi / 2$.

45. (c) Let $y=m x$ be a common line to both

$$
2 x^{2}+a x(m x)+3 m^{2} x^{2}=0
$$

and $2 x^{2}+b x(m x)-3 m^{2} x^{2}=0$

Comman from $x^{2}$ in both equation,

$$
2+m a+3 m^{2}=0
$$

and $\quad 2+m b-3 m^{2}=0$

Adding both equation, we get

$$
m(a+b)=-4
$$

$\Rightarrow m=\frac{-4}{a+b}$

Subtracting both equations, we get

$$
m(a-b)+6 m^{2}=0
$$

$\Rightarrow m \neq 0$, so $m=\frac{-(a-b)}{6}$

$\Rightarrow \frac{-4}{a+b}=\frac{-(a-b)}{6}$

$\Rightarrow a^{2}-b^{2}=24$

Now, let $y=m_{1} x$ and $y=\frac{-1}{m_{1}} x$ be two perpendicular line.

$\Rightarrow 2+m_{1} a+3 m_{1}^{2}=0$ and $2 m_{1}^{2}-b m_{1}-3=0$

Solving, we get $m_{1}=\frac{-13}{2 a+3 b}$ and $m_{1}=-\frac{(3 a-2 b)}{13}$

$\Rightarrow \quad(2 a+3 b)(3 a-2 b)=169$

$\Rightarrow 6 a^{2}-4 a b+9 a b-6 b^{2}=169$

$\Rightarrow \quad 6(24)+5 a b=169$

$\Rightarrow \quad 5 a b=25 \Rightarrow a b=5$

$\Rightarrow \quad a^{2}-\left(\frac{5}{a}\right)^{2}=24 \Rightarrow a^{2}-\frac{25}{a^{2}}=24$

$\Rightarrow \quad a^{4}-24 a^{2}-25=0$

$\Rightarrow a^{2}=25$

$\Rightarrow a=5$ and $b=1$

46. (a) We have,

$x y-4 x-4 y+16=0$

$\Rightarrow x(y-4)-4(y-4)=0$

$\Rightarrow(x-4)(y-4)=0$

$x=4$ or $y=4$

and $x+y=5$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-08.jpg?height=617&width=518&top_left_y=385&top_left_x=1200)

Let incentre be $(h, k)$.

$\Rightarrow O M=O N$

$\frac{|h-4|}{\sqrt{1^{2}+0}}=\frac{|k-4|}{\sqrt{1^{2}+0^{2}}}$

$\Rightarrow h-4=\pm(k-4)$

Either $h=k$ or $h=8-k$

$\therefore$ The locus of the incentre formed by the triangle is $x-y=0$.

47. (a)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-08.jpg?height=488&width=437&top_left_y=1481&top_left_x=1232)

Here, $B C=6$ units

$O D$ is perpendicular to $B C$.

$$
\begin{aligned}
B D & =3 \text { units } \\
O D & =4 \text { units } \\
O B & =\sqrt{(O D)^{2}+(B D)^{2}} \\
& =\sqrt{3^{2}+4^{2}} \\
& =5 \text { units }
\end{aligned}
$$

$\therefore$ Radius 5 units

Coordinate of the centre is $(\pm 5,4)$.

Equation of circle $(x \pm 9)^{2}+(y-4)^{2}=5^{2}$

$\Rightarrow x^{2}+y^{2} \pm 10 x-8 y+25+16-25=0$

$\Rightarrow x^{2}+y^{2} \pm 10 x-8 y+16=0$

48. (b) Let $(x, y)$ denotes the set of the points that are at distance at least 2 units from $(-3,0)$.

According to question, $\sqrt{(x+3)^{2}+y^{2}} \geq 2$ $\Rightarrow(x+3)^{2}+y^{2} \geq 4$

$\Rightarrow x^{2}+y^{2}+6 x+9-4 \geq 0$

$x^{2}+y^{2}+6 x+5 \geq 0$

$\therefore$ Required set of points is

$\left\{(x, y) \mid x^{2}+y^{2}+6 x+5 \geq 0\right\}$.

49. (a) Let the centre of circle be $(h, k)$.

Here, $\quad|h|=|k|=r$

$\Rightarrow \quad h^{2}=k^{2}=r$

Centre of the circle lies on line $x-2 y-3=0$,

$$
h-2 k-3=0
$$

$\Rightarrow \quad h=2 k+3$

Equation of circle is

$$
(x-h)^{2}+(y-k)^{2}=r^{2}
$$

$\Rightarrow(x-2 k-3)^{2}+(y-k)^{2}=k^{2}$

Circle passes through $(0, k)$

$$
(2 k+3)^{2}+(0)^{2}=k^{2}
$$

$\Rightarrow 4 k^{2}+9+12 k=k^{2} \Rightarrow 3 k^{2}+12 k+9=0$

$\Rightarrow k^{2}+4 k+3=0 \Rightarrow k=-1,-3$

When $k=-1$, then $h=1$

and when $k=-3$, then $h=-3$

The values are $(1,-1)$ and $(-3,-3)$.

The equation of circles are $(x-1)^{2}+(y+1)^{2}=1$ or

$$
(x+3)^{2}+(y+3)^{2}=3^{2}
$$

$\Rightarrow x^{2}+y^{2}-2 x+2 y+1=0$ or

$x^{2}+y^{2}+6 x+6 y+9=0$

50. (a) Equation of circle

$(x-c)^{2}+(y-0)^{2}=r^{2}$

$\Rightarrow x^{2}+c^{2}-2 x c+y^{2}=r^{2}$

Circle passes through $(0, a)$

$$
c^{2}+a^{2}=r^{2}
$$

Circle also passes through $(b, h)$,

$$
b^{2}+c^{2}-2 b c+h^{2}=r^{2} \text {. }
$$

Substituting value of $r^{2}$ from Eq. (i),

$\therefore b^{2}+c^{2}-2 b c+h^{2}=c^{2}+a^{2}$

$\Rightarrow 2 b c=b^{2}+h^{2}-a^{2}$

$\Rightarrow c=\frac{b^{2}+h^{2}-a^{2}}{2 b}$.

51. (a) $x^{2}+y^{2}-4 y=0$

$\Rightarrow x^{2}+y^{2}-4 y+4=4$

$\Rightarrow \quad x^{2}+(y-2)^{2}=2^{2}$

The circle passes through origin.

Given centre of circle $(0,2)$ and radius is 2 .

Distance between $(0,2$ and $(4,5)$

$$
=\sqrt{(4-0)^{2}+(5-2)^{2}}=5
$$

As the circle can touch internally or externally to the given circle.

$$
\begin{aligned}
& R-2 \leq 5 \text { and } R+2 \geq 5 \\
& R \leq 7 \text { and } R \geq 3 \\
\therefore \quad & 3 \leq R
\end{aligned}
$$

52. (c) Focus of the parabola $y^{2}=8 x$ is $(2,0)$.

$$
\begin{aligned}
\text { Required distance } & =\sqrt{(6-2)^{2}+(4 \sqrt{3}-0)^{2}} \\
& =\sqrt{4^{2}+(4 \sqrt{3})^{2}} \\
& =\sqrt{16+48} \\
& =\sqrt{64}=8 \text { units }
\end{aligned}
$$

53. (c) Given equation of ellipse $\frac{x^{2}}{36}+\frac{y^{2}}{20}=1$

Here, $a^{2}=36, b^{2}=20$

$\Rightarrow \quad b^{2}=a^{2}\left(1-e^{2}\right) \Rightarrow 20=36\left(1-e^{2}\right)$

$\Rightarrow 1-e^{2}=\frac{5}{9} \Rightarrow e^{2}=\frac{4}{9}$

$\Rightarrow \quad e=\frac{2}{3}$

Distance between the directrix

$$
\frac{2 a}{e}=\frac{2 \times 6}{2 / 3}=18
$$

54. (*) Equation of directrix of conjugate hyperbola is $y=\pm \frac{b}{e}$

Comparing it with the given equation of directrix, we get

$$
\frac{b}{e}=\frac{\sqrt{8}}{\sqrt{5}}
$$

$\Rightarrow \quad b=\frac{\sqrt{8}}{\sqrt{5}} e \Rightarrow b=\frac{2 \sqrt{2}}{\sqrt{5}} \times \frac{\sqrt{5}}{2}$

$\Rightarrow \quad b=\sqrt{2} \Rightarrow a^{2}=b^{2}\left(e^{2}-1\right)$

$\Rightarrow \quad a^{2}=2\left(\frac{5}{4}-1\right) \Rightarrow a^{2}=2 \times \frac{1}{4}$

$\Rightarrow \quad a^{2}=\frac{1}{2}$

$\Rightarrow \quad a=\frac{1}{\sqrt{2}}$

55. (b) Let $P\left(x_{1}, y_{1}\right)$ be the point of intersection of tangents at the ends of a normal chord of the hyperbola $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.

Equation of chord is $\frac{x x_{1}}{a^{2}}-\frac{y y_{1}}{b^{2}}=1$

$$
b^{2} x x_{1}-a^{2} y y_{1}=a^{2} b^{2}
$$

Equation of a normal chord is $a x \cos \theta+b y \cot \theta=a^{2}+b^{2}$

Eqs. (i) and (ii) represent the same line

$$
\frac{b^{2} x_{1}}{a \cos \theta}=\frac{-a^{2} y_{1}}{b \cot \theta}=\frac{a^{2} b^{2}}{a^{2}+b^{2}}
$$

$$
\begin{aligned}
& \frac{b^{2} x_{1}}{a \cos \theta}=\frac{a^{2} b^{2}}{a^{2}+b^{2}} \text { and } \frac{-a^{2} y_{1}}{b \cot \theta}=\frac{a^{2} b^{2}}{a^{2}+b^{2}}
\end{aligned}
$$

$\sec \theta=\frac{a^{3}}{\left(a^{2}+b^{2}\right) x_{1}}$ and $\tan \theta=\frac{-b^{3}}{\left(a^{2}+b^{2}\right) y_{1}}$

As $\sec ^{2} \theta-\tan ^{2} \theta=1$

$$
\left(\frac{a^{3}}{\left(a^{2}+b^{2}\right) x_{1}}\right)^{2}-\left(\frac{-b^{3}}{\left(a^{2}+b^{2}\right) y_{1}}\right)^{2}=1
$$

$\Rightarrow \frac{a^{6}}{\left(a^{2}+b^{2}\right)^{2} x_{1}^{2}}-\frac{b^{6}}{\left(a^{2}+b^{2}\right)^{2} y_{1}^{2}}=1$

$\Rightarrow \frac{a^{6}}{x_{1}^{2}}-\frac{b^{6}}{y_{1}^{2}}=\left(a^{2}+b^{2}\right)^{2}$

The locus of the required point is

$\frac{a^{6}}{x^{2}}-\frac{b^{6}}{y^{2}}=\left(a^{2}+b^{2}\right)^{2}$

56. (c) The coordinate of centroid of triangle

$$
=\left(\frac{a-2+4}{3}, \frac{1+b+7}{3}, \frac{3-5+c}{3}\right)^{3}
$$

$$
\begin{aligned}
& =\left(\frac{a+2}{3}, \frac{b+8}{3}, \frac{c-2}{3}\right)
\end{aligned}
$$

$\Rightarrow \quad \frac{a+2}{3}=\frac{b+8}{3}=\frac{c-2}{3}=0$.

$\Rightarrow a=-2 b=-8, c=2$

$$
a^{2}+b^{2}+c^{2}=4+64+4=72
$$

57. (d) $l=\cos \alpha, m=\cos 2 \alpha$ and $n=\cos 3 \alpha$

$$
l^{2}+m^{2}+n^{2}=1
$$

$$
\cos ^{2} \alpha+\cos ^{2} 2 \alpha+\cos ^{2} 3 \alpha=1
$$

$$
\begin{aligned}
& \cos ^{2} \alpha+\left(2 \cos ^{2} \alpha-1\right)^{2}+\left(4 \cos ^{3} \alpha-3 \cos \alpha\right)^{2}=1
\end{aligned}
$$

Let $\cos \alpha=y$

$$
y^{2}+\left(2 y^{2}-1\right)^{2}+\left(4 y^{3}-3 y\right)^{2}=1
$$

$\Rightarrow y^{2}+4 y^{4}+1-4 y^{2}+16 y^{6}+9 y^{2}-24 y^{4}=1$

$\Rightarrow 16 y^{6}-20 y^{4}+6 y^{2}=0$.

$\Rightarrow 8 y^{4}-10 y^{2}+3=0$

$\Rightarrow y^{2}=\frac{3}{4}$ and $y^{2}=\frac{1}{2}$

$\left[\because y^{2} \neq 0\right]$

$$
\cos \alpha=\frac{\sqrt{3}}{2} \text { and } \cos \alpha=\frac{1}{\sqrt{2}}
$$

$\therefore \quad \alpha=\frac{\pi}{6}, \frac{\pi}{4}$ 58. (d) Equation of plane is

$$
\frac{x}{-2}+\frac{y}{4 / 3}+\frac{z}{-4 / 5}=1
$$

$\Rightarrow \frac{-x}{2}+\frac{3 y}{4}-\frac{5 z}{4}=1$

$\Rightarrow \quad-2 x+3 y-5 z=4$

$\Rightarrow \quad 2 x-3 y+5 z+4=0$

Direction rations are $2,-3,5$.

Direction cosines are $\frac{2}{\sqrt{2^{2}+(-3)^{2}+5^{2}}}$,

$$
\begin{aligned}
& \frac{-3}{\sqrt{2^{2}+(-3)^{2}+5^{2}}}, \frac{5}{\sqrt{2^{2}+(-3)^{2}+5^{2}}} \\
& =\frac{2}{\sqrt{38}}, \frac{-3}{\sqrt{38}}, \frac{5}{\sqrt{38}}
\end{aligned}
$$

59. (d) We have,

$\lim _{n \rightarrow \infty} \sqrt{2}\left[\frac{(2+\sqrt{2})^{n}+(2-\sqrt{2})^{n}}{(2+\sqrt{2})^{n}-(2-\sqrt{2})^{n}}\right]$

$=\sqrt{2} \lim _{n \rightarrow \infty} \frac{(2+\sqrt{2})^{n}\left[1+\left(\frac{2-\sqrt{2}}{2+\sqrt{2}}\right)^{n}\right]}{(2+\sqrt{2})^{n}\left[1-\left(\frac{2-\sqrt{2}}{2+\sqrt{2}}\right)^{n}\right]}$

$=\sqrt{2} \frac{\lim _{n \rightarrow \infty}\left[1+\left(\frac{2-\sqrt{2}}{2+\sqrt{2}}\right)^{n}\right]}{\lim _{n \rightarrow \infty}\left[1-\left(\frac{2-\sqrt{2}}{2+\sqrt{2}}\right)^{n}\right]}$

$=\sqrt{2} \quad\left[\because \lim _{n \rightarrow \infty}\left(\frac{2-\sqrt{2}}{2+\sqrt{2}}\right)^{n}=0\right]$

60. (b) We have,

$\lim _{x \rightarrow a^{-}}\left(\frac{|x|^{3}}{a}-\left[\frac{x}{a}\right]^{3}\right)=k$

$\Rightarrow \lim _{x \rightarrow a^{-}} \frac{|\dot{x}|^{3}}{a}-\lim _{x \rightarrow a^{-}}\left[\frac{x}{a}\right]^{3}=k \Rightarrow \frac{a^{3}}{a}-0=k$

$k=a^{2}$

Now, $\lim _{x \rightarrow a^{+}}\left(\frac{|x|^{3}}{3}-\left[\frac{x}{a}\right]^{3}\right)=1$

$\lim _{x \rightarrow a^{+}} \frac{|x|^{3}}{a}-\lim _{x \rightarrow a^{+}}\left[\frac{x}{a}\right]^{3}=1$

$$
a^{2}-1=1
$$

$$
\begin{aligned}
& k-1=l \Rightarrow k-l=1 
\end{aligned}
$$

61. (a) $\lim _{n \rightarrow \infty} \frac{A+e^{n x}}{x+A e^{n x}}$

$$
\begin{aligned}
& =\frac{A+\lim _{n \rightarrow \infty} e^{n x}}{x+A \lim _{n \rightarrow \infty} e^{n x}} \\
& =\frac{A}{x}
\end{aligned}
$$

$\left[\because e^{-\infty}=0\right]$

62. (c) $f(x)$ is continuous at $\pi / 2$

$$
\begin{aligned}
& \lim _{x \rightarrow \frac{\pi^{-}}{2}} f(x)=\lim _{x \rightarrow \frac{\pi^{-}}{2}} f(x)=f\left(\frac{\pi}{2}\right) \\
= & \lim _{x \rightarrow \frac{\pi^{-}}{2}} f(x)=\lim _{x \rightarrow \frac{\pi^{-}}{2}}\left(\frac{1-\sin ^{3} x}{3 \cos ^{2} x}\right) \\
= & \lim _{x \rightarrow \frac{\pi^{-}}{2}}\left(\frac{1-\sin x)\left(1+\sin ^{2} x+\sin x\right)}{3(1-\sin x)(1+\sin x)}\right) \\
= & \lim _{x \rightarrow \frac{\pi^{-}}{2}}\left[\frac{1+\sin ^{2} x+\sin x}{3(1+\sin x)}\right]=\frac{3}{3(2)} \\
= & \frac{1}{2}
\end{aligned}
$$

and $\lim _{x \rightarrow \frac{\pi^{\frac{\pi}{}}}{2}} f(x)=\lim _{x \rightarrow \frac{\pi^{*}}{2}} \frac{\beta(1-\sin x)}{(\pi-2 x)^{2}}$

$=\lim _{h \rightarrow 0^{+}} \frac{\beta\left(1-\sin \left(\frac{\pi}{2}+h\right)\right)}{\left(\pi-2\left(\frac{\pi}{2}+h\right)\right)^{2}}, h=x-\frac{\pi}{2}$

$=\lim _{h \rightarrow 0^{+}} \beta\left(\frac{1-\cos h}{4 h^{2}}\right)$

$=\lim _{h \rightarrow 0^{+}} \frac{\beta\left(2 \sin ^{2} h / 2\right)}{4 \times 4\left(\frac{h}{2}\right)^{2}}=\frac{\beta}{8}$

$\therefore \quad \frac{1}{2}=\frac{\beta}{8}=\alpha$

$\Rightarrow \alpha=\frac{1}{2}$ and $\beta=4$

$\therefore \quad \alpha \beta=2$

63. (c) $|f(x)-f(y)| \leq \frac{1}{2}|x-y|, \forall x, y \in R$

$=\lim _{h \rightarrow 0}|f(x+h)-f(x)| \leq \frac{1}{2}|x+h-x|$

$=\lim _{h \rightarrow 0} \frac{\mid f(x+h-f(x) \mid}{h} \leq \frac{1}{2}$

$f^{\prime}(x) \leq \frac{1}{2}$

But $f^{\prime}(x) \geq \frac{1}{2}$ (given) $\Rightarrow f^{\prime}(x)=\frac{1}{2} \Rightarrow f(x)=\frac{1}{2} x+c$

$\Rightarrow f(1)=\frac{1}{2} \times 1+c \Rightarrow \frac{1}{2}=\frac{1}{2}+c$

$$
c=0
$$

$\therefore f(x)=\frac{1}{2} x$ or $y=\frac{1}{2} x$

Substitute $y=\frac{1}{2} x$ in equation

$y=x^{2}-2 x-5$ to determine the number of points of intersection

$$
\begin{aligned}
& \frac{1}{2} x=x^{2}-2 x-5 \\
\Rightarrow & 2 x^{2}-5 x-10=0 \\
\Rightarrow & x=\frac{5 \pm \sqrt{25+80}}{4}=\frac{5 \pm \sqrt{105}}{4}
\end{aligned}
$$

$\therefore$ There are two point of intersection.

64. (b) Given,

$$
\begin{aligned}
& \frac{d^{n} y}{d x^{n}}=y_{n} \text { and } y=e^{\sqrt{x}}+e^{-\sqrt{x}} \\
\Rightarrow \quad y_{1} & =e^{\sqrt{x}} \times \frac{1}{2 \sqrt{x}}+e^{-\sqrt{x}} \times\left(\frac{-1}{2 \sqrt{x}}\right) \\
& =\frac{1}{2 \sqrt{x}}\left[e^{\sqrt{x}}-e^{-\sqrt{x}}\right]
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow \quad 2 \sqrt{x} y_{1}=e^{\sqrt{x}}-e^{-\sqrt{x}} \text {. }
\end{aligned}
$$

Again differentiate, we get,

$$
2 \sqrt{x} y_{2}+2 y_{1} \times \frac{1}{2 \sqrt{x}}
$$

$$
\begin{aligned}
& =e^{\sqrt{x}} \times \frac{1}{2 \sqrt{x}}-e^{-\sqrt{x}}\left(\frac{-1}{2 \sqrt{x}}\right) \\
& \Rightarrow \frac{4 x y_{2}+2 y_{1}}{2 \sqrt{x}}=\frac{e^{\sqrt{x}}+e^{-\sqrt{x}}}{2 \sqrt{x}}
\end{aligned}
$$

$\Rightarrow 4 x y_{2}+2 y_{1}=y$.

65. (a) $y=a^{x}$ and $y=b^{x}$ only intersect at the point

$$
y=a^{x}, \frac{d y}{d x}=a^{x} \log a
$$

Let $m_{1}=\left.\frac{d y}{d x}\right|_{(0,1)}=\log a$

$$
y=b^{x}, \frac{d y}{d x}=b^{x} \log b
$$

Let $m_{2}=\left.\frac{d y}{d x}\right|_{0,11}=\log b$

$$
\tan \alpha=\left|\frac{m_{1}-m_{2}}{1+m_{1} m_{2}}\right|=\left|\frac{\log a-\log b}{1+\log a \log b}\right|
$$

66. (c) $x y=a^{2}$

$\Rightarrow \quad x \frac{d y}{d x}+y=0 \Rightarrow \frac{d y}{d x}=\frac{-y}{x}$

Equation of tangent is $y-y_{1}=\frac{-y_{1}}{x_{1}}\left(x-x_{1}\right)$

$\Rightarrow x_{1} y-y_{1} x_{1}=-y_{1} x+x_{1} y_{1} \Rightarrow x y_{1}+y x_{1}=2 x_{1} y_{1}$ The tangent meet $X$-axis when $y=0$

$$
x y_{1}=2 x_{1} y_{1} \Rightarrow x=2 x_{1}
$$

The tangent meet $Y$-axis when $x=0$

$$
y x_{1}=2 x_{1} y_{1} \Rightarrow y=2 y_{1}
$$

$\therefore$ The points on $X$-axis is $\left(2 x_{1}, 0\right)$ and the point on $Y$-axis $\left(0,2 y_{1}\right)$.

Area of triangle $=\frac{1}{2} \times 2 x_{1} \times 2 y_{1}=2 x_{1} y_{1}=2 a^{2}$.

67. (a) Let the curve and line intersect at point $\left(x_{1}, y_{1}\right)$

$$
\begin{aligned}
& y=x^{2}+x+16 \\
& \left.\frac{d y}{d x}\right|_{\left(x_{1}, y_{1}\right)}=2 x_{1}+1
\end{aligned}
$$

Slope of line $=\frac{y_{1}-0}{x_{1}-0}=\frac{y_{1}}{x_{1}}$

$\Rightarrow 2 x_{1}+1=y_{1} / x_{1}$

$\Rightarrow 2 x_{1}^{2}+x_{1}=y_{1}$

$\left(x_{1} ; y_{1}\right)$ also satisfy the equation of curve.

$y_{1}=x_{1}^{2}+x_{1}+16$

$\Rightarrow 2 x_{1}^{2}+x_{1}=x_{1}^{2}+x_{1}+16$

$\Rightarrow \quad x_{1}^{2}=16$

or $x_{1}=4$

If $x_{1}=4$, then $y_{1}=16+4+16=36$

$$
m=\frac{d y}{d x}=2 x_{1}+1=2 \times 4+1=9
$$

68. (a) $f(x)=|x-5|+2|x-7|$

When $x \in(7, \infty)$

$$
\begin{aligned}
f(x) & =(x-5)+2(x-7) \\
& =x-5+2 x-14=3 x-19
\end{aligned}
$$

$f^{\prime}(x)=3>0$

$\therefore f(x)$ is an increasing function at $x \in(7, \infty)$.

69. (b) Let the curve and the normal intersect at point $\left(x_{1}, y_{1}\right)$

$$
x_{1} y_{1}=1 \text { and } a x_{1}+b y_{1}+c=0
$$

Differentiating $x y=1$ w.r.t. ' $x$ ',

$$
x \frac{d y}{d x}+y=0
$$

[only use $x_{1}=4$ ]

$\left.\Rightarrow \frac{d y}{d x}\right|_{\left(x_{1}, y_{1}\right)}=\frac{-y_{1}}{x_{1}}$ $\Rightarrow-\left.\frac{d x}{d y}\right|_{\left(x_{1}, y_{1}\right)}=\frac{x_{1}}{y_{1}}$

Equation of normal is

$$
y-y_{1}=\frac{x_{1}}{y_{1}}\left(x-x_{1}\right)
$$

$\Rightarrow y y_{1}-y_{1}^{2}=x x_{1}-x_{1}^{2} \Rightarrow x x_{1}-y y_{1}=x_{1}^{2}-y_{1}^{2}$ The product of $x_{1} y_{1}$ is positive,

$x_{1} y_{1}$ are of same sign.

$\Rightarrow a$ and $b$ are of opposite sign.

From options, we can conclude that $a>0, b<0$.

70. (d) Let $I=\int \frac{d x}{1+a \cos x}$

$$
=\int \frac{1}{1+a\left(\frac{1-\tan ^{2} \frac{x}{2}}{1+\tan ^{2} \frac{x}{2}}\right)} d x
$$

$$
\begin{aligned}
& =\int \frac{\sec ^{2} x / 2 d x}{1+\tan ^{2} x / 2+a\left(1-\tan ^{2} x / 2\right)} \\
& =\int \frac{\sec ^{2} x / 2 d x}{(1+a)-\tan ^{2} \frac{x}{2}(a-1)} \\
& =\frac{1}{(a+1)} \int \frac{\sec ^{2} x / 2}{1-\left(\frac{a-1}{a+1}\right) \tan ^{2} \frac{x}{2}} d x
\end{aligned}
$$

Let $\sqrt{\frac{a-1}{a+1}} \tan \frac{x}{2}=t$

$\Rightarrow \sqrt{\frac{a-1}{a+1}} \times \frac{1}{2} \times \sec ^{2} \frac{x}{2} d x=d t$

$\Rightarrow \sec ^{2} \frac{x}{2} d x=2 \sqrt{\frac{a+1}{a-1}} d t$

$I=\frac{2}{(a+1)} \sqrt{\frac{a+1}{a-1}} \int \frac{1}{1-t^{2}} d t$

$I=\frac{2}{\sqrt{a^{2}-1}} \times \frac{1}{2} \log \left|\frac{1+t}{1-t}\right|+C$

$=\frac{1}{\sqrt{a^{2}-1}} \log \left|\frac{1+\sqrt{\frac{a-1}{a+1}} \tan \frac{x}{2}}{1-\sqrt{\frac{a-1}{a+1}} \tan \frac{x}{2}}\right|$

$=\frac{1}{\sqrt{a^{2}-1}}$

$\log \left|\frac{\sqrt{a+1} \cos x / 2+\sqrt{a-1} \sin x / 2}{\sqrt{a+1} \cos x / 2-\sqrt{a-1} \sin \frac{x}{2}}\right|+c$ 

\section{AP EAPCET (Engineering) Solved Papers 155}

71. (d) Let $I=\int \frac{x^{2}-2}{x^{3} \sqrt{x^{2}-1}} d x=\int \frac{\left(x^{2}-2\right) x d x}{x^{4} \sqrt{x^{2}-1}}$

Let $x^{2}-1=t^{2}$

$\Rightarrow \quad x d x=t d t$

$I=\int \frac{\left(t^{2}-1\right) t d t}{\left(t^{2}+1\right)^{2} t}=\int \frac{t^{2}-1}{\left(t^{2}+1\right)^{2}} d t=\int \frac{\left(1-\frac{1}{t^{2}}\right)}{\left(t+\frac{1}{t}\right)^{2}} d t$

Let $t+\frac{1}{t}=u$

$\Rightarrow \quad\left(1-\frac{1}{t^{2}}\right) d t=d u$

$\therefore \quad I=\int \frac{1}{u^{2}} d u=-\frac{1}{u}+C$

$=-\left(\frac{t}{t^{2}+1}\right)+C=-\frac{\sqrt{x^{2}-1}}{x^{2}}+C$

72. (a) Let $I=f(x)-g(x)$

$=\int \frac{e^{3 x} d x}{4+8 e^{2 x}+e^{4 x}}-\int \frac{2}{e^{3 x}+8 e^{x}+4 e^{-x}} d x$

$=\int \frac{e^{3 x} d x}{4+8 e^{2 x}+e^{4 x}}-\int \frac{2 e^{x}}{e^{4 x}+8 e^{2 x}+4} d x$

$=\int\left(\frac{e^{3 x}-2 e^{x}}{e^{4 x}+8 e^{2 x}+4}\right) d x=\int \frac{e^{x}\left(e^{2 x}-2\right)}{e^{4 x}+8 e^{2 x}+4} d x$

Let $e^{x}=t$, then $e^{x} d x=d t$

$\doteq \int \frac{t^{2}-2}{t^{4}+8 t^{2}+4} d t=\int\left(\frac{1-\frac{2}{t^{2}}}{t^{2}+8+\frac{4}{t^{2}}}\right) \cdot d t$

$=\int \frac{\left(1-\frac{2}{t^{2}}\right)}{\left(t^{2}+\frac{4}{t^{2}}+4\right)+4} d t=\int \frac{\left(1-\frac{2}{t^{2}}\right) d t}{\left(t+\frac{2}{t}\right)^{2}+(2)^{2}}$

Let $t+\frac{2}{t}=u$

$\Rightarrow\left(1-\frac{2}{t^{2}}\right) d t=d u$

$I=\int \frac{1}{u^{2}+2^{2}} d u=\frac{1}{2} \tan ^{-1}\left(\frac{u}{2}\right)=\frac{1}{2} \tan ^{-1}\left(\frac{t^{2}+2}{2 t}\right)$

$=\frac{1}{2} \tan ^{-1}\left[\frac{e^{2 x}+2}{2 e^{x}}\right)$

$=\frac{1}{2} \tan ^{-1}\left(\frac{e^{\dot{x}}+2 e^{-x}}{2}\right)+C$

73. (a) Let $\frac{a t+b}{c t+d}=x$ in the function $f\left(\frac{a t+b}{c t+d}\right)=t$ $a t+b=c t x+d x$ $\Rightarrow \quad t(a-c x)=d x-b$

$\Rightarrow \quad t=\frac{d x-b}{a-c x}$

$\int f(x) d x=\int \frac{d x-b}{a-c x} d x=\int \frac{b-d x}{c x-a} d x$

$=b \int \frac{1}{c x-a} d x-\frac{d}{c} \int \frac{c x-a+a}{c x-a} d x$

$=\frac{b}{c} \log (c x-a)-\frac{d}{c} \int 1 d x-\frac{a d}{c} \int \frac{1 d x}{c x-a}$

$=\frac{b}{c} \log \left|(c x-a)-\frac{d x}{c}-\frac{a d}{c^{2}} \log \right| c x-a \mid$

$=\frac{-d x}{c}+\left(\frac{b c-a d}{c^{2}}\right) \log (c x-a)+K$

74. (d) $\int_{\sqrt{3}}^{\sqrt{18}}[x] d x=a+b \sqrt{2}+c \sqrt{3}$

As $\sqrt{3}=1.732$ and $\sqrt{18}=4 \cdot 24$

$\therefore \int_{\sqrt{3}}^{\sqrt{4}} 1 d x+\int_{\sqrt{4}}^{\sqrt{9}} 2 d x+\int_{\sqrt{9}}^{\sqrt{16}} 3 d x+\int_{\sqrt{16}}^{\sqrt{18}} 4 d x$

$=2-\sqrt{3}+2(3-2)+3(4-3)+4(\sqrt{18}-4)$

$=2-\sqrt{3}+2+3+4 \sqrt{18}-16$

$=-9+12 \sqrt{2}-\sqrt{3}$

$\therefore \quad a=-9, b=12, c=-1$

$a+b+c=-9+12-1=2$

75. ( $\left.{ }^{*}\right)$ Let $I=\int_{0}^{4} \frac{x+2}{\sqrt{4 x-x^{2}}} d x$

$$
=\int_{0}^{4} \frac{x+2}{\sqrt{4-(x-2)^{2}}} d x
$$

Let $x-2=t$

$\Rightarrow \quad d x=d t$

When $x \rightarrow 0, t \rightarrow-2$ and $x \rightarrow 4, t \rightarrow 2$.

$I=\int_{-2}^{2} \frac{t+4}{\sqrt{4-t^{2}}} d t$

$=\frac{-1}{2} \int_{-2}^{2} \frac{-2 t}{\sqrt{4-t^{2}}} d t+4 \int_{-2}^{2} \frac{1}{\sqrt{4-t^{2}}} d t$

$=-\left[\sqrt{4-t^{2}}\right]_{2}^{2}+4\left[\sin ^{-1} \frac{t}{2}\right]_{-2}^{2}$

$=0+4\left[\sin ^{-1} 1-\sin ^{-1}(-1)\right]$

$=0+4\left[\frac{\pi}{2}+\frac{\pi}{2}\right]=4 \pi$

76. (b) Let $I=\int_{-\pi}^{\pi} \frac{2 x(1+\sin x)}{1+\cos ^{2} x} d x$

$\int_{-\pi}^{\pi} \frac{2 x d x}{1+\cos ^{2} x}+\int_{-\pi}^{\pi} \frac{2 x \sin x d x}{1+\cos ^{2} x}$

As $\frac{2 x}{1+\cos ^{2} x}$ is an odd function. So, $\int_{-\pi}^{\pi} \frac{2 x}{1+\cos ^{2} x} d x=0$

As $\frac{2 x \sin x}{1+\cos ^{2} x}$ is an even function.

So, $\int_{-\pi}^{\pi} \frac{2 x \sin x}{1+\cos ^{2} x} d x=2 \int_{0}^{\pi} \frac{2 x \sin x}{1+\cos ^{2} x} d x$

$I=4 \int_{0}^{\pi} \frac{x \sin x}{1+\cos ^{2} x} d x$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-14.jpg?height=111&width=349&top_left_y=682&top_left_x=243)

$\Rightarrow \quad I=4 \int_{0}^{\pi} \frac{(\pi-x) \sin x}{1+\cos ^{2} x}$

On adding Eqs. (i) and (ii),

$$
2 I=4 \pi \int_{0}^{\pi} \frac{\sin x}{1+\cos ^{2} x} d x
$$

Let $\cos x=t$

$\Rightarrow-\sin x d x=d t$

When $x \rightarrow 0, t \rightarrow 1$ and $x \rightarrow \pi, t \rightarrow-1$

$$
\begin{aligned}
& I=-2 \pi \int_{1}^{-1} \frac{1}{1+t^{2}} d t \\
& I=2 \pi \int_{-1}^{1} \frac{1}{1+t^{2}} d t=2 \pi\left[\tan ^{-1} t\right]_{-1}^{1} \\
& =2 \pi\left[\tan ^{-1}(1)-\tan ^{-1}(-1)\right]=2 \pi\left[\frac{\pi}{4}+\frac{\pi}{4}\right] \\
& =\pi^{2}
\end{aligned}
$$

78. (a) $y=\mathrm{IF}$

$\Rightarrow \quad y=e^{\int P(x) d x} \Rightarrow \log y=\log e^{j P(x) d x}$

$\Rightarrow \quad \log y=\int P(x) d x$

... (ii) . On differentiating both sides,

$$
\begin{aligned}
& =2\left[\frac{x^{2}}{2}+3 x+9 \log (x-3)\right]_{0}^{1} \\
& =2\left[\frac{1}{2}+3+9 \log (-2)-9 \log (-3)\right] \\
& =2\left[\frac{7}{2}-9 \log \left(\frac{3}{2}\right)\right]=7-18 \log \frac{3}{2}+C
\end{aligned}
$$

$$
\begin{aligned}
& \frac{1}{y} \frac{d y}{d x}=P(x) \\
\Rightarrow & \frac{d y}{d x}=P(x) y \Rightarrow \frac{d y}{d x}-P(x) y=0
\end{aligned}
$$

79. (c) We have,

$\begin{aligned} & \frac{d y}{d x}=\frac{y-4}{x-3} \\ \Rightarrow & \int \frac{1}{y-4} d y=\int \frac{1}{x-3} d x \\ \Rightarrow & \log (y-4)=\log (x-3)+\log C \\ \Rightarrow & y-4=C(x-3) \Rightarrow y=C(x-3)+4\end{aligned}$

The curve passes through $(4,3)$

$\begin{aligned} & 3=C(4-3)+4 \\ \Rightarrow \quad & C=-1 \\ \Rightarrow \quad & y=3-x+4 \\ \Rightarrow \quad & y=7-x\end{aligned}$

Substitute $y=x$ inequation $y=7-x$

$$
=\int_{-1}^{1} \frac{\sin x}{3-|x|} d x-\int_{-1}^{1} \frac{x^{2}}{3-|x|} d x
$$

As $\frac{\sin x}{3-|x|}$ is an odd function:

$\therefore \int_{-1}^{1} \frac{\sin x}{3-|x|} d x=0$

As $\frac{x^{2}}{3-|x|}$ is an even function,

$\int_{-1}^{1} \frac{x^{2}}{3-|x|} d x=2 \int_{0}^{1} \frac{x^{2}}{3-|x|} d x$

$I=-2 \int_{0}^{1} \frac{x^{2}}{3-x}$

$=2 \int_{0}^{1} \frac{x^{2}-3 x+3 x-9+9}{x-3} d x$

$=2 \int_{0}^{1}\left(x+3+\frac{9}{x-3}\right) d x$

$$
\begin{aligned}
& x=7-x \\
& \Rightarrow \quad 2 x=7
\end{aligned}
$$

$\Rightarrow \quad x=7 / 2$

The intersecting point of curve and line is $\left(\frac{7}{2}, \frac{7}{2}\right)$.

80. (c) Given, $\frac{d y}{d x}+P(x) y=Q(x)$

Multiplying $e^{\int P d x}$ on both sides,

$\Rightarrow \frac{d}{d x}\left[y \times e^{\int P d x}\right]=Q(x) \times e^{\int P d x}$

On comparing with left side of the equation takes the form $\frac{d}{d x}(y f(x))$,

$\therefore f(x)=e^{\int P d x}$

$$
\frac{d y}{d x} \times e^{\int P d x}+P(x) \cdot e^{\int P d x} \cdot y \doteq Q(x) \times e^{\int P d x}
$$



\section{Physics}

81. (a) Dimensional formula of energy,

$$
[\text { Energy }]=\left[\mathrm{ML}^{2} \mathrm{~T}^{-2}\right]
$$

Dimensional formula of speed,

$$
[\text { speed }]=\left[\mathrm{LT}^{-1}\right]
$$

Dimensional formula of

Energy $\times$ speed $=[$ Energy $][$ speed $]$

$$
=\left[\mathrm{ML}^{2} \mathrm{~T}^{-2}\right]\left[\mathrm{LT}^{-1}\right]
$$

$$
\begin{aligned}
& =\left[M^{1} L^{3} T^{-3}\right] \\
& =\left[\mathrm{M}^{a} \mathrm{~L}^{b} \mathrm{~T}\right]
\end{aligned}
$$

(given)

$$
\therefore \quad a=1, b=3, c=-3
$$

82. (a) Ball dropped from height $h$ takes $t$ second to reach on the surface of earth. Hence,

i.e

$$
\begin{aligned}
h & =0 \times t+\frac{1}{2} g t^{2} \\
t & =\sqrt{\frac{2 h}{g}}
\end{aligned}
$$

For another planet, mass $M_{p}=100 M_{e}$ where, $M_{e}$ is mass of the earth:

Radius of planet, $R_{p}=10 R_{e}$ where, $R_{e}$ is the radius of earth.

The value of gravitational acceleration on the surface of planet,

$$
\begin{aligned}
g_{p}=\frac{G M_{p}}{R_{p}^{2}} & =\frac{G \times 100 M_{e}}{\left(10 R_{c}\right)^{2}} \\
& =\frac{G M_{e}}{R_{e}^{2}}=g
\end{aligned}
$$

Since, the value of gravitational acceleration is same for other planet, hence time taken to cover same height on the planet is same as $t$ seconds.

83. (a) Unit vector $\hat{\mathbf{n}}_{1}$ parallel to vector $5 \hat{i}+12 \hat{j}$ is given as

$$
\begin{aligned}
\hat{\mathbf{n}}_{1} & =\frac{5 \hat{i}+12 \hat{j}}{\sqrt{5^{2}+12^{2}}}=\frac{5 \hat{i}+12 \hat{j}}{13} \\
& =\frac{5}{13} \hat{i}+\frac{12}{13} \hat{j}
\end{aligned}
$$

Similarly, unit vector $\hat{\mathbf{n}}_{2}$ parallel to vector $3 \hat{i}+4 \hat{j}$ is given as

$$
\begin{aligned}
\hat{\mathbf{n}}_{2,} & =\frac{3 \hat{i}+4 \hat{j}}{\sqrt{3^{2}+4^{2}}} \\
\hat{\mathbf{n}}_{2} & =\frac{3}{5} \hat{i}+\frac{4}{5} \hat{j} \\
\hat{\mathbf{n}}_{1} \cdot \hat{\mathbf{n}}_{2} & =\left(\frac{5}{13} \hat{i}+\frac{12}{13} \hat{j}\right)\left(\frac{3}{5} \hat{i}+\frac{4}{5} \hat{j}\right)
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{5}{13} \times \frac{3}{5}+\frac{12}{13} \times \frac{4}{5}=\frac{15}{65}+\frac{48}{65} \\
& =\frac{63}{65}
\end{aligned}
$$

84. (d) The given situation is shown in the figure

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-15.jpg?height=372&width=488&top_left_y=642&top_left_x=1155)

$$
\begin{aligned}
E F & =E B-F B \\
& =E B-G A \\
& =8.75-3.75=5 \mathrm{~m}
\end{aligned}
$$

$\therefore$ In $\triangle E F G$

$$
\tan 30^{\circ}=\frac{E F}{G F}
$$

$$
\begin{aligned}
& \Rightarrow \quad \frac{1}{\sqrt{3}}=\frac{5}{G F} \\
& \Rightarrow \quad G F=5 \sqrt{3} \mathrm{~m}
\end{aligned}
$$

Total time taken by the sphere to reach the ground is $t$, then

$$
\begin{aligned}
& h=\frac{1}{2} g t^{2} \\
& 8.75=\frac{1}{2} \times 10 \times t^{2} \Rightarrow \frac{17.50}{10}=t^{2}
\end{aligned}
$$

$\Rightarrow \quad t^{2}=1.75$

$\Rightarrow \quad t=\sqrt{1.75} \mathrm{~s}=1.32 \mathrm{~s}$

If $t_{1}$ be the time taken to cover a distance of $E F$, then, $\quad 5=\frac{1}{2} g t_{1}^{2}$

$\Rightarrow \quad t_{1}=1 \mathrm{~s}$

Time taken to cover distance $F B$

$$
t^{\prime}=t-t_{1}=1.32-1=0.32 \mathrm{~s}
$$

If $v$ be the velocity of sphere at point $G$, then gravitational potential energy at point $E$ $=$ Gravitational potential energy at point $G$

$$
m g h+\frac{1}{2} I \omega^{2}+\frac{1}{2} m v^{2}
$$

$m g \times 8.75=m g \times 3.75+\frac{1}{2} \cdot \frac{2}{5} m R^{2}\left(\frac{v}{R}\right)^{2}+\frac{1}{2} m v^{2}$

$\Rightarrow 8.75 g=3.75 g+\frac{1}{5} \times v^{2}+\frac{1}{2} v^{2}$ $\Rightarrow \quad 5 g=\frac{7}{10} v^{2}$

$\Rightarrow \quad v=\sqrt{\frac{5 g \times 10}{7}}=\sqrt{\frac{5 \times 10 \times 10}{7}}=10 \sqrt{\frac{5}{7}} \mathrm{~m} / \mathrm{s}$

Horizontal component of velocity at point $G$,

$$
v_{x}^{\prime}=v \cos 30^{\circ}
$$

$$
=10 \sqrt{\frac{5}{7}} \cos 30^{\circ}=10 \sqrt{\frac{5}{7}} \times \frac{\sqrt{3}}{2}=5 \sqrt{\frac{15}{7}} \mathrm{~m} / \mathrm{s}
$$

Range, $O A=v_{x}^{\prime} \times t^{\prime}$

$$
=5 \times \sqrt{\frac{15}{7}} \times 0.32=1.5 \sqrt{\frac{15}{7}} \mathrm{~m}
$$

$\therefore \quad O B=A B+O A$

$$
\begin{aligned}
& =G F+O A \\
& =\left(5 \sqrt{3}+1.5 \sqrt{\frac{15}{7}}\right) \mathrm{m} \\
& =101 \mathrm{~m} \simeq 10 \mathrm{~m}
\end{aligned}
$$

85. (b) The given situation is shown below

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-16.jpg?height=445&width=445&top_left_y=1165&top_left_x=337)

Let us draw the free body diagram for the small body of mass $m$. Let block breaks off the plane at $t=t_{0}$, i.e at $t=t_{0}$, normal reaction $(R)$ will become zero.

i.e.

$$
R=0
$$

$\Rightarrow \quad m g-F \sin \theta=0$

$\Rightarrow \quad m g-a t_{0} \sin \theta=0$

$\Rightarrow \quad t_{0}=\frac{m g}{a \sin \theta}$

From the figure,

$$
\begin{aligned}
& m a_{x}=F_{x} \\
& m \frac{d v}{d t}=F \cos \theta=a t \cos \theta
\end{aligned}
$$

$\Rightarrow \quad m d v=a t \cos \theta d t$

Integrating both sides, we have

$$
m \int_{0}^{v} d v_{x}=a \cos \theta \int_{0}^{t_{0}} t d t
$$

$\Rightarrow \quad m v=\frac{a t_{0}^{2} \cos \theta}{2}$

$\Rightarrow \quad v=\frac{a t_{0}^{2} \cos \theta}{2 m}$ From Eqs. (i) and (ii), we get

$$
\Rightarrow \quad v=a \frac{\left(\frac{m g}{a \sin \theta}\right)^{2} \cos \theta}{2 m} \Rightarrow v=\frac{m g^{2} \cos \theta}{2 a \sin ^{2} \theta}
$$

$$
\text { Putting } \begin{aligned}
m & =1 \mathrm{~kg} \\
a & =1 \mathrm{~ms}^{-2} \\
\theta & =45^{\circ} \\
v & =\frac{\left(110^{2}\right) \cos 45^{\circ}}{2 \times l \times \sin ^{2} 45^{\circ}}=50 \sqrt{2} \mathrm{~ms}^{-1}
\end{aligned}
$$

86. (b) The given situation is shown below.

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-16.jpg?height=428&width=509&top_left_y=814&top_left_x=1256)

From the diagram, it is clear that acceleration in the block is only due to force $m g \sin 30^{\circ}$.

i.e. Acceleration, $a=\frac{m g \sin 30^{\circ}}{m}$

$$
\begin{aligned}
& =g \sin 30^{\circ}=9.8 \times \frac{1}{2} \\
& =4.9 \mathrm{~ms}^{-2}
\end{aligned}
$$

87. (b) Given; $\mathbf{F}=4 \hat{i}-15 \hat{j} \mathrm{~N}$

Displacement, $s=6 \hat{i}$

Initial kinetic energy, $K_{i}=7 \mathrm{~J}$

Work done, $\mathbf{W}=\mathbf{F} \cdot \mathbf{s}$

$$
=(4 \hat{i}-15 \hat{j}) \cdot 6 \hat{i}=24 \mathrm{~J}
$$

if $K$, be the final kinetic energy i.e at the end of the displacement, then according to work-energy theorem,

$\mathrm{W}=K_{f}-K_{i}$

$\Rightarrow \quad 24=K_{f}-7$

$\Rightarrow \quad K_{f}=24+7=31 \mathrm{~J}$

88. (d) Given, $F=k x^{3}, k=2 \mathrm{Nm}^{-3}$

Work done,

$$
\begin{aligned}
W & =\int_{0}^{2} F \cdot d x=\int_{0}^{2} k x^{3} d x \\
& =k\left[\frac{x^{4}}{4}\right]_{0}^{2}=k \times\left[\frac{2^{4}}{4}-0\right] \\
& =k\left(\frac{16}{4}\right)=4 k=4 \times 2=8 \mathrm{~J}
\end{aligned}
$$

89. (b) Centre of mass of a homogeneous semi- circular plate of radius $r$ is given as

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-17.jpg?height=209&width=399&top_left_y=433&top_left_x=295)

$$
y_{\mathrm{CM}}=\frac{2 r}{3}
$$

90. (c) Given, moment of inertia of the wheel

$$
\begin{aligned}
I & =0.2 \mathrm{~kg}-\mathrm{m}^{2} \\
\Delta t & =4 \mathrm{~s}
\end{aligned}
$$

Average power of the wheel,

$$
\begin{aligned}
P & =\tau \times \Delta \omega \\
& =\frac{\Delta L}{\Delta t} \times \Delta \omega \\
& =\frac{4-2}{4} \times \Delta \omega
\end{aligned}
$$

$\Rightarrow \quad P=\frac{\Delta \omega}{2}$

We know that, $L=I \omega$

$$
\Delta L=I \Delta \omega
$$

$\Rightarrow \quad \Delta \omega=\frac{\Delta L}{I}=\frac{4-2}{0.2}=\frac{2}{0.2}$

$\Rightarrow \quad \Delta \omega=10$

From Eq (i), we get

$$
P=\frac{10}{2}=5 \mathrm{~W}
$$

91. (c) Initial frequency of oscillating pendulum,

$$
f_{1}=8 \mathrm{~Hz}
$$

We know that, frequency of oscillation of pendulum

$$
f=\frac{1}{T}=\frac{1}{2 \pi} \sqrt{\frac{g}{l}} \Rightarrow f \propto \frac{1}{\sqrt{l}}
$$

$\Rightarrow \quad \frac{f_{2}}{f_{1}}=\sqrt{\frac{l_{1}}{l_{2}}}$

When the pendulum is clamped at its mid-point, then its length becomes half of initial length.

i.e

$$
l_{2}=\frac{l}{2}
$$

From Eq. (i), we get

$$
\frac{f_{2}}{f_{1}}=\sqrt{\frac{l_{1}}{l_{1}}}=\sqrt{2}
$$

$\Rightarrow$

$$
\begin{aligned}
f_{2} & =\sqrt{2} f_{1}=\sqrt{2} \times 8 \\
& =11.31 \mathrm{~Hz} \\
& \simeq 11.28 \mathrm{~Hz}
\end{aligned}
$$

92. (a) Time period of simple pendulum,

$$
\begin{aligned}
T & =4 \mathrm{~s} \\
g & =\pi^{2} \mathrm{~ms}^{-2}
\end{aligned}
$$

Length of the pendulum, $l=$ ?

We know that,

$$
T=2 \pi \sqrt{\frac{l}{g}}
$$

$\Rightarrow \quad T^{2}=4 \pi^{2} \frac{l}{g} \Rightarrow 4^{2}=4 \pi^{2} \times \frac{l}{\pi^{2}}$

$\Rightarrow \quad l=4 \mathrm{~m}$

93. (d) Given, $T_{A}=8 T_{B}$

If $R_{A}$ and $R_{B}$ are the radii of planets $A$ and $B$ respectively, then according to Kepler's law

$$
\begin{array}{ll} 
& \frac{T_{A}}{T_{B}}=\left(\frac{R_{A}}{R_{B}}\right)^{3 / 2} \\
\Rightarrow \quad & \frac{8 T_{B}}{T_{B}}=\left(\frac{R_{A}}{R_{B}}\right)^{3 / 2} \Rightarrow 8=\left(\frac{R_{A}}{R_{B}}\right)^{3 / 2} \\
\Rightarrow & 2^{3}=\left(\frac{R_{A}}{R_{B}}\right)^{3 / 2} \Rightarrow 2=\left(\frac{R_{A}}{R_{B}}\right)^{1 / 2} \\
\Rightarrow \quad & \frac{R_{A}}{R_{B}}=4
\end{array}
$$

Orbital velocity of planet, $v=\sqrt{\frac{G m}{R}}$

$\Rightarrow \quad v \propto \frac{1}{\sqrt{R}} \Rightarrow \frac{v_{A}}{v_{B}}=\sqrt{\frac{R_{B}}{R_{A}}}$.

$$
=\sqrt{\frac{1}{4}}
$$

[From Eq. (i)]

$$
=\frac{1}{2}
$$

$\Rightarrow \quad v_{A}: v_{B}=1: 2$

94. (c) Given, length of copper wire, $l_{\mathrm{cu}}=2.4 \mathrm{~m}$

Length of aluminium wire, $l_{\mathrm{Al}}=0.7 \mathrm{~m}$ diameter of both wire, $d_{\mathrm{cu}}=d_{\mathrm{Al}}=3 \mathrm{~mm}$ Radius, $r_{\mathrm{cu}}=r_{\mathrm{Al}}=\frac{3}{2} \mathrm{~mm}=1.5 \mathrm{~mm}=1.5 \times 10^{-3}$ Elongation in length, $\Delta l=0.6 \mathrm{~mm}$

$$
=6 \times 10^{-4} \mathrm{~m}
$$

Let $F$ be load applied, then for copper wire,

$$
\begin{aligned}
Y_{1} & =\frac{F}{\pi r_{\mathrm{cu}}^{2}} \times \frac{l_{\mathrm{cu}}}{\Delta l_{\mathrm{cu}}} \\
F & =\frac{Y_{1} \pi r_{\mathrm{cu}}^{2} \times \Delta l_{\mathrm{cu}}}{l_{\mathrm{cu}}} \\
& =\frac{1.1 \times 10^{11} \times \pi \times\left(1.5 \times 10^{-3}\right)^{2} \times 6 \times 10^{-4}}{2.4}=20 \pi \mathrm{N}
\end{aligned}
$$

95. (a) Surface area of big liquid drop of radius $R$,

$$
A_{1}=4 \pi R^{2}
$$

Surface area of small liquid drop of radius $r$,

$$
a_{2}=4 \pi r^{2}
$$

Total surface area of $\mathbf{n}$ small liquid drops of radius $R$,

$$
A_{2}=n a_{2}=n .4 \pi r^{2}
$$

Required energy $=T \times \Delta A$

$$
=T\left(A_{2}-A_{1}\right)=T\left(4 \pi r^{2} n-4 \pi R^{2}\right)
$$

96. (b) Given, mass of object, $m=10 \mathrm{~kg}$

distance travelled by object, $s=2 \mathrm{~m}$

Time, $t=1 \mathrm{~s}$

According to given situation,

$$
s=u t+\frac{1}{2} a t^{2}
$$

$\Rightarrow \quad s=0+\frac{1}{2} a t^{2}$

$[\therefore u=0]$

$$
s=\frac{1}{2} a t^{2}
$$

$\Rightarrow \quad 2=\frac{1}{2} \times a \times 1^{2}$

$$
a=4 \mathrm{~ms}^{-2} \text {. }
$$

Net force on the object in liquid,

$$
F_{\text {net }}=m a=10 \times 4=40 \mathrm{~N}
$$

Weight of the object,

$$
\begin{aligned}
w & =m g \\
& =10 \times 10=100 \mathrm{~N}
\end{aligned}
$$

Upthrust force on the object,

$$
F^{\prime}=w-F_{\text {net }}=100-40=60 \mathrm{~N}
$$

According to Archimedes' principle,

Weight liquid displaced = Upthrust force

$$
m^{\prime} g=F^{\prime}
$$

$\Rightarrow \quad m^{\prime}=\frac{F^{\prime}}{g}=\frac{60}{10}=6 \mathrm{~kg}$

97. (a) Given, $s_{\text {ice }}=2100 \mathrm{~J} \mathrm{~kg}^{-1} \mathrm{~K}^{-1}$

$$
s_{\text {water }}=4186 \mathrm{~J} \mathrm{~kg}^{-1} \mathrm{~K}^{-1}
$$

Latent heat of fusion of ice,

$$
L_{\text {kce }}=3.35 \times 10^{5} \mathrm{Jkg}^{-1}
$$

Mass of ice, $m=200 \mathrm{~g}=0.2 \mathrm{~kg}$

Temperature of ice, $T_{1}=-10^{\circ} \mathrm{C}$

Final temperature of water, $T_{2}=30^{\circ} \mathrm{C}$

Total required heat,

$Q=m s_{\text {ice }}\left(0-T_{1}\right)+m L_{\text {ice }}+m s_{\text {water }}\left(T_{2}-0\right)$

$$
=0.2 \times 2100[0-(-10)]+0.2 \times 3.35 \times 10^{5}
$$

$+0.2 \times 4186(30-0)$

$$
\begin{aligned}
& =0.2 \times 2100 \times 10+0.2 \times 3.35 \times 10^{5}+0.2 \times 4186 \times 30 \\
& =9.6316 \times 10^{4} \mathrm{~J} \\
& =96316 \mathrm{~J}
\end{aligned}
$$

98. (a) For Carnot engine,

$T_{1}=600 \mathrm{~K}, T_{2}=300 \mathrm{~K}$

Heat absorbed, $Q=800 \mathrm{~J}$

If $W$ be the mechanical work done by Carnot engine, then using the formula,

$$
\eta=\frac{W}{Q}=1-\frac{T_{2}}{T_{1}}
$$

$\Rightarrow \quad \frac{W}{Q}=1-\frac{T_{2}}{T_{1}} \Rightarrow \frac{W}{800}=1-\frac{300}{600}$

$\Rightarrow \quad \frac{W}{800}=\left(1-\frac{1}{2}\right) \Rightarrow \frac{W}{800}=\frac{1}{2}$

$$
W=\frac{800}{2}=400 \mathrm{~J}
$$

99. (c) According to Newton's law of cooling,

$$
m c\left(\frac{T_{1}-U_{1}}{t}\right)=K\left(\frac{T_{1}+T_{2}}{2}-T_{0}\right)
$$

For the first condition,

$$
m c\left(\frac{75-65}{10}\right)=K\left(\frac{75+65}{2}-T_{0}\right)
$$

$\Rightarrow \quad m c\left(\frac{10}{10}\right)=K\left(70-T_{0}\right)$

$\Rightarrow \quad \quad m c=K\left(70-T_{0}\right)$

According to second condition,

$$
m c\left(\frac{65-55}{t^{\prime}}\right)=K\left(\frac{65+55}{2}-T_{0}\right)
$$

$\Rightarrow \quad m c\left(\frac{10}{t^{\prime}}\right)=K\left(60-T_{0}\right)$

Dividing Eq. (i) by Eq: (ii), we get

$$
\frac{1}{\frac{10}{t^{\prime}}}=\frac{70-T_{0}}{.60-T_{0}}
$$

$\Rightarrow \quad \frac{t^{\prime}}{10}=\frac{70-T_{0}}{60-T_{0}} \Rightarrow t^{\prime}=10\left(\frac{70-T_{0}}{60-T_{0}}\right)$

clearly, $\Rightarrow \frac{70-T_{0}}{60-T_{0}}>1$

$\therefore t^{\prime}>10$ minutes.

100. (b) Given $\left(v_{\mathrm{rms}}\right)_{0_{2}}=500 \mathrm{~m} / \mathrm{s}$

$$
\left(v_{\mathrm{rms}}\right)_{\mathrm{H}_{2}}=\text { ? }
$$

We know that,

$$
v_{\mathrm{ms}}=\sqrt{\frac{3 R T}{M}}
$$

$\Rightarrow \quad v_{\mathrm{ms}} \propto \frac{1}{\sqrt{M}}$

$\Rightarrow \quad \frac{\left(v_{\mathrm{ms}}\right)_{\mathrm{H}_{2}}}{\left(v_{\mathrm{ms}} \mathrm{o}_{2}\right.}=\sqrt{\frac{M_{\mathrm{O}_{2}}}{M_{\mathrm{H}_{2}}}}$

$\Rightarrow \quad \frac{\left(V_{\mathrm{ms}}\right)_{\mathrm{H}_{2}}}{500}=\sqrt{\frac{32}{2}}$

$$
=\sqrt{16}=4
$$

$\Rightarrow \quad\left(v_{\mathrm{ms}}\right)_{\mathrm{H}_{2}}=4 \times 500=2000 \mathrm{~ms}^{-1}$

101. (c) A wave which travels continuously in a medium in the same direction without the change in its amplitude is called a progressive wave. Equation of progressive wave is given as $y(x, t)=A \sin (\omega t-k x+\phi)$

We can write the above equation as a linear combination of sine and cosine function as, $y(x, t)=A \sin (k x-\omega t)+B \cos (k x-\omega t)$

Hence, among the given options

$y=3 \sin (5 x-0.5 t)+4 \cos (5 x-0.5 t)$

represents the equation of progressive wave.

102. (a) Given, refractive index of glass, $\mu=1.4$

When the light beam incident of polarising angle i.e at $i=i_{p}$, then refracted and reflected rays are perpendicular to each other.

Hence, according to Brewster's law

$\therefore \quad \mu=\tan i_{p}$

$\Rightarrow \quad i_{p}=\tan ^{-1}(\mu)=\tan ^{-1}(1.4)$

$\therefore$ Angle of incidence

$$
i=i_{p}=\tan ^{-1}(1.4)
$$

103. (d) The given situation is shown below

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-19.jpg?height=399&width=434&top_left_y=1828&top_left_x=317)

According to Snell's law,

$2 \mu_{1}=\frac{\sin 30^{\circ}}{\sin r}$

$\Rightarrow \quad \frac{\mu_{1}}{\mu_{2}}=\frac{1 / 2}{\sin r}$

$\Rightarrow \quad \frac{1}{2}=\frac{1}{2 \sin r}$

$\Rightarrow \quad \sin r=1^{\circ}=\sin 90^{\circ}$

$\Rightarrow \quad r=90^{\circ}$ 104. (a) Let $Q$ be divided into two charges $q$ and $Q-q$ i.e $q_{1}=q$ and $q_{2}=Q-q$

$\therefore$ Electrostatic force between $q$ and $Q-q$ is given as

$$
F=\frac{1}{4 \pi \varepsilon_{0}} \cdot \frac{q(Q-q)}{r^{2}}
$$

$F$ will be maximum if

$$
\frac{d F}{d q}=0
$$

$\Rightarrow \quad \frac{d}{d q} \cdot\left[\frac{q(Q-q)}{r^{2}}\right]=0$

$\Rightarrow \quad q(0-1)+(Q-q) \cdot 1=0$

$\Rightarrow \quad Q-2 q=0$

$\Rightarrow \quad q=\frac{Q}{2}$

Hence, $q_{1}=q=\frac{Q}{2}$

$$
q_{2}=Q-q=Q-\frac{Q}{2}=\frac{Q}{2}
$$

105. (c) From the given situation,

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-19.jpg?height=368&width=357&top_left_y=1352&top_left_x=1226)

$$
\begin{aligned}
V_{A}-V_{0} & =-\iint_{0}^{10} E d x d y \\
0-V_{0} & \left.=-\int_{0}^{10} \int_{0}^{20} A x \hat{i}+A y \hat{j}\right) d x d y \\
\Rightarrow \quad-V_{0} & =-\int_{0}^{10} \int_{0}^{20} A x \hat{i} d x \hat{i}+A y \hat{j} d y \hat{j} \\
V_{0} & =-\int_{0}^{10} \int_{0}^{20} A x d x+A y d y \\
& =\int_{0}^{10} A x d x+\int_{0}^{20} A y d y \\
& =\left[A \frac{x^{2}}{2}\right]_{0}^{10}+\left[\frac{A y^{2}}{2}\right]_{0}^{20} \\
& =A \frac{10^{2}}{2}+A \frac{20^{2}}{2}=50 A+200 A \\
& \left.=250 A=250 \times 10 \quad \quad \because A=10 \mathrm{Vm}^{-2}\right] \\
& =2500 \mathrm{~V}
\end{aligned}
$$

106. (a) Electric potential,

$$
\phi(x, y, z)=\phi_{1} \frac{x_{0}}{x}
$$

where, $x_{0}=5 \mathrm{~m}, \phi_{1}=8 \mathrm{~V}$ Electric field is given as

$$
\begin{aligned}
\mathbf{E} & =\frac{-d V}{d x} \hat{i}-\frac{d V}{d x} \hat{j}-\frac{d V}{d x} \hat{k} \\
& =-\frac{d V}{d x} \hat{i} \\
& =-\frac{d}{d x} \phi \hat{i} \\
& =\frac{-d}{d x} \phi_{0} \frac{x_{0}}{x} \hat{i}=\frac{\phi_{0} x_{0}}{x^{2}} \hat{i}
\end{aligned}
$$

$$
\begin{aligned}
& (\because V=\phi)
\end{aligned}
$$

At point $(10 \mathrm{~m}, 5 \mathrm{~m}, 5 \mathrm{~m})$

$$
\mathrm{E}=\frac{\phi_{0} x_{0}}{10^{2}} \hat{i}=\frac{8 \times 5}{100} \hat{i}=0.4 \hat{i} \mathrm{Vm}^{-1}
$$

107. (b) If the resistor connected to a battery is heated due to current flowing through it, then resistivity and resistance of conductor increases. But due to increasing temperature, relaxation time of electron decreases and hence drift velocity of electrons decreases. Number of free electrons in the conductor does not depend on the temperature for a given current $i$.e. number of free electrons remains unchanged when a resistor connected to a battery is heated due to the current flowing through it.

108. (b) Given, $V=12 \mathrm{~V}$.

$$
\begin{aligned}
& q=80 \mathrm{Ah}=80 \times 60 \times 60 \mathrm{As} \\
& P=120 \mathrm{~W} .
\end{aligned}
$$

We know delivered energy,

$E=W=V q$

$\Rightarrow \quad E=12 \times 80 \times 60 \times 60 \mathrm{~J}$

We know that,

$$
P=\frac{W}{t}
$$

$\Rightarrow \quad t=\frac{W}{P}=\frac{E}{P}$

$(\because W=E)$

$$
\begin{aligned}
& =\frac{12 \times 80 \times 60 \times 60}{120} \\
& =8 \times 60 \times 60 \mathrm{~s}=8 \mathrm{~h}
\end{aligned}
$$

109. (c) Since, plane of current carrying loop is perpendicular to the direction of magnétic field. Hence, each arm of isosceles triangle is parallel to the direction of magnetic field i.e $\theta=0$

$\therefore \quad F=I B L \sin 0^{\circ}=0$

There, force on each arm triangle is zero. Hence, net force on the loop in magnetic field is zero.

110. (c) We know that, radius $(r)$ of circular path of a charged particle in magnctic field (B);

$$
r=\frac{m v}{B q}=\frac{p}{B q}
$$

$$
\begin{aligned}
& =\frac{\sqrt{2 m E}}{B q} \quad(\because p=\sqrt{2 m E}) \\
\Rightarrow \quad r & \propto \sqrt{E} \Rightarrow \frac{r_{2}}{r_{1}}=\sqrt{\frac{E_{2}}{E_{1}}} \\
& =\sqrt{\frac{\frac{E_{1}}{2}}{E_{1}}} \quad\left(\because E_{2}=\frac{E_{1}}{2}\right) \\
& =\frac{1}{\sqrt{2}} \\
\Rightarrow \quad r_{2} & =\frac{r_{1}}{\sqrt{2}} .
\end{aligned}
$$

111. (a) Given, magnetic field, $B=28.3 \times 10^{-3} \mathrm{~T}$ Torque, $\tau=3.6 \times 10^{-5} \mathrm{~J}$

Magnet moment, $M=$ ?

$$
\theta=45^{\circ}
$$

We know that, torque on bar magnet in magnetic field,

$$
\begin{aligned}
\tau & =M B \sin \theta \\
\Rightarrow \quad M & =\frac{\tau}{B \sin \theta}=\frac{3.6 \times 10^{-5}}{28.3 \times 10^{-3} \sin 45^{\circ}} \\
& =\frac{\sqrt{2} \times 3.6}{28.3} \times 10^{-2}=1.79 \times 10^{-3} \mathrm{JT}^{-1} \\
& =1.8 \times 10^{-3} \mathrm{JT}^{-1}
\end{aligned}
$$

112. (a) Given, Area of metal loop, $A=10 \mathrm{~cm}^{2}=10^{-3} \mathrm{~m}^{2}, \mathbf{A}=10^{-3} \hat{k}$

Magnitude of magnetic field,

$$
B=1.73 \mathrm{~T}
$$

Magnetic field is directed along,

$$
\hat{i}+\hat{j}+\hat{k}
$$

Unit vector along the direction of magnetic field,

$$
\begin{aligned}
& \hat{\mathbf{n}}=\frac{\hat{i}+\hat{j}+\hat{k}}{\sqrt{1^{2}+1^{2}+1^{2}}}=\frac{\hat{i}+\hat{j}+\hat{k}}{\sqrt{3}} \\
& \mathbf{B}=B \hat{\mathbf{n}} \\
& =1.73 \frac{(\hat{i}+\hat{j}+\hat{k})}{\sqrt{3}}=\hat{i}+\hat{j}+\hat{k}
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \quad \mathbf{B}=B \hat{\mathbf{n}}
\end{aligned}
$$

Magnetic flux linked with coil,

$$
\begin{gathered}
\phi=\mathbf{B} \cdot \mathbf{A} \\
(\hat{i}+\hat{j}+\hat{k}) \cdot\left(10^{-3} \hat{k}\right)=10^{-3} \mathrm{~Wb}
\end{gathered}
$$

$$
\begin{aligned}
& \text { Induced emf, }|e|=\frac{\Delta \phi}{\Delta t}=\frac{\phi-\phi_{2}}{10} \\
& =\frac{10^{-3}-0}{10}=\frac{10^{-3}-0}{10}=10^{-4} \mathrm{~V} \\
& =0.1 \times 10^{-3} \mathrm{~V}
\end{aligned}
$$

$=0.1 \mathrm{mV}$ 113. (b) Given, $L=70 \mathrm{mH}=7 \times 10^{-2} \mathrm{H}$

Supply voltage, $V=220 \mathrm{~V}$

$$
\begin{aligned}
f & =50 \mathrm{~Hz} \\
I_{\mathrm{rms}} & =\frac{V_{\mathrm{nns}}}{X_{L}}=\frac{220}{2 \pi f \mathrm{~L}} \\
& =\frac{220}{2 \times \frac{22}{7} \times 50 \times 7 \times 10^{-2}}=10 \mathrm{~A}
\end{aligned}
$$

114. (a) Frequency of $\mathrm{EM}$ wave,$f=50 \mathrm{MHz}$

$$
=5 \times 10^{7} \mathrm{~Hz}
$$

In free space, the energy density of a static electric field,

$$
K_{E}=\frac{1}{2} \varepsilon_{0} E^{2}
$$

Again, in free space, the energy density of a static magnetic field,

$$
\begin{aligned}
& K_{B}=\frac{B^{2}}{2 \mu_{0}}=\frac{\left(\frac{E}{c}\right)^{2}}{2 \mu_{0}} \quad\left(\therefore B=\frac{E}{c}\right) \\
&=\frac{E^{2}}{2 c^{2} \mu_{0}}=\frac{E^{2}}{2 \frac{1}{\mu_{0} \varepsilon_{0}} \mu_{0}} \quad\left(\because c^{2}=\frac{1}{\mu_{0} \varepsilon_{0}}\right) \\
&=\frac{1}{2} \varepsilon_{0} E^{2} \cdot \\
&=K_{E} \\
& \text { [From Eq. (i)] }
\end{aligned}
$$

$\therefore \quad K_{E}=\dot{K}_{B}$

115. (a) The increasing order of frequency of electromagnetic waves is given as

$f_{\text {radiowave }}<f_{\text {Microwave }}<f_{\text {infrared }}<f_{\text {visible }}<f_{\mathrm{uV}}<f_{\mathrm{X} \text {-rays }}$ $<f_{\gamma-\text {-rays }}$

Hence, $f_{\text {infrared }}<f_{\mathrm{X} \text {-rays }}<f_{\text {yrays }}$ is the correct order of electromagnetic waves with increasing frequency.

116. (c) Mass of particle, $m=2 \times 10^{-27} \mathrm{~kg}$

de-Broglie wavelength, $\lambda=3.3 \times 10^{-10} \mathrm{~m}$

Planck's constant $h=6.6 \times 10^{-34} \mathrm{~J}-\mathrm{s}$

we know that, de-Broglie wavelength

$$
\lambda=\frac{h}{p}
$$

$\Rightarrow \quad \lambda=\frac{h}{\sqrt{2 m K}}$

$(\because p=\sqrt{2 m K})$

Where, $K$ is kinetic energy of particle

$\Rightarrow \quad \lambda^{2}=\frac{h^{2}}{2 m K}$

$\Rightarrow \quad K=\frac{h^{2}}{2 m \lambda^{2}}=\frac{\left(6.6 \times 10^{-34}\right)^{2}}{2 \times 2 \times 10^{-27} \times\left(3.3 \times 10^{-10}\right)^{2}}$ $=1 \times 10^{-21} \mathrm{~J}$ 117. (a) In hydrogen atom, radius (r) of $n$th orbit is gives as

$$
\begin{aligned}
& r \propto n^{2} \\
& =\left(\frac{n_{3}}{n_{6}}\right)^{2} \\
& =\left(\frac{3}{6}\right)^{2} \quad\left(\therefore n_{3}=3, n_{6}=6\right) \\
& =(0.5)^{2}=0.25 \quad
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow \quad \frac{r_{3}}{r_{6}}=\left(\frac{n_{3}}{n_{6}}\right)^{2}
\end{aligned}
$$

118. (a) We know that, frequency of light radiation emitted during the transition of electron from energy level $n_{2}$ to $n_{1}$ in $\mathrm{H}$-atom

$$
v=Z^{2} R c\left[\frac{1}{n_{1}^{2}}-\frac{1}{n_{2}^{2}}\right] \quad(\because Z=1 \text { for hydrogen })
$$

where $R$ is Rydberg constant and $c$ is speed of light.

For the first case $n_{1}=2$ and $n_{2}=4$

$$
\begin{gathered}
v_{1}=R c\left(\frac{1}{2^{2}}-\frac{1}{4^{2}}\right)=R c \times \frac{3}{16} \\
v_{1}=\frac{3 R c}{16} \\
\frac{3}{7} \text { times of transition of } \mathrm{Li} \text { atom }=\frac{7}{3} \times \frac{3 R c}{16}=\frac{7 R c}{16}
\end{gathered}
$$

For lithium atom, $Z=3$ and for transition for 4 th orbit to 3rd orbit is given as

$$
\begin{aligned}
v_{2} & =Z^{2} R c\left(\frac{1}{3^{2}}-\frac{1}{4^{2}}\right) \\
& =(3)^{2} R c\left(\frac{7}{144}\right)=\frac{7}{16} R c
\end{aligned}
$$

Hence, option (a) correct.

119. (a) The given logic circuit are represented as

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-21.jpg?height=271&width=646&top_left_y=1889&top_left_x=1072)

From the above logic circuit,

$$
\begin{aligned}
Y & =\overline{A B+A+B \cdot B}=\overline{[A(B+1)+B] \cdot B} \\
& =\overline{(A+B) B} \quad[\because 1+B=1] \\
& =\overline{(1+0) \cdot 0}=\overline{0}=1 \\
Z & =Y+\overline{A+B} \\
& =1+\overline{1+0} \\
& =1+\overline{1}=1+0=1
\end{aligned}
$$

120. (b) The frequency suitable for beyond the horizon communication using sky wave is $10 \mathrm{MHz}$. 

\section{Chemistry}

121. (c) Given,

$$
\begin{aligned}
\lambda & =3.3 \times 10^{-10} \mathrm{~m} \Rightarrow h=6.6 \times 10^{-34} \mathrm{Js} \\
m_{c} & =9.0 \times 10^{-31} \mathrm{~kg} \\
\lambda & =h / m v \Rightarrow v=h / m \lambda \\
& =\frac{6.626 \times 10^{-34}}{9.0 \times 10^{-31} \times 3.3 \times 10^{-10}} \\
v & =0.223 \times 10^{7} \\
\cdot \mathrm{KE} & =\frac{1}{2} m v^{2}=\frac{1}{2} \times 9.0 \times 10^{-31} \times\left(0.223 \times 10^{7}\right)^{2} \\
& =2.23 \times 10^{-18} \mathrm{~J}
\end{aligned}
$$

122. (a) Number of orbitals $=n^{2}$

$$
n=4
$$

Number of orbitals $=(4)^{2}=16$

(given)

So, the number of electrons with $\dot{m}_{s}=+\frac{1}{2}$ will be 16 .

123. (a) The metallic character decreases from left to right across a period. $K$ belongs to group l, so have highest metallic character followed by $\mathrm{Mg}$ (group 2 element). Also the metallic character increases down the group, so $\mathrm{Al}$ metallic character is more than $B$. Thus, the correct order of metallic character in increasing order will be

$$
\mathrm{B}<\mathrm{Al}<\mathrm{Mg}<\mathrm{K} \text {. }
$$

124. (a) Atomic number $=117$

Electronic configuration $=[R n] 5 f^{14} 6 d^{10} 7 s^{2} 7 p^{5}$

Outermost orbital have principal quantum number $n=7$

$\therefore$ Valence electrons $=2(s$-orbital $)+5(p$-orbital $)=7$

125. (b) As per Fajan's rule, more is the charge on cation and less is the size of the cation, more is the covalency. Out of $\mathrm{Mg}^{2+}$ and $\mathrm{Na}^{+}$, charge on $\mathrm{Mg}^{2+}$ is more hence, its compound will be more covalent. Similarly, more is the change on anion, more is the size of anion and hence more is the covalent character. $\mathrm{O}^{2-}$ has higher charge than $\mathrm{Cl}^{-}$. $\therefore \mathrm{Mg}^{2+}$ and $\mathrm{O}^{2-}$ combination will have more covalent character.

126. (c)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-22.jpg?height=342&width=773&top_left_y=2256&top_left_x=116)

$\therefore$ Option (c) $\mathrm{SF}_{4}$ and $\mathrm{NH}_{4}^{+}$have different shapes. 127. (a) Kinetic energy of an ideal gas is given by the formula $\frac{3}{2} n R T$. It depends only on absolute temperature and does not depend on mass of the gas molecule.

$\therefore$ Statement (a) kinetic energy of 1 mole of gas depends on mass of gas molecule is false.

128. (a) Disproportionation reactions are the reactions in which a compound undergoes oxidation as well as reduction.

$$
\mathrm{CaCO}_{3} \longrightarrow \mathrm{CaO}+\mathrm{CO}_{2}
$$

is an exämple of decomposition reaction. There is no simultaneous oxidation or reduction happening.

$\therefore$ It is not an example of disproportionation reaction. Rest all examples

$$
\begin{aligned}
& \stackrel{0}{\mathrm{P}_{4}}+3 \mathrm{NaOH}+3 \mathrm{H}_{2} \mathrm{O} \longrightarrow 3 \mathrm{NaH}_{2} \mathrm{PO}_{2}^{+1}+\mathrm{PH}_{3}^{-3} \\
& 2 \mathrm{H}_{2} \mathrm{O}_{2}^{-1} \longrightarrow 2 \mathrm{H}_{2} \mathrm{O}^{-2}+\mathrm{O}_{2}^{0} \\
& 2 \mathrm{Cu}^{+} \longrightarrow \mathrm{Cu}^{2+}+\mathrm{Cu}
\end{aligned}
$$

The element undergoes oxidation and reduction both. Hence, are examples of disproportionation reactions.

129. (d)

(a) $\stackrel{+1}{\mathrm{H}} \mathrm{g}_{2} \mathrm{Cl}_{2} \longrightarrow \stackrel{0}{\longrightarrow} \mathrm{H}+\stackrel{+2}{\mathrm{H}} \mathrm{gCl}_{2}$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-22.jpg?height=78&width=502&top_left_y=1600&top_left_x=1077)

(c) $\stackrel{0}{\mathrm{C}}_{2}+2 \mathrm{NaOH} \longrightarrow \stackrel{+1}{\mathrm{~N}} \mathrm{aCl}+\mathrm{NOCl}+\mathrm{H}_{2} \mathrm{O}$

(d) $\mathrm{BaO}_{2}+\mathrm{H}_{2} \mathrm{SO}_{4} \longrightarrow \mathrm{BaSO}_{4}+\mathrm{H}_{2} \mathrm{O}_{2}$

$\therefore$ It is only (d) which is not an example of disproportionation reaction. In rest of the reactions, there is simultaneous oxidation and reduction of an element. Hence, others are example of disproportionation reaction.

130. (a) $2 \mathrm{CO}(g)+\mathrm{O},(g) \rightleftharpoons 2 \mathrm{CO}_{2}(g)$

Given, $\Delta_{r} G=-128 \mathrm{~kJ}$

$$
\Delta_{r} S^{\circ}=-40 \mathrm{~K} \Rightarrow \Delta_{r} U=\text { ? }
$$

$$
\begin{aligned}
& \Delta G=\Delta H-T \Delta S \\
& \Delta H=\Delta U+\Delta n R T \text {. }
\end{aligned}
$$

From (i) and (ii),

$$
\Delta G=\Delta U+\Delta n R T-T \Delta S
$$

$$
\begin{aligned}
& -128000=\Delta U+(-1) \times 8.314 \times 300-300 \times(-40) \\
& -128000=\Delta U-2494.2+12000 \\
& -128000=\Delta U-9505.8 \\
& \Delta U=-128000-9505.8
\end{aligned}
$$

$$
=-137505.8 \mathrm{~J} \cong-137.50 \mathrm{~kJ}
$$

131. (b) (A) $U=H-p V$, (B) $G=H-T S$, (C) $U=q+W$ The enthalpy of system is sum of internal energy and product of pressure and volume.

$$
\begin{aligned}
\Delta H & =\Delta U+p \Delta V ; \quad H=U+p V \\
U & =H-p V
\end{aligned}
$$

Also, $\Delta G=\Delta H-T \Delta S$ or $G=H-T S$

According to first law of thermodynamics,

$$
\Delta U=q-W .
$$

$\therefore$ Equation (C), $U=q+W$ is incorrect.

Option (b), only (A) and (B) are correct.

132. (b) For the given reaction,

$$
A(\mathrm{~g})+\frac{1}{2} B(\mathrm{~g}) \rightleftharpoons C(\mathrm{~g})+\text { Heat }
$$

Low temperature will favour the forward reaction as it is an exothermic reaction. According to

Le-Chatelier's principle, if there is any change in the conditions of equilibrium, then the equilibrium shifts in the direction that can reduce the effect of the change. As given reaction is. exothermic, increase temperature will favour backward/reverse reaction and decrease temperature will favour forward reaction. Number of moles of reactant $=1+0.5=1.5$

Number of moles of product $=1$

$\therefore$ High pressure will favour forward reaction as the effect of increased pressure can be minimised, if it goes in forward reaction.

133. (d) $K_{a}$ for $A=1.8 \times 10^{-4}$

$K_{a}$ for $B=5 \times 10^{-10} ; K_{a}$ for $C=3 \times 10^{-8}$

$K_{a} \propto$ acidic strength

More is $K_{a}$ and more is acidic strength.

$\therefore$ Correct order of acidic strength is $A>C>B$.

134. (b)

I. The correct formula for Calgon is $\mathrm{Na}_{6}\left(\mathrm{PO}_{3}\right)_{6}$ is a correct statement.

II. Exhausted permutit is regenerated by aqueous $\mathrm{KCl}$ solution. It is an incorrect statement. The exhausted permutit is regenerated by brine solution, i.e. aqueous $\mathrm{NaCl}$.

III. Calcium stearate is soluble in water is an incorrect statement. Calcium stearate being a carboxylate salt of $\mathrm{Ca}$ is highly insoluble in water but is soluble in pyridine.

IV. In ice crystal, each oxygen is surrounded by four oxygen atoms. Each water molecule is hydrogen bonded to 4 other neighbouring water molecules. The statement is correct. $\therefore$ I and IV only are correct. 135. (d) Smoke screens are used for hiding military areas with help of dense fake smoke cloud. $\mathrm{Ca}_{3} \mathrm{P}_{2}$ is used for producing smoke screens.

$$
\begin{aligned}
& \mathrm{Ca}_{3} \mathrm{P}_{2}+6 \mathrm{H}_{2} \mathrm{O} \longrightarrow 3 \mathrm{Ca}(\mathrm{OH})_{2}+2 \mathrm{PH}_{3} \\
& 2 \mathrm{PH}_{3}+4 \mathrm{O}_{2} \longrightarrow \mathrm{P}_{2} \mathrm{O}_{5}+3 \mathrm{H}_{2} \mathrm{O} \\
& \downarrow
\end{aligned}
$$

Responsible for white dense smoke screen

136. (d) $2 \mathrm{MNO}_{3} \longrightarrow \mathrm{M}_{2} \mathrm{O}+2 \mathrm{NO}_{2}+\frac{1}{2} \mathrm{O}_{2}$

Metal, $M$ in the given reaction is $\mathrm{Li}$.

$$
2 \mathrm{LiNO}_{3} \longrightarrow \mathrm{Li}_{2} \mathrm{O}+2 \mathrm{NO}_{2}+\frac{1}{2} \mathrm{O}_{2}
$$

137. (c) $X+\mathrm{B}_{2} \mathrm{H}_{6} \stackrel{\left(\mathrm{C}_{2} \mathrm{H}_{5}\right)_{2} \mathrm{O}}{\longrightarrow} 2 \mathrm{XBH}_{4}$

$$
\underset{\text { diumrhydride }}{2 \mathrm{NaH}}+\mathrm{B}_{2} \mathrm{H}_{6} \underset{\left(\mathrm{C}_{2} \mathrm{H}_{5}\right)_{2} \mathrm{O}}{\longrightarrow} \underset{\text { Sodium borohydridc }}{2 \mathrm{NaBH}_{4}}
$$

$\therefore X$ is a metal hydride.

138. (c)

I. Both $\mathrm{CCl}_{4}$ and $\mathrm{SiCl}_{4}$ undergo hydrolysis is incorrect. $\mathrm{CCl}_{4}$ does not undergo hydrolysis. due to absence of vacant $d$-orbitals whereas $\mathrm{SiCl}_{4}$ does undergo hydrolysis.

II. $\mathrm{Ge} X_{4}$ is more stable than $\mathrm{GeX}$ is a.correct statement. The stability of $+2$ oxidation state increases down the group due to inert pair effect. Also electrons configuration of $\mathrm{Ge}^{+4}$ is stable electrons configuration $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{6} 3 d^{10}$ Hence, $\mathrm{Ge} X_{4}$ is more stable than $\mathrm{Ge} X_{2}$.

III. $\mathrm{PbX}_{4}$ is less stable than $\mathrm{Pb} X_{2}$. The stability of $+2$ oxidation state of group 14 clements increases down the group due to inert pair effect.

$\therefore \mathrm{Pb} X_{4}$ is less stable than $\mathrm{Pb} X_{2}$. Hence, the statement is correct.

IV. Stability of dihalides decreases down the group. The statement is incorrect. The stability of lower oxidation state (+2) i.e. dihalides increases down the group due to inert pair effect. Only (II) and (III) are correct.

139. (b) (I) $\mathrm{C}_{2} \mathrm{H}_{2}$ (II) $\left(\mathrm{CH}_{3}\right)_{2} \mathrm{C}_{2} \quad$ (III) $\left(\mathrm{CH}_{3}\right) \mathrm{C}_{2} \mathrm{H}$

More are the alkyl groups $\left(-\mathrm{CH}_{3}\right)$, decrease is the acidic character due to $+I$ effect of alkyl group. Hence, the correct order of acidic strength is II $<$ III $<$ I. 140. (b)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-24.jpg?height=491&width=785&top_left_y=317&top_left_x=173)

141. (d) Number of cations $=1+\frac{1}{2} \times 12 \times \frac{1}{4}$ Anion $\rightarrow A=\mathrm{fcc}=4$ $\mathrm{C}_{5 / 2} A_{4}=\mathrm{C}_{5} \mathrm{H}_{8}$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-24.jpg?height=263&width=448&top_left_y=919&top_left_x=473)

So, the formula of the molecules is $\mathrm{C}_{5} A_{8}$.

142. $(a) a=3 \AA$, i.e. $3 \times 10^{-10} \mathrm{~m}$

Number of atoms in $210 \mathrm{~g}$ of $A$ $=$ Number of atoms in $594 \mathrm{~g}$ of $B$

$$
d_{A}=7 \mathrm{~g} / \mathrm{cm}^{3}, \quad d_{B}=?, \quad a^{3}=\frac{Z \times M}{N_{A} \times d}
$$

As $a$ is same for both $A$ and $B$.

$\therefore \quad \frac{Z \times M_{A}}{N_{A} \times d_{A}}=\frac{Z \times M_{B}}{N_{B} \times d_{B}}$

$\Rightarrow \frac{4 \times 210}{.6 .023 \times 10^{23} \times 7}=\frac{2 \times 594}{6.023 \times 10^{23} \times d_{B}}$

$\Rightarrow \quad d_{B}=\frac{594 \times 7}{420}=9.9 \mathrm{~g} / \mathrm{cm}^{3}$

143. (b) Reverse osmosis can take place when pressure higher than osmotic pressure is applied on the solution.

$\therefore p_{\text {ext }}>C R T$ is correct.

144. (b) Isotonic solutions are the solutions that have same concentration' of water and solutes. Cells placed in isotonic solutions will never shrink or swell.

(A) Strength of $18 \mathrm{~g} / \mathrm{L}$ glucose $=\frac{18}{180}=\frac{1}{10}$

Strength of $6 \mathrm{~g} / \mathrm{L}$ urea $=\frac{6}{60}=\frac{1}{10}$

$\therefore 18 \mathrm{~g} / \mathrm{L}$ glucose is isotonic with $6 \mathrm{~g} / \mathrm{L}$ urea.

(B) Strength of $10 \mathrm{~g} / \mathrm{L}$ glucose $=\frac{10}{180}$

Strength of $10 \mathrm{~g} / \mathrm{L}$ urea $=\frac{10}{60}$ (C) The van't Hoff factor for $\mathrm{NaOH}=2$.

Due to 2 ions are produced, $\mathrm{Na}^{+}$and $\mathrm{OH}^{-}$.

So strength of $\mathrm{NaOH}=2 \times 0.01=0.02 \mathrm{M}$

Strength of glucose $=0.02 \mathrm{M}$

Therefore, (A) and (C) are isotonic solutions.

145. (d) Given, resistance of $0.1 \dot{\mathrm{M}}$ solution of $\mathrm{NaCl}$ $=100 \mathrm{ohm}$.

Resistance of $0.02 \mathrm{~mol} / \mathrm{L} \mathrm{NaCl}=258 \mathrm{ohm}$ Conductivity of $0.02 \mathrm{~mol} / \mathrm{L} \mathrm{NaCl}=$ ?

Conductivity of $0.1 \mathrm{~mol} / \mathrm{L} \mathrm{NaCl}=1.29 \mathrm{Sm}^{-1}$

Cell constant $=\kappa \times R=1.29 \times 100=129 \mathrm{~m}^{-1}$

Conductivity of $0.02 \mathrm{M} \mathrm{KCl}$ solution

$$
=\frac{\text { Cell constant }}{\text { Resistance }}=\frac{129}{528}=0.5 \mathrm{sm}^{-1}
$$

146. (c) $\mathrm{CH}_{3} \mathrm{COOC}_{2} \mathrm{H}_{5}+\mathrm{H}_{2} \mathrm{O} \longrightarrow \mathrm{CH}_{3} \mathrm{COOH}+\mathrm{C}_{2} \mathrm{H}_{5} \mathrm{OH}$ Rate $=\left[\mathrm{H}_{2} \mathrm{O}\right]\left[\mathrm{CH}_{3} \mathrm{COOC}_{2} \mathrm{H}_{5}\right]$

Given, initial $\left[\mathrm{H}_{2} \mathrm{O}\right]=2 \mathrm{M}$

initial $\left[\mathrm{CH}_{3} \mathrm{COOC}_{2} \mathrm{H}_{5}\right]=0.001 \mathrm{M}$, Value of $K=$ ?,

If $99 \%$ ethyl acetate hydrolyse in $10 \mathrm{~s}$.

As the initial concentrations of ethyl acetate and $\mathrm{H}_{2} \mathrm{O}$ vary widely.

$\therefore$ The reaction might be pseudo Ist order

$$
k=\frac{2.303}{t} \log \frac{A_{0}}{A}
$$

As $99 \%$ is hydrolysed in $10 \mathrm{~s}$.

So, $[A]$ at 10 s will be $1 \%$,

i.e. $\frac{1}{100} \times 0.001 \doteq[0.01 \times 0.001]$

$k=\frac{2.303}{10} \log \frac{0.001}{0.01 \times 0.001}=0.2303 \log 100=0.4606$

147. (b) $\mathrm{As}_{2} \mathrm{O}_{3}+3 \mathrm{H}_{2} \mathrm{~S} \longrightarrow \mathrm{AS}_{2} \mathrm{~S}_{3}+\mathrm{H}_{2} \mathrm{O}$

$\therefore$ The correct option is $\mathrm{As}_{2} \mathrm{~S}_{3}$.

148. (c) Stomach disorders are mostly due to high acidity which can be treated by use of base. Milk of Magnesia being basic in nature is used to treat stomach disorders as it can neutralise high acidity.

149. (b) Oxygen is second most electronegative element after fluorine as it has high tendency to attract the electron. It is only two electron short than attaining inert gas configuration. Thus, its size and tendency to attract electron, makes it second most electronegative element.

150. (d)
![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-24.jpg?height=280&width=744&top_left_y=2426&top_left_x=1086)

Square planar 151. (b) $\mathrm{Fe}(26):[\mathrm{Ar}] 4 s^{2} 3 d^{6} \Rightarrow \mathrm{Fe}^{2+}:[\mathrm{Ar}] 4 s^{0} 3 d^{6}$ Number of unpaired electron $=4$ Magnetic moment $=\sqrt{4(4+2)}$

$$
=\sqrt{4 \times 6}=\sqrt{24} \cong 4.90 \mathrm{BM}
$$

152. (b) Ruby and emerald both contains chromium $\left(\mathrm{Cr}^{3+}\right)$ ion. Chromium ion occupies position in lattice by replacing $\mathrm{Al}$ and thus exhibit colour. [Cr belongs to transition metals which have property of imparting colour due to $d-d$ transition].

153. (c) Curdling of milk is caused due to formation of lactic acid by lactabacillus bacteria present is milk.

154. (a) Serine is

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=251&width=280&top_left_y=951&top_left_x=380)

$\therefore$ Functional group in addition to $-\mathrm{NH}_{2}$ and $-\mathrm{COOH}$ is $-\mathrm{OH}$.

155. (a) $\mathrm{S}_{\mathrm{N}} 1$ rate depends on the stability of carbocation formed as an intermediate. The carbocations formed by given bromides will be

(a)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=148&width=208&top_left_y=1471&top_left_x=250)

(b)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=137&width=403&top_left_y=1642&top_left_x=244)

(c)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=163&width=237&top_left_y=1783&top_left_x=264)

(d)
![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=446&width=538&top_left_y=1640&top_left_x=266)

The carbocation $\mathrm{Ph} \overbrace{\mathrm{Ph} \text { is most stable as it can }}$ be resonance stabilised by two phenyl rings.

$\therefore$ The $\mathrm{S}_{\mathrm{N}} \mathrm{l}$ will be faster in $\mathrm{Ph}$

156. (c)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=237&width=617&top_left_y=2440&top_left_x=248)

$\therefore(\mathrm{A})$ is correct. Reason $\mathrm{AgCN}$ is mainly ionic in nature is incorrect as $\mathrm{AgCN}$ is mostly covalent in nature and not ionic. $\mathrm{N}$ in $\mathrm{AgCN}$ due to its covalent nature is free to donote electron pair and thus forms isocyanide and not cyanide.

Hence, (A) is true but (R) is false.

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=314&width=882&top_left_y=617&top_left_x=975)

(iii) $\mathrm{H}_{2} \mathrm{O}$

158. (d)

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=520&width=708&top_left_y=999&top_left_x=1071)

159. (a) $2 \mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{COONa} \frac{\text { Kolbe's }}{\text { electrolysis }}$

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=205&width=503&top_left_y=1605&top_left_x=1322)

$\therefore$ Number of carbons present in hydrocarbon formed is 6.

160. (d) Gabriel phthalimide is used for the preparation of aliphatic primary amines

![](https://cdn.mathpix.com/cropped/2023_02_06_9c5f6b08b17e043b12ebg-25.jpg?height=509&width=762&top_left_y=2010&top_left_x=1041)

Out of the given options, only option (d) $\mathrm{NH}_{2}$ is aliphatic primary amine.

$\therefore$ (d) is the correct option.