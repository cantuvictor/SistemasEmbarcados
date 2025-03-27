Victor Hugo Cantu Ramires

# Esquemático

![image](https://github.com/user-attachments/assets/240c4c9a-daa2-4c80-80cd-259eea4ab55d)



1. Entrada AC e Transformador (TR1)
O circuito começa com uma fonte de corrente alternada (AC) conectada ao transformador (TR1).
O transformador reduz a tensão da rede elétrica para um valor adequado para o retificador.

2. Ponte Retificadora (BR1)
O componente BR1 é uma ponte de diodos que converte a tensão AC do transformador para DC pulsante.

3. Capacitor de Filtro (C1)
O capacitor C1 (1µF) atua como um filtro, suavizando a tensão DC pulsante para reduzir ondulações.

4. Regulador de Tensão (U1 - 7805)
O 7805 é um regulador linear de tensão que fornece uma saída de 5V DC estável.

   Pinos do 7805:

   VI): Entrada de tensão (proveniente do capacitor C1).
  
   (GND): Terra.
 
   (VO): Saída de 5V DC regulados.

5. Capacitores de Estabilização (C2 e C3)
C2 (22nF) e C3 (22nF) ajudam a estabilizar a tensão e eliminar ruídos.

7. Carga: LED e Resistor
R1 (220Ω) limita a corrente para o LED D1, que indica que a saída de 5V está funcionando corretamente.

# Prática

![image](https://github.com/user-attachments/assets/e43f1fe4-4e44-465c-abfb-5b5d334225dd)



