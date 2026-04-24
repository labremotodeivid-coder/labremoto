# Mecânica Quântica — Volume I
### *Basic Concepts, Tools, and Applications*
**Claude Cohen-Tannoudji, Bernard Diu e Franck Laloë**
*Segunda Edição — Wiley-VCH, 2020*

---

## Sobre a Obra

*Quantum Mechanics* de Cohen-Tannoudji, Diu e Laloë é considerado um dos tratados mais completos e pedagogicamente cuidadosos já escritos sobre mecânica quântica. Nascida de anos de ensino na École Normale Supérieure de Paris, a obra foi concebida com o objetivo explícito de facilitar o primeiro contato com a teoria e conduzir o leitor progressivamente até os níveis mais avançados do formalismo quântico.

A obra completa é composta por três volumes:

| Volume | Conteúdo principal | Nível |
|--------|-------------------|-------|
| **I** | Conceitos básicos, ferramentas matemáticas, postulados, oscilador harmônico, momento angular, átomo de hidrogênio | Graduação avançada |
| **II** | Espalhamento, spin, perturbação, sistemas de partículas idênticas | Pós-graduação |
| **III** | Segunda quantização, eletrodinâmica quântica, entrelaçamento e Bell | Pós-graduação avançada |

---

## Como Usar o Livro

O livro é organizado em dois tipos de texto com papéis distintos:

- **Capítulos:** apresentam os conceitos fundamentais e as ideias gerais. Correspondem ao conteúdo de um curso típico de graduação avançada (Vol. I) ou pós-graduação (Vols. II e III). Os 21 capítulos são completos em si mesmos e podem ser estudados independentemente dos complementos.

- **Complementos:** seguem o capítulo correspondente e são identificados por uma letra e subscrito — por exemplo, os complementos do Capítulo V são $A_V$, $B_V$, $C_V$, etc. Variam em dificuldade: alguns são exemplos simples, outros se aproximam do nível de pesquisa atual. O estudante deve escolher dois ou três por capítulo, conforme seus objetivos.

> Passagens em corpo menor de letra podem ser omitidas numa primeira leitura.

---

## Prefácio

A importância da mecânica quântica não parou de crescer nas últimas décadas. Ela é essencial para compreender a estrutura e dinâmica de objetos microscópicos como átomos e moléculas, e é a base de inúmeras tecnologias modernas: lasers, relógios atômicos (essenciais para o GPS), transistores, ressonância magnética, painéis solares e reatores nucleares. Fenômenos como superfluidez e supracondutividade também só se explicam dentro do formalismo quântico. Há ainda grande interesse nos estados entrelaçados, cujas propriedades de não-localidade e não-separabilidade permitem aplicações notáveis na área emergente de informação quântica.

A obra nasceu das experiências de ensino dos autores ao longo de muitos anos. Os dois primeiros volumes — publicados originalmente há mais de quarenta anos — foram utilizados no mundo inteiro. O terceiro volume foi adicionado para tratar temas mais avançados. A abordagem adotada é **progressiva e sem atalhos**: nenhuma dificuldade é ignorada, e cada aspecto é discutido em detalhe, frequentemente começando com uma revisão clássica.

---

## Capítulo I — Introdução às Ideias Básicas da Mecânica Quântica

> *"O objetivo essencial é despertar a curiosidade do leitor. Fenômenos serão descritos que perturbam ideias tão firmemente ancoradas em nossa intuição quanto o conceito de trajetória."*

---

### A. Ondas Eletromagnéticas e Fótons

#### A-1. Quanta de Luz e as Relações de Planck-Einstein

Newton considerava a luz como um feixe de partículas. Na primeira metade do século XIX, a natureza ondulatória da luz foi demonstrada por interferência e difração, integrando a óptica à teoria eletromagnética de Maxwell.

