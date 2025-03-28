

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

📌 Medição na Saída do Transformador

![image](https://github.com/user-attachments/assets/1dfd02e0-064f-4cff-89c3-a515198d7736)



A leitura de 11V AC confirma que o transformador está reduzindo a tensão conforme esperado.

📌 Retificação e Filtragem da Tensão


![image](https://github.com/user-attachments/assets/7b872252-9fa3-4d23-9099-69b0e8c5cbd2)



Após a retificação e filtragem, a tensão fica pronta para ser estabilizada pelo regulador 7805.

O circuito entrega uma saída de 5V DC, ideal para alimentar circuitos eletrônicos.

✅ Conclusão

Este conversor AC-DC com regulador 7805 é uma solução eficiente para obter uma saída estável de 5V DC a partir da rede elétrica. Sua aplicação pode ser utilizada em projetos de eletrônica, microcontroladores e fontes de alimentação para circuitos diversos.

🚀 Projeto testado e funcionando!
