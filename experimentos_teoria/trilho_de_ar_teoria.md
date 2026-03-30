# 📚 Teoria — Trilho de Ar

O **Trilho de Ar** é um equipamento utilizado para estudar o movimento de corpos com **mínimo atrito**, simulando condições ideais descritas pelas Leis de Newton.

---

## 1. 🏃 Cinemática do Movimento

### 1.1 Posição em função do tempo

A posição $x$ de um corpo em movimento uniformemente variado é dada por:

$$x = x_0 + v_0 t + \frac{1}{2} a t^2$$

Onde:
- $x_0$ → posição inicial (m)
- $v_0$ → velocidade inicial (m/s)
- $a$ → aceleração (m/s²)
- $t$ → tempo (s)

---

### 1.2 Velocidade em função do tempo

$$v = v_0 + at$$

Para o **Movimento Uniforme** (aceleração nula):

$$v = \frac{\Delta x}{\Delta t} = \text{constante}$$

---

### 1.3 Equação de Torricelli

Relaciona velocidade e posição **sem o tempo**:

$$v^2 = v_0^2 + 2a \Delta x$$

---

## 2. ⚖️ Leis de Newton

### 2.1 Primeira Lei — Inércia

> *"Um corpo em repouso permanece em repouso, e um corpo em movimento permanece em movimento retilíneo uniforme, a menos que uma força resultante atue sobre ele."*

No trilho de ar, o **colchão de ar** elimina o atrito, aproximando o sistema de um corpo **livre de forças horizontais**.

---

### 2.2 Segunda Lei — Força Resultante

$$F = ma$$

Para o carrinho no plano inclinado, a componente da gravidade ao longo do trilho é:

$$F = mg \sin\theta$$

Portanto a aceleração do carrinho é:

$$a = g \sin\theta$$

Onde:
- $m$ → massa do carrinho (kg)
- $g$ → aceleração gravitacional ≈ 9,8 m/s²
- $\theta$ → ângulo de inclinação do trilho

---

### 2.3 Terceira Lei — Ação e Reação

$$\vec{F}_{AB} = -\vec{F}_{BA}$$

---

## 3. 📐 Plano Inclinado

![Diagrama do plano inclinado](https://raw.githubusercontent.com/labremotodeivid-coder/labremoto/main/experimentos_info/trilho_diagrama.png)

No trilho inclinado com ângulo $\theta$, as forças que atuam no carrinho são:

| Força | Símbolo | Direção |
|-------|---------|---------|
| Peso | $mg$ | Vertical ↓ |
| Normal | $N$ | Perpendicular ao trilho |
| Componente paralela | $mg\sin\theta$ | Ao longo do trilho |

A aceleração resultante:

$$a = g \sin\theta$$

---

## 4. 📊 Energia Mecânica

### 4.1 Energia Cinética

$$E_c = \frac{1}{2}mv^2$$

### 4.2 Energia Potencial Gravitacional

$$E_p = mgh$$

### 4.3 Conservação de Energia

Na ausência de atrito (trilho de ar):

$$E_c + E_p = \text{constante}$$

$$\frac{1}{2}mv_1^2 + mgh_1 = \frac{1}{2}mv_2^2 + mgh_2$$

---

## 5. 📏 Análise Gráfica

### Gráfico Posição × Tempo

- **MU** → reta com inclinação constante
- **MUV** → parábola

### Gráfico Velocidade × Tempo

- **MU** → reta horizontal
- **MUV** → reta com inclinação = aceleração

### Gráfico Aceleração × Tempo

- **MUV** → reta horizontal (aceleração constante)

---

## 6. 🔢 Determinação Experimental da Aceleração

A partir dos dados coletados pelos sensores, calcula-se a velocidade média entre dois pontos:

$$v_m = \frac{x_2 - x_1}{t_2 - t_1}$$

E a aceleração média:

$$a = \frac{v_2 - v_1}{t_2 - t_1}$$

Comparando com o valor teórico $a = g\sin\theta$, avalia-se a qualidade do experimento.

---

## 📖 Referências

1. HALLIDAY, D.; RESNICK, R.; WALKER, J. **Fundamentos de Física**, Vol. 1. LTC, 10ª ed.
2. NUSSENZVEIG, H. M. **Curso de Física Básica**, Vol. 1. Edgard Blücher, 5ª ed.
3. TIPLER, P. A. **Física para Cientistas e Engenheiros**, Vol. 1. LTC, 6ª ed.

---

*🔬 Lab Remoto © 2025 — UNIFEI Itajubá*
