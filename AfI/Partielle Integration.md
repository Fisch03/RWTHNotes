---
aliases: []
tags:
- AfI
---
Aus $(f\cdot g)'=f'\cdot g+f\cdot g'$ folgt 
$$\int(f\cdot g)'dx=f(x)g(x)=\int(f'(x)g(x)dx)+\int f(x)g'(x)dx$$
also 
$$\int f(x)g'(x)dx=f(x)g(x)-\int f'(x)g(x)dx$$
bzw.
$$\int_{a}^{b}f(x)g'(x)dx=f(x)g(x)\big|_{a}^{b}-\int_{a}^{b}f'(x)g(x)dx$$

> [!NOTE]
> $F(x)\big|_{a}^{b}:=F(b)-F(a)$

## Beispiele
$$\int \underbrace{t^2}_{f(t)}\underbrace{e^{t}}_{g'(x)}dt=\underbrace{t^{2}e^{t}}_{f\cdot g}-\int(2t)e^{t}dt=t^{2}e^{t}-(2te^{t}-2e^{t})=(t^{2}-2t+2)e^{t}+\mathbb{C}$$