No entanto, o estudo da **radiação de corpo negro** levou **Planck (1900)** a propor a hipótese da quantização da energia: para uma onda eletromagnética de frequência $\nu$, as únicas energias possíveis são múltiplos inteiros de $h\nu$, onde $h$ é uma nova constante fundamental. Generalizando essa hipótese, **Einstein (1905)** propôs que a luz consiste num feixe de **fótons**, cada um possuindo energia $h\nu$. O fóton foi demonstrado como entidade distinta pelo **Efeito Compton (1924)**.

As relações fundamentais que ligam parâmetros de partícula (energia $E$ e momento $\mathbf{p}$) a parâmetros de onda (frequência angular $\omega$ e vetor de onda $\mathbf{k}$) são as **Relações de Planck-Einstein**:

$$E = \hbar\omega$$

$$\mathbf{p} = \hbar\mathbf{k}$$

onde $\hbar = h / 2\pi \approx 1{,}055 \times 10^{-34}\ \text{J·s}$ é a constante de Planck reduzida.

---

#### A-2. Dualidade Onda-Partícula

O experimento de dupla fenda de Young revela o paradoxo central da mecânica quântica. A intensidade observada na tela com as duas fendas abertas **não** é a soma das intensidades individuais:

$$I(x) \neq I_1(x) + I_2(x)$$

A teoria ondulatória explica naturalmente as franjas: o campo elétrico total é $\mathcal{E} = \mathcal{E}_1 + \mathcal{E}_2$, e a intensidade é proporcional a $|\mathcal{E}|^2$, o que gera um termo de interferência.

Quando a intensidade da fonte é reduzida ao ponto de os fótons atingirem a tela **um a um**, as franjas **não desaparecem** — cada fóton produz um impacto localizado, mas ao acumular muitos fótons o padrão de interferência emerge. Isso mostra que:

1. A interpretação puramente **corpuscular** falha: franjas não podem ser explicadas por interações entre fótons.
2. A interpretação puramente **ondulatória** falha: cada fóton produz um impacto puntual, não um padrão difuso.

A resolução é a **dualidade onda-partícula**:

- Os aspectos de partícula e de onda da luz são inseparáveis. A onda permite calcular a **probabilidade** de manifestação de uma partícula.
- As predições sobre o comportamento de um fóton só podem ser **probabilísticas**.
- A onda $\mathcal{E}(\mathbf{r}, t)$ caracteriza o **estado** dos fótons; $|\mathcal{E}(\mathbf{r}, t)|^2$ é interpretado como a **densidade de probabilidade** de encontrar o fóton no ponto $\mathbf{r}$ no instante $t$.

---

#### A-3. O Princípio de Decomposição Espectral

Um experimento de polarização da luz introduz os conceitos fundamentais sobre a medição de grandezas físicas. Um fóton com polarização arbitrária $\mathbf{e}$ passa por um analisador de eixo $\mathbf{e}_x$. Escrevendo:

$$\mathbf{e} = \mathbf{e}_x \cos\theta + \mathbf{e}_y \sin\theta$$

o fóton atravessa o analisador com probabilidade $\cos^2\theta$ e é absorvido com probabilidade $\sin^2\theta$. Isso constitui o **Princípio de Decomposição Espectral**:

- O resultado da medição é sempre **quantizado**: o fóton atravessa ou é absorvido — não há resultados intermediários.
- A cada *eigenresultado* corresponde um **eigenestado**; se o fóton está num eigenestado, o resultado é certo.
- Para um estado arbitrário, decompõe-se o estado em combinação linear dos eigenestados e a probabilidade de cada resultado é o **quadrado do módulo** do coeficiente correspondente.
- Após a medição, o estado do fóton **muda abruptamente** — a medição perturba o sistema de forma fundamental.

---

### B. Partículas Materiais e Ondas de Matéria

#### B-1. As Relações de De Broglie

