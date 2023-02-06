\title{
Answer with Solutions
}

\section{Mathematics}

$$
\begin{aligned}
& \text { 1. (a) } f(x)=\log \left(\left(\frac{2 x^{2}-3}{x}\right)+\sqrt{\frac{4 x^{4}-11 x^{2}+9}{|x|}}\right) \\
& f(-x)=\log \left(\frac{2(-x)^{2}-3}{(-x)}+\sqrt{\frac{4(-x)^{4}-11(-x)^{2}+9}{|-x|}}\right) \\
& f(-x)=\log \left[\frac{2 x^{2}-3}{-x}+\sqrt{\frac{4 x^{4}-11 x^{2}+9}{|x|}}\right]
\end{aligned}
$$

We know that, if function $f(x)$ is an odd function. Then,

$$
\begin{aligned}
& f(x)+f(-x)=0 \\
& \log \left[\left(\frac{2 x^{2}-3}{x}\right)+\sqrt{\frac{4 x^{4}-11 x^{2}+9}{|x|}}\right] \\
& \quad+\log \left[\sqrt{\frac{4 x^{4}-11 x^{2}+9}{|x|}}-\frac{\left(2 x^{2}-3\right)}{x}\right] \\
& =\log \left[\frac{4 x^{4}-11 x^{2}+9}{x^{2}}-\frac{\left(2 x^{2}-3\right)^{2}}{x^{2}}\right] \\
& =\log \left[\frac{4 x^{4}-11 x^{2}+9-4 x^{4}-9+12 x^{2}}{x^{2}}\right] \\
& =\log 1=0
\end{aligned}
$$

2. (a) $f(x)=\frac{x-2}{2 x+1}$

$$
\begin{aligned}
& f(f(x))=-x \\
& \Rightarrow \quad \frac{f(x)-2}{2(f(x))+1}=-x \\
& \Rightarrow \quad \frac{\frac{x-2}{2 x+1}-2}{\frac{2 x-4}{2 x+1}+1}=-x \\
& \Rightarrow \frac{x-2-4 x-2}{2 x-4+2 x+1}=-x \\
& \Rightarrow \quad \frac{-3 x-4}{4 x-3}=-x \Rightarrow \frac{3 x+4}{4 x-3}=x \\
& \Rightarrow \quad 3 x+4=4 x^{2}-3 x \\
& \Rightarrow \quad 4 x^{2}-6 x-4=0 \\
& \Rightarrow \quad 2 x^{2}-3 x-2=0 \\
& \text { Now, } \alpha+\beta=\frac{3}{2}, \alpha \beta=-1 \\
& \text { Now, }(\alpha+\beta)^{2}=\alpha^{2}+\beta^{2}+2 \alpha \beta \\
& \Rightarrow \quad \frac{9}{4}=\alpha^{2}+\beta^{2}-2
\end{aligned}
$$

[Given]

$$
\begin{aligned}
& \Rightarrow \alpha^{2}+\beta^{2}=\frac{17}{4} \\
& \Rightarrow 4\left(\alpha^{2}+\beta^{2}\right)=17
\end{aligned}
$$

3. (a) Here,

$$
A=\left[\begin{array}{lll}
3 & -3 & 4 \\
2 & -3 & 4 \\
0 & -1 & 1
\end{array}\right]
$$

$$
\begin{aligned}
& A^{T}=\left[\begin{array}{ccc}3 & 2 & 0 \\-3 & -3 & -1 \\4 & 4 & 1\end{array}\right] \\
& A A^{T}=\left[\begin{array}{lll}3 & -3 & 4 \\2 & -3 & 4 \\0 & -1 & 1\end{array}\right]\left[\begin{array}{ccc}3 & 2 & 0 \\-3 & -3 & -1 \\4 & 4 & 1\end{array}\right] \\
& A A^{T}=\left[\begin{array}{ccc}9+9+16 & 6+9+16 & 0+3+4 \\6+9+16 & 4+9+16 & 0+3+4 \\0+3+4 & 0+3+4 & 0+1+1\end{array}\right] \\
& A A^{T}=\left[\begin{array}{ccc}34 & 31 & 7 \\31 & 29 & 7 \\7 & 7 & 2\end{array}\right] \\
& \left(A A^{T}\right)^{T}=\left[\begin{array}{ccc}34 & 31 & 7 \\31 & 29 & 7 \\7 & 7 & 2\end{array}\right] \text {. }
\end{aligned}
$$

So, $A A^{T}$ is a symmetric matrix.

4. (*) The given system of equation is $5 x-y+2 z=3, x+y+z=6$ and $2 x+y-z=-5$ In matrix form, if may be represented as where $A=\left[\begin{array}{ccc}1 & 1 & 1 \\ 5 & -1 & 2 \\ 2 & 1 & -1\end{array}\right] x=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $D=\left[\begin{array}{c}6 \\ 3 \\ -5\end{array}\right]$.

Thus, $A$ is a non-singular matrix, so $A^{-1}$ exist. $C_{11}=(-1)^{1+1}\left|\begin{array}{cc}-1 & 2 \\ 1 & -1\end{array}\right|=-1$

$C_{12}=(-1)^{1+2}\left|\begin{array}{cc}5 & 2 \\ 2 & -1\end{array}\right|=9$

$C_{13}=(-1)^{1+3}\left|\begin{array}{cc}5 & -1 \\ 2 & 1\end{array}\right|=7$

$C_{21}=(-1)^{2+1}\left|\begin{array}{cc}1 & 1 \\ 1 & -1\end{array}\right|=2$ 

$$
\begin{aligned}
& C_{22}=(-1)^{2+2}\left|\begin{array}{cc}1 & 1 \\2 & -1\end{array}\right|=-3 \\
& C_{23}=(-1)^{2+3}\left|\begin{array}{ll}1 & 1 \\2 & 1\end{array}\right|=1 \\
& C_{31}=(-1)^{3+1}\left|\begin{array}{cc}1 & 1 \\-1 & 2\end{array}\right|=3 \\
& C_{32}=(-1)^{3+2}\left|\begin{array}{ll}1 & 1 \\5 & 2\end{array}\right|=3 \\
& C_{33}=(-1)^{3+3}\left|\begin{array}{cc}1 & 1 \\5 & -1\end{array}\right|=-6 \\
& \text { Then, } \operatorname{adj}(A)=\left[\begin{array}{ccc}-1 & 9 & 7 \\2 & -3 & 1 \\3 & 3 & -6\end{array}\right]^{r}=\left[\begin{array}{ccc}-1 & 2 & 3 \\9 & -3 & 3 \\7 & 1 & -6\end{array}\right] \\
& (\operatorname{adj} A) \cdot D=\left[\begin{array}{ccc}-1 & 2 & 3 \\9 & -3 & 3 \\7 & 1 & -6\end{array}\right]\left[\begin{array}{c}6 \\3 \\-5\end{array}\right] \\
& =\left[\begin{array}{c}-6+6-15 \\54-9-15 \\42+3+30\end{array}\right]=\left[\begin{array}{c}-15 \\30 \\75\end{array}\right]
\end{aligned}
$$

5. (*) Given,

$$
A=\left[\begin{array}{ll}
1 & 0 \\
2 & 1
\end{array}\right], B=\left[\begin{array}{ll}
1 & 3 \\
0 & 1
\end{array}\right]
$$

$$
\begin{aligned}
& \Rightarrow A^{2}=\left[\begin{array}{ll}1 & 0 \\2 & 1\end{array}\right]\left[\begin{array}{ll}1 & 0 \\2 & 1\end{array}\right] \text {. } \\
& \Rightarrow A^{2}=\left[\begin{array}{ll}1+0 & 0+0 \\2+2 & 0+1\end{array}\right]=\left[\begin{array}{ll}1 & 0 \\4 & 1\end{array}\right] \\
& \Rightarrow A^{3}=\left[\begin{array}{ll}1 & 0 \\4 & 1\end{array}\right]\left[\begin{array}{ll}1 & 0 \\2 & 1\end{array}\right] \text {. } \\
& \left[A^{2}: A=A^{3}\right]
\end{aligned}
$$

$\Rightarrow A^{3}=\left[\begin{array}{cc}1+0 & 0+0 \\ 4+2 & 1\end{array}\right]=$
Similarly, $A^{6}=\left[\begin{array}{cc}1 & 0 \\ 12 & 1\end{array}\right]$

Now, $B=\left[\begin{array}{ll}1 & 3 \\ 0 & 1\end{array}\right]$

$\Rightarrow B^{2}=\left[\begin{array}{ll}1 & 3 \\ 0 & 1\end{array}\right]\left[\begin{array}{ll}1 & 3 \\ 0 & 1\end{array}\right]$

$\Rightarrow B^{2}=\left[\begin{array}{ll}1+0 & 3+3 \\ 0+0 & 0+1\end{array}\right]=\left[\begin{array}{ll}1 & 6 \\ 0 & 1\end{array}\right]$

$\Rightarrow B^{3}=\left[\begin{array}{ll}1 & 6 \\ 0 & \mathrm{i}\end{array}\right]\left[\begin{array}{ll}1 & 3 \\ 0 & 1\end{array}\right]=\left[\begin{array}{ll}1 & 9 \\ 0 & 1\end{array}\right]$ Similarly, $B^{6}=\left[\begin{array}{cc}1 & 18 \\ 0 & 1\end{array}\right] . \quad\left[B^{n}=B_{12}=n \times 3\right]$

$\therefore\left(A^{6}+B^{6}\right)=\left[\begin{array}{cc}1 & 0 \\ 12 & 1\end{array}\right]+\left[\begin{array}{cc}1 & 18 \\ 0 & 1\end{array}\right]$.

$A^{6}+B^{6}=\left[\begin{array}{cc}2 & 18 \\ 12 & 2\end{array}\right]$

$\operatorname{Det}\left(A^{6}+B^{6}\right)=4-216=-212$

6. (c) Here, $G(x)=\left[\begin{array}{ccc}\cos x & -\sin x & 0 \\ \sin x & \cos x & 0 \\ 0 & 0 & 1\end{array}\right]$

$$
G(y)=\left[\begin{array}{ccc}
\cos y & -\sin y & 0 \\
\sin y & \cos y & 0 \\
0 & 0 & 1
\end{array}\right]
$$

So, $x+y=0 \Rightarrow y=(-x)$

$$
\text { Now, } G(-x)=\left[\begin{array}{ccc}
\cos (-x) & -\sin (-x) & 0 \\
\sin (-x) & \cos (-x) & 0 \\
0 & 0 & 1
\end{array}\right]
$$

$$
\begin{aligned}
& G(x) \cdot G(y)=\left[\begin{array}{ccc}\cos x & -\sin x & 0 \\\sin x & \cos x & 0 \\0 & 0 & 1\end{array}\right]\left[\begin{array}{ccc}\cos x & \sin x & 0 \\-\sin x & \cos x & 0 \\0 & 0 & 1\end{array}\right]
\end{aligned}
$$

$$
=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]=I
$$

7. $\left(\right.$ c) $i^{18}-3 i^{7}+i^{2}\left(1+i^{4}\right)(i)^{22}$

$$
\begin{aligned}
& =i^{4 \times 4+2}-3 i^{4+3}+-1(1+1)\left(i^{2}\right)^{11} \\
& =i^{2}-3 i^{3}+2 \quad\left[\because i^{2}=-1 \text { and } i^{4}=1\right] \\
& =-1+3 i+2=1+3 i \quad
\end{aligned}
$$

8. (b) Conjugate of $\cos x-i \sin 2 x$ is $\cos x+i \sin 2 x$

So, $\sin x+i \cos 2 x=\cos x+i \sin 2 x$

Comparing real and imaginary parts,

$$
\sin x=\cos x \text { or } \tan x=1
$$

and $\cos 2 x=\sin 2 x$ or $\tan 2 x=1$

But for same value of $x$, both $\tan x$ and $\tan 2 x$ can not.

Hence, no solution is possible.

9. (c) Let $z=x+i y$

$$
\begin{gathered}
|z|=\sqrt{x^{2}+y^{2}} \\
\text { Now, }|z|^{2}=\operatorname{Re}(z) \\
x^{2}+y^{2}=x \\
\Rightarrow \quad x^{2}+y^{2}-x=0 \\
g=1 / 2, f=0
\end{gathered}
$$

So, centre of circle $\left(\frac{1}{2}, 0\right)$. 10. (a) Given,

