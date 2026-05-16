
# 02 - Fundamentos de FPGA

<p align="center">
  <img src="../../../images/open_fpga_robot_lab_banner.png">
</p>

# Introdução

Neste módulo aprenderemos os conceitos básicos do desenvolvimento FPGA.

Os tópicos incluem:
- lógica digital
- clocks
- registradores
- lógica combinacional
- lógica sequencial
- FSM
- processamento paralelo

---

# O que torna FPGA diferente?

Microcontroladores tradicionais executam instruções sequencialmente.

FPGAs executam lógica em paralelo.

Isso significa:
- múltiplas operações simultâneas
- temporização determinística
- processamento de alta velocidade
- hardware customizado

---

# Lógica Digital

Sistemas FPGA são construídos usando lógica digital.

Elementos básicos:
- AND
- OR
- XOR
- NOT

Esses blocos formam sistemas digitais maiores.

---

# Clocks

O clock sincroniza a lógica FPGA.

A placa DE0-Nano possui:
- clock onboard de 50 MHz

Utilizado para:
- contadores
- temporizadores
- FSM
- interfaces de comunicação

---

# Registradores

Registradores armazenam valores digitais.

Exemplos:
- contadores
- máquinas de estado
- dados temporários

Registradores mudam nas bordas do clock.

---

# Lógica Combinacional

A saída depende apenas das entradas atuais.

Exemplo:
- portas lógicas
- operações aritméticas

---

# Lógica Sequencial

A saída depende:
- das entradas atuais
- dos estados anteriores

Exemplos:
- contadores
- FSM
- memórias

---

# Máquinas de Estado (FSM)

FSMs são fundamentais em projetos FPGA.

Usadas para:
- controle robótico
- protocolos de comunicação
- automação
- sistemas embarcados

---

# Processamento Paralelo

Uma das maiores vantagens FPGA.

Exemplo:
- UART funcionando
- PWM funcionando
- sensores funcionando

Tudo simultaneamente.

---

# Exemplo Verilog

Exemplo simples de LED:

```verilog
module blink (
    input clk,
    output reg led
);

always @(posedge clk)
begin
    led <= ~led;
end

endmodule
```

---

# Objetivos Educacionais

Após este módulo você deverá compreender:
- fundamentos FPGA
- comportamento de clock
- lógica digital
- execução paralela
- estrutura básica Verilog

---

# Próximo Módulo

Continuar para:

## 03_quartus_installation
