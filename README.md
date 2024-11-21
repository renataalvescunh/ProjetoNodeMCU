  <h1 align="center" id="project_name">
  <img src="https://github.com/user-attachments/assets/b2d46483-62ba-4f6b-a25e-000a550c525e" alt="Logo" width="204px">
  <br>
  ⚙ Sistema de Monitoramento de Iluminação Pública  
  <br> </h1>
Este projeto visa desenvolver um sistema simples de monitoramento de iluminação pública utilizando o microcontorlador NodeMCU e o protocolo MQTT. O sistema detecta o estado de postes de iluminação através de um sensor de luz LDR, que envia os dados para um microcontrolador. Com o uso de um protocolo MQTT, as informações sobre o status das lâmpadas são transmitidas para uma plataforma de monitoramento, que alerta em casos de falha ou uso indevido. 

## 🖱 Funcionalidades
- Ligamento automático das luzes ao anoitecer e desligamento ao amanhecer.
- Monitoramento em tempo real do status das luzes.

## 🖥 Software desenvolvido 
O código-fonte está disponível na pasta `src`. Consulte `docs.md` para documentação detalhada.

## 🔌 Hardware Utilizado

- **Plataforma de Desenvolvimento:** NodeMCU ESP8266
- **Sensores:** Fotocélula para detecção de luz ambiente
- **Atuadores:** Relés para controle das luzes
- **Impressão 3D:** Suportes para sensores e caixas de proteção
- 
## 📁 Documentação das Interfaces e Protocolos

- **Interface Web:** Interface para controle manual e monitoramento
- **Protocolos de Comunicação:** 
  - **TCP/IP:** Utilizado para conexão com a rede local e controle remoto
  - **MQTT:** Utilizado para comunicação entre o NodeMCU e o servidor central

## 📌 Protocolo MQTT

