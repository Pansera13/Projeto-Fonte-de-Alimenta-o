<div align="center">
  <h1>⚡ Projeto: Fonte de Alimentação ⚡</h1>
  <p><strong>Fonte Linear Regulada 12V - Projeto Open Hardware</strong></p>
  <p>
    <img src="https://img.shields.io/badge/status-finalizado-brightgreen?style=flat-square">
    <img src="https://img.shields.io/badge/Proteus-8%20Professional-blue?style=flat-square">
  </p>
  <p>
    <sub>🛠️ Desenvolvido por Lucas Pansera • 2026 • Proteus 8 Pro</sub>
  </p>
</div>

---

## 💡 Sobre o Projeto

Este repositório documenta o desenvolvimento de uma **fonte de alimentação linear regulada de 12V DC** projetada para aplicações que exigem estabilidade e baixo ruído. Diferente de fontes chaveadas, esta topologia linear oferece uma resposta mais limpa, ideal para circuitos analógicos sensíveis, sensores e microcontroladores.

> 🎯 **Objetivo:** Criar uma fonte confiável, de baixo custo e fácil reprodução para makers e hobistas.

---

## 🧠 Arquitetura do Circuito

O projeto segue a topologia clássica de fontes lineares, dividida em 5 estágios:


### 🔄 Fluxo Detalhado

1. **🌐 Estágio 1 - Entrada**  
   O conector **J3** recebe a tensão alternada reduzida por um transformador (recomendado: 15V a 24V AC).

2. **⚡ Estágio 2 - Retificação**  
   A ponte de diodos **BR3** converte a tensão AC em DC pulsante (retificação em onda completa).

3. **💧 Estágio 3 - Filtro Capacitivo**  
   O capacitor **C6 (1000µF)** atua como reservatório de energia, reduzindo a ondulação (ripple).

4. **🎯 Estágio 4 - Regulação**  
   O CI **U2 (7812)** mantém a saída fixa em 12V, independente de variações na entrada ou carga.

5. **🧹 Estágio 5 - Pós-Filtragem**  
   Capacitores **C4 e C5 (100nF)** eliminam ruídos de alta frequência.  
   O LED **D2** com resistor **R2 (100kΩ)** sinaliza o funcionamento.

6. **🔌 Estágio 6 - Saída**  
   O conector **J4** disponibiliza os 12V estabilizados para a carga.

<img width="1101" height="362" alt="Captura de tela 2026-03-10 221609" src="https://github.com/user-attachments/assets/eeffd354-b954-43a8-b724-d6c2edc16974" />

---

## 🖨️ Layout da PCB

A placa foi desenvolvida no Proteus 8 Professional com as seguintes características:

| Característica | Especificação |
|----------------|---------------|
| **Camadas** | Single Layer (Bottom Copper) |
| **Acabamento** | Silk screen azul |
| **Identificação** | "Lucas Pansera" |

### 🔍 Visualização

<img width="435" height="656" alt="Captura de tela 2026-03-10 221659" src="https://github.com/user-attachments/assets/1581b818-27ae-42ec-887c-a5da65dcc1ed" />
<img width="472" height="816" alt="Captura de tela 2026-03-10 221630" src="https://github.com/user-attachments/assets/711b0c88-098a-4452-9efd-25ab84294ce8" />
<img width="635" height="826" alt="Captura de tela 2026-03-10 221719" src="https://github.com/user-attachments/assets/94d5be0d-76cd-4f7f-9577-c354cdbc5e06" />

---