Em **1923**, De Broglie lançou a hipótese: assim como os fótons têm aspectos de onda e de partícula, as **partículas materiais também possuem aspecto ondulatório**. Os experimentos de difração de elétrons de **Davisson e Germer (1927)** confirmaram espetacularmente essa hipótese.

A uma partícula material de energia $E$ e momento $\mathbf{p}$ associa-se uma onda com as mesmas relações de Planck-Einstein. O comprimento de onda associado é dado pela **Relação de De Broglie**:

$$\lambda = \frac{h}{p}$$

O valor extremamente pequeno de $h$ explica por que a natureza ondulatória da matéria é muito difícil de demonstrar em escala macroscópica.

---

#### B-2. Função de Onda e a Equação de Schrödinger

Em analogia com o caso dos fótons, a descrição quântica de uma partícula material é formulada pelos seguintes princípios:

1. O **estado quântico** de uma partícula é caracterizado por uma **função de onda** $\psi(\mathbf{r}, t)$, que contém toda a informação possível sobre a partícula.

2. $|\psi(\mathbf{r}, t)|^2$ é a **densidade de probabilidade de presença**: a probabilidade de encontrar a partícula num volume $d^3r$ em torno de $\mathbf{r}$ é

$$dP(\mathbf{r}, t) = |\psi(\mathbf{r}, t)|^2\, d^3r$$

3. O **Princípio de Decomposição Espectral** se aplica à medição de qualquer grandeza física: decompõe-se $\psi$ em autofunções $\varphi_n$ do operador correspondente,

$$\psi(\mathbf{r}, t_0) = \sum_n c_n\,\varphi_n(\mathbf{r})$$

e a probabilidade de obter o autovalor $a_n$ é $P_n = |c_n|^2$.

4. A função de onda evolui no tempo segundo a **Equação de Schrödinger**:

$$i\hbar\,\frac{\partial\psi}{\partial t} = \hat{H}\psi$$

onde o operador hamiltoniano é

$$\hat{H} = -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r})$$

Esta equação é **linear** — o que garante o princípio da superposição — e de primeira ordem no tempo, determinando $\psi$ unicamente a partir do estado inicial.

---

### C. Descrição Quântica de uma Partícula — Pacotes de Onda

#### C-1. Partícula Livre

Para uma partícula livre ($V = 0$), as soluções da equação de Schrödinger são **ondas planas**:

$$\psi(\mathbf{r}, t) = A\,e^{i(\mathbf{k}\cdot\mathbf{r} - \omega t)}$$

com relação de dispersão $\hbar\omega = \hbar^2 k^2 / 2m$. Uma onda plana possui momento bem definido $\mathbf{p} = \hbar\mathbf{k}$, mas a posição é completamente indeterminada pois $|\psi|^2 = |A|^2 = \text{constante}$ em todo o espaço. Para representar uma partícula localizada, utiliza-se um **pacote de ondas**:

$$\psi(\mathbf{r}, t) = \int g(\mathbf{k})\,e^{i(\mathbf{k}\cdot\mathbf{r} - \omega(\mathbf{k})t)}\,d^3k$$

onde $g(\mathbf{k})$ é uma distribuição espectral centrada em $\mathbf{k}_0$ com largura $\Delta k$.

---

#### C-2. As Relações de Incerteza de Heisenberg

A análise do pacote de ondas revela uma limitação fundamental e incontornável:

$$\Delta x \cdot \Delta p_x \geq \frac{\hbar}{2}$$

$$\Delta E \cdot \Delta t \geq \frac{\hbar}{2}$$

Estas relações **não** expressam imperfeições técnicas da medição — são consequências matemáticas da natureza ondulatória da matéria. Elas estabelecem um limite fundamental à precisão com que pares de grandezas conjugadas podem ser simultaneamente definidas.

**Consequências físicas imediatas:**

- O conceito clássico de **trajetória** de uma partícula não tem sentido em mecânica quântica.
- As condições iniciais não determinam completamente o movimento subsequente — apenas probabilidades podem ser previstas.
- O estado fundamental de um sistema tem energia *zero-point* não-nula: mesmo no estado de menor energia, $\Delta p \neq 0$ e portanto $\langle p^2 \rangle / 2m > 0$.

