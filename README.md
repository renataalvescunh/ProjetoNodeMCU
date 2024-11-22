  <h1 align="center" id="project_name">
  <img src="https://github.com/user-attachments/assets/b2d46483-62ba-4f6b-a25e-000a550c525e" alt="Logo" width="204px">
  <br>
  ⚙💡 Sistema de Monitoramento de Iluminação Pública  
  <br> </h1>
Este projeto propõe um sistema inteligente de monitoramento de iluminação pública utilizando o microcontrolador NodeMCU ESP8266 e o protocolo MQTT. O sistema realiza a detecção do status de luminosidade por meio de um sensor LDR, enviando as informações para uma plataforma de monitoramento em tempo real. 

## 🖱 Funcionalidade

- Verifica e monitora o nível de iluminação no ambiente em tempo real.
  

## 🖥 Software desenvolvido 
O código-fonte está disponível na pasta `src`. Consulte `README.md` para documentação detalhada.

## 🔌 Hardware Utilizado

Este projeto utiliza os seguintes componentes:

| Quantidade | Componente         | Descrição                                    |
|-------------|--------------------|----------------------------------------------|
| 1           | **NodeMCU ESP8266** | Microcontrolador Wi-Fi para controle remoto  |
| 1           | **Sensor LDR**      | Sensor de luz para detectar a luminosidade   |
| 1           | **Fonte de Energia**| Fonte para alimentar o NodeMCU e outros componentes |
| X           | **Resistores**      | Para controlar a corrente elétrica no circuito|
| X           | **Transistores**    | Para amplificar sinais no circuito           |
| 1           | **Protoboard**      | Placa de ensaio para montagem do circuito    |
| X           | **Jumpers**         | Fios para conexões no protoboard             |


## 📁 Documentação das Interfaces e Protocolos

O protocolo MQTT é utilizado para a comunicação entre o NodeMCU e a plataforma de monitoramento. O NodeMCU publica o status do sensor de luz em tópicos específicos no broker MQTT. A plataforma de monitoramento assina esses tópicos e recebe as atualizações em tempo real, permitindo o controle e a automação da iluminação pública. Para uma visualização mais clara, observe a imagem abaixo. 
![git](https://github.com/user-attachments/assets/de293ae1-0022-4b80-975a-39c907cad013)

### 🌐 Interface Web
Uma interface intuitiva que permite controle manual e monitoramento em tempo real da iluminação pública.

### 📡 Protocolos de Comunicação
- **TCP/IP:** Usado para comunicação local entre os dispositivos, permitindo a integração com a rede local e controle remoto.
- **MQTT:** Protocolo de comunicação leve e eficiente utilizado para enviar e receber dados sobre o status das lâmpadas via broker centralizado. Permite o controle remoto das lâmpadas de maneira eficaz.


## 📌 Como Reproduzir 

1. Clone este repositório:

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

5. **Configuração do Broker MQTT:** 
6. **Plataforma de Controle:** Acesse a interface de controle para monitorar em tempo real.


