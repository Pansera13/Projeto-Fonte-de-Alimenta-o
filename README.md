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
   O conector **J3** recebe a tensão alternada 

2. **⚡ Estágio 2 - Retificação**  
   A ponte de diodos **BR3** converte a tensão AC em DC pulsante tudo em um so caminho

3. **💧 Estágio 3 - Filtro Capacitivo**  
   O capacitor **C6 (1000µF)** atua como reservatório de energia, reduzindo a ondulação (ripple).

4. **🎯 Estágio 4 - Regulação**  
   O CI **U2 (7812)** mantém a saída fixa em 12V, independente de variações na entrada ou carga.

5. **🧹 Estágio 5 - Pós-Filtragem**  
   Capacitores **C4 e C5 (100nF)** eliminam ruídos de alta frequência.  
   O LED **D2** com resistor **R2 (100kΩ)** sinaliza o funcionamento.

6. **🔌 Estágio 6 - Saída**  
   O conector **J4** disponibiliza os 12V estabilizados para a carga.

<img width="1269" height="351" alt="{987CBFFB-6605-4294-90A8-7F3BEDD00BDE}" src="https://github.com/user-attachments/assets/d04ea31a-5b44-41e6-be0d-906ee6f2b918" />


---

## 🖨️ Layout da PCB

A placa foi desenvolvida no Proteus 8 Professional com as seguintes características:

| Característica | Especificação |
|----------------|---------------|
| **Camadas** | Single Layer (Bottom Copper) |
| **Acabamento** | Silk screen azul |
| **Identificação** | "Lucas Pansera" |

### 🔍 Visualização

<img width="332" height="610" alt="{EDD42FCF-E53A-476E-BC6B-D146FE6D55EE}" src="https://github.com/user-attachments/assets/0de9a146-3961-4890-b5b2-354f514387f2" />

<img width="389" height="696" alt="{6E2EBF4D-AD68-4B21-8859-04A1FE691F32}" src="https://github.com/user-attachments/assets/60a527ac-eaa8-46a4-9a09-e3b5fbfdc77c" />

<img width="445" height="743" alt="{888BB21A-CBE3-461E-BCEA-5A06B19CD570}" src="https://github.com/user-attachments/assets/781f9d48-fd46-4959-8913-097ac082e2f1" />

---