---

#### C-3. Evolução Temporal de um Pacote de Ondas Livre

Um pacote de ondas livre se propaga com a **velocidade de grupo**:

$$v_g = \left.\frac{d\omega}{dk}\right|_{k_0} = \frac{\hbar k_0}{m} = \frac{p_0}{m}$$

que coincide com a velocidade clássica da partícula. Ao mesmo tempo, o pacote se **alastra** no tempo — sua largura espacial cresce como:

$$\Delta x(t) = \Delta x(0)\sqrt{1 + \left(\frac{\hbar t}{2m\,[\Delta x(0)]^2}\right)^2}$$

Este alargamento é um fenômeno puramente quântico sem análogo clássico.

---

### D. Partícula em um Potencial Independente do Tempo

#### D-1. Estados Estacionários

Para um potencial $V(\mathbf{r})$ independente do tempo, a equação de Schrödinger admite soluções separáveis:

$$\psi(\mathbf{r}, t) = \varphi(\mathbf{r})\,e^{-iEt/\hbar}$$

onde $\varphi(\mathbf{r})$ satisfaz a **equação de Schrödinger independente do tempo**:

$$\hat{H}\,\varphi = E\,\varphi$$

Os estados que satisfazem esta equação são chamados **estados estacionários**: a densidade de probabilidade $|\psi|^2 = |\varphi(\mathbf{r})|^2$ é independente do tempo. A energia $E$ é quantizada — só pode assumir os autovalores do operador $\hat{H}$.

---

#### D-2. Efeitos Quânticos Típicos em Potenciais Simples

**Reflexão parcial:** uma partícula com energia $E > V_0$ que incide sobre uma barreira de potencial tem probabilidade não-nula de ser *refletida* — classicamente impossível. O coeficiente de reflexão é:

$$R = \left|\frac{k_1 - k_2}{k_1 + k_2}\right|^2, \qquad k_i = \frac{\sqrt{2m(E - V_i)}}{\hbar}$$

**Efeito Túnel:** uma partícula com energia $E < V_0$ tem probabilidade não-nula de *atravessar* a barreira. Para uma barreira retangular de largura $a$, o coeficiente de transmissão decresce exponencialmente:

$$T \approx e^{-2\kappa a}, \qquad \kappa = \frac{\sqrt{2m(V_0 - E)}}{\hbar}$$

Este efeito é a base do diodo de túnel, do microscópio de varredura por tunelamento (STM) e da fusão nuclear.

**Quantização de energia:** em um poço infinito de largura $L$, as energias permitidas são:

$$E_n = \frac{n^2\pi^2\hbar^2}{2mL^2}, \qquad n = 1, 2, 3, \ldots$$

---

## Estrutura do Volume I

### Capítulo I — Introdução às Ideias Básicas
Ondas e partículas, dualidade onda-partícula, relações de Planck-Einstein e De Broglie, função de onda, equação de Schrödinger, pacotes de ondas, relações de Heisenberg, efeitos quânticos em potenciais simples.

### Capítulo II — Ferramentas Matemáticas da Mecânica Quântica
Espaço de funções de onda, espaço de estados e notação de Dirac (bras e kets $\langle\phi|\psi\rangle$), representações, equações de autovalor, observáveis, representações de posição $|\mathbf{r}\rangle$ e momento $|\mathbf{p}\rangle$, produto tensorial de espaços de estados.

### Capítulo III — Os Postulados da Mecânica Quântica
Enunciado formal dos postulados, interpretação física, corrente de probabilidade

$$\mathbf{j} = \frac{\hbar}{2mi}\left(\psi^*\nabla\psi - \psi\nabla\psi^*\right)$$

teorema de Ehrenfest, princípio da superposição e previsões físicas.