$$
\begin{aligned}
& \sin ^{4} \theta \cos ^{2} \theta=\sum_{n=0}^{\infty} a_{2 n} \cos 2 n \theta \\
\Rightarrow & \left(\sin ^{2} \theta\right)^{2} \cos ^{2} \theta=\sum_{n=0}^{\infty} a_{2 n} \cos 2 n \theta \\
\Rightarrow & \left(1-\cos ^{2} \theta\right)^{2} \cos ^{2} \theta=\sum_{n=0}^{\infty} a_{2 n} \cos 2 n \theta \\
\Rightarrow & \left(1+\cos ^{4} \theta-2 \cos ^{2} \theta \cos ^{2} \theta=\sum_{n=0}^{\infty} a_{2 n} \cos 2 n \theta\right. \\
\therefore & \cos ^{2} \theta+\cos ^{4} \theta \cos ^{2} \theta-2 \cos ^{4} \theta \\
& =\sum_{n=0}^{\infty} a_{2 n} \cos 2 n \theta \\
\Rightarrow & \left(\frac{\cos 2 \theta+1}{2}\right)+\left(\frac{\cos 2 \theta+1}{2}\right)^{2}\left(\frac{1+\cos 2 \theta}{2}\right) \\
& -2\left(\frac{\cos 2 \theta+1}{2}\right)^{2}=\sum_{n=0}^{\infty} a_{2 n} \cos 2 n \theta
\end{aligned}
$$

On comparing both sides, we get minimum value of $n$ is 1 .

11. (d) Given, equation $x^{2}-2(+3 m) x+7(3+2 m)=0$ Here, $a>0$ and $D=b^{2}-4 a c>0$

Expression is always positive, if roots are distinct then $D>0$,

$$
\left[[-2(1+3 m)]^{2}-4 \times 7(3+2 m)>0\right.
$$

$$
\begin{aligned}
& \Rightarrow 4\left[1+9 m^{2}+6 m\right]-84-56 m>0 \\
& \Rightarrow \quad 36 m^{2}-32 m-80>0 \\
& \Rightarrow 9 m^{2}-8 m-20>0 \\
& \Rightarrow(m-2)\left(m+\frac{10}{9}\right)>0 \text {. } \\
& \Rightarrow m \in\left(-\infty, \frac{-10}{9}\right) \cup(2, \infty)
\end{aligned}
$$

$\therefore$ Integral value of $m$ are $3 i, 1,2,3,4,5,6$.

So, the number of element in $S$ is infinite.

12. (c) Given,

$$
\begin{aligned}
& 4^{x}-3^{x-\frac{1}{2}}=3^{x+\frac{1}{2}}-2^{2 x-1} \\
\Rightarrow & (2)^{2 x}+2^{2 x-1}=3^{x+\frac{1}{2}}+3^{x-\frac{1}{2}} \\
\Rightarrow & 2^{2 x}+\frac{2^{2 x}}{2}=3^{x} \cdot \sqrt{3}+\frac{3^{x}}{\sqrt{3}} \\
\Rightarrow & 2^{2 x}\left[1+\frac{1}{2}\right]=3^{3}\left[\sqrt{3}+\frac{1}{\sqrt{3}}\right] . \\
\Rightarrow & 2^{2 x} \times \frac{3}{2}=3^{x} \times \frac{4}{\sqrt{3}} \\
\Rightarrow & 2^{2 x}(3 \sqrt{3})=3^{x}(8) \\
\Rightarrow & 2^{2 x}(3)^{\frac{3}{2}}=3^{x} \times(2)^{3} .
\end{aligned}
$$

Comparing power of $2,2 x=3$

and comparing power of $3, x=\frac{3}{2}$

Both equations given us $x=\frac{3}{2}$.

13. (c) Considering the question to be, to find the roots of the equation $x^{4}-2 x^{3}+x-380=0$ Now, by trial error method we find that $x=5$ is a solution to the equation

$$
\begin{aligned}
\Rightarrow & 5^{4}-2 \times 5^{3}+5-380=0 \\
& =625-250+5-380=0 \\
& =380-380=0
\end{aligned}
$$

Thus, $x=5$ is a solution.

We also find that $x=-4$ is a solution

$$
\begin{aligned}
& (-4)^{4}-2 \times(-4)^{3}-4-380=0 \\
& =256+128-4-380 \\
& =380-380=0
\end{aligned}
$$

The real roots are 5 and $-4$. Sum of real roots are $5+(-4)=1$

14. (a) Let $a, 2 a$ and $b$ be roots of the cubic equation $x^{3}+36-7 x^{2}=0$.

So, sum of roots $=-\frac{(-7)}{1}$

$\therefore \quad a+2 a+b=7$

$\Rightarrow \quad 3 a+b=7$

Now, $a(2 a) b=36 \quad\left[\right.$ product of roots $\left.=\frac{d}{a}\right]$

$2 a^{2} b=36$ and $a b+a(2 a)+2 a(b)=0$

$\Rightarrow \quad 2 a^{2}+3 a b=0 \Rightarrow a(2 a+3 b)=0$

$\Rightarrow \quad b=\frac{-2 a}{3}$

$\Rightarrow \quad 3 a-\frac{2 a}{3}=7$

[from Eq. (i)]

$\Rightarrow \quad \frac{9 a-2 a}{3}=7 \Rightarrow 9 a-2 a=21$

$\Rightarrow \quad 7 a=21 \Rightarrow a=3$

and $b=7-3 a$

$$
=7-3(3)=-2
$$

[from Eq. (i)]

Roots are $3,6,-2$

$\therefore$ Number of negative root is 1 .

15. (d) $10^{n} C_{2}=3^{n+1} C_{3}$

$$
\begin{array}{rlrl} 
& & \frac{10 n !}{(n-2) ! 2 !}=\frac{3(n+1) !}{(n+1-3) ! \times 3 !} \\
\Rightarrow & \frac{10 n !}{2}=\frac{3(n+1) n !}{3 \times 2} \\
\Rightarrow & 10=n+1 \\
\Rightarrow & n & =9
\end{array}
$$

16. (c) If all 10 points are collinear, then number of triangles formed

$$
{ }^{10} \mathrm{C}_{3}=\frac{10 !}{3 ! 7 !}=\frac{10 \times 9 \times 8}{3 \times 2}=120
$$

Triangles formed using $6{ }^{\circ}$ collinear points ${ }^{6} \mathrm{C}_{3}=20$ Therefore, required number of triangles $120-20=100$

17. (a) Total number of students $=205$

Number of students passed in Math $=70$

Number of students passed in English $=105$ and number of students pass in both $=30$ Now,

Number of students passed in Math or English. $=$ Number of students passed in Math $+$ Number of student passed in English - Number of students passed in both $=70+105-30=145$

So, number of students fail in both subjects $=$ Total number of students - Students passed in Math or English $=205-145=60$

18. (d) Total marks $=$ Marks for first 3 papers $+$ Marks for fourth paper $=3 n+2 n=5 n$ Candidate needs to get $3 n$ marks.

Let $x_{1}, x_{2}, x_{3}, x_{4}$ be the marks of candidate in I, II, III and IV paper, respectively.

Then, $x_{1}+\dot{x}_{2}+x_{3}+x_{4}$

$$
=3 n\left(0 \leq x_{1}, x_{2}, x_{3} \leq n \text { and } 0 \leq x_{4} \leq 2 n\right)
$$

Using multinomial theorem,

Number of ways $=$ Coefficient of $x^{3 n}$ in

$\underbrace{\left(1+x+\ldots .+x^{n}\right)^{3}}_{\text {GP series }} \underbrace{\left(1+x+\ldots . x^{2 n}\right)}_{\text {GP Series }}$

$\Rightarrow\left(\frac{1-x^{n+1}}{1-x}\right)^{3}\left(\frac{1-x^{2 n+1}}{1-x}\right)$

$\Rightarrow 1-x^{3(n+1)}-3 x^{n+1}\left(1-x^{n+1}\right)\left(1-x^{2 n+1}\right)(1-x)^{-4}$

$\Rightarrow\left(1-x^{3(n+1)}-3 x^{n+1}+3 x^{2 n+2}\right)\left(1-x^{2 n+1}\right)(1-x)^{-4}$

$\Rightarrow\left(1-x^{3(n+1)}-3 x^{n+1}+3 x^{2 n+2}-x^{2 n+1}+x^{5 n+4}\right.$

$$
\left.+3 x^{3 n+2}-3 x^{4 n+3}(1-x)^{-4}\right)
$$

Finding the coefficient of $x^{3 n}$ using binomial expansion, we get

$$
\begin{gathered}
{ }^{3 n+3} C_{3}-3^{2 n+2} C_{3}+3^{n+2} C_{3}-{ }^{n+3} C_{3} \\
=\frac{1}{6}(n+1)\left(5 n^{2}+10 n+6\right)
\end{gathered}
$$

19. (b) Here, $\frac{2 x^{2}+1}{x^{3}-1}=\frac{A}{x-1}+\frac{B x+C}{x^{2}+x+1}$.

Resolving into partial fractions,

$\frac{2 x^{2}+1}{x^{3}-1}=\frac{A\left(x^{2}+x+1\right)+(B x+C)(x-1)}{(x-1)\left(x^{2}+x+1\right)}$ $\Rightarrow 2 x^{2}+1=A x^{2}+A x+A+B x^{2}-B x+C x-C$

$\Rightarrow 2 x^{2}+1=x^{2}(A+B)+x(A-B+C)+A-C$

Comparing with coefficient, we get

$$
A+B=2, A-B+C=0 \text { and } A-C=1
$$

Clearly, $A=1, B=1$ and $C=0$

So, $7 A+2 B+C=7(l)+2(l)+0=9$

20. (b) If $\sin \theta=\frac{-3}{4}$

$$
\cos \theta=\sqrt{1-\sin ^{2} \theta}
$$

$$
\begin{aligned}
& \cos \theta=\sqrt{1-\left(\frac{-3}{4}\right)^{2}} \\
& \cos \theta=\sqrt{\frac{16-9}{4}}=\sqrt{\frac{7}{16}} \\
& \therefore \sin 2 \theta=2 \sin \theta \cdot \cos \theta
\end{aligned}
$$

$$
=2 \times\left(\frac{-3}{4}\right)\left(\frac{\sqrt{7}}{4}\right)=\frac{-3 \sqrt{7}}{8}
$$

21. (b) Here,

$$
\begin{array}{r}
\frac{1}{\sin 1^{\circ} \sin 2^{\circ}}+\frac{1}{\sin 2^{\circ} \sin 3^{\circ}}+\ldots+\frac{1}{\sin 89^{\circ} \sin 90^{\circ}} \\
=\frac{1}{\sin 1^{\circ}}\left[\begin{array}{l}
\frac{\sin \left(2^{\circ}-11^{\circ}\right)}{\sin 1^{\circ} \sin 2^{\circ}}+\frac{\sin \left(3^{\circ}-2^{\circ}\right)}{\sin 2^{\circ} \sin 3^{\circ}}+\ldots . . \\
+\frac{\sin \left(90^{\circ}-89^{\circ}\right)}{\sin 89^{\circ} \sin 90^{\circ}}
\end{array}\right]
\end{array}
$$

We know that

$$
\begin{aligned}
& \sin (A-B)=\sin A \cdot \cos B-\cos A \cdot \sin B \text {. } \\
& =\frac{1}{\sin 1^{\circ}}\left[\begin{array}{l}\frac{\sin 2^{\circ} \cdot \cos 1^{\circ}-\cos 2^{\circ} \cdot \sin 1^{\circ}}{\sin 1^{\circ} \cdot \sin 2^{\circ}} \\+\frac{\sin 3^{\circ} \cdot \cos 2^{\circ}-\cos 3^{\circ} \cdot \sin 2^{\circ}}{\sin 3^{\circ} \cdot \sin 2^{\circ}}+\ldots .\end{array}\right. \\
& \left.+\frac{\sin 90^{\circ} \cdot \cos 89^{\circ}-\cos 90^{\circ} \cdot \sin 89^{\circ}}{\sin 89^{\circ} \cdot \sin 90^{\circ}}\right] \\
& =\frac{1}{\sin 1^{\circ}}\left[\cot 1^{\circ}-\cot 2^{\circ}+\cot 2^{\circ}-\cot 3^{\circ}+\ldots\right.
\end{aligned}
$$

22. (d) For option I,

$\sin \left(-292^{\circ}\right)=-\sin 292^{\circ}$

$$
\begin{aligned}
& =-\sin \left(360^{\circ}-68^{\circ}\right)=-\sin 68^{\circ} \\
& =-(-)=+\text { vevalue }
\end{aligned}
$$

So, clearly $\sin \left(-292^{\circ}\right)$ give + ve value.

For option II,

$$
\tan \left(-193^{\circ}\right)=-\tan 193^{\circ}
$$

$$
=-\tan \left(180^{\circ}+13^{\circ}\right)
$$

$$
\begin{aligned}
& =-\operatorname{tanl} 3^{\circ} \text { (-ve value) }
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-04.jpg?height=154&width=704&top_left_y=2113&top_left_x=1112)



$$
\begin{aligned}
& \text { For option III, } \\
& \begin{aligned}
\cos \left(-207^{\circ}\right) & =\cos 207^{\circ} \\
& =\cos \left(180+27^{\circ}\right) \\
& =-\cos 27^{\circ}(-\text { ve value })
\end{aligned}
\end{aligned}
$$

For option IV,

$$
\cot \left(-222^{\circ}\right)=\cot \left(180^{\circ}+42^{\circ}\right)
$$

$$
=+\cot 42^{\circ}(+\text { ve value })
$$

23. (d) We have, $\sin \theta+\operatorname{cosec} \theta=4$

$\Rightarrow \frac{1}{\operatorname{cosec} \theta}+\operatorname{cosec} \theta=4$

Squaring both sides,

$$
\begin{aligned}
& \frac{1}{\operatorname{cosec}^{2} \theta}+\operatorname{cosec}^{2} \theta+2=16 \\
\Rightarrow & \sin ^{2} \theta+\operatorname{cosec}^{2} \theta=16-2=14
\end{aligned}
$$

24. (b) Here,

$$
\begin{aligned}
& \sin ^{2}\left(\frac{2 \pi}{3}\right)+\cos ^{2}\left(\frac{5 \pi}{6}\right)-\tan ^{2}\left(\frac{3 \pi}{4}\right) \\
= & \sin ^{2}\left(\pi-\frac{\pi}{3}\right)+\cos ^{2}\left(\pi-\frac{\pi}{6}\right)-\tan ^{2}\left(\pi-\frac{\pi}{4}\right) \\
= & \sin ^{2}\left(\frac{\pi}{3}\right)+\left(-\cos \left(\frac{\pi}{6}\right)\right)^{2}-\left(-\tan \frac{\pi}{4}\right)^{2} \\
= & \left(\frac{\sqrt{3}}{2}\right)^{2}+\left(\frac{-\sqrt{3}}{2}\right)^{2}-(-1)^{2} \\
= & \left.\frac{3}{4}+\frac{3}{4}-1=\frac{6}{4}-1=\frac{1}{2} \begin{array}{l}
\cos (\pi-x)=-\cos x, \\
\tan (\pi-x)=-\tan x
\end{array}\right]
\end{aligned}
$$

25. (a) Here, $2 \cosh 2 x+10 \sinh 2 x=5$

We know that,

$$
\cosh 2 x=\frac{1}{2}\left(e^{2 x}+e^{-2 x}\right)
$$

$$
\begin{aligned}
& \sinh 2 x=\frac{1}{2}\left(e^{2 x}-e^{-2 x}\right) \\
& \text { So, } 2\left[\frac{1}{2}\left(e^{2 x}+e^{-2 x}\right)\right]+10\left[\frac{1}{2}\left(e^{2 x}-e^{-2 x}\right)\right]=5 \\
& \Rightarrow e^{2 x}+e^{-2 x}+5 e^{2 x}-5 e^{-2 x}=5 \\
& \Rightarrow 6 e^{2 x}-5-4 e^{-2 x}=0 \Rightarrow\left(3 e^{2 x}-4\right)\left(2 e^{2 x}+1\right)=0
\end{aligned}
$$

$$
e^{2 x}=\frac{4}{3} \text { or } e^{2 x}=-\frac{1}{2}
$$

The only real solution occurs when $e^{2 x}>0$.

So, $2 x=\ln \frac{4}{3}$

$\Rightarrow \quad x=\frac{1}{2} \ln \frac{4}{3}$ 26. (b) Given, in a $\triangle A B C$, $\frac{\cos A}{a}+\frac{\cos B}{b}+\frac{\cos C}{c}$

We know that,

$$
\begin{aligned}
& \cos A=\frac{b^{2}+c^{2}-a^{2}}{2 b c} \\
& \cos B=\frac{a^{2}+c^{2}-b^{2}}{2 a c} \\
& \cos C=\frac{a^{2}+b^{2}-c^{2}}{2 a b} \\
& \text { Since, } \frac{b^{2}+c^{2}-a^{2}}{2 a b c}+\frac{a^{2}+c^{2}-b^{2}}{2 a b c}+\frac{a^{2}+b^{2}-c^{2}}{2 a b} \\
& =\frac{b^{2}+c^{2}-a^{2}+a^{2}+c^{2}-b^{2}+a^{2}+b^{2}-c^{2}}{2 a b c} \\
& =\frac{a^{2}+b^{2}+c^{2}}{2 a b c}
\end{aligned}
$$

27. (d) Given,

$$
r_{1}=36, r_{2}=18 \text { and } r_{3}=12
$$

We know that, in a $\triangle A B C$

ఛ. $\quad \frac{1}{r}=\frac{1}{r_{1}}+\frac{1}{r_{2}}+\frac{1}{r_{3}}$

$\Rightarrow \frac{1}{r}=\frac{1}{36}+\frac{1}{18}+\frac{1}{12} \Rightarrow \frac{1}{r}=\frac{2+4+6}{72}$ $r=6$

Now, we know that,

$$
\begin{aligned}
\Delta^{2} & =r \cdot r_{1} \cdot r_{2} \cdot r_{3}=6 \times 36 \times 18 \times 12 \\
\Delta^{2} & =6^{2} \times 6^{2} \times 6^{2} \\
\Delta & =6 \times 6 \times 6=216
\end{aligned}
$$

Again we know that,

$r=\frac{\Delta}{S}=\frac{216}{S}$

$\Rightarrow S=\frac{216}{6}=36$

28. (a) In a $\triangle A B C, a=6$ units, $b=5$ units and

$c=4$ units

As we know that,

$$
\begin{aligned}
\cos A & =\frac{b^{2}+c^{2}-a^{2}}{2 b c} \\
\Rightarrow \cos A & =\frac{b^{2}+c^{2}-a^{2}}{2 b c}=\frac{5^{2}+4^{2}-6^{2}}{2 \times 5 \times 4}=\frac{1}{8}
\end{aligned}
$$

As we know that,

$$
\begin{aligned}
\cos 2 A & =\cos ^{2} A-\sin ^{2} A \\
& =2 \cos ^{2} A-1=2 \times\left(\frac{1}{8}\right)^{2}-1 \\
& =\frac{1}{32}-1=\frac{-31}{32}
\end{aligned}
$$

29. (b) $\mathrm{a}+3 \mathrm{~b}+4 \mathrm{c}=\mathrm{a}(x+y+6 z)+\mathrm{b}(-2 x+5 y+14 z)$

$$
+\mathrm{c}(3 x-2 y+4 z)
$$

(because $a, b$ and $c$ are non-coplanar vectors)

Comparing both sides,

$$
\begin{aligned}
& x+y+6 z=1 \\
& -2 x+5 y+14 z=3 \\
& 3 x-2 y+4 z=4
\end{aligned}
$$

By solving Eqs. (i), (ii) and (iii), we get

$$
\begin{aligned}
& x=-2, y=-3, z=1 \\
& x+y+z=-4
\end{aligned}
$$

30. (b) Let the vectors of magnitude $a, 2 a, 3 a$ are along $O P, O Q, O R$, respectively.

Then, vectors are $O P, O Q, O R$ are

$$
a\left(\frac{\hat{i}+\hat{j}}{\sqrt{2}}\right), 2 a\left(\frac{\hat{j}+\hat{k}}{\sqrt{2}}\right), 3 a\left(\frac{\hat{k}+\hat{i}}{\sqrt{2}}\right) \text {. }
$$

\section{respectively.}

Their resultant say $R$ is given by

$$
\begin{aligned}
\mathbf{R} & =a\left(\frac{\hat{i}+\hat{j}}{\sqrt{2}}\right)+2 a\left(\frac{\hat{j}+\hat{k}}{\sqrt{2}}\right)+3 a\left(\frac{\hat{k}+\hat{i}}{\sqrt{2}}\right) \\
& =\frac{\dddot{a}}{\sqrt{2}}(4 \hat{i}+3 \hat{j}+5 \hat{k})
\end{aligned}
$$

$\therefore|R|=\sqrt{\frac{a^{2}}{2}(16+9+25)}=5 a$

31. (c) Let $\mathbf{a}=x \hat{i}+y \hat{j}+z \hat{k}, b=3 \hat{i}+6 \hat{j}+6 \hat{k}$.

$$
\mathbf{a} \cdot \mathbf{b}=27
$$

According to question, $a$ is a collinear with $b$, then

$$
a=\lambda b
$$

$\Rightarrow \quad \mathbf{a} \cdot \mathbf{b}=27$

$\Rightarrow \quad \lambda b \cdot b=27$

$\Rightarrow \quad \lambda|b|^{2}=27$

$$
\lambda=\frac{27}{\left(\sqrt{(3)^{2}+(6)^{2}+(6)^{2}}\right)^{2}}=\frac{27}{(9)^{2}}
$$

$$
\begin{aligned}
& \lambda=\frac{1}{3}
\end{aligned}
$$

$$
a=\frac{1}{3}(3 \hat{i}+6 \hat{j}+6 \hat{k}) \Rightarrow a=\hat{i}+2 \hat{j}+2 \hat{k}
$$

So, $|a|=\sqrt{1+(2)^{2}+(2)^{2}}$

$$
=\sqrt{9}=3 \text { units }
$$

[from Eq. (i)]

32. (c) As given a is perpendicular to $b$ and $c$

$\Rightarrow \mathbf{a} \cdot \mathbf{b}=\mathbf{0}$ and $\mathbf{a} \cdot \mathbf{c}=\mathbf{0}$ and angle between $\mathbf{b}$ and $\mathrm{c}=\frac{\pi}{3}$

$\therefore \mathbf{b} \cdot \mathbf{c}=|\mathbf{b}||\mathbf{c}| \cos \frac{\pi}{3}=1 \cdot 1 \cdot \frac{1}{2}$

$$
\begin{aligned}
& =\frac{1}{2}
\end{aligned}
$$

[ $\because \mathbf{b}$ and $\mathbf{c}$ are unit vectors]

Now, $|a+b+c|^{2}=|a|^{2}+|b|^{2}+|c|^{2}$

$+2(a \cdot b+b \cdot c+c \cdot a)$

$=1+1+1+2\left(0+\frac{1}{2}+0\right)=1+1+1+1=4$

$|a+b+c|=\sqrt{4}=2$ units

33. (d) Given,

$$
\begin{aligned}
& \mathbf{F}=2 i+2 j+5 k, A=(1,2,5) \\
& B=(-1 ;-2,-3) \\
& \mathbf{B A}=\mathbf{A}-\mathbf{B}=(\hat{i}+2 \hat{j}+5 \hat{k})-(-\hat{i}-2 \hat{j}-3 \hat{k}) \\
& \mathbf{B A}=2 \hat{i}+4 \hat{j}+8 \hat{k} \\
& \mathbf{B A} \times \mathbf{F}=\left|\begin{array}{lll}\hat{i} & \hat{j} & \hat{k} \\2 & 4 & 8 \\2 & 2 & 5\end{array}\right| \\
& =\hat{i}(20-16)-\hat{j}(10-16)+\hat{k}(4-8) \\
& =4 \hat{i}+6 \hat{j}-4 \hat{k} \\
& \text { So, } 4 \hat{i}+6 \hat{j}-4 \hat{k}=4 \hat{i}+6 \hat{j}+2 \lambda \hat{k} \\
& \because \quad 2 \lambda=-4 \\
& \lambda=-2
\end{aligned}
$$

34. (a) Mean $\bar{x}=\frac{\text { Sum of quantities }}{n}$

$$
\begin{aligned}
& =\frac{\frac{n}{2}(a+l)}{n}
\end{aligned}
$$

$[l=$ last team $]$

$=\frac{1}{2}(a+l)=\frac{1}{2}(1+1+100 d)$

$=1+50 \mathrm{~d}$

$\mathrm{MD}=\frac{1}{n} \Sigma\left|x_{i}-\bar{x}\right|$

$\Rightarrow 255=\frac{1}{101}[50 d+49 d+48 d+\ldots$

$+d+0+d+\ldots . .+50 d]$

$\Rightarrow 255=\frac{2 d}{101}\left[\frac{50 \times 51}{2}\right]$.

$d=\frac{255 \times 101}{50 \times 51}=101$

35. (c) When twa dice are rolled together, then total outcomes are 36 and sample space is

$[(1,1),(1,2),(1,3),(1,4),(1,5)(1,6)$,

$(2,1),(2,2),(2,3),(2,4),(2,5),(2,6)$,

$(3,1),(3,2),(3,3),(3,4),(3,5),(3,6)$,

$(4,1),(4,2),(4,3),(4,4),(4,5),(4,6)$,

$(5,1),(5,2),(5,3),(5,4),(5,5),(5,6)$,

$(6,1),(6,2),(6,3),(6,4),(6,5),(6,6)]$ So, pairs with sum 9 are $(3,6)(4,5),(5,4),(6,3)$ i.e total 4 pairs.

Total outcomes $=36$

Favourable outcomes $=4$

Probability of getting the sum of 9

$$
=\frac{4}{36}=\frac{1}{9}
$$

36. (c) $P(\bar{A} \mid \bar{B})=\frac{P(\bar{B} \cap \bar{A})}{P(B)}=\frac{1-P(A \cup B)}{P(B)}$

37. (c) Given, $A$ be the event that $x$ is selected and $B$ is the event that $y$ is selected.

$P(A)=\frac{1}{7}, P(B)=\frac{2}{9}$.

Let $C$ be the event that both are selected.

$P(C)=P(A) \times P(B)$ as $A$ and $B$ are independent events

$$
=\frac{1}{7} \times\left(\frac{2}{9}\right)=\frac{2}{63}
$$

38. (d) A red ball can be drawn in two mutually exclusive ways.

(i) Selecting bag I and then drawing a red ball from it.

(ii) Selecting bag II and then drawing a red ball from it

Let $E_{1}, E_{2}$ and $A$ denote the events defined as follows

$$
\begin{aligned}
& E_{1}=\text { Selecting bag I } \\
& E_{2}=\text { Selecting bag II }
\end{aligned}
$$

Since, one of the two bags is selected randomly.

$\therefore P\left(E_{1}\right)=\frac{1}{2}$ and $P\left(E_{2}\right)=\frac{1}{2}$

Now, $P\left(\frac{A}{E_{1}}\right)=$ Probability of drawing a red ball

when the first bag has been selected $=4 / 7$

$P\left(\frac{A}{E_{2}}\right)=$ Probability of drawing a red ball when the second bag has been selected $=2 / 5$

$$
\begin{aligned}
P(\text { red ball }) & =P\left(E_{1}\right) P\left(\frac{A}{E_{1}}\right)+P\left(E_{2}\right) P\left(\frac{A}{E_{2}}\right) \\
& =\frac{1}{2} \times \frac{4}{7}+\frac{1}{2} \times \frac{2}{5}=\frac{2}{7}+\frac{1}{5}=\frac{17}{35}
\end{aligned}
$$

39. (a) Let $X$ be the binomial variate for which mean $=4$ and variance $=3$, then $n p=4$ and $n p q=3$ $\Rightarrow q=\frac{3}{4}$

$\therefore P=(1-q)=\left(1-\frac{3}{4}\right)=\frac{1}{4}$ and $n p=4$ $\Rightarrow n=\frac{4}{1} \times 4=16$

Thus, $n=16, p=\frac{1}{4}$ and $q=\frac{3}{4}$

Hence, the binomial distribution

$$
\begin{aligned}
& 2^{32} P\left(X=\frac{n}{2}\right)=2^{32} \cdot{ }^{16} C_{\frac{16}{2}} \cdot\left(\frac{1}{4}\right)^{\frac{16}{2}}\left(\frac{3}{4}\right)^{16-\frac{16}{2}} \\
& =2^{32} \cdot{ }^{16} C_{8}\left(\frac{1}{4}\right)^{8} \times\left(\frac{3}{4}\right)^{8}=2^{32} \cdot{ }^{16} C_{8} \frac{(3)^{8}}{(4)^{16}} \\
& ={ }^{16} C_{8}(3)^{8} \\
& \left[\because(4)^{16}=\left(2^{32}\right]\right.
\end{aligned}
$$

40. (b) For Poisson distribution, mean $=$ variance

$$
\text { So, } \begin{aligned}
& l=m=4 \\
& e^{4}[1-P(X>2)] \\
&=e^{4}[P \leq 2] \\
&=e^{4}[P(X=0)+P(X=1)+P(X=2] \\
&=e^{4}\left[\frac{e^{-4} \times 4^{0}}{0 !}+\frac{e^{-4} \times 4^{4}}{1 !}+\frac{e^{-4} \times 4^{2}}{2 !}\right] \\
&=e^{4} \times e^{-4}(1+4+8)=13
\end{aligned}
$$

41. (*) Let the line cut the axes in $A$ and $B$ and if $(h, k)$ be the mid-point of $A B$, then

$$
2 h=\frac{1}{\cos \theta}, 2 k=\frac{1}{\sin \theta} .
$$

In order to find the locus, eleminate the variable $\theta$ by $\cos ^{2} \theta+\sin ^{2} \theta=1$

$$
\frac{1}{4 h^{2}}+\frac{1}{4 k^{2}}=1 \Rightarrow \frac{1}{x^{2}}+\frac{1}{y^{2}}=4
$$

42. $(a)$

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-07.jpg?height=373&width=652&top_left_y=1738&top_left_x=1130)

Let the line $P Q$ be

$$
y-5=m(x-1)
$$

Substituting $y=m x+5-m$ in the equation

$$
5 x-\dot{y}-4=0
$$

We have, $5 x-m x-5+m-4=0$

$\Rightarrow \quad(5-m) x+m-9=0$

Therefore, $x=\frac{9-m}{5-m}$ and $y=m\left(\frac{9-m}{5-m}\right)+5-m$

$$
=\frac{25-m}{5-m}
$$

Here, $Q=\left(\frac{9-m}{5-m}, \frac{25-m}{5-m}\right)$ Substituting $y=m x+5-m$ in the equation

$$
3 x+4 y-4=0
$$

We have, $3 x+4(m x+5-m)-4=0$

$$
(3+4 m) x+16-4 m=0
$$

Therefore, $x=\frac{4 m-16}{4 m+3}$

and

$$
y=\frac{m(4 m-16)}{4 m+3}+5-m
$$

$$
y=\frac{m+15}{4 m+3}
$$

Hence, $P=\left(\frac{4 m-16}{4 m+3}, \frac{m+15}{4 m+3}\right)$

Since, $m(1,5)$ is the mid-point of $P Q$, we have

$$
1=\frac{1}{2}\left[\frac{9-m}{5-m}+\frac{4 m-16}{4 m+3}\right]
$$

and $5=\frac{1}{2}\left[\frac{25-m}{5-m}+\frac{m+15}{4 m+3}\right]$

From Eq. (ii), we get

$2(5-m)(4 m+3)$

$=(9-m)(4 m+3)+(5-m)(4 m-16)$

$\Rightarrow 2\left(-4 m^{2}+17 m+15\right)=\left(-4 m^{2}+33 m+27\right)$

$+\left(-4 m^{2}+36 m-80\right)$

$\Rightarrow-8 m^{2}+.34 m+30=-8 m^{2}+69 m-53$

$\Rightarrow \quad 35 m=83$

$\Rightarrow \quad \dot{m}=\frac{83}{35}$

43. (b)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-08.jpg?height=283&width=374&top_left_y=1689&top_left_x=201)

\section{Length of intercept $=$}

$$
\sqrt{(-1+1)^{2}+(4-3)^{2}}=1
$$

4. (c) Let the coordinate $A\left(x_{1}, y_{1}\right), B\left(x_{2}, y_{2}\right)$ and $C\left(x_{3}, y_{3}\right)$.

According to question, $x$ - coordinate as well as $y$ coordinates are in GP.

Let $x_{1}=a, x_{2}=$ ar and $x_{3}=a r^{2}$.

$y_{1}=b_{1} y_{2}=b r$ and $y_{3}=b r^{2}$

Now, $A(a, b), B(a r, b r), C\left(a r^{2}, b r^{2}\right)$.

Slope of $A B=\frac{b(1-r)}{a(1-r)}=\frac{b}{a}$ and

Slope of $\mathrm{BC}=\frac{b r(1-r)}{\operatorname{ar}(1-r)}=\frac{b}{a}$

As slope of $\triangle D$ - Slope of $B C$ $\therefore A, B$ and $C$ are collinear.

$\therefore A, B$ and $C$ lie on a straight line.

45. (a) Given, lines $a x^{2}+2 h x y+b y^{2}=0$

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-08.jpg?height=160&width=442&top_left_y=480&top_left_x=1361)

