$u_n$ is the $n\text{th}$ term of sequence $u$.
$\{u_n\}$ is considered the whole sequence.
A series is defined either recursively or absolutely.
* $u_{n+1}=u_n+d$ is the recursive definition for arithmetic series
* $u_n=u_1+dn$ is the absolute definition for arithmetic series
* $u_{n+1}=u_nd$ is the recursive definition for geometric series
* $u_n=u_1d^n$ is the absolute definition for geometric series
## Arithmetic Series
The sum of ${u_n}$ is $S_n$. It can be defined as

$$S_n=\sum_{r=0}^{n}u_r$$

Which equals

$$S_n=u_1n+d(\frac{n^2+n}{2})$$
### Finding $d$
If at least two terms of $\{u_n\}$ are known (as $u_a$ and $u_b$), $d$ can be defined as:

$$d(a-b)=u_a-u_b$$

If $d$ is known, $u_1$ can be defined as:

$$u_1=u_n-dn$$
### Rules
If there is an arithmetic series $\{u_n\}$ defined as $u_n=u_1+dn$, and a boundary $u_m$, $m$ can be defined as

$$m=\frac{u_m-u_1}{d}$$
## Geometric Series
The sum of $\{u_n\}$ is $S_n$. It can be defined as 

$$S_n=\sum_{r=0}^{n}u_r$$

When $r<1$:

$$S_n=\frac{u_1(1-r^n)}{1-r}$$

When $r>1$:

$$S_n=\frac{u_1(r^n-1)}{r-1}$$
### Finding $r$
If at least two terms of $\{u_n\}$ are known (as $u_a$ and $u_b$), $r$ can be defined as:

$$r^{a-b}=\frac{u_a}{u_b}$$

If $r$ is known, $u_1$ can be defined as:

$$u_1=\frac{u_n}{r^{n-1}}$$
### Rules
If there is a geometric sequence $\{u_n\}$ defined as $u_n=u_1d^n$ and a boundary $u_m$, $m$ can be found with:

$$m=\log_d{\frac{u_m}{u_1}}$$

([[Logarithm Laws]])