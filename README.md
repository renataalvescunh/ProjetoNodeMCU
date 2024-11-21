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

Este projeto utiliza os seguintes componentes: 

| Quantidade | Componente | 
|------------|------------|
|     1      | NodeMCU ESP8266 | 
| 1 | Sensor de Luz (LDR) | 
| 1 | Fonte de energia | 
| x | Resistores | 
| x | LEDs | 
| x | Transistores |
| 1 | Protoboard | 
| x | Jumpers |


## Descrição dos Componentes - 

- **NodeMCU ESP8266**: Placa de desenvolvimento baseada no chip ESP8266, ideal para projetos de IoT devido ao seu WiFi embutido. 
- **Sensor de Luz (LDR)**: Utilizado para detectar a luminosidade ambiente e acionar as luzes dos postes. 
- **Fonte de energia**: Necessária para alimentar o NodeMCU e os outros componentes do circuito. 
- **Resistores**: Utilizados para limitar a corrente em diversos pontos do circuito. 
- **LEDs**: Utilizados como indicadores visuais no projeto. 
- **Transistores**: Utilizados para amplificar ou comutar sinais eletrônicos. 
- **Protoboard**: Placa de ensaio utilizada para montar circuitos eletrônicos sem a necessidade de solda. 



- **Jumpers**: Fios utilizados para realizar as conexões no protoboard.


## 📁 Documentação das Interfaces e Protocolos

- **Interface Web:** Interface para controle manual e monitoramento
- **Protocolos de Comunicação:** 
  - **TCP/IP:** Utilizado para conexão com a rede local e controle remoto
  - **MQTT:** Utilizado para comunicação entre o NodeMCU e o servidor central
 
## 💡 Protocolo MQTT


## 📌 Como Reproduzir 

1. Clone este repositório com o seguinte comando:

    ```
   git clone https://github.com/seu-usuario/ProjetoNodeMCU.git
2. **Instale as dependências:** Bibliotecas do Arduino IDE: O projeto utiliza o NodeMCU ESP8266, então você precisará instalar as bibliotecas específicas para esse dispositivo no Arduino IDE. Após feito isso, vá em **Ferramentas > Placa > Gerenciador de Placas.** Busque por esp8266 e instale a última versão.
3. **Acesse o código-fonte:** Dentro deste repositório, o código fonte está localizado na pasta `src`.
4. **Código do NodeMCU:**
- Abra o código no Arduino IDE;
- Navegue até o arquivo `.ino` do projeto;
- Conecte o NodeMCU ao seu computador via cabo USB;
- Selecione a placa NodeMCU 1.0 (ESP-12E Module) em Ferramentas > Placa;
- Clique em **carregar** para enviar o código para o NodeMCU.

4. **Configuração do Broker MQTT:**
  
5. **Plataforma de Controle:**