$$
y-m_{1} x=0
$$

$$
\begin{aligned}
& y-m_{2} x=0
\end{aligned}
$$

$\Rightarrow\left(y-m_{1} x\right)\left(y-m_{2} x\right)=0$

$y^{2}-\left(m_{1}+m_{2}\right) x y+m_{1} m_{2} x^{2}=0$

Now, $a x^{2}+2 h x y+b y^{2}=0$

$\left(\frac{a}{b}\right) x^{2}+\frac{2 h}{b} x y+y^{2}=0 \Rightarrow m_{1} \cdot m_{2}=\frac{a}{b}$

$\therefore \quad 2=\frac{a}{b} \Rightarrow a=2 b$

$\Rightarrow$

$\frac{a}{12}=\frac{b}{6}$

46. $(*)$

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-08.jpg?height=463&width=546&top_left_y=1199&top_left_x=1189)

$$
y^{2}-8 x y-9 x^{2}=0
$$

$y^{2}-9 x y+x y-9 x^{2}=0$

$(y-9 x)(y+x)=0$

The two given lines are $y=9 x$ and $y=-x$

Slope of line $y=9 x$ is 9 and slope of line $y=-x$ is $-1$.

Let $A B$ and $B C$ be the line perpendicular to $y=9 x$ and $y=-x$ respectively.

Slope of $A B=\frac{-1}{9}$ and slope of line $B C$ is 1 .

Equation of $A B$ is $y-\beta=\frac{-1}{9}(x-\alpha)$

$$
9 y-9 \beta=-x+\alpha
$$

$\Rightarrow \quad x+9 y-\alpha-9 \beta=0$

$M$ is Mid-point of the $A B$ and $y=9 x$.

So, $x+9(9 x)+\alpha+9 \beta$

$$
\begin{array}{r}
82 x=\alpha+9 \beta \\
\dot{x}=\frac{\alpha+9 \beta}{82}
\end{array}
$$

Coordinate of $M$ is $\left(\frac{\alpha+9 \beta}{82}, \frac{9 \alpha+81 \beta}{82}\right)$. $M$ is Mid-point of $A B$,

Let coordinate of $A$ be $h, k$

$$
\begin{array}{rlrl} 
& & \frac{\alpha+9 \beta}{82}= & \frac{\alpha+h}{2} \text { and } \frac{9 \alpha+81 \beta}{82}=\frac{\beta+k}{2} \\
\Rightarrow & 2 \alpha+18 \beta=82 \alpha+82 h \\
\Rightarrow & 82 h=-80 \alpha+18 \beta \\
\Rightarrow & h=\frac{-80 \alpha+18 \beta}{82} \\
\text { and } 18 \alpha+162 \beta=82 \beta+82 k \\
\Rightarrow & 82 k=18 \alpha-80 \beta \\
\Rightarrow & & k=\frac{18 \alpha-80 \beta}{82}
\end{array}
$$

Equation of $B C$ is $y-\beta=1(x-\alpha)$

$$
x-y=\alpha-\beta
$$

$N$ is intersection point of $B C$ and $y=-x$

$\therefore \quad x+x=\alpha-\beta$

$\Rightarrow \quad 2 x=\alpha-\beta$

$\Rightarrow \quad x=\frac{\alpha-\beta}{2}$

$\Rightarrow \quad y=\frac{\beta-\alpha}{2}$

Coordinate of $N$ is $\left(\frac{\alpha-\beta}{2}, \frac{\beta-\alpha}{2}\right)$.

$N$ is Mid-point of $B C$.

Let coordinate of $C$ be $(a, b)$

$\frac{\alpha-\beta}{2}=\frac{\alpha+a}{2}$ and $\frac{\beta-\alpha}{2}=\frac{\beta+b}{2}$

$\Rightarrow a=-\beta$ and $b=-\alpha$

$\therefore$ Coordinate of $C$ is $(-\beta,-\alpha)$.

Centroid of $A B C$ is

$\left(\frac{h+a+\alpha}{3}, \frac{k+b+\beta}{3}\right)$

$=\left(\frac{1}{2}\left[\frac{-80 \alpha+18 \beta}{52}-\beta+\alpha\right], \frac{1}{2}\left[\frac{18 \alpha-80 \beta}{82}-\alpha+\beta\right]\right)$

$=\left(\frac{1}{2}\left[\frac{-80 \alpha+18 \beta-82 \beta+82 \alpha}{82}\right]\right.$,

$\left.\frac{1}{3}\left[\frac{18 \alpha-80 \beta-82 \alpha+82 \beta}{82}\right]\right)$

$=\left(\frac{1}{3}\left[\frac{2 \alpha-64 \beta}{82}\right], \frac{1}{3}\left[\frac{-64 \alpha+2 \beta}{82}\right]\right)$

$=\frac{1}{123}(\alpha-32 \beta,-32 \alpha+\beta)$

47. (d) Equation of the given tangents are

$$
\begin{aligned}
E_{1}=3 x-4 y+4 & =0 \\
E_{2}=6 x-8 y-7 & =0 \\
\Rightarrow \quad 3 x-4 y-\frac{7}{2} & =0
\end{aligned}
$$

Here, $a=3, b=-4 c_{1}=4, c_{2}=\frac{-7}{2}$

Since, slopes of the given tangents are equal, i.e. $\frac{3}{4}$.

$\therefore$ The given tangents are parallel,

$$
\begin{aligned}
& d=\left|\frac{c_{2}-c_{1}}{\sqrt{a^{2}+b^{2}}}\right|=\left|\frac{4-\left(\frac{-7}{2}\right)}{\sqrt{3^{2}+(-4)^{2}}}\right| \\
& d=\frac{\frac{15}{2}}{\sqrt{9+16}}=\frac{15}{2 \times 5}=\frac{3}{2}
\end{aligned}
$$

As we know that distance between two parallel tangents of a circle is equal to the diameter of that circle.

$\therefore$ Diameter of given circle $=\frac{3}{2}$

$\therefore$ Radius of the given circle $=\frac{\text { Diameter }}{2}$

$$
=\left(\frac{3 / 2}{2}\right)=\frac{3}{4}
$$

48. (a) Since, the line $(x-2) \cos \theta+(y-2) \sin \theta=1$ touches a circle. So it is a tangent equation to a circle.

Equation of tangent to a circle at

$\left(x_{1}, y_{1}\right)$ is $(x-h) x_{1}+(y-k) y_{1}$

$=a^{2}$ to a circle

$(x-h)^{2}+(y-k)^{2}=a^{2}$

Then, after comparing

$$
\begin{aligned}
& x-h=x-2 y-k=y-2 \text { and } a^{2}=1 \\
& x_{1}=\cos \theta, y_{1}=\sin \theta
\end{aligned}
$$

$\therefore$ Required equation of circle

$$
(x-2)^{2}+(y-2)^{2}=1
$$

$\Rightarrow x^{2}+y^{2}-4 x-4 y+7=0$

49. (d) Given equation $\left(x^{2}+y^{2}-4 x-2 y-20=0\right)$

So, $C=(2,1)$ and radius $=\sqrt{(g)^{2}+(f)^{2}-c}$

$$
=\sqrt{(2)^{2}+(1)^{2}+20}
$$

Radius $=5$

When substituted $x=10$ and $y=7$ in equation, then value becomes

$$
(10)^{2}+(7)^{2}-4(10)-2(7)-20=75
$$

which is greater than zero.

Thus, the point $(10,7)$ lies outside the circle.

Its distance from the centre of the circle $(2,1)$ is $\sqrt{(10-2)^{2}+(7-1)^{2}}=10$ units

So, the minimum distance from the circle therefore becomes $10-5=5$ units 50. (a) Let $x_{1}$ and $x_{2}$ are roots of equation $x^{2}+2 x-a^{2}=0$ and $y_{1}$ and $y_{2}$ are roots of equation $y^{2}+4 b-b^{2}=\left(x-x_{1}\right)\left(x-x_{2}\right)=0$ and $y^{2}+4 b-b^{2} \rightarrow y_{1}, y_{2}$ $=\left(y-y_{1}\right)\left(y-y_{2}\right)$ (roots of equation)

Let $A\left(x_{1}, y_{1}\right)$ and $B\left(x_{2}, y_{2}\right)$.

Now, the equation of circle with diameter $A B$ is given by $\Rightarrow\left(x-x_{1}\right)\left(x-x_{2}\right)+\left(y-y_{1}\right)\left(y-y_{2}\right)=0$ $\Rightarrow x^{2}+2 x-a^{2}+y^{2}+4 y-b^{2}=0$ $\Rightarrow x^{2}+y^{2}+2 x+4 y=a^{2}+b^{2}$ $\Rightarrow x^{2}+y^{2}+2 x+4 y-a^{2}-b^{2}=0$

51. (a) Let $S_{1}: x^{2}+y^{2}-1=0$ $S_{2}: x^{2}+y^{2}-8 x+15=0$ and $S_{3}: x^{2}+y^{2}+10 y+24=0$ From Eqs. (i) and (ii),

$$
8 x-15=1
$$

$\Rightarrow x=2$

Now, from Eqs. (i) and (iii),

$$
-10 y-24=1
$$

$\Rightarrow-10 y=25 \Rightarrow y=\frac{-5}{2}$

Hence, the radical centre is $\left(2, \frac{-5}{2}\right)$.

52. (b) From option (a).

$x=4 \cos t, y=4 \sin t$

$x^{2}=16 \cos ^{2} t, y^{2}=16 \sin ^{2} t$

So, $x^{2}+y^{2}=16$, so this equation of a circle.

From option (b),

$$
\begin{aligned}
& x^{2}-2=-2 \cos t, y=\cos ^{2}\left(\frac{t}{2}\right) \\
& x^{2}=2-2 \cos t \\
& y=\frac{1+\cos }{2}
\end{aligned}
$$

From Eq. (ii),

$\cos t=2 y-1$

Now, $x^{2}=2-2 \cos t$

$$
\begin{aligned}
x^{2} & =2-2(2 y-1) \Rightarrow x^{2}=2-4 y+2 \\
x^{2} & =4-4 y
\end{aligned}
$$

So, this is represent the parabola.

53. (d)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-10.jpg?height=406&width=534&top_left_y=2347&top_left_x=241)

Apply pythagoras theorem, in $\triangle A S_{1} S_{2}$

$$
\begin{array}{rlrl}
\left(S_{1} A\right)^{2}+\left(A S_{2}\right)^{2} & =\left(S_{1} S_{2}\right)^{2} \\
a^{2}+a^{2} & =(2 a e)^{2} \\
\Rightarrow & 2 a^{2} & =4 a^{2} e^{2} \\
\therefore & e & =\frac{1}{\sqrt{2}}
\end{array}
$$

54. (c) Let $p(h, k)$ be the point of intersection of tangents at the ends of a normal chord of the hyperbola, $\dot{x}^{2}-y^{2}=a^{2}$, then the equation of the chord is

$$
h x-k y=a^{2}
$$

But its is normal chord. So; its equation must be of the form $x \cos \theta+y \cot \theta=2 a$

Eqs. (i) and (ii) represents the same line

$\therefore \quad \frac{\cos \theta}{h}=\frac{\cot \theta}{-k}=\frac{2 a}{a^{2}}$

$$
\sec \theta=\frac{a}{2 h^{\prime}}, \tan \theta=\frac{-a}{2 k}
$$

$\therefore \quad \sec ^{2} \theta-\tan ^{2} \theta=1$

$\Rightarrow \quad \frac{a^{2}}{4 h^{2}}-\frac{b^{2}}{4 k^{2}}=1$

