```math
f = \exp(c x^{m}), \quad x, c, m \in \mathbb{C}
```

---

```math
\frac{df}{dx} = e^{cx^m} \left( q(0,1)c^0x^{0\cdot m-1} + q(1,1)c^1x^{1\cdot m-1} \right)
```

```math
q(0,1)=0
```

```math
q(1,1)=m
```

---

```math
q(k, n+1) = (km - n)q(k, n) + mq(k-1, n)
```

```math
\text{if } k > n, \text{ then } q(k, n) = 0
```

---

```math
\frac{d^2f}{dx^2} = e^{cx^m} \left( q(0,2)c^0x^{0\cdot m-2} + q(1,2)c^1x^{1\cdot m-2} + q(2,2)c^2x^{2\cdot m-2} \right)
```

```math
q(0,2)=0
```

```math
q(1,2)=m(m-1)
```

```math
q(2,2)=m^2
```

---

```math
\frac{d^3f}{dx^3} = e^{cx^m} \left( q(0,3)c^0x^{0\cdot m-3} + q(1,3)c^1x^{1\cdot m-3} + q(2,3)c^2x^{2\cdot m-3} + q(3,3)c^3x^{3\cdot m-3} \right)
```

```math
q(0,3)=0
```

```math
q(1,3)=m(m-1)(m-2)
```

```math
q(2,3)=3m^2(m-1)
```

```math
q(3,3)=m^3
```

---

```math
\frac{d^4f}{dx^4} = e^{cx^m} \left( q(0,4)c^0x^{0\cdot m-4} + q(1,4)c^1x^{1\cdot m-4} + q(2,4)c^2x^{2\cdot m-4} + q(3,4)c^3x^{3\cdot m-4} + q(4,4)c^4x^{4\cdot m-4} \right)
```

```math
q(0,4)=0
```

```math
q(1,4)=m(m-1)(m-2)(m-3)
```

```math
q(2,4)=m^2(m-1)(7m-11)
```

```math
q(3,4)=6m^3(m-1)
```

```math
q(4,4)=m^4
```

---

```math
\frac{d^5f}{dx^5} = e^{cx^m} \left( q(0,5)c^0x^{0\cdot m-5} + q(1,5)c^1x^{1\cdot m-5} + q(2,5)c^2x^{2\cdot m-5} + q(3,5)c^3x^{3\cdot m-5} + q(4,5)c^4x^{4\cdot m-5} + q(5,5)c^5x^{5\cdot m-5} \right)
```

```math
q(0,5)=0
```

```math
q(1,5)=m(m-1)(m-2)(m-3)(m-4)
```

```math
q(2,5)=5m^2(m-1)(m-2)(3m-5)
```

```math
q(3,5)=5m^3(m-1)(5m-7)
```

```math
q(4,5)=10m^4(m-1)
```

```math
q(5,5)=m^5
```

---

```math
\frac{d^6f}{dx^6} = e^{cx^m} \left( q(0,6)c^0x^{0\cdot m-6} + q(1,6)c^1x^{1\cdot m-6} + q(2,6)c^2x^{2\cdot m-6} + q(3,6)c^3x^{3\cdot m-6} + q(4,6)c^4x^{4\cdot m-6} + q(5,6)c^5x^{5\cdot m-6} + q(6,6)c^6x^{6\cdot m-6} \right)
```

```math
q(0,6)=0
```

```math
q(1,6)=m(m-1)(m-2)(m-3)(m-4)(m-5)
```

```math
q(2,6)=m^2(m-1)(m-2)(31m^2-132m+137)
```

```math
q(3,6)=15m^3(m-1)(2m-3)(3m-5)
```

```math
q(4,6)=5m^4(m-1)(13m-17)
```

```math
q(5,6)=15m^5(m-1)
```

```math
q(6,6)=m^6
```

---

Since

```math
q(k, n+1) = (km - n)q(k, n) + mq(k-1, n)
```

---

Therefore

```math
q(0,7) = (0\cdot m-6)q(0,6)+m q(-1,6) = 0
```

---

```math
q(1,7) = (1\cdot m-6)q(1,6)+m q(0,6) = m(m-1)(m-2)(m-3)(m-4)(m-5)(m-6)
```

---

```math
q(2,7) = (2\cdot m-6)q(2,6)+m q(1,6) = 21m^2(m-1)(m-2)^2(m-3)(3m-7)
```

---

```math
q(3,7) = (3\cdot m-6)q(3,6)+m q(2,6) = 7m^3(m-1)(m-2)(43m^2-141m+116)
```

---

```math
q(4,7) = (4\cdot m-6)q(4,6)+m q(3,6) = 35m^4(m-1)(2m-3)(5m-7)
```

---

```math
q(5,7) = (5\cdot m-6)q(5,6)+m q(4,6) = 35m^5(m-1)(4m-5)
```

---

```math
q(6,7) = (6\cdot m-6)q(6,6)+m q(5,6) = 21m^6(m-1)
```

---

```math
q(7,7) = (7\cdot m-6)q(7,6)+m q(6,6) = m^7
```
