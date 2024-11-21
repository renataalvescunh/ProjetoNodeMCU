# Projeto Sistema de Monitoramento de Iluminação Pública 

Este projeto visa desenvolver um sistema simples de monitoramento de iluminação pública utilizando o microcontorlador NodeMCU  e o protocolo MQTT. O sistema detecta o estado de postes de iluminação através de um sensor de luz LDR, que envia os dados para um microcontrolador. Com o uso de um protocolo MQTT, as informações sobre o status das lâmpadas são transmitidas para uma plataforma de monitoramento, que alerta em casos de falha ou uso indevido. 

## Funcionalidades
- Ligamento automático das luzes ao anoitecer e desligamento ao amanhecer.
- Controle manual via interface web.
- Monitoramento em tempo real do status das luzes.