$\Rightarrow \quad a^{2}\left(k^{2}-h^{2}\right)=4 h^{2} k^{2}$

Therefore, the locus of $p(h, k)$ is $a^{2}\left(y^{2}-x^{2}\right)=4 x^{2} y^{2}$

55. (b) Given, hyperbola is $16 x^{2}-9 y^{2}=1$

$$
\begin{aligned}
& \frac{x^{2}}{\frac{1}{16}}-\frac{y^{2}}{\frac{1}{9}}=1 \\
& \frac{x^{2}}{\left(\frac{1}{4}\right)^{2}}-\frac{y^{2}}{\left(\frac{1}{3}\right)^{2}}=1
\end{aligned}
$$

We know that

Eccentricity of a hyperbola, $e_{1}^{2}=1+\frac{b^{2}}{a^{2}}$

$\Rightarrow e_{1}^{2}=1+\frac{1 \times 16}{9 \times 1}$

$\Rightarrow e_{1}^{2}=\frac{25}{9}$

$\Rightarrow e_{1}=\frac{5}{3}$

Now, eccentricity of its conjugate

$$
\begin{aligned}
& \quad e_{2}^{2}=1+\frac{a^{2}}{b^{2}} \\
& \Rightarrow \quad e_{2}^{2}=1+\frac{1 \times 9}{16 \times 1} \\
& \Rightarrow \quad e_{2}^{2}=\frac{25}{16} \\
& \Rightarrow \quad e_{2}=\frac{5}{4}
\end{aligned}
$$



\section{AP EAPCET (Engineering) Solved Papers 111}

From Eqs. (i) and (ii),

$$
3 e_{1}=3 \times \frac{5}{3}=\frac{5}{4} \times 4
$$

$\Rightarrow$

$$
3 e_{1}=4 e_{2} \quad \text {. }\left[\because e_{2}=\frac{5}{4}\right]
$$

56. (b) Given, points $A(1,2,-1)$ and $B(-1,0,1)$ and $P$ divides the line segment externally in the ratio $1: 2$.

For external division, coordinates are

$\left[\frac{m_{1} x_{2}-m_{2} x_{1}}{m_{1}-m_{2}}, \frac{m_{1} y_{2}-m_{2} y_{1}}{m_{1}-m_{2}}, \frac{m_{1} z_{2}-m_{2} z_{1}}{m_{1}-m_{2}}\right]$

$$
=\left[\frac{1(-1)-2(1)}{1-2}, \frac{1(0)-2(2)}{1-2}, \frac{1(1)-2(-1)}{1-2}\right]
$$

$$
\begin{aligned}
& =\left[\frac{-1-2}{-1}, \frac{-4}{-1}, \frac{3}{-1}\right]
\end{aligned}
$$

$$
=[3,4,-3]
$$

So, $P Q=\sqrt{(3-1)^{2}+(4-3)^{2}+(-3+1)^{2}}$

$$
\begin{aligned}
& =\sqrt{(2)^{2}+(1)^{2}+(-2)^{2}} . \\
& =\sqrt{4+1+4}=3 \text { units }
\end{aligned}
$$

57. (b) Direction cosine of $a \hat{i}+b \hat{j}+c \hat{k}$ can be

$\frac{a}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{b}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{c}{\sqrt{a^{2}+b^{2}+c^{2}}}$

According to question,

$\sqrt{a^{2}+b^{2}+c^{2}}=\sqrt{83}, b=5$

$\Rightarrow \quad a^{2}+(5)^{2}+c^{2}=83$

$\Rightarrow a^{2}+c^{2}=83-25$

$\Rightarrow a^{2}+c^{2}=58$

and $c-a=4$

[given]

$(c-a)^{2}+2 a c=a^{2}+c^{2}$

$\Rightarrow(4)^{2}+2 a c=58$

[from Eq. (i), $c^{2}+a^{2}=58$ ]

$\Rightarrow 2 a c=58-16$

$$
a c=\frac{42}{2}=21
$$

58. (d) The equation of plane passes through the point $(1,0,1)$ is

$a(x-1)+b(y-0)+c(z-1)=0$

If this plane is perpendicular to the planes

$2 x+3 y-z=2$ and $x-y+2 z=1$

Then, $2 a+3 b-c=2$ and $a-b+2 c=1$

$\Rightarrow \frac{a}{6-1}=\frac{b}{-1-4}=\frac{c}{2(-1)-3}$

$\Rightarrow \frac{a}{5}=\frac{b}{-3}=\frac{c}{-5}=k$

Let $a=5 k, b=-3 k, c=-5 k$ Putting the values of $a, b$ and $c$ in Eq. (i), we get the required equation of plane

$$
5 k(x-1)+(-3 k)(y)+(-5 k)(z-1)=0
$$

$\Rightarrow 5 x-5-3 y-5 z+5=0$

$\Rightarrow 5 x-3 y-5 z=0$

Now, plane passing through $(11,7,5)$ and parallel to the plane $\pi(5 x-3 y-5 z)$.

Equation of a plane parallel to

$$
5 x-3 y-5 z=k
$$

and passing through $(11,7,5)$

$5(11)-3(7)-5(5)=k$

$\Rightarrow \quad 55-21-25=k$

$\Rightarrow \quad k=9$

So, equation of plane

$\Rightarrow 5 x-3 y-5 z=9$

Comparing with $a x+b y-z+d=0$ (given)

So, $a=5, b=-3, c=5, d=9$

$$
\frac{a}{b}+\frac{b}{d}=\frac{5}{-3}+\frac{-3}{9}
$$

$\Rightarrow \frac{a}{b}+\frac{b}{d}=\frac{-15-3}{9}=\frac{-18}{9}=-2$

59. (b) Here, $\lim _{x \rightarrow-\infty} \log _{i}(\cosh x)+x$

$$
=\lim _{x \rightarrow-\infty} \log \left(e^{x}+e^{-x}\right)+\ln 2
$$

$\Rightarrow \quad \lim _{x \rightarrow-\infty} \log \left(1+e^{2 x}\right)+\ln 2$

$$
=-\ln 2
$$

60. (c) $\lim _{x \rightarrow \infty} \frac{(b-c) x^{2}+(c-a) x+(a-b)}{(a-b) x^{2}+(b-c) x+(c-a)}=\frac{1}{a}$

$=\lim _{x \rightarrow \infty} \frac{x^{2}}{x^{2}}\left[\frac{(b-c)+(c-a) \frac{1}{x}+\frac{(a-b)}{x^{2}}}{(a-b)+(b-c) \frac{1}{x}+\frac{(c-a)}{x^{2}}}\right]=\frac{1}{2}$

$=\frac{b-c}{a-b}=\frac{1}{2}$

$\Rightarrow \quad 2 b-2 c=a-b$

$\Rightarrow 3 b=a+2 c$

61. (a) $\lim _{x \rightarrow-\infty} \frac{3|x|-x}{|x|-2 x}-\lim _{x \rightarrow 0} \frac{\log \left(1+x^{3}\right)}{\sin ^{3} x}$

$$
\lim _{x \rightarrow-\infty} \frac{-3 x-x}{-x-2 x}-\lim _{x \rightarrow 0} \frac{\log \left(1+x^{3}\right)}{x^{3} \frac{\left(\sin x^{3} x\right)}{x^{3}}}
$$

$\Rightarrow \lim _{x \rightarrow-\infty} \frac{-4 x}{-3 x}-\lim _{x \rightarrow 0} \frac{1}{\left(\frac{\sin ^{3} x}{x^{3}}\right)}$

$\lim _{x \rightarrow-\infty} \frac{4}{3}-1=\frac{1}{3}$ 62. (c) $3 f(\cos x)+2 f(\sin x)=5 x$

$3 f(\sin x)+2 f(\cos x)=5\left(\frac{\pi}{2}-x\right)$

Solving Eqs. (i) and (ii) simultaneously, we get

$$
f(\cos x)=5 x-\pi
$$

$\Rightarrow-\sin x f^{\prime}(\cos x)=5$

$\Rightarrow \quad f^{\prime}(\cos x)=\frac{-5}{\sin x}$

Similarly, $f^{\prime}(\sin x)=\frac{-5}{\cos x}$

$$
=f^{\prime}(\cos x)+f^{\prime}(\sin x)
$$

$$
\begin{aligned}
& =\frac{-5}{\sin x}-\frac{5}{\cos x}
\end{aligned}
$$

63. (a) Assertion: $\frac{d}{d x}\left(\frac{x^{2} \sin x}{\log x}\right)$

$=\frac{(\log x)\left[x^{2} \cos x+2 x \sin x\right]-x \sin x}{(\log x)^{2}}$.

$=\frac{x^{2} \cos x \log x+2 x \sin x \log x-x \sin x}{(\log x)^{2}}$

$=\frac{x^{2} \sin x}{\log x}\left[\cot x+\frac{2}{x}-\frac{1}{x \log x}\right]$

Reason : $\frac{d}{d x}\left(\frac{u v}{w}\right)=\frac{u w}{w}\left[\frac{u^{\prime}}{u}+\frac{v^{\prime}}{v}+\frac{w}{w}\right]$.

64. (c) Given,

$$
x=f(\theta)
$$

and $y=g(\theta)$

$$
\frac{d x}{d \theta}=f^{\prime}(\theta), \frac{d y}{d \theta}=g^{\prime}(\theta)
$$

$\Rightarrow \frac{d y}{d x}=\frac{g^{\prime}(\theta)}{f^{\prime}(\theta)}$

$\Rightarrow \frac{d^{2} y}{d x^{2}}=\left(\frac{g^{\prime \prime}(\theta) f^{\prime}(\theta)-f^{\prime \prime}(\theta) g^{\prime}(\theta)}{\left(f^{\prime}(\theta)^{2}\right)}\right) \frac{d \theta}{d x}$

$\Rightarrow \frac{d^{2} y}{d x^{2}}=\left(\frac{g^{\prime \prime}(\theta) f^{\prime}(\theta)-f^{\prime \prime}(\theta) g^{\prime}(\theta)}{\left(f^{\prime}(\theta)\right)^{3}}\right)$.

65. (a) Given curve $3 y=6 x-5 x^{3}$

$\Rightarrow \quad \frac{d y}{d x}=2 \div 5 x^{2}$

Slope of normal $=\frac{-1}{2-5 x^{2}}$.

Equation of normal with slope $\frac{-1}{2-5 x^{2}}$

passing through origin $(0,0)$.

$$
\frac{\left(y-y_{1}\right)}{x-x_{1}}=m
$$

$\Rightarrow \frac{y-0}{x-0}=\frac{-1}{2-5 x^{2}} \Rightarrow \frac{y}{x}=\frac{-1}{2-5 x^{2}}$

Since, $(h, k)$ lies on normal

$\frac{k}{h}=\frac{-1}{2-5 h^{2}}$

$\Rightarrow \frac{k}{h}=\frac{1}{5 h^{2}-2}$

Since, $(h, k)$ lies on curve

$$
3 k=6 h-5 h^{3} \text {. }
$$

$\Rightarrow \quad 3 k=h\left(6-5 h^{2}\right)$

$\Rightarrow \frac{k}{h}=\frac{6-5 h^{2}}{3}$

On solving Eqs. (i) and (ii),

$\frac{1}{5 h^{2}-2}=\frac{6-5 h^{2}}{3}$.

$\Rightarrow \quad 3=\left(6-5 h^{2}\right)\left(5 h^{2}-2\right)$

$\Rightarrow \quad 3=30 h^{2}-12-25 h^{4}+10 h^{2}$

$\Rightarrow 15=-25 h^{4}+40 h^{2}$

$\Rightarrow \quad 5 h^{4}-8 h^{2}+3=0$

For simplicity, let $h^{2}=z$

The equation becomes $5 z^{2}-8 z+3=0$

$$
(5 z-3)(z-1)=0
$$

Now, $z=\frac{3}{5}, 1$

Putting $h^{2}=z$

$\Rightarrow \quad h^{2}=\frac{3}{5} \Rightarrow h=\pm \sqrt{\frac{3}{5}}$

It is not in option.

or $(z-1)=0$

$$
z=1
$$

Putting $h^{2}=z$

$\Rightarrow \quad h^{2}=1$

$h=\pm 1$

But $h=-1$ is not in option.

$\therefore h=1$ is correct

66. (c) Slope of line joining the points $(0,3)$ and $(5,-2)$ is $\frac{3+2}{0-5}=-1$

This is equal to the slope of tangent on the curve and that is given by

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{-c}{(x+1)^{2}} \\
\Rightarrow & \frac{d y}{d x}=-1 \\
\Rightarrow & c=(x+1)^{2}
\end{aligned}
$$

Equation of line joining the points $(0,3)$ and $(5,2)$ is given by $(y-3)=-1(x-0)$. Solving equation of tangent and the curve for point of intersection

$$
\frac{c}{x+1}+x=3
$$

Solving Eqs. (i) and (ii),

$$
x=1
$$

On putting this in Eq. (ii), we get $c=4$

67. (b) Given, equation $y=x^{3}-a x^{2}+48 x+7$

Differentiating the above equation with respect to the variable $x$, we have

$$
\frac{d y}{d x}=3 x^{2}-2 a x+48
$$

Thus, above function is a quadratic function.

So, $D<0$.

In $y^{\prime}=3 x^{2}-2 a x+48, A=3, B=-2 a$ and $c=48$

$\therefore \quad D<0$

$\Rightarrow(-2 a)^{2}-4 \cdot 3 \cdot 48<0 \Rightarrow 4 a^{2}-4 \cdot 3 \cdot 48<0$

$\Rightarrow 4\left(a^{2}-144\right)<0 \Rightarrow a^{2}-(12)^{2}<0$

$\Rightarrow(a-12)(a+12)<0$

$\Rightarrow a \in(-12,12)$

68. (*) Given, $y=\frac{b^{2}}{a-x}+\frac{a^{2}}{x}$

$\therefore \quad \frac{d y}{d x}=\frac{-b^{2}(-1)}{(a-x)^{2}}+\left(\frac{-a^{2}}{x^{2}}\right) \Rightarrow \frac{d y}{d x}=\frac{b^{2}}{(a-x)^{2}}-\frac{a^{2}}{x^{2}}$

$\because \quad \frac{d y}{d x}=0, x=\frac{a^{2}}{a \pm b}$.

$\frac{d^{2} y}{d x^{2}}=\frac{2 a^{2}}{x^{3}}+\frac{2 b^{2}}{(a-x)^{3}}$

So, $\left.\frac{d^{2} y}{d x^{2}}\right|_{x=\frac{a^{2}}{a+b}}>0$

Therefore, $y$ is minimum at $x=\frac{a^{2}}{a+b}$

$$
y_{\min }=\frac{b^{2}}{a-\left(\frac{a^{2}}{a+b}\right)}+\frac{a^{2}}{(a)^{2}}(a+b) \text {. }
$$

$$
\begin{aligned}
& =\frac{b^{2}(a+b)}{a^{2}+a b-a^{2}}+(a+b)=(a+b)\left[\frac{b}{a}+1\right] \\
& =\frac{(a+b)^{2}}{a}
\end{aligned}
$$

69. (b) Let $(x, y)$ be on the parabola $y=x^{2}+4 x+3$ which is closet to the line $y=3 x+2$

Perpendicular distance between a point $\left(x_{1}, y_{1}\right)$ and a line $(a x+b y+c=0)$

$$
D=\left|\frac{a x_{1}+b y_{1}+c}{\sqrt{a^{2}+b^{2}}}\right|
$$

$$
\left[\therefore \text { line } 3 x-y+2=0 \text { at point }\left(x_{1}, y_{1}\right)\right]
$$

$$
\begin{aligned}
& D=\left|\frac{3 x-y+2}{\sqrt{(3)^{2}+(-1)^{2}}}\right|=\frac{\left|3 x-\left(x^{2}+4 x+3\right)+2\right|}{\sqrt{9+1}}
\end{aligned}
$$

$\Rightarrow \quad D=\frac{\left|-x^{2}-x-1\right|}{\sqrt{10}}$

$\Rightarrow D=\frac{x^{2}+x+1}{\sqrt{10}}=\frac{\left(x+\frac{1}{2}\right)^{2}+\frac{3}{4}}{\sqrt{10}}$

On differentiating w.r.t. $x$,

$$
\frac{d D}{d x}=\frac{\left(x+\frac{1}{2}\right)^{2}}{\sqrt{10}}+\frac{\frac{3}{4}}{\sqrt{10}}
$$

$\Rightarrow \frac{d D}{d x}=0, x=\frac{-1}{2} \Rightarrow y=x^{2}+4 x+3$

$\Rightarrow y=\left(\frac{-1}{2}\right)^{2}+(4)\left(\frac{-1}{2}\right)+3 \Rightarrow y=\frac{1}{4}+3-2=0$

$\Rightarrow y=\frac{1+12-8}{4} \Rightarrow y=\frac{5}{4}$

$\frac{d D}{d x}=\frac{2\left(x+\frac{1}{2}\right)}{\sqrt{10}} \Rightarrow \frac{d^{2} D}{d x^{2}}>0$

Hence, minimum at $\left(\frac{-1}{2}, \frac{5}{4}\right)$.

70. (a) $\int \frac{3 x+4}{x^{3}-2 x+4} d x=\log f(x)+C$

$$
I=\int \frac{3 x+4}{x^{3}-2 x+4}
$$

Since, $x^{3}-2 x-4=(x-2)\left(x^{2}+2 x+2\right)$

$$
\frac{3 x+4}{x^{3}-2 x+4}=\frac{A}{(x-2)}+\frac{B x+C}{\left(x^{2}+2 x+2\right)}
$$

$\Rightarrow 3 x+4=A\left(x^{2}+2 x+2\right)+(B x+C)(x-2)$

On putting $x=2, A=1$ and comparing coefficients

of $x^{2}$, we get

$0=A+B \Rightarrow B=-1$

On putting $x=0$, we have $2 A-2 C$

$\Rightarrow \quad C=-1$

$\int \frac{3 x+4}{x^{3}-2 x+4} d x=\int \frac{d x}{x-2}-\int \frac{x+1}{x^{2}+2 x+2} d x$

$=\log |x-2|-\frac{1}{2} \log \left|\left(x^{2}+2 x+2\right)\right|+C$

$=\log f(x)+C=\log \frac{|x-2|}{\sqrt{\left(x^{2}+2 x+2\right)}}+C$ 

\section{AP EAPCET (Engineering) Online Solved Paper 2022}

So, $f(x)=\frac{|x-2|}{\sqrt{\left(x^{2}+2 x+2\right)}}$

$$
\begin{aligned}
& f(3)=\frac{|3-2|}{\sqrt{\left((3)^{2}+2(3)+2\right)}} \\
& f(3)=\frac{1}{\sqrt{9+6+2}}=\frac{1}{\sqrt{17}}
\end{aligned}
$$

71. (a) Let

$I=\int \frac{e^{\tan -1}(x)}{1+x^{2}}\left[\left(\sec ^{-1} \sqrt{1+x^{1}}\right)^{2}+\cos ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)\right] d x$

On putting $\tan ^{-1} x=t$ and $\frac{d x}{1+x^{2}}=d t$, we get

