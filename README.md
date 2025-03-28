

📜 Esquemático

![image](https://github.com/user-attachments/assets/611c4006-0028-473c-ac47-334ff36793c2)


Este circuito converte uma tensão de corrente alternada (AC) em uma saída regulada de 5V em corrente contínua (DC), utilizando um transformador, uma ponte retificadora e um regulador 7805.

🛠 Componentes e Funcionamento

1️⃣ Entrada AC e Transformador (TR1)

A alimentação inicial vem da rede elétrica (AC).

O transformador (TR1) reduz a tensão para um nível adequado para o retificador.

2️⃣ Ponte Retificadora (BR1)

A ponte de diodos (BR1) converte a tensão AC em uma tensão DC pulsante.

3️⃣ Capacitor de Filtro (C1)

O capacitor C1 (1µF) suaviza a tensão DC, reduzindo ondulações.

4️⃣ Regulador de Tensão (U1 - 7805)

O regulador 7805 estabiliza a tensão de saída em 5V.

Pinos do 7805:

VI: Entrada de tensão (vinda do capacitor C1).

GND: Terra.

VO: Saída regulada de 5V DC.

5️⃣ Capacitores de Estabilização (C2 e C3)

C2 (22nF) e C3 (22nF) eliminam ruídos e garantem maior estabilidade da tensão.

6️⃣ Carga: LED Indicador

R1 (220Ω) limita a corrente do LED D1, que indica o funcionamento correto do circuito.

🔬 Testes Práticos

![image](https://github.com/user-attachments/assets/b1164b0c-e1d9-438a-9fc1-7a5ad1baa560)


📌 Medição na Saída do Transformador

![image](https://github.com/user-attachments/assets/1dfd02e0-064f-4cff-89c3-a515198d7736)



A leitura de 11V AC confirma que o transformador está reduzindo a tensão conforme esperado.

📌 Retificação e Filtragem da Tensão


![image](https://github.com/user-attachments/assets/b0753b24-face-4dd0-a76b-d93b88ee0dc7)

PCB

![image](https://github.com/user-attachments/assets/e1078dfa-c6a1-4558-b0c1-07442ae583c6)

Visão Geral

Esta PCB foi projetada com um formato compacto de 50 mm x 30 mm, apresentando diversos componentes eletrônicos interligados por trilhas condutoras. O layout prioriza eficiência e organização, garantindo um bom desempenho elétrico e facilidade de montagem.

Especificações Técnicas

Conectores e Terminais

J1 e J2: Conectores de entrada e saída, possivelmente para alimentação ou sinal.

BR1: Ponte retificadora de quatro terminais, responsável pela conversão de corrente alternada (CA) em corrente contínua (CC).

Componentes Passivos

R1: Resistor, possivelmente utilizado para limitar corrente.

C1, C2, C3: Capacitores, sendo C1 um capacitor eletrolítico, indicado pela serigrafia com polaridade marcada. C2 e C3 podem ser cerâmicos ou de filme.

Componentes Ativos

U1: Componente de três terminais, possivelmente um regulador de tensão (ex: LM7805) ou um circuito integrado similar.

D1: Diodo, que pode ser um LED indicador ou um diodo de proteção.



