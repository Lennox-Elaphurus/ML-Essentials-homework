# Exercise2.2


$$
\begin{array}{lcl}
\text{For L = 1 :} \\
Z_{0} = X \\
\tilde{Z}_{1} = Z_{0}B_{0} + b_{0} \\
Z_{1}=\tilde{Z}_{1}=XB_{0} + b_{0}
\end{array}\\
$$
$$
\begin{aligned}

\begin{array}{lcl}
\text{For L = 2 :} \\
\tilde{Z}_{2} = Z_{1}B_{1} + b_{1} \\

\begin{align*}
Z_{2}&=\tilde{Z}_{2}\\
&=(Z_{0}B_{0} + b_{0})B_{1} + b_{1}\\
&=XB_{0}B_{1} + b_{0}B_{1} + b_{1}\\
\end{align*}\\

\text{Let} \tilde{B}_{1} = B_{0}B_{1}, \tilde{b}_{1} = b_{0}B_{1}+ b_{1}, \\
\Rightarrow Z_{2} = X\tilde{B}_{1} + \tilde{b}_{1} \\
\therefore \text{network with depth L = 2 is equivalent to 1-layer network (a)} 

\end{array}\\
\end{aligned}
$$
$$
\begin{array}{lcl}
\text{For L = n and L = n+1 :} \\

Z_{n}=Z_{n-1}B_{n}+b_{n}\\

\begin{align*}
Z_{n+1}&=Z_{n}B_{n+1}+b_{n+1} \\
&=(Z_{n-1}B_{n}+b_{n})B_{n+1}+b_{n+1} \\
&=Z_{n-1}B_{n}B_{n+1} + b_{n}B_{n+1}+b_{n+1} \\
\end{align*}\\

\text{Let} \tilde{B}_{n+1} = B_{n}B_{n+1}, \tilde{b}_{n+1} = b_{n}B_{n+1}+ b_{n+1}, \\

Z_{n+1} = Z_{n-1}\tilde{B}_{n+1}+\tilde{b}_{n+1}\\
\therefore \text{network with depth L = n is equivalant to network with depth L = n + 1 (b)}\\

\because \text{(a) and (b)}
\therefore \text{Any network with depth L larger than 1 is equivalent to a 1-layer network}
\end{array}\\
$$