$$
I=\int e^{\prime}\left[t^{2}+2 t\right] d t \Rightarrow I=\int\left(t^{2} e^{t}+2 e^{t} t\right) d t
$$

By integration by parts, we get

$$
\begin{aligned}
& I=t^{2} e^{t}-\int 2 t t^{t} d t-\int 2 t e^{t} d t+C \\
& I=t^{2} e^{t}+C=e^{t \tan ^{-1}(x)}\left(\tan ^{-1} x\right)^{2}+C
\end{aligned}
$$

72. (a) Let $I=\int \frac{d x}{(x+1)^{\frac{6}{5}}(x-3)^{\frac{4}{5}}}$

$$
I=\int \frac{d x}{(x+1)^{2}\left(\frac{x-3}{x+1}\right)^{\frac{4}{5}}}
$$

On putting $\frac{(x-3)}{(x+1)}=t$, then

$$
\begin{aligned}
& d l=\frac{4}{(x+1)^{2}} d x \\
& I=\int \frac{d t}{4 t^{\frac{1}{5}}}=\frac{5}{4} t^{5}+C=\frac{5}{4}\left(\frac{x-3}{x+1}\right)^{\frac{1}{5}}+C
\end{aligned}
$$

73. (b) Here, $I_{n}=\int\left(\cos ^{n} x+\sin ^{n} x\right) d x$

$I_{n}=\int \cos ^{n-1} x \cos x d x+\int \sin ^{n-1} x \sin x d x$

Using by parts,

$\left.I_{n}=\cos ^{n-1} x \int \cos x d x-\int\left(\frac{d}{d x}\left(\cos ^{n-1} x\right) \int \cos x d x\right)\right) d x$

$+\sin ^{n-1} x \int \sin x d x-\int\left(\frac{d}{d x}\left(\sin ^{n-1}\right) \iint\left(\int \sin d x\right) d x\right.$

$\Rightarrow I_{n i}=\cos ^{n-1} \sin x+\int(n-1) \cos ^{n-2} x \sin ^{2} x d x$

$-\sin ^{n-1} x \cos x+\int(n-1) \sin ^{n-2} x \cos ^{2} x d x$

$\Rightarrow I_{n}=\cos ^{n-1} x \sin x-\sin ^{n-1} x \cos x$

$+\int(n-1) \cos ^{n-2} x\left(1-\cos ^{2} x\right) d x$

$+\int(n-1) \sin ^{n-2} x\left(1-\sin ^{2} x\right) d x$

$$
\begin{aligned}
\Rightarrow I_{n}=\cos ^{n-1} x \sin x-\sin ^{n-1} \cdot & x \cos x \\
& +\int(n-1) \cos ^{n-2} x d x \\
-\int(n-1) \cos ^{n} x d x+ & \int(n-1) \sin ^{n-2} x d x \\
& -\int(n-1) \sin ^{n} x d x
\end{aligned}
$$

$\Rightarrow I_{n}=\cos ^{n-1} x \sin x-\sin ^{n-1} x \cos x$.

$$
+\int(n-1) \cos ^{n-2} x d x+\int(n-1) \sin ^{n-2} x d x
$$

$$
\begin{aligned}
& \cdots\left[(n-1) \int\left(\cos ^{n} x+\sin ^{n} x\right) d x\right.
\end{aligned}
$$

$\Rightarrow I_{n}=\cos ^{n-1} x \sin x-\sin ^{n-1} x \cos x$

$$
+(i 1-1) I_{n},--(n-1) I_{n}
$$

$\Rightarrow I_{n}(1+n-1)-(n-1) I_{n-2}$

$=\cos ^{n \prime-1} x \sin x-\sin ^{n \prime \prime} x \cos x$

$\Rightarrow n\left(l_{n}\right)-(n-1) I_{n-2}=\cos ^{n-1} x \sin x-\sin ^{n-1} x \cos x$

$\Rightarrow I_{n}-\left(\frac{n-1}{n}\right) I_{n-2}=\frac{\sin x \cos x}{n}\left(\cos ^{n-2} x-\sin ^{n \prime} x_{1}\right.$

$=\frac{\sin x \cos x}{n} f(x)$

$\therefore f(x)=\cos ^{n-2} x-\sin ^{n-2} x$

74. (c) Given, $I=\int_{0}^{T} f(x) d x$

If $f(x+T)=f(x)$

Now $=\int_{0}^{5 T} f(2 x) d x$

On putting $2 x=y$

$\Rightarrow \quad d x=\frac{1}{2} d y$.

$$
\frac{1}{2} \int_{0}^{10 I} f(y) d y=\frac{10 I}{2}=51
$$

75. (b) Let $I=\int_{1}^{3} x \sqrt[n]{x^{2}-1} d x=6$.

$$
=\frac{1}{2} \int_{1}^{3} 2 x\left(x^{2}-1\right)^{\frac{1}{n}} d x=6
$$

$\Rightarrow\left[\frac{\left(n^{2}-1\right)^{\frac{1}{n}+1}}{\frac{1}{n}+1}\right]_{1}^{3}=12$

$\Rightarrow \quad \frac{(8)^{\frac{1}{n}+1}}{\frac{1}{n}+1}=12$

$\Rightarrow \quad \frac{(8)^{\frac{1}{n}}}{(n+1)}(n)=\frac{3}{2}$

Now, on putting $n=3$,

L H S $=$ R. H S

$\therefore n=3$ 76. (c) $\int_{-1}^{1}(x[1+\sin \pi x]+1) d x$

$$
I=\int_{-1}^{1}(x[1+\sin \pi x]+1) d x
$$

We know that, $-1 \leq \sin \pi x \leq 1$

$I=\int_{-1}^{0}(x[1+\sin \pi x]+1) d x+\int_{0}^{1}(x(1+\sin \pi x)+1) d x$

$\Rightarrow I=\int_{-1}^{0}(x \cdot 0+1) d x+\int_{0}^{1}(x+1) d x$

$\Rightarrow I=[x]_{-1}^{0}+\left[\frac{x^{2}}{2}+x\right]_{0}^{1}$

$\Rightarrow I=0-(-1)+\left[\frac{1}{2}+1\right]$

$\Rightarrow I=2+\frac{1}{2}=\frac{5}{2}$

77. (a) Here, $\lim _{n \rightarrow \infty}\left[\begin{array}{rl}\frac{n}{(n+1) \sqrt{2 n+1}}+\frac{n}{(n+2) \sqrt{2(n+2)}} \\ & +\ldots \text { upto } n \text { terms }\end{array}\right]$

$$
=\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{k=1}^{n} \frac{n^{2}}{(n+k) \sqrt{k(2 n+k)}}
$$

$$
\begin{aligned}
& =\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{k=1}^{n} \frac{n^{2}}{(n+k) \sqrt{k(2 n+k)}} \times \frac{n^{2}}{n^{2}} \\
& =\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{k=1}^{n} \frac{1}{\left(\frac{n+k}{n}\right) \sqrt{\frac{k}{n}\left(\frac{2 n+k}{n}\right)}} \\
& =\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{k=1}^{n} \frac{1}{\left(1+\frac{k}{n}\right) \sqrt{\frac{k}{n}\left(2+\frac{k}{n}\right)}} \\
& =\int_{0}^{1} \frac{1}{(1+x) \sqrt{x(2-x)}} d x=\int_{0}^{1} f(x) d x
\end{aligned}
$$

$$
f(x)=\frac{1}{(1+x) \sqrt{2 x+x^{2}}}
$$

78. (a) Here, $\frac{d y}{d x}=\cos ^{2}(3 x+y)$

On putting $3 x+y=t$

$$
3+\frac{d y}{d x}=\frac{d t}{d x}
$$

$\Rightarrow \quad \frac{d y}{d x}=\frac{d t}{d x}-3 \Rightarrow \frac{d t}{d x}-3=\cos ^{2} t$

$\Rightarrow \quad \frac{d t}{d x}=\cos ^{2} t+3 \Rightarrow \frac{d t}{\cos ^{2} t+3}=d x$

Integrate both side,

$$
\int \frac{d t}{\cos ^{2} t+3}=\int d x
$$

$\Rightarrow \int \frac{\sec ^{2} t d t}{1+3 \sec ^{2} t}=\int d x \Rightarrow \int \frac{\sec ^{2} t}{1+3+3 \tan ^{2} t}=\int d x$

$\Rightarrow \int \frac{\sec ^{2} t d t}{4+3 \tan ^{2} t}=\int d x$

On putting $\tan t=m$,

$\sec ^{2} t d x=d m=\frac{1}{4} \int \frac{d m}{1+\left(\frac{\sqrt{3}}{2} m\right)^{2}} x+C$

$=\frac{1}{4} \times \frac{2}{\sqrt{3}} \tan ^{-1}\left(\frac{\sqrt{3}}{2} m\right)=x+C$

$=\frac{1}{2 \sqrt{3}} \tan ^{-1}\left[\frac{\sqrt{3}}{2} \tan t\right]=x+c \quad[\because m=\tan t]$

$=\tan ^{-1}\left[\frac{\sqrt{3}}{2} \tan (3 x+y)=2 \sqrt{3}(x+0)\right][\because t=3 x+y]$

So, $f(x)=2 \sqrt{3}(x+C)$

79. (a) Given,

$\cos ^{2} x \frac{d y}{d x}+y=\tan x$

$\Rightarrow \frac{d x}{d x}+y \sec ^{2} x=\tan x \cdot \sec ^{2} x$

Here, $p=\sec ^{2} x$

$\Rightarrow \int p d p=\int \sec ^{2} x d x=\tan x$

$I F=e^{\operatorname{lan} x}$

Multiplying Eq. (i) by $I F$, we get

$$
e^{\tan x} \frac{d y}{d x}+e^{\tan x} y \sec ^{2} x=e^{\tan x} \cdot \tan x \cdot \sec ^{2} x
$$

Integrating both sides, we get

$$
y e^{\tan x}=\int e^{\tan x} \tan x \cdot \sec ^{2} x d x
$$

On putting $\tan x=t$,

$$
\sec ^{2} x d x=d t
$$

$\therefore \quad y e^{t}=\int t e^{\prime} d t=e^{t}(t-1)+C$

$\therefore \quad y e^{\operatorname{lan} x}=\tan x-1+C e^{-\operatorname{lan} x}$

If $y\left(\frac{\pi}{4}\right)=1$

$\Rightarrow \quad 1=1-1+C e^{-1} \Rightarrow 1=C e^{-1}$

$\therefore \quad C=e$

80. (a) Any circle with given radius can be written as, $(x-h)^{2}+(y-k)^{2}=a^{2}$ where $(h, k)$ be the centre of the circle which is variable. So, in above algebraic equation, there are two arbitrary constant $h$ and $k$. Hence, order of differential equation will be second order.

Hence, assertion and reason are true and reason is the correct explanation to assertion. 

\section{Physics}

81. (c) Energy of the system as a function of time, $E(t)=\alpha t-\beta t^{3}$.

Where, $\alpha$ and $\beta$ are constant.

According to principle of homogenity, dimension of $a t=$ dimension of energy i.e

$\Rightarrow \quad[\alpha][t]=[E]$

$\Rightarrow \quad[\alpha][\mathrm{T}]=\left[\mathrm{ML}^{2} \mathrm{~T}^{-2}\right]$

$\Rightarrow \quad[\alpha]=\left[\mathrm{ML}^{2} \mathrm{~T}^{-3}\right]$

Again, dimension of $\beta t^{3}=$ dimension of energy

$\Rightarrow \quad[\beta]\left[t^{3}\right]=\left[\mathrm{ML}^{2} \mathrm{~T}^{-2}\right]$

$\Rightarrow \quad[\beta]\left[\mathrm{T}^{3}\right]=\left[\mathrm{ML}^{2} \mathrm{~T}^{-2}\right]$

$\Rightarrow \quad[\beta]=\left[\mathrm{ML}^{2} \mathrm{~T}^{-5}\right]$

82. (b) Let $v$ be the minimum velocity of student so, that he could catch the bus

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-16.jpg?height=215&width=460&top_left_y=1166&top_left_x=318)

If student catch the bus in time $t$, then distance travelled by student in time $t$

$=16+$ distance travelled by bus in time $t$.

$\Rightarrow v t=16+\left(u t+\frac{1}{2} a t^{2}\right)$

$\Rightarrow v t=16+0 \times t+\frac{1}{2} \times 9 \times t^{2}$

$\Rightarrow v t=16+\frac{9}{2} t^{2} \Rightarrow 9 t^{2}-2 v t+32=0$

The above equation must have real roots. i.e its discriminant $\geq 0$

i.e $(2 v)^{2}-4 \times 9 \times 32 \geq 0$

$\Rightarrow 4 v^{2}-4 \times 288 \geq 0 \Rightarrow v^{2}-288 \geq 0$

$\Rightarrow v^{2} \geq 288$

$v \geq 12 \sqrt{2} \mathrm{~m} / \mathrm{s}$

Minimum velocity of student to catch the bus $=12 \sqrt{2} \mathrm{~m} / \mathrm{s}=\alpha \sqrt{2} \mathrm{~m} / \mathrm{s}$ (given)

$\therefore \alpha=12$

83. (b) Given, $\mathbf{P}=3 \hat{i}+4 \hat{j}$

Let $Q=\hat{i}+2 \hat{j}$

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-16.jpg?height=211&width=396&top_left_y=2453&top_left_x=316)

The component of $\mathbf{P}$ along the $\mathbf{Q}$ is given as $|\mathbf{P}| \cos \theta$.

Hence, we know that,

P. $\mathbf{Q}=|\mathbf{P}||\mathbf{Q}| \cos \theta$

$\Rightarrow|P| \cos \theta=\frac{\mathbf{P} \cdot \mathbf{Q}}{|\mathbf{Q}|}$

$=\frac{(3 \hat{i}+4 \hat{j}) \cdot(\hat{i}+2 \hat{j})}{\sqrt{1^{2}+2^{2}}}=\frac{3+8}{\sqrt{5}}=\frac{11}{\sqrt{5}}$

84. (d) Since, launched projectile hit the target on the ground $90 \mathrm{~m}$ away hence, range, $R=90 \mathrm{~m}$.

For minimum velocity $\left(u_{\min }\right)$ of projectile, range should be maximum. i.e. $\theta=45^{\circ}$

$$
R=\frac{u^{2} \sin 2 \theta}{g}
$$

$\Rightarrow \quad 90=\frac{u_{\min }^{2} \sin 2 \times 45^{\circ}}{10} \Rightarrow 900=u_{\min }^{2}$

$\Rightarrow \quad u_{\min }=\sqrt{900}=30 \mathrm{~m} / \mathrm{s}$

85. (c) The two vectors $\mathbf{A}$ and $\mathbf{B}$ are mutually perpendicular to each other

$\Rightarrow$

$\Rightarrow$

A. $\mathbf{B}=\mathbf{0}$.

$A B \cos \theta=0$

$|\mathbf{A}-\mathbf{B}|$

$$
\cos \theta=0 \Rightarrow \theta=90^{\circ}
$$

$$
\begin{aligned}
& =\sqrt{A^{2}+B^{2}-2 A B \cos 90^{\circ}} \\
& =\sqrt{A^{2}+B^{2}}
\end{aligned}
$$

Unit vector along $\mathbf{A}-\mathbf{B}$

$$
=\frac{\mathbf{A}-\mathbf{B}}{|\mathbf{A}-\mathbf{B}|}=\frac{\mathbf{A}-\mathbf{B}}{\sqrt{A^{2}+B^{2}}}
$$

component of $(\mathbf{A}+\mathbf{B})$ in direction of $(\mathbf{A}-\mathbf{B})$ will be given as,

$$
\begin{aligned}
& =\frac{(\mathbf{A}+\mathbf{B}) \cdot(\mathbf{A}-\mathbf{B})}{|\mathbf{A}-\mathbf{B}|} \\
& =\frac{\mathbf{A} \cdot \mathbf{A}-\mathbf{A} \cdot \mathbf{B}+\mathbf{B} \cdot \mathbf{A}-\mathbf{B} \cdot \mathbf{B}}{\sqrt{A^{2}+B^{2}}} \\
& =\frac{A^{2}-B^{2}}{\sqrt{A^{2}+B^{2}}}=\frac{|\mathbf{A}|^{2}-|\mathbf{B}|^{2}}{\sqrt{|\mathbf{A}|^{2}+|\mathbf{B}|^{2}}}
\end{aligned}
$$

86. (b) Initial speed of body on the horizontal rough surfaces, $u=10 \mathrm{~ms}^{-1}$

Final velocity, $v=4 \mathrm{~ms}^{-1}$ and $t=2 \mathrm{~s}$.

If $a$ be the retardation due to friction, then by using equation,

$$
v=u-a t
$$

$\Rightarrow$

$$
4=10-a \times 2
$$

$\Rightarrow \quad 2 a=6 \Rightarrow a=3 \mathrm{~ms}^{-2}$

According to given situation,

friction force $=m a$

$\Rightarrow \quad \mu_{k} m g=m a$

$\Rightarrow \quad \mu_{k}=\frac{a}{g}=\frac{3}{10}=0.3$

87. (c) According to law of conservation of energy at point $B$ shown in the figure given in question part,

Loss in PE = Gain in $\mathrm{KE}$

$\Rightarrow m g(H-h)=\frac{1}{2} m v^{2}$

$\Rightarrow \quad v=\sqrt{2 g(H-h)}$

Now, $\quad h=\frac{1}{2} g t^{2} \Rightarrow t=\sqrt{\frac{2 \dot{h}}{g}}$

$\therefore$ Distance covered in horizontal portion,

$$
\begin{aligned}
s & =v \times t \\
& =\sqrt{2 g(H-h)} \times \sqrt{\frac{2 h}{g}}
\end{aligned}
$$

$\Rightarrow \quad s=\sqrt{4 h(H-h)}$

For maximum value of $s$

$$
\begin{array}{ccc} 
& \frac{d s}{d h}=0 \\
\Rightarrow & \frac{1}{2 \sqrt{4 h(H-h)}} \times 4[(H-h) \cdot 1+h(-1)]=0 \\
\Rightarrow & 2(H-2 h)=0 \Rightarrow H=2 h \\
\Rightarrow & h=\frac{H}{2}
\end{array}
$$

Substituting the value of $h$ in Eq. (i), we get,

$$
\begin{aligned}
s & =\sqrt{4 \frac{H}{2}\left(H-\frac{H}{2}\right)} \\
& =\sqrt{2 H \cdot \frac{H}{2}}=H
\end{aligned}
$$

88. (c) Mass of block, $m=50 \mathrm{~kg}$,

speed of block, $v=4 \mathrm{~ms}^{-1}$,

$$
F=500 \mathrm{~N} \text { and } \theta=30^{\circ} \text {, }
$$

The rate at which the force does work on the block is equal to power which is given as

$$
\begin{aligned}
P & =\text { Force in the horizontal direction } \times \text { velocity } \\
& =500 \times \cos 30^{\circ} \times v \\
& =500 \times \frac{\sqrt{3}}{2} \times 4=100 \sqrt{3} \\
& =100 \times 1.732=1732 \mathrm{~W}
\end{aligned}
$$

89. (a) For ball $A$,

$m_{A}=1 \mathrm{~kg}, v_{A}=4 \mathrm{~ms}^{-1}$

for ball $B, m_{B}=3 \mathrm{~kg}, v_{B}=0$ $\therefore$ Total momentum before collision,

$$
\begin{aligned}
p_{i} & =m_{A} v_{A}+m_{B} v_{B} \\
& =1 \times 4+3 \times 0=4 \mathrm{~kg}-\mathrm{ms}^{-1}
\end{aligned}
$$

Since, after collision, both body stick together, therefore, it is the case of perfectly enelastic collision. Let $v$ be the common velocity, then total momentum after collision,

$$
\begin{aligned}
p_{f} & =\left(m_{A}+m_{B}\right) v \\
& =(1+3) v=4 v
\end{aligned}
$$

According to law of conservation of linear momentum,

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-17.jpg?height=102&width=495&top_left_y=904&top_left_x=1042)