### Capítulo IV — Spin 1/2 e Sistemas de Dois Níveis
Quantização do momento angular de spin, matrizes de Pauli $\sigma_x, \sigma_y, \sigma_z$, sistemas de dois níveis em geral, ressonância magnética.

### Capítulo V — O Oscilador Harmônico Unidimensional
Eigenvalores $E_n = \hbar\omega\!\left(n + \tfrac{1}{2}\right)$, operadores de criação e aniquilação $\hat{a}^\dagger$ e $\hat{a}$, estados coerentes, aplicações a fonons e fótons.

### Capítulo VI — Momento Angular em Mecânica Quântica
Relações de comutação $[L_x, L_y] = i\hbar L_z$, teoria geral com números quânticos $l$ e $m$, harmônicos esféricos $Y_l^m(\theta, \varphi)$, momento angular orbital.

### Capítulo VII — Partícula em Potencial Central: Átomo de Hidrogênio
Solução exata com níveis de energia

$$E_n = -\frac{m_e e^4}{2\hbar^2}\,\frac{1}{n^2} = -\frac{13{,}6\ \text{eV}}{n^2}$$

orbitais $\psi_{nlm}$, números quânticos $n$, $l$, $m$, degenerescência $n^2$.

---

## Contexto Histórico

No final do século XIX, a física estava estruturada em dois pilares consolidados: a **mecânica newtoniana** e o **eletromagnetismo de Maxwell**. O conjunto parecia satisfatório diante dos dados experimentais da época.

No início do século XX, dois grandes abalos intelectuais reformularam esses fundamentos:

1. **A revolução relativista (Einstein, 1905):** as leis clássicas falham para corpos em movimento a velocidades comparáveis à da luz $c$.
2. **A revolução quântica (Planck 1900, Einstein 1905, Bohr 1913, De Broglie 1923, Heisenberg 1925, Schrödinger 1926):** as leis clássicas falham na escala atômica e subatômica.

A física clássica não é *errada* — é uma aproximação válida para fenômenos cotidianos. Mas, do ponto de vista fundamental, a teoria quântica permanece indispensável: é a única teoria capaz de explicar a própria existência de um sólido e os valores de seus parâmetros macroscópicos (densidade, calor específico, elasticidade, etc.).

> **Nota dos autores:** *"Não tratamos das implicações filosóficas da mecânica quântica, nem das diversas interpretações dessa teoria. Limitamo-nos ao chamado 'ponto de vista ortodoxo'. Fizemos essa escolha porque sentimos que tais questões podem ser abordadas com mais eficiência depois de se dominar o formalismo quântico e suas inúmeras aplicações."*

---

## Pré-Requisitos e Roteiro de Estudo

**Pré-requisitos recomendados:**
- Mecânica clássica lagrangiana e hamiltoniana
- Eletromagnetismo (equações de Maxwell, ondas eletromagnéticas)
- Álgebra linear (vetores, matrizes, autovalores)
- Análise matemática (equações diferenciais, séries de Fourier)

**Roteiro sugerido:**

1. **Cap. I** — Leitura integral (vocabulário quântico essencial)
2. **Cap. II** — Leitura cuidadosa (formalismo matemático — base de tudo)
3. **Cap. III** — Leitura integral (postulados — núcleo da teoria)
4. **Cap. IV** — Spin 1/2 (aplicação imediata dos postulados)
5. **Cap. V** — Oscilador harmônico (sistema modelo fundamental)
6. **Cap. VI** — Momento angular (essencial para o Cap. VII)
7. **Cap. VII** — Átomo de hidrogênio (culminação do volume)

Para os complementos: consultar o **Reader's Guide** ao final de cada capítulo, que discute a dificuldade e importância de cada um.

---

*Cohen-Tannoudji, C., Diu, B., Laloë, F. — Quantum Mechanics, Volume I, 2nd ed. — Wiley-VCH, 2020*
