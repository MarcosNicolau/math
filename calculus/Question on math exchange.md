#### Expanding the boundary of a chain over more general regions

Hello, I have been studying the General Stokes Theorem. I understand that the integrals are defined over $p$-chains and their boundary. 

Now, regarding the boundary of a p-chain, I saw that given the $p$-chain $T$ defined on $\mathbb R^n$, that is $T:I^p \to \mathbb R^n$, then one defines the boundary of  $T$ as 
$$
\tag{1}
\partial T = \sum _{i = 1} ^p (-1)^{i+1}(T(x_1,\dots,x_{i-1} 1, x_{i+1} \dots, x_p) -T(x_1,\dots,x_{i-1} 0, x_{i+1} \dots, x_p))
$$


My question is: couldn't we expand the formula of a boundary for more general region? More specifically, suppose there is a bounded region $\Omega$ in $\mathbb R^p$ such that 
$$
\begin{gathered}
\Omega = \{(x_1, x_2, \dots, x_p) \in \mathbb R^p \, | & f_1 ^0 \leq x_1 \leq f_2 ^0  \\
& f_1 ^1 (x_1) \leq x_2 \leq f_2 ^1 (x_1) \\
& f_1 ^2 (x_1, x_2) \leq x_3 \leq f_2 ^2 (x_1, x_2)  \\
& \vdots \\
& f_1 ^{p -1} (x_1, x_2, \dots, x_{p -1}) \leq x_p \leq f_2 ^{p-1} (x_1, x_2, \dots, x_{p - 1})
\}
\end{gathered}
$$

where $f_i ^j$ is continuos $\forall i,j$ and $f^0 _1 \, f^0 _2$ are real numbers.

Suppose now that there exists a $p$-chain $T:\Omega\to \mathbb R^n$, then following (1) couldn't we say that the boundary of $T$ becomes
$$
\partial T = \sum _{i = 1} ^p (-1)^{i+1}(T(x_1,\dots,x_{i-1} f_2 ^{i - 1}, x_{i+1} \dots, x_p) -T(x_1,\dots,x_{i-1} f_1 ^{i - 1}, x_{i+1} \dots, x_p))
$$

I tried this for some surfaces with bounded domains and it worked.

Furthermore, since $\Omega$ is bounded, then surely we can find a rectangle that contains $\Omega$.

But, I wonder: does it apply to all bounder regions where $f ^i$ are continuos? I've been trying to figure that out for the last couple of weeks but there are nothing but really advance papers that are really out of my current level and I just want a quick answer :). 

Btw, for I saw that it has something to do with CW complex spaces.

Thanks in advance!