Time of impact, $\Delta t=0.1 \mathrm{~s}$

Force exerted on the body $B$,

$$
\begin{aligned}
& F_{B}=\frac{\Delta p_{B}}{\Delta t}=\frac{m_{B}\left(v_{B}-u_{B}\right)}{\Delta t}=\frac{3(v-0)}{0.1} \\
\Rightarrow \cdot & F_{B}=\frac{3(1-0)}{0.1}=\frac{3}{0.1}=30 \mathrm{~N} .
\end{aligned}
$$

90. (d) The given situation is shown below

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-17.jpg?height=306&width=411&top_left_y=1385&top_left_x=1190)

Let $v$ be the velocity of solid cylinder on reaching the ground.

According to conservation of energy,

Total energy at point $A=$ Total energy at point $B$

i. e $m g h+0=\frac{1}{2} I \omega^{2}+\frac{1}{2} m v^{2}+0$

$\Rightarrow \quad m g h=\frac{1}{2}\left(\frac{1}{2} M R^{2}\right)\left(\frac{v}{R}\right)^{2}+\frac{1}{2} m v^{2}$

$\Rightarrow\left(\right.$ Where, $I=\frac{1}{2} M R^{2}$ and $\omega=\frac{v}{R}$ )

$\Rightarrow \quad g h=\frac{v^{2}}{4}+\frac{v^{2}}{2} \Rightarrow g h=\frac{3 v^{2}}{4}$

$\Rightarrow \quad v^{2}=\frac{4 g h}{3} \Rightarrow v=\sqrt{\frac{4 g h}{3}}$

91. (b) Given, instantaneous displacement of particle executing SHM.

$\begin{aligned} x & =A \sin ^{2}(\omega t-4) \\ \Rightarrow x & =A\left[\frac{1-\cos 2(\omega t-4)}{2}\right]\end{aligned}$

$\left(\right.$ Since, $\left.\sin ^{2} \theta=\frac{1-\cos 2 \theta}{2}\right)$ $\Rightarrow x=\frac{A}{2}[1-\cos (2 \omega t-8)]$

Here, angular velocity of particle

$$
\begin{aligned}
\omega^{\prime} & =2 \omega \\
\frac{2 \pi}{T^{\prime}} & =2 \times \frac{2 \pi}{T} \Rightarrow T^{\prime}=\frac{T}{2}
\end{aligned}
$$

$\Rightarrow$

$$
=\frac{\frac{2 \pi}{\omega}}{2}=\frac{\pi}{\omega}
$$

$$
\left(\therefore T=\frac{2 \pi}{\omega}\right)
$$

92. (d) We know that, mechanical energy of oscillator lost in each cycle is proportional to the square of amplitude $(A)$. Then fractional change in energy

$$
\begin{aligned}
\frac{\Delta E}{E} \simeq \frac{d E}{E} & =\frac{d A^{2}}{A^{2}} \\
& =\frac{2 A d A}{A^{2}}=2 \frac{d A}{A} \\
& =2 \times 1.5 \%=3 \% .
\end{aligned}
$$

93. (b) Time period of satellite moving around a planet with angular velocity $\omega$ is given as,

$$
T=\frac{2 \pi}{\omega}
$$

Since, the two artificial satellites revolving in the same circular orbit, then their angular velocities will be same.

Hence, both satellites revolve with same period of revolution.

Orbital velocity of revolving satellite, $v=\sqrt{\frac{G m}{r}}$ i.e $v \propto \frac{1}{\sqrt{r}}$

Where, $m=$ mass of the planet

$G=$ Universal gravitational constant

$r=$ radius of circular orbit.

Escape velocity depends on the gravitational potential at the point from where the body is launched. Since, this potential depends on the height of the point of projection, hence escape velocity also depends on the height (altitude) of the point of projection.

94. (a) The given situation is shown below.

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-18.jpg?height=174&width=603&top_left_y=2323&top_left_x=178)

Here, elongation in wire $B$ is twice of elongation in wire $A$ on the application of same tension $T$.

i.e $\Delta L_{B}=2 \Delta L_{A}$

Young's modulus of wire $A$ and $B$ are given as

$$
\begin{aligned}
& Y_{A}=\frac{T L_{A}}{A \cdot \Delta L_{A}} \text { and } Y_{B}=\frac{T L_{B}}{A \Delta L_{B}} \\
& \therefore \quad \frac{Y_{A}}{Y_{B}}=\frac{L_{A}}{L_{B}} \times \frac{\Delta L_{B}}{\Delta L_{A}} \Rightarrow \frac{2 \times 10^{11}}{11 \times 10^{11}}=\frac{L_{A}}{L_{B}} \times \frac{2 \Delta L_{A}}{\Delta L_{A}} \\
& \Rightarrow \quad \frac{2}{11}=\frac{L_{A}}{L_{B}} \times 2 \Rightarrow \frac{L_{A}}{L_{B}}=\frac{1}{11}=\frac{10}{11}
\end{aligned}
$$

95. (d) Given, $s_{w}=1 \mathrm{cal} \mathrm{g}^{-1}{ }^{\circ} \mathrm{C}^{-1}$

$$
\begin{aligned}
& s_{\text {ice }}=0.5 \mathrm{cal} \mathrm{g}^{-1}{ }^{\circ} \mathrm{C}^{-1} \\
& L_{f}=80 \mathrm{cal} \mathrm{g}^{-1}
\end{aligned}
$$

Mass of ice $m_{\text {ice }}=5 \mathrm{~g}$

Mass of water, $m_{w}=20 \mathrm{~g}$

Let final temperature of the mixture be $T^{\circ} \mathrm{C}$.

According to principle of calorimetry, Heat lost by water $=$ Heat gained by ice

$m_{w} s_{w}(35-T)=m_{\text {ice }} s_{\text {ice }}[0-(-30)]$

$$
+m_{i c e} \times L_{f}+m_{\text {ice }} \times s_{w} \times T
$$

$\Rightarrow 20 \times 1 \times(35-T)=5 \times 0.5 \times 30+5 \times 80+5 \times 0.5 \times T$

On solving, we get

$$
T=9^{\circ} \mathrm{C}
$$

96. (*) Given, $r_{A}=10 \mathrm{~cm}=0.1 \mathrm{~m}$

$$
\begin{aligned}
& r_{B}=100 \mathrm{~m} \\
& r_{C}=5 \mathrm{~cm}=0.05 \mathrm{~m}
\end{aligned}
$$

weight placed on piston $A=m \times g$

Using Pascal's law;

$$
=2 \mathrm{~g}
$$

$\frac{F_{A}}{A_{A}}=\frac{F_{B}}{A_{B}}=\frac{F_{C}}{A_{C}}$

$\Rightarrow \quad \frac{2 g}{\pi(01)^{2}}=\frac{F_{B}}{\pi(100)^{2}}=\frac{F_{C}}{\pi(0.05)^{2}}$

From Eq. (i) we have

$$
\begin{aligned}
F_{B} & =\frac{2 g}{\pi(0.1)^{2}} \times \frac{\pi(100)^{2}}{1}=\frac{2 \times 10000 \times g}{0.01} \\
& =2 \times 10^{6} \mathrm{~g} \\
& =\frac{\pi(0.05)^{2}}{1} \times \frac{2 g}{\pi(0.1)^{2}} \\
= & \frac{0.0025}{0.01} \times 2 \mathrm{~g}=0.50 \mathrm{~g}
\end{aligned}
$$

$$
\begin{aligned}
& \text { Similarly, } F_{c}=\frac{\pi(0.05)^{2}}{1} \times \frac{2 g}{\pi(0.1)^{2}}
\end{aligned}
$$

Hence, $B$ can lift mass of $2 \times 10^{6} \mathrm{~kg}$ and $C$ can lift mass of $0.50 \mathrm{~kg}$.

Therefore, no option is correct.

97. (d) Given, diameter of sphere $=D$

Initial surface area, $A=4 \pi R^{2}$

$$
\begin{aligned}
& =4 \pi\left(\frac{D}{2}\right)^{2} \\
& =\pi D^{2}
\end{aligned}
$$



\section{AP EAPCET (Engineering) Solved Papers 119}

Surface area after heating by temperature $\delta T$,

$$
A^{\prime}=4 \pi\left(\frac{D^{\prime}}{2}\right)^{2}=\pi\left(D^{\prime}\right)^{2}
$$

where $D^{\prime}$ is the new diameter.

From the equation of lincar expansion, we have

$$
D^{\prime}=D(1+\alpha \delta T)
$$

putting the value of $D^{\prime}$ from eq. (iii) in cq. (ii) we get

$$
\begin{aligned}
A^{\prime} & =\pi D^{2}(1+\alpha \delta T)^{2} \\
& =\pi D^{2}\left(1+\alpha^{2} \delta T^{2}+2 \alpha \delta T\right) \\
& =\pi D^{2}\left(1+\alpha^{2} \delta T^{2}+2 \alpha \delta T\right)-\pi D^{2} \\
& =\pi D^{2}\left[1+\alpha^{2} \delta T^{2}+2 \alpha \delta T-1\right] \\
& =\pi D^{2}\left[\alpha^{2} \delta T^{2}+2 \alpha \delta T\right]
\end{aligned}
$$

Change in surface area $=A^{\prime}-A=\pi D^{\prime 2}-\pi D^{2}$

$$
=\pi D^{2} \alpha \delta T(\alpha . \delta T+2)
$$

98. (b) Given, source temperature, $T_{1}=400 \mathrm{~K}$

Sink temperature, $T_{2}=300 \mathrm{~K}$

Work done, $W=400 \mathrm{~J}$

We know that, efficiency of carnot heat engine

$$
\eta=\frac{W}{Q}=1-\frac{T_{2}}{T_{1}}
$$

$\Rightarrow \quad \frac{W}{Q}=1-\frac{T_{2}}{T_{1}} \Rightarrow \frac{400}{Q}=1-\frac{300}{400}$

$\Rightarrow \quad \frac{400}{Q}=\frac{1}{4} \Rightarrow Q=1600 \mathrm{~J}$

$\therefore$ Energy exhausted by the heat engine $=Q-W$

$$
=1600-400=1200 \mathrm{~J}
$$

99. (b) The slope of isothermal $\left(S_{1}\right)$ and adiabatic $\left(S_{A}\right)$

$p-V$ graph of gas are related as

Slope of adiabatic $=\gamma \times$ slope of isothermal

$\Rightarrow$

$$
\begin{aligned}
S_{A} & =\gamma \times S_{I} \Rightarrow S_{I} / S_{A}=1 / \gamma \\
& =\frac{1}{3 / 2} \quad\left(\therefore \text { Given } \gamma=\frac{3}{2}\right) \\
& =2 / 3
\end{aligned}
$$

100. (c) The diatomic molecule can rotate about any axis at right angles to its own axis. Hence, it has two rotational degrees of freedom.

101. (b) Here, both cars are moving towards each other, hence one car is like an observer and another car is like a source .

$\therefore \quad v_{s}=50 \mathrm{~m} / \mathrm{s} \Rightarrow v_{0}=-50 \mathrm{~m} / \mathrm{s}$

Frequency of horn blown by the source car,

$$
v=250 \mathrm{~Hz}
$$

According to Doppler's effect, frequency heared by another car $v^{\prime}$ is given as

$$
\begin{aligned}
& v^{\prime}=\frac{v-v_{0}}{v-v_{s}} \times v=\frac{350-(-50)}{350-50} \times 250 \\
& \therefore(v=\text { speed of sound }=350 \mathrm{~m} / \mathrm{s}) \\
& =\frac{400 \times 250}{300} \Rightarrow v^{\prime}=\frac{100}{3} \mathrm{~Hz}
\end{aligned}
$$

Wavelength of heard sound,

$$
\begin{aligned}
\lambda^{\prime} & =\frac{v}{v^{\prime}} \\
& =\frac{350}{1000 / 3}=\frac{1050}{1000}=1.05 \mathrm{~m}=105 \mathrm{~cm}
\end{aligned}
$$

102. (c) For watter, real depth $=12 \mathrm{~cm}$

Apparent depth $=9 \mathrm{~cm}$

Since, refractive index, $\mu_{w}=\frac{\text { Real depth }}{\text { Apparent depth }}$

$\Rightarrow$

$$
\mu_{w}=\frac{12}{9}
$$

when water is replaced by liquid of refractive index $\mu=1.5$, we have

New apparent depth $=\frac{\text { real depth }}{\mu_{1}}=\frac{12}{1.5} \doteq 8 \mathrm{~cm}$

Hence, required shifted distance $=9-8=1 \mathrm{~cm}$

103. (b) Given, wavelength, $\lambda=5000 \AA=5 \times 10^{-7} \mathrm{~m}$

Slit separation, $d=3 \mathrm{~mm}=3 \times 10^{-3} \mathrm{~m}$

Distance between slit and screen,

$$
D=20 \mathrm{~cm}=0.2 \mathrm{~m}
$$

Thickness of transparent plate $=1 \mathrm{~mm}=1 \times 10^{-3} \mathrm{~m}$ Fringe shift, $\Delta x=6 \mathrm{~mm}=6 \times 10^{-3} \mathrm{~m}$

Fringe shift is given by

$$
\begin{aligned}
\Delta x & =\frac{D}{d}(\mu-1) t \\
\Rightarrow \quad 6 \times 10^{-3} & =\frac{0.2}{3 \times 10^{-3}}(\mu-1) \times 10^{-3} \\
\Rightarrow & \frac{6 \times 3 \times 10^{-3}}{0.2}=\mu-1 \Rightarrow 9 \times 10^{-2}=\mu-1 \\
\Rightarrow \quad \mu & =1.09
\end{aligned}
$$

Hence, refractive index of transparent plate is $1.09$.

104. (a) The given situation is shown below.

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-19.jpg?height=352&width=731&top_left_y=2340&top_left_x=1007)

From the above figure total charge enclosed by the sphere of radius $2.5 \mathrm{~cm}=5 \dot{q}$

$\therefore$ According to gauss law; total electric flux passing through spherical surface,

$$
\begin{aligned}
\phi & =\frac{\text { total charge enclosed }}{\varepsilon_{0}} \\
& =\frac{5 q}{\varepsilon_{0}}
\end{aligned}
$$

105. (b) The given circuit diagram can be represented as

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-20.jpg?height=405&width=625&top_left_y=834&top_left_x=247)

Since, $\quad \frac{C_{1}}{C_{2}}=\frac{C_{3}}{C_{4}}=\frac{1}{3}$

Hence, given circuit follows the condition of balance wheatstone bridge.

Hence, capacitor $C_{5}$ is ineffective.

Now, the circuit diagram is redrawn as

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-20.jpg?height=625&width=651&top_left_y=1538&top_left_x=248)

106. (c) The given situation is shown below

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-20.jpg?height=420&width=526&top_left_y=2246&top_left_x=274)

Since, electric field is directed along the $X$-axis, hence, point $A$ and $C$ lie on equipotential surface $\therefore$ Potential at point $C=$ Potential at point $A$

$\Rightarrow \quad V_{C}=V_{A}$

$\therefore \quad V_{B}-V_{A}=V_{B}-V_{C}$.

$=-E \Delta x=-5(2-0)=-10 \mathrm{~V}$

107. (a) The given circuit diagram is shown as :

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-20.jpg?height=542&width=531&top_left_y=700&top_left_x=1211)

Applying KVL in loop $A B D A$, we get

$$
\begin{aligned}
2 I_{1}+4-I_{2} & =0 \\
I_{2} & =2 I_{1}+4
\end{aligned}
$$

Applying KVL in loop $B C D B$, we get

$$
1\left(I_{1}+I_{3}\right)-4\left(I_{2}-I_{3}\right)-4=0
$$

$\Rightarrow \quad I_{1}+I_{3}-4 I_{2}+4 I_{3}-4=0$

$\Rightarrow \quad I_{1}+5 I_{3}-4\left(2 I_{1}+4\right)-4=0$

$\Rightarrow \quad-7 I_{1}+5 I_{3}=20$

$\Rightarrow \quad I_{3}=\frac{20+7 I_{1}}{5}$

By applying KVL in loop $A D C A$, we get

$I_{2}+4\left(I_{2}-I_{3}\right)-10=0$

$\Rightarrow \quad 5 I_{2}-4 I_{3}=10$

$\Rightarrow \quad 5\left(2 I_{1}+4\right)-4\left(\frac{20+7 I_{1}}{5}\right)=10$

[From Eqs. (i) and (ii)]

$\Rightarrow$

$$
I_{1}=1.364 \mathrm{~A}
$$

From Eq. (i), $I_{2}=2 \times 1.364+4=6.278 \mathrm{~A}$

From Eq (ii), $I_{3}=\frac{20+7 \times 1.364}{5}=5.91 \mathrm{~A}$

108. (b) Resistance of wire at $0^{\circ} \mathrm{C}, R_{0}=20 \Omega$

Temperature coefficient,

$$
\begin{aligned}
& \alpha=5 \times 10^{-3}{ }^{\circ} \mathrm{C}^{-1} \\
& R_{t}=2 R_{0}=2 \times 20=40 \Omega
\end{aligned}
$$

we know that,

$\begin{array}{ll} & R_{t}=R_{0}(1+\alpha t) \\ \Rightarrow & 40=20\left(1+5 \times 10^{-3} t\right) \Rightarrow 2=1+5 \times 10^{-3} t\end{array}$ $\Rightarrow \quad t=\frac{1}{5 \times 10^{-3}}=\frac{1000}{5}=200^{\circ} \mathrm{C}$

109. (a) Kinctic energy of electron,

$$
\begin{aligned}
K & =100 \mathrm{eV} \\
& =100 \times 1.6 \times 10^{-19} \mathrm{~J}=1.6 \times 10^{-17} \mathrm{~J}
\end{aligned}
$$

Radius of circular path, $r=10 \mathrm{~cm}=01 \mathrm{~m}$

Mass of electron, $m=0.5 \mathrm{MeVc}^{-2}$

$$
\begin{aligned}
& =\frac{0.5 \mathrm{MeV}}{c^{2}}=\frac{0.5 \times 10^{6} \times 1.6 \times 10^{-19}}{3 \times 10^{8} \times 3 \times 10^{8}} \mathrm{~kg} \\
& =8.89 \times 10^{-31} \mathrm{~kg}
\end{aligned}
$$

