# Mecânica Quântica — Introdução

![Capa](https://raw.githubusercontent.com/labremotodeivid-coder/labremoto/main/imagens/mecanica_quantica/Capa_1.png)

---

## 📌 Introdução

A mecânica quântica é a teoria fundamental que descreve o comportamento da matéria e da radiação em escalas microscópicas, como átomos, elétrons e fótons.

Diferente da mecânica clássica, ela introduz conceitos como:

- Dualidade onda-partícula  
- Princípio da incerteza  
- Quantização de energia  
- Função de onda  

---

## 🌊 Dualidade Onda-Partícula

Experimentos como o de dupla fenda mostram que partículas podem se comportar como ondas.

A relação de De Broglie descreve esse comportamento:

$$
\lambda = \frac{h}{p}
$$

Onde:
- $\lambda$ = comprimento de onda  
- $h$ = constante de Planck  
- $p$ = momento linear  

---

## ⚛️ Função de Onda

O estado de uma partícula é descrito por uma função de onda:

$$
\psi(x,t)
$$

A interpretação física é dada por:

$$
|\psi(x,t)|^2 = \text{densidade de probabilidade}
$$

Ou seja, representa a probabilidade de encontrar a partícula em uma posição.

---

## 📏 Normalização

A função de onda deve satisfazer:

$$
\int_{-\infty}^{\infty} |\psi(x,t)|^2 dx = 1
$$

Isso garante que a partícula existe em algum lugar do espaço.

---

## 📐 Operadores

Observáveis físicos são representados por operadores.

Exemplo:

### Posição
$$
\hat{x} = x
$$

### Momento
$$
\hat{p} = -i\hbar \frac{d}{dx}
$$

---

## 📊 Valor Esperado

O valor médio de uma grandeza é:

$$
\langle A \rangle = \int \psi^* \hat{A} \psi \, dx
$$

---

## ⚡ Equação de Schrödinger

A equação fundamental da mecânica quântica é:

### Forma dependente do tempo:

$$
i\hbar \frac{\partial \psi}{\partial t} = \hat{H} \psi
$$

Onde:
- $\hat{H}$ = Hamiltoniano

---

## 🧮 Hamiltoniano

Para uma partícula em 1D:

$$
\hat{H} = -\frac{\hbar^2}{2m} \frac{d^2}{dx^2} + V(x)
$$

---

## ⏱️ Equação independente do tempo

Quando o potencial não depende do tempo:

$$
\hat{H} \psi = E \psi
$$

Essa é uma equação de autovalores.

---

## 🔒 Poço de Potencial Infinito

Um dos sistemas mais importantes:

### Condições:
- $V(x) = 0$ dentro do poço
- $V(x) = \infty$ fora

### Soluções:

$$
\psi_n(x) = \sqrt{\frac{2}{L}} \sin\left(\frac{n\pi x}{L}\right)
$$

### Energia quantizada:

$$
E_n = \frac{n^2 \pi^2 \hbar^2}{2mL^2}
$$

---

## ❗ Princípio da Incerteza

Formulado por Heisenberg:

$$
\Delta x \cdot \Delta p \geq \frac{\hbar}{2}
$$

Isso significa que não podemos conhecer simultaneamente posição e momento com precisão infinita.

---

## 🔄 Comutadores

Dois operadores obedecem:

$$
[\hat{x}, \hat{p}] = i\hbar
$$

---

## 📌 Postulados da Mecânica Quântica

1. O estado do sistema é descrito por $\psi$
2. Observáveis são operadores
3. Medidas retornam autovalores
4. Evolução temporal segue Schrödinger
5. Após medida, o sistema colapsa

---

## 🎯 Interpretação Física

- A mecânica quântica é probabilística
- Não descreve trajetórias exatas
- Mede distribuições de probabilidade

---

## 📚 Conclusão

A mecânica quântica substitui a visão clássica determinística por uma visão probabilística, sendo essencial para entender:

- Estrutura atômica  
- Física do estado sólido  
- Eletrônica moderna  
- Física de partículas  

---

## 🚀 Próximos passos

Nos próximos tópicos você verá:

- Operadores mais avançados  
- Estados estacionários  
- Oscilador harmônico quântico  
- Átomo de hidrogênio  
