# Fórmulas — Mecânica Quântica 1

---

## 🌊 Relação de De Broglie

$$\lambda = \frac{h}{p}$$

$$p = \hbar k \qquad k = \frac{2\pi}{\lambda}$$

---

## ⚛️ Função de Onda

$$\Psi(x,t) \in \mathbb{C}$$

$$|\Psi(x,t)|^2 = \text{densidade de probabilidade}$$

---

## 📏 Normalização

$$\int_{-\infty}^{+\infty} |\Psi(x,t)|^2 \, dx = 1$$

---

## ⚡ Equação de Schrödinger — Dependente do Tempo

$$i\hbar \frac{\partial \Psi}{\partial t} = \hat{H}\,\Psi$$

---

## ⏱️ Equação de Schrödinger — Independente do Tempo

$$\hat{H}\,\psi = E\,\psi$$

$$-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2} + V(x)\,\psi = E\,\psi$$

---

## 🧮 Operador Hamiltoniano

$$\hat{H} = -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r})$$

Em 1D:

$$\hat{H} = -\frac{\hbar^2}{2m}\frac{d^2}{dx^2} + V(x)$$

---

## 📐 Operadores Fundamentais

### Posição

$$\hat{x} = x$$

### Momento Linear

$$\hat{p} = -i\hbar\frac{\partial}{\partial x}$$

### Energia Cinética

$$\hat{T} = \frac{\hat{p}^2}{2m} = -\frac{\hbar^2}{2m}\frac{d^2}{dx^2}$$

---

## 🔄 Relações de Comutação

$$[\hat{x},\,\hat{p}] = i\hbar$$

$$[\hat{x},\,\hat{x}] = 0 \qquad [\hat{p},\,\hat{p}] = 0$$

$$[\hat{H},\,\hat{p}] = i\hbar\frac{\partial V}{\partial x}$$

---

## ❗ Princípio da Incerteza de Heisenberg

$$\Delta x \cdot \Delta p \geq \frac{\hbar}{2}$$

$$\Delta E \cdot \Delta t \geq \frac{\hbar}{2}$$

Onde:

$$\Delta A = \sqrt{\langle\hat{A}^2\rangle - \langle\hat{A}\rangle^2}$$

---

## 📊 Valor Esperado

$$\langle\hat{A}\rangle = \int_{-\infty}^{+\infty} \Psi^*\,\hat{A}\,\Psi \, dx$$

$$\langle x \rangle = \int_{-\infty}^{+\infty} x\,|\Psi|^2 \, dx$$

$$\langle p \rangle = -i\hbar \int_{-\infty}^{+\infty} \Psi^*\frac{\partial\Psi}{\partial x} \, dx$$

---

## 🔒 Poço de Potencial Infinito

Para $0 \leq x \leq L$:

$$\psi_n(x) = \sqrt{\frac{2}{L}}\sin\!\left(\frac{n\pi x}{L}\right) \qquad n = 1,2,3,\ldots$$

$$E_n = \frac{n^2\pi^2\hbar^2}{2mL^2} = \frac{n^2 h^2}{8mL^2}$$

$$E_1 = \frac{\pi^2\hbar^2}{2mL^2} \quad \text{(energia do estado fundamental)}$$

---

## 🎵 Oscilador Harmônico Quântico

$$V(x) = \frac{1}{2}m\omega^2 x^2$$

$$E_n = \hbar\omega\!\left(n + \frac{1}{2}\right) \qquad n = 0,1,2,\ldots$$

### Operadores de Criação e Aniquilação

$$\hat{a} = \sqrt{\frac{m\omega}{2\hbar}}\left(\hat{x} + \frac{i\hat{p}}{m\omega}\right)$$

$$\hat{a}^\dagger = \sqrt{\frac{m\omega}{2\hbar}}\left(\hat{x} - \frac{i\hat{p}}{m\omega}\right)$$

$$[\hat{a},\,\hat{a}^\dagger] = 1$$

$$\hat{H} = \hbar\omega\!\left(\hat{a}^\dagger\hat{a} + \frac{1}{2}\right)$$

---

## 🌀 Momento Angular

$$\hat{L}_z = -i\hbar\frac{\partial}{\partial\phi}$$

$$\hat{\mathbf{L}}^2 = -\hbar^2\left[\frac{1}{\sin\theta}\frac{\partial}{\partial\theta}\left(\sin\theta\frac{\partial}{\partial\theta}\right) + \frac{1}{\sin^2\theta}\frac{\partial^2}{\partial\phi^2}\right]$$

$$\hat{\mathbf{L}}^2\,Y_l^m = \hbar^2 l(l+1)\,Y_l^m$$

$$\hat{L}_z\,Y_l^m = m\hbar\,Y_l^m$$

$$[\hat{L}_x,\,\hat{L}_y] = i\hbar\hat{L}_z$$

---

## ⚛️ Átomo de Hidrogênio

$$E_n = -\frac{m_e e^4}{2(4\pi\epsilon_0)^2\hbar^2}\cdot\frac{1}{n^2} = -\frac{13{,}6\,\text{eV}}{n^2}$$

$$a_0 = \frac{4\pi\epsilon_0\hbar^2}{m_e e^2} \approx 0{,}529\,\text{Å} \quad \text{(raio de Bohr)}$$

---

## 🔁 Equação de Continuidade

$$\frac{\partial\rho}{\partial t} + \frac{\partial J}{\partial x} = 0$$

$$\rho = |\Psi|^2 \qquad J = \frac{\hbar}{2mi}\left(\Psi^*\frac{\partial\Psi}{\partial x} - \Psi\frac{\partial\Psi^*}{\partial x}\right)$$

---

## 📌 Postulados — Resumo

| # | Postulado |
|---|-----------|
| 1 | O estado é descrito por $\Psi$ |
| 2 | Observáveis são operadores hermitianos $\hat{A} = \hat{A}^\dagger$ |
| 3 | Medidas retornam autovalores $a_n$ de $\hat{A}$ |
| 4 | Evolução: $i\hbar\,\partial_t\Psi = \hat{H}\Psi$ |
| 5 | Colapso: após medida, $\Psi \to \psi_n$ |

---

## 📎 Constantes Úteis

$$\hbar = \frac{h}{2\pi} \approx 1{,}055 \times 10^{-34}\,\text{J·s}$$

$$h \approx 6{,}626 \times 10^{-34}\,\text{J·s}$$

$$m_e \approx 9{,}109 \times 10^{-31}\,\text{kg}$$

$$e \approx 1{,}602 \times 10^{-19}\,\text{C}$$