$\because$ Radius of circular path of electron in magnetic field $B$ in terms of kinetic energy $(K)$ is given as

$$
r=\frac{\sqrt{2 m K}}{B q}
$$

$$
\begin{aligned}
& \Rightarrow \quad B=\frac{\sqrt{2 m K}}{r q}=\frac{\sqrt{2 \times 8.89 \times 10^{-31} \times 1.6 \times 10^{-17}}}{0.1 \times 1.6 \times 10^{-19}} \\
& =3.3 \times 10^{-4} \mathrm{~T}
\end{aligned}
$$

110. (d) Given, mass of the particle,

$$
m=22 \times 10^{-30} \mathrm{~kg}
$$

Charge, $q=1.6 \times 10^{-19} \mathrm{C}$

Velocity, $v=10 \mathrm{kms}^{-1}=10^{4} \mathrm{~ms}^{-1}$

Radius of circular path, $r=2.8 \mathrm{~cm}=2.8 \times 10^{-2} \mathrm{~m}$

$$
n=25 \text { turns } / \mathrm{cm}=2500 \frac{\text { turns }}{\mathrm{m}}
$$

Since, $r=m v / B q$

Magnetic field inside the solenoid,

$$
B=\mu_{0} n I
$$

From Eqs. (i) and (ii), we get

$$
\begin{aligned}
r & =\frac{m v}{\left(\mu_{0} n I\right) q} \Rightarrow I=\frac{m v}{\mu_{0} n q r} \\
& =\frac{22 \times 10^{-30} \times 10^{4}}{4 \pi \times 10^{-7} \times 2500 \times 1.6 \times 10^{-19} \times 28 \times 10^{-2}} \\
& =1.56 \times 10^{-3} \mathrm{~A}=1.56 \mathrm{~mA}
\end{aligned}
$$

111. (a) When two short magnets of equal dipole moments $M$ are fastened perpendicularly at their centres. Then their resultant dipole moment is given as

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-21.jpg?height=480&width=417&top_left_y=2270&top_left_x=317)

$$
\begin{aligned}
M^{\prime} & =\sqrt{M_{1}^{2}+M_{2}^{2}+2 M_{1} M_{2} \cos \theta} \\
& =\sqrt{M^{2}+M^{2}+2 M M \cos 90^{\circ}} \\
\Rightarrow M^{\prime} & =M \sqrt{2}
\end{aligned}
$$

The magnitude of the magnetic field at a distance $d$ from the centre on the bisector i.e at a distance $d$ on the axial position of dipole,

$$
\begin{aligned}
B & =\frac{\mu_{0}}{4 \pi} \cdot \frac{2 M^{\prime}}{d^{3}} \\
& =\frac{\mu_{0}}{4 \pi} \cdot \frac{2 \sqrt{2} M}{d^{3}}
\end{aligned}
$$

[from Eq. (i)]

112. (b) Given, Radius of circular loop of wire,

$$
r=14 \mathrm{~cm}=0.14 \mathrm{~m}
$$

Rate of change of magnetic field with respect to time,

$$
\frac{d B}{d t}=0.05 \mathrm{Ts}^{-1}
$$

According to Faraday law of electromagnetic induction, induced emf, $|e|=\frac{d \phi}{d t}$

$$
\begin{aligned}
& =\frac{d}{d t}(B A) \quad(\therefore \phi=B A) \\
& =\frac{A d B}{d t}=\pi r^{2} \frac{d B}{d t} \\
& =\frac{22}{7} \times 0.14 \times 0.14 \times 0.05=0.00308 \\
& =3.08 \times 10^{-3} \mathrm{~V}=3.08 \mathrm{mV}
\end{aligned}
$$

113. (d) In R-L-C series circuit,

$R=150 \Omega C=20 \mu \mathrm{F}$

$$
=2 \times 10^{-5} \mathrm{~F}
$$

$L=500 \mathrm{mH}=0.5 \mathrm{H}$

Supply voltage, $V=100 \mathrm{~V}$

Angular frequency, $\omega=400 \mathrm{rads}^{-1}$

Now, $X_{L}=\omega L$

$$
=400 \times 0.5=200 \Omega
$$

$$
\begin{aligned}
& X_{C}=\frac{1}{\omega C}=\frac{1}{400 \times 2 \times 10^{-5}} \Rightarrow X_{C}=125 \Omega
\end{aligned}
$$

$$
X_{L}>X_{c}
$$

$\therefore \tan \phi=\frac{X_{L}-X_{C}}{R}=\frac{200-125}{150}=\frac{75}{150}=0.5$

$\therefore \quad \phi=\tan ^{-1}(0.5)$

114. (b) Given, Magnetic field in a plane EM wave,

$$
B=\left(3 \times 10^{-7}\right) \sin \left(3 \times 10^{4} x+9 \times 10^{12} t\right) \mathrm{T}
$$

Here, $B_{0}=3 \times 10^{-7} \mathrm{~T}$

Amplitude of electric field,

$$
\begin{aligned}
E_{0} & =B_{0} c \\
& =3 \times 10^{-7} \times 3 \times 10^{8}
\end{aligned}
$$

$\Rightarrow \quad E_{0}=90 \mathrm{Vm}^{-1}$ From the given equation of $B$, it is clear that EM wave is travelling along negative direction of $X$ - axis i.c.

$\therefore$ If $\hat{\mathbf{n}}$ be the unit vector along the dircction of electric ficld, then

$$
\hat{\mathbf{n}} \times \hat{j}=-\hat{i}
$$

Clearly, $\hat{\mathbf{n}}=\hat{k}$

Hence, $E=E_{0} \sin \left(k x+\omega t_{1} \hat{k}\right.$

$$
=90 \sin \left(3 \times 10^{4} x+9 \backslash 10^{12} t\right) \hat{k} \mathrm{Vm}^{-1}
$$

115. (c) Given, $\lambda_{1}=3750 \AA$

$$
\begin{aligned}
\lambda_{2} & =7500 \AA \\
D & =4 \mathrm{~m} \\
d & =3 \mathrm{~mm}=3 \times 10^{-3} \mathrm{~m}
\end{aligned}
$$

since, $\quad \frac{\lambda_{1}}{\lambda_{2}}=\frac{3750}{7500}=\frac{1}{2}$

We know that,

$\Rightarrow$

$$
n_{1} \lambda_{1}=n_{2} \lambda_{2} \Rightarrow \frac{n_{2}}{n_{1}}=\frac{\dot{\lambda}_{1}}{\lambda_{2}}=\frac{1}{2}
$$

$\therefore$ Required minimum distance,

$$
\begin{aligned}
x & =\frac{n_{1} \lambda_{1} D}{d} \\
& =\frac{2 \times 3750 \times 10^{-10} \times 4}{3 \times 10^{-3}}=\frac{3 \times 10^{4} \times 10^{-10}}{3 \times 10^{-3}} \\
& =10^{-3} \mathrm{~m}=1 \mathrm{~mm}
\end{aligned}
$$

116. (c) Maximum kinetic energy of the emitted photoclectrons in photoclectric emission, depends on the frequency of incident radiation and does not depend on the intensity of incident radiation. Hence, statement given in option (c) is correct. For a given frequency of incident radiation, the photocurrent varies with the variation of intensity of incident radiation.

For a given frequency of radiation, the stopping potential does not depend on the intensity of incident radiation.

For a frequency lower than cut off frequency, photoelectric emission is not possible on increasing the intensity upto any value of incident radiation.

117. (a) Change in angular momentum of the electron in $\mathrm{H}$-atom when it is excited from 2nd orbit to 4 th orbit is given as

$$
\Delta L=L_{2}-L_{1}
$$

Where, $L_{2}$ is angular nomentum of 4 th excited state $(n=5)$ and $L$ is angular moment of $2 \mathrm{nd}$ excited state $(n=3)$.

$$
\begin{aligned}
\therefore \quad \Delta L & =\frac{n_{2} h}{2 \pi}-\frac{n_{1} h}{2 \pi} \\
& =\frac{h}{2 \pi}\left[n_{2}-n_{1}\right]=\frac{6.64 \times 10^{-34}}{2 \times 314}[5-4] \\
& =2.11 \times 10^{-34} \mathrm{~J}-\mathrm{s}
\end{aligned}
$$

118. (a) We know that, the radius $(R)$ of nucleus is given as

$$
\begin{aligned}
R & =R_{0} A^{1 / 3} \text { or } R \propto A^{1 / 3} \\
R_{0} & =\text { constant } \\
A & =\text { mass number }
\end{aligned}
$$

Where, $R_{0}=$ constant

$\therefore$ Nuclear density, $\rho=\frac{\text { mass }}{\text { volume }}=\frac{m A}{\frac{4}{3} \pi R^{3}}$

(here, $m$ is mass of each nucleon)

$\Rightarrow \quad \rho=\frac{m A}{\frac{4}{3} \pi\left(R_{0} A^{i / 3}\right)^{3}}=\frac{m A}{\frac{4}{3} \pi R_{0}^{3} A}$

$$
\rho=\frac{3 m}{4 \pi R_{0}^{3}}
$$

Hence, it is clear from above formula, nuclear density is independent of mass number $A$.

The binding energy, $E=\Delta m c^{2}$

i. $\mathrm{e} \quad E \propto \Delta m$

Where, $\Delta m=$ mass defect

Energy is released whon heavy nuclei undergo transmutation into light nuclei.

119. (b) For a carbon sample $\left(\mathrm{C}^{14}\right)$,

$T_{1 / 2}=5730$ year

Decay constant, $K=\frac{0.693}{T_{1 / 2}}$

$$
\begin{aligned}
& =\frac{0.693}{5730} \\
& =1.209 \times 10^{-4} / \text { year }
\end{aligned}
$$

The rate of counts is proportional to the number of $\mathrm{C}^{14}$ atom in the sample

$$
N_{0}=100, N=75
$$

The age of the sample is given as,

$$
\begin{aligned}
t & =\frac{2.303}{K} \log \frac{N_{0}}{N}=\frac{2.303}{K} \log \frac{1}{0.75} \\
& =\frac{2303}{1.209 \times 10^{-4}} \log \frac{100}{75} \\
& =2456 \times 10^{3} \text { years } \\
& =2456 \text { years }
\end{aligned}
$$

120. (a) Ultra high frequency range normally propagated by means of space wave. 

\section{Chemistry}

121. (b) According to de-Broglie's equation,

$$
\lambda=\frac{h}{m v}
$$

where, $\lambda$ is wavelength

$h$ is Planck's constant $\left(6.626 \times 10^{-34} \mathrm{Js}\right)$

$m$ is mass of electron (given $9.0 \times 10^{-31} \mathrm{~kg}$ )

$v$ is velocity of electron (given $2.2 \times 10^{6} \mathrm{~m} / \mathrm{s}$ )

$\therefore \quad \lambda=\frac{6.626 \times 10^{-34}}{9.0 \times 10^{-31} \times 2.2 \times 10^{6}}$

$$
=0.33 \times 10^{-9} \mathrm{~m}
$$

i.e. $0.33 \mathrm{~nm}\left(\right.$ as $1 \mathrm{~nm}=10^{-9} \mathrm{~m}$ )

122. (c) $E=\frac{-136 Z^{2}}{n^{2}}$

$$
\begin{aligned}
E_{1} & =\frac{-136 \times \mathrm{l}^{2}}{\mathrm{l}^{2}} \\
& =-136 \mathrm{eV} \\
E_{2} & =\frac{-136 \times \mathrm{l}^{2}}{3^{2}} \\
& =-1.5111 \mathrm{eV} \\
\Delta E & =E_{2}-E_{1} \\
& =-1.511-(-136) \\
& =12.08 \mathrm{eV} \\
& \cong 12.1 \mathrm{eV}
\end{aligned}
$$

123. (d) Element ' $X$ ' is forming a complex of the type $\left[\mathrm{XCl}\left(\mathrm{H}_{2} \mathrm{O}\right)_{5}\right]^{2+}$.

Total number of ligands attached to $X$ is 6 (one $\mathrm{Cl}$ and five $\mathrm{H}_{2} \mathrm{O}$ ).

$\therefore$ Covalency of $X$ is 6 .

$\mathrm{Cl}$ is a unidentate ligand with charge $-\mathrm{l}$.

$\mathrm{H}_{2} \mathrm{O}$ is a unidentate ligand with charge 0 .

$\therefore \quad x+(-1)+0=+2$

$$
x-1=+2
$$

$$
\begin{aligned}
& x=+2+1=+3
\end{aligned}
$$

$\therefore$ Oxidation state of $x$ is $+3$.

124. (c) Element Electronic configuration

$\begin{array}{ll}X & {[\mathrm{Ne}] 3 s^{2} 3 p^{1}} \\ Y & {[\mathrm{Ne}] 3 s^{2} 3 p^{5}} \\ Z & {[\mathrm{Ne}] 3 s^{2}}\end{array}$

According to given electronic configuration, $X$ is $\mathrm{Al} ; Y$ is $\mathrm{Cl}$ and $Z$ is $\mathrm{Mg}$. Along a period, the basic nature of oxides decreases and acidic nature of oxides increases. $\mathrm{Mg}, \mathrm{Al}$ and $\mathrm{Cl}$ belong to same period with $\mathrm{Mg}$ on left side of the period, $\mathrm{Cl}$ on the right side and $\mathrm{Al}$ in between them. $\therefore$ Oxide of $\mathrm{Cl}$ is i.e. $Y$ will be most acidic oxide of $\mathrm{Mg}$, i.e. $Z$ will be basic and oxide of $\mathrm{Al}$, i.e. $X$ in between the other two.

$\therefore$ Correct increasing order acidic nature will be

$$
Z<X<Y
$$

125. (b)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-23.jpg?height=230&width=279&top_left_y=650&top_left_x=1277)

Solution

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-23.jpg?height=262&width=247&top_left_y=897&top_left_x=1293)
Formal charge $(\mathrm{FC})=V-L-\frac{1}{2} B \rightarrow$ Number of electron Number of valence electron non-bonding electron

FC $($ oxygen 1$)=6-6-\frac{1}{2} \times 2=-1$.

$\mathrm{FC}($ oxygen 2$)=6-4-\frac{1}{2} \times 4=6-6=0$

FC (oxygen 3$)=6-6-\frac{1}{2} \times 2=-1$

126. (b) Bond order $(\mathrm{BO})=\frac{1}{2}$ (number of electron in bonding MO's - number of electron in anti-bonding MO's)

$C_{2}^{2-}:$ Total number of electrons $=6+6+2=14$ Electronic configuration $\sigma\left(1 s^{2}\right), \sigma{ }^{*}\left(1 s^{2}\right), \sigma\left(2 s^{2}\right), \sigma^{*}\left(2 s^{2}\right), \pi 2 p_{x}^{2}=\pi 2 p_{y}^{2}, \sigma 2 p_{z}^{2}$ $\mathrm{BO}=\frac{1}{2} \times(10-4)=\frac{1}{2} \times 6=3$

$N_{2}$ : Total number of electrons $=7 .+7=14$

$\sigma\left(1 s^{2}\right), \sigma\left(1 s^{2}\right), \sigma\left(2 s^{2}\right), \sigma{ }^{*}\left(2 s^{2}\right), \pi 2 p_{x}^{2}=\pi 2 p_{y}^{2}, \sigma 2 p_{z}^{2}$ $\mathrm{BO}=\frac{1}{2}(10-4)=\frac{6}{2}=3$

$0_{2}^{2-}:$ Total number of electron $=8+8+2=18$

$\sigma\left(1 s^{2}\right), \sigma^{*}\left(1 s^{2}\right), \sigma\left(2 s^{2}\right), \sigma^{*}\left(2 s^{2}\right), \sigma 2 p_{z}^{2}, \pi 2 p_{x}^{2}=\pi 2 p_{y}^{2}$

$\mathrm{BO}=\frac{1}{2}(10-8)$

$\pi^{*} 2 p_{x}^{2}=\pi^{*} 2 p_{y}^{2}$ Number of

$$
=\frac{1}{2} \times 2=1
$$

Option (a) is incorrect. $\mathrm{O}_{2}^{+}$Total number of electrons $=8+8-1=15$

$\sigma\left(1 s^{2}\right), \sigma^{*}\left(1 s^{2}\right), \sigma\left(2 s^{2}\right), \sigma^{+}\left(2 s^{2}\right), \sigma\left(2 p_{z}^{2}\right), \pi\left(2 p_{x}^{2}\right)$ $=\pi\left(2 p_{y}^{2}\right), \pi p_{x}^{1}$ $\mathrm{BO}=\frac{1}{2}(10-5)=\frac{1}{2} \times 5=2.5$

$\mathrm{O}_{2}^{-}$Total number of electrons $=8+8+1=17$.

$\sigma\left(1 s^{2}\right), \sigma^{\cdot}\left(1 s^{2}\right), \sigma\left(2 s^{2}\right), \sigma^{+}\left(2 s^{2}\right), \sigma\left(2 p^{2}\right), \pi\left(2 p_{x}^{2}\right)$ $\mathrm{BO}=\frac{1}{2}(10-7)=\frac{1}{2} \times 3=1.5$

$$
=\pi\left(2 p_{y}^{2}\right), \pi^{*}\left(2 p_{x}^{2}\right)=\pi^{*}\left(2 p_{y}^{1}\right)
$$

$\mathbf{N}_{2}^{+}$Total number of electron $=7+7-1=13$

$\sigma\left(1 s^{2}\right), \sigma^{*}\left(1 s^{2}\right), \sigma\left(2 s^{2}\right), \sigma^{*}\left(2 s^{2}\right), \pi\left(2 p_{x}^{2}\right)=\pi\left(2 p_{y}^{2}\right), \sigma\left(2 p_{z}^{1}\right)$ $\mathrm{BO}=\frac{1}{2}(9-4)=\frac{1}{2} \times 5=2.5$

Option (b) is correct.

Similarly, bond order of $O_{2}=\frac{1}{2}(10-6)=\frac{1}{2} \times 4=2$

Bond order of $\mathrm{Li}_{2}=\frac{1}{2}(4-2)=1$

Bond order of $\mathrm{H}_{2}^{+}=\frac{1}{2}(1-0)=0.5$

Bond order of $\mathrm{C}_{2}=\frac{1}{2}(8-4)=\frac{1}{2} \times 4=2$

Rest other options are incorrect, as they don't have bond order in fraction.

127. (c) Ideal gas equation $=p V=n R T$

On rearranging $p=\frac{n R T}{V}$ or $V=\frac{n R T}{p}$

i.e. $p \propto \frac{1}{V}$ or $V \propto \frac{1}{p}$

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-24.jpg?height=382&width=618&top_left_y=1825&top_left_x=205)

At low pressures, the real gas shows very small deviation from ideal behaviour and the curve for ideal gas and real gas almost coincides. There is a large deviation from ideal gas behaviour at high pressure, hence the curve are far apart.

128. (b) $-\mathrm{O}-\|_{S}^{O}-S-S-{ }_{S}^{O}-O^{-}$

When an atom is bonded to similar atoms, has zero oxidation state. $\therefore$ Twio middle sulphur atoms have zero oxidation state.

For other two sulphur atoms.

$$
\begin{aligned}
2 x+6 \times(-2) & =-2 \\
2 x-12 & =-2 \\
2 x & =-2+12 \\
2 x & =+10 \\
x & =+5
\end{aligned}
$$

$\therefore$ The oxidation number on $\mathrm{S}$-atoms in $\mathrm{S}_{4} \mathrm{O}_{6}^{2-}$ is $+5,0,0+5$.

129. (b) Molarity $=\frac{\text { Weight dissolved }}{\text { Molar mass }} \times \frac{1000}{V(\mathrm{~mL})}$ and $V=\frac{\text { Mass of solution }}{\text { Density }}$

Molarity (1) at $90^{\circ} \mathrm{C}=\frac{50}{x} \times \frac{1000 \times 1.1}{1050}=\frac{.52 .38}{x}$

Molarity (2) at $10^{\circ} \mathrm{C}=\frac{50}{x} \times \frac{1000 \times 1.15}{1050}=\frac{54.76}{x}$

Change in molarity $=$ Molarity (2) $-$ Molarity (1) $\%$ change in molarity will be

$$
\begin{aligned}
& =\frac{\text { Molarity }(2)-\text { Molarity }(1)}{\text { Molarity }(1)} \times 100 \\
& =\frac{\frac{54.76}{x}-\frac{52.38}{x}}{\frac{52.38}{x}} \times 100 \\
& =\frac{2.38}{x} \times \frac{x}{52.38} \times 100=4.5
\end{aligned}
$$

130. (b) At $0 \mathrm{~K}$, the entropy of pure crystalline materials is zero.

$\therefore$ The statement (I) is correct as entropy approach zero, at absolute zero.

Statement (II) entropy for the process, $\mathrm{H}_{2} \mathrm{O}(l) \longrightarrow \mathrm{H}_{2} \mathrm{O}(g)$ decreases is incorrect as entropy increases. The degree of randomness when water vaporises to gaseous statē increases.

(III) Gibbs' energy is a state function is correct as the Gibbs' free energy depends on initial and final state only.

Hence, statement (I) and (III) are correct.

131. (a) $2 \mathrm{C}+2 \mathrm{H}_{2}+\frac{1}{2} \mathrm{O}_{2} \longrightarrow \mathrm{CH}_{3} \mathrm{CHO}$

$$
\begin{aligned}
\Delta H_{f}= & \Sigma \mathrm{BE}_{\text {(reaclants) }}-\Sigma \mathrm{BE}_{\text {(products) }} \\
= & {\left[(2 \times 700)+(2 \times 400)+\left(\frac{1}{2} \times 500\right)\right] } \\
& =2450-2650 \\
& -[(4 \times 400)+(250 \times 1)+(700 \times \mathrm{l})] \\
= & -200 \mathrm{~kJ} / \mathrm{mol}
\end{aligned}
$$

132. (c) $K_{p}=K_{C}(R T)^{\Delta n}$

$$
\begin{aligned}
& \mathrm{N}_{2}(g)+3 \mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NH}_{3}(g) \\
& \Delta n=2-(3+\mathrm{l})=2-4=-2 \\
& K_{p}=0.036 \quad \text { given }) \\
& 0.036=K_{c}(0.082 \times 500)^{-2} \\
& \Rightarrow K_{C}=\frac{0.036}{(0.082 \times 500)^{-2}}=60.516 \mathrm{~L}^{2} \mathrm{~mol}^{-2}
\end{aligned}
$$
133. (c) The correct order of relative basic strength will
be

$$
\ddot{\mathrm{NH}}_{3}>\ddot{\mathrm{NH}}_{2}-\ddot{\mathrm{NH}}_{2}>\ddot{\mathrm{NH}}_{2}-\mathrm{OH}
$$

In $\mathrm{NH}_{3}$, the lone pair is completely available for donation, hence is most basic whereas $\mathrm{NH}_{2}-\mathrm{NH}_{2}$ $\mathrm{NH}_{3}$. Here, $\mathrm{H}$ is replaced by $-\mathrm{NH}_{2}$ forming $\mathrm{NH}_{2}-\mathrm{NH}_{2}$ and $-\mathrm{OH}$ forming $\mathrm{NH}_{2}-\mathrm{OH}$ being highly electron withdrawing due to $-\mathrm{O}$ will -decrease the electron density most on $-\mathrm{N}$.

$\therefore$ Least basic electron withdrawing $-I$-effect of - $\mathrm{NH}_{2}$ is less as compared to $-\mathrm{OH}$.

Hence correct order of basic strength is

$$
\mathrm{NH}_{3}>\mathrm{NH}_{2}-\mathrm{NH}_{2}>\mathrm{NH}_{2}-\mathrm{OH}
$$

134. (b) $\mathrm{CaC}_{2}+2 \mathrm{D}_{2} \mathrm{O} \longrightarrow \mathrm{C}_{2} \mathrm{D}_{2}+\mathrm{Ca}(\mathrm{OD})_{2}$ Deutero acetylene

The hybridisation of carbon atoms in deutero acetylene is $s p$.

$$
\mathrm{D}-\mathrm{C} \equiv \mathrm{C}-\dot{\mathrm{D}}
$$

135. (b)

(A) $\mathrm{BeSO}_{4}$ is soluble in water due to higher hydration energy of $\mathrm{Be}^{2+}$. It overcomes the lattice energy factors making $\mathrm{BeSO}_{4}$ soluble in water. The statement is correct.

(B) BeO is amphoteric oxide as it can react with both acid and base, thus acting as basic and acidic respectively. The given statement is thus correct.

(C) $\mathrm{CO}$ can be obtained by heating $\mathrm{CaCO}_{3}$ at $1070-1270 \mathrm{~K}$ is a incorrect statement.

$$
\mathrm{CaCO}_{3} \stackrel{\Delta}{\longrightarrow} \mathrm{CaO}+\mathrm{CO}_{2} \uparrow
$$

$\therefore$ The correct statements are only A and B.

136. (a) The portland cement consists of tricalcium silicate $\left(3 \mathrm{CaO} \cdot \mathrm{SiO}_{2}\right)$, dicalcium silicate $\left(2 \mathrm{CaO} \cdot \mathrm{SiO}_{2}\right)$, tricalcium aluminate $\left(3 \mathrm{CaO} \cdot \mathrm{Al}_{2} \mathrm{O}_{3}\right)$ and tetra-calcium aluminoferrite (4CaO $\cdot \mathrm{Al}_{2} \mathrm{O}_{3} \cdot \mathrm{Fe}_{2} \mathrm{O}_{3}$ ). Hence, the major constituent in it is $\mathrm{CaO}$ and $\mathrm{SiO}_{2}$. The percentage of $\mathrm{CaO} \approx 64 \%$ and $\mathrm{SiO}_{2}$ is $21 \%$. 137. (b) $P+Q \longrightarrow\left[\mathrm{B}(\mathrm{OH})_{4}\right]^{-}+\mathrm{H}_{3} \mathrm{O}^{+}$ $\mathrm{B}(\mathrm{OH})_{3}+2 \mathrm{H}_{2} \mathrm{O} \longrightarrow\left[\mathrm{B}(\mathrm{OH})_{4} \mathrm{~S}^{-}+\mathrm{H}, \mathrm{O}^{+}\right.$ $\mathrm{H}_{3} \mathrm{BO}_{3}+2 \mathrm{H}_{2} \mathrm{O} \longrightarrow\left[\mathrm{B}(\mathrm{OH})_{4} \mathrm{I}^{-}+\mathrm{H}_{3} \mathrm{O}^{+}\right.$ where, $\mathrm{P}_{\mathrm{is}} \mathrm{H}_{3} \mathrm{BO}_{3}$ and $Q$ is $2 \mathrm{H}_{2} \mathrm{O}$. $\mathrm{H}_{3} \mathrm{BO}_{3}$ behaves as Lewis acid in given reaction.

138. (b) Presence of vacant $d$-orbitals in $\mathrm{Si}, \mathrm{Ge}$ and $\mathrm{Sn}$, makes the existence of species $\left[\mathrm{SiF}_{6}\right]^{2-},\left[\mathrm{GeCl}_{6}\right]^{2-}$ and $\left[\mathrm{Sn}(\mathrm{OH})_{6}\right]^{2}-$ feasible. But $\left[\mathrm{SiCl}_{6}\right]^{2-}$ cannot exist as six large $\mathrm{Cl}^{-}$cannot be accomodated around $\mathrm{Si}^{4+}$ ion due to smaller size of cation.

139. (c)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-25.jpg?height=239&width=231&top_left_y=869&top_left_x=1138)

The priority order for the given functionalities in $-\mathrm{CN}>-\mathrm{OH}>-\mathrm{Br}$.

$\therefore$ The numbering will be done from $-\mathrm{CN}$ and in such a way that the groups get lowest number possible.

Hence, the IUPAC name will be 2-bromo-3-hydroxy benzonitrile.

140. (d) Mixture of acetylene and oxygen is used as a fuel for oxy-welding. As this mixture forms flames hot enough, cutting and welding of metals becomes easier.

141. (b) Given, $d=8.92 \mathrm{~g} \mathrm{~cm}^{-3}$

(Edge length) $a=3.61 \times 10^{-8} \mathrm{~cm}$

$$
M=\text { ? }
$$

For fcc, $Z=4$

$$
d=\frac{Z \times M}{a^{3} \times N}
$$

$$
\begin{aligned}
& 8.92=\frac{4 \times M}{\left(3.61 \times 10^{-8}\right)^{3} \times 6.022 \times 10^{23}} .
\end{aligned}
$$

$\Rightarrow \quad M=\frac{8.92 \times 47.045 \times 10^{-24} \times 6.022 \times 10^{-23}}{4}$

$$
=63.178 \mathrm{u}
$$

142. (c)

(a) There are equal number of octahedral and tetrahedral voids in a unit cell for fcc lattice is incorrect statement. The number of octahedral and tetrahedral void in unit cell for fcc lattice is 4 and 8 respectively.

(b) The tetrahedral voids are present at the edge centers is incorrect as they are present on each body diagonal, i.e. diagonal of cubic unit cell. 

\section{AP EAPCET (Engineering) Online Solved Paper 2022}

(c) Octahedral voids are present at the body center and edge centers. Statement $(c)$ is correct.

(d) Its packing efficiency (PE) is higher than hcp lattice $P E$ is incorrect.

The packing efficiency of hcp is $74 \%$ and that of fcc is also 74\%. It is higher in comparison to packing efficiency of simple cube and bcc which have values $52.4$ and $68 \%$ respectively.

143. (d) Given, $n=0.05 \mathrm{~mol}$

$$
\begin{aligned}
V & =500 \mathrm{~g} \text { of water } \\
K_{f} & =1.86 \mathrm{k} \mathrm{kg} / \mathrm{mol} \\
\Delta T_{f} & =?
\end{aligned}
$$

$\therefore$ Molality $=\frac{\text { Number of moles }}{\text { Weight of solvent }(\mathrm{kg})}$

$$
=\frac{0.05}{0.5} \text {. }
$$

$$
\begin{aligned}
& \Delta T_{f}=m \times K_{f} \\
& =\frac{0.05}{0.5} \times 1.86 \\
& =0.186 \mathrm{~K}
\end{aligned}
$$

144. (b) Ideal solutions are the solutions which obey Raoult's law at all temperatures and pressures. The interactions of solute-solute, solvent-solvent and solute-solvent in these solutions are almost similar. No association/dissociation occurs in these solutions.

Mixture of phenol and aniline shows negative deviation from ideal behaviour and forms an azeotropic mixture. The phenol-aniline interactions are stronger than phenol-phenol or aniline-aniline interactions.

$$
\begin{aligned}
& \Delta V_{\text {mixing }}<0 \\
& \Delta H_{\text {mixing }}>0
\end{aligned}
$$

Hence, it does not form an ideal solution.

Rest options (I), (II) and (III) form ideal solution.

145. (a) Given, $I=96.5 \mathrm{~A}$

$$
\Rightarrow \quad \begin{aligned}
& t=100 \mathrm{~s} \\
& \Rightarrow \quad m=?
\end{aligned}
$$

Atomic weight of $\mathrm{Al}=27 \mathrm{u}$

$$
\begin{aligned}
Q & =I \times t=96.5 \times 100 \\
& =9650 \mathrm{C}
\end{aligned}
$$

$\mathrm{AlCl}_{3} \longrightarrow \mathrm{Al}^{3+}+3 \mathrm{Cl}^{-}$

$\mathrm{Al}^{3+}+3 e^{-} \longrightarrow \mathrm{Al}$

$96500 \times 3 \mathrm{C}$ of electricity deposits, 1 mole $\mathrm{Al}$. $\therefore 9650 \mathrm{C}$ will deposit $\mathrm{Al}=\frac{9650}{96500 \times 3}=0.0333 \mathrm{~mol}$.

Weight of $\mathrm{Al}$ deposited $=n \times$ molar mass

$$
\begin{aligned}
& =0.0333 \times 27 \\
& \cong 0.90 \mathrm{~g}
\end{aligned}
$$

146. (b) Given, $k_{1}=0.02 \mathrm{~s}^{-1}$

$$
\begin{aligned}
& k_{2}=0.2 \mathrm{~s}^{-1} \\
& E_{a}=? \\
& R=8.3 \\
& T_{1}=500 \mathrm{~K} \\
& T_{2}=700 \mathrm{~K}
\end{aligned}
$$

$\operatorname{In} \frac{k_{2}}{k_{1}}=-\frac{E_{a}}{R}\left(\frac{1}{T_{2}}-\frac{1}{T_{1}}\right)$.

$\operatorname{In} \frac{0.2}{0.02}=-\frac{E_{a}}{8.3}\left[\frac{1}{700}-\frac{1}{500}\right]$

In $10=\frac{-E_{a}}{8.3}\left(\frac{500-700}{700 \times 500}\right)$

$2.302 \times 8.3 \times .700 \times 500=200 E_{a}$

$\Rightarrow E_{a}=\frac{2.302 \times 8.3 \times 700 \times 500}{200}$

$=33436 \mathrm{~J} / \mathrm{mol}$

$\approx 33.44 \mathrm{~kJ} / \mathrm{mol}$

147. (c) Sucrose $\stackrel{\text { Invertase }}{\longrightarrow}$ Glucose + Fructose

Proteins $\stackrel{\text { Pepsin }}{\longrightarrow}$ Peptides

Starch $\stackrel{\text { Diastase }}{\longrightarrow}$ Maltose

The correct match is A-II, B-III, C-IV.

148. (d) Coagulating power $\propto$ Charge

Charge on $\left[\mathrm{Fe}(\mathrm{CN})_{6}\right]^{4-}>\mathrm{SO}_{4}^{2-}>\mathrm{Cl}^{-}$

$\therefore$ Correct order of coagulating power is

$$
\text { I }>\text { III }>\text { II }
$$

149. (d) (A) is incorrect but (R) is correct as ionisation enthalpy values of group 15 th is higher than group l6th due to stable half-filled electronic configurations.

150. (c) (A) is correct but (R) is incorrect. Due to small size of fluorine, the electronic repulsions in - fluorine are higher as compared to chlorine with larger size. Hence, the incoming electron does not experience much attraction due to which the electron gain enthalpy is less negative. 151. (c) Isoclectronic species have same number of elcctrons in them.

(a) $\operatorname{Pr}^{\text {i- }}$ number of elcitron $=59-3=56$

$\mathrm{Nd}^{3+}$ number of clectron $=60-3=57$

$\therefore \operatorname{Pr}^{3+}$ and $\mathrm{Nd}^{31}$ are not isoclectronic.

(b) $\mathrm{Tb}^{3+}$ : Total number of electron $=65-3=62$

$D^{2+}:$ Total number of electron $=66-2=64$

$\therefore \mathrm{Tb}^{3+}$ and $\mathrm{Dy}^{2}$ are not isoelectronic.

(c) $\mathrm{Eu}^{2+}$ number of dection $=63-2=61$

$\mathrm{Gd}^{3+}$ number of electron $=64-3=61$

$\therefore \mathrm{Eu}^{2+}$ and $\mathrm{Gd}^{3+}$ are isoelectronic.

(d) $\mathrm{Pr}^{3+}$ number of electron $=59-3=56$

$\mathrm{Ce}^{4+}$ number of electron $=58-4=54$

$\therefore \mathrm{Pr}^{3+}$ and $\mathrm{Cc}^{4+}$ are not isoclectronic.

152. (c) Homoleptic complexes are the complexes in which all the ligands attached to central metal atom/ion are same or identical.

$\left.\therefore \mathrm{Co}\left(\mathrm{NH}_{3}\right)_{6}\right]^{3+}$ is a homolep :omplex whereas other complexes are not.

1.53. (d) Carbohydrates are stored in plants in form of starch and in animals in the form of glycogen. The starch and glycogen are broken during metabolism to release energy.

154. (a) Glycylalanine is a dipeptide made up of glycine and L-alanine residues. When glycine and alanine link together, a water molecule is released and glycylalanine is formed which works as a metabolite.

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-27.jpg?height=548&width=703&top_left_y=1796&top_left_x=194)

155. $(d)$
![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-27.jpg?height=1024&width=544&top_left_y=351&top_left_x=1165)

is correct option.

156. (d)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-27.jpg?height=297&width=791&top_left_y=1436&top_left_x=1044)

$\mathrm{Cl}$ has $-I$ and $+R$-effect. Due to electron donating resonance effect it is ortho/para-directing and donates the electron density to benzene ring. Thus, the incoming electrophile - $\mathrm{Br}$ gets attached on para-position and para disubstituted product is obtained as major product and ortho as minor product.

157. (a)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-27.jpg?height=220&width=686&top_left_y=2106&top_left_x=1093)



![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-28.jpg?height=105&width=1108&top_left_y=340&top_left_x=0)

Methanol is industrially prepared when mixture of carbon monoxide and hydrogen is subjected to high temperature and pressure in presence of $\mathrm{ZnO}-\mathrm{Cr}_{2} \mathrm{O}_{3}$ as catalyst.

159. (c)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-28.jpg?height=1157&width=872&top_left_y=632&top_left_x=536)

160. (a)

(A)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-28.jpg?height=73&width=296&top_left_y=1876&top_left_x=230)

(B)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-28.jpg?height=97&width=300&top_left_y=1875&top_left_x=674)

(C)

![](https://cdn.mathpix.com/cropped/2023_02_06_fcd6df5e8e22358f383ag-28.jpg?height=91&width=207&top_left_y=1881&top_left_x=1107)

The boiling point of (A) alcohol is highest due to $\mathrm{H}$-bonding.

Out of primary (B), secondary (D) and tertiary amines (C), the boiling point in decreasing order is Primary amine $>$ Secondary amine $>$ Tertiary amine

as intermolecular association decreases in same order, being highest in primary amine and least in tertiary
amine due to steric hindrance.

$\therefore$ The correct decreasing order of boiling point in given compound is

$$
\mathrm{A}>\mathrm{B}>\text { D }>\text { C } \text {. }
$$