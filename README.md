# Projeto Arduino: Vida Marinha - FECAP

## Descrição

Este projeto foi desenvolvido pelo Gustavo Leonardi estudante da Fundação de Comércio Álvares Penteado (FECAP) com o objetivo de contribuir para a meta 14 da ONU, que visa conservar e utilizar de forma sustentável os oceanos, mares e recursos marinhos para o desenvolvimento sustentável. Nosso foco é monitorar a qualidade da água marinha utilizando um sistema baseado em Arduino.

## Objetivo

O objetivo principal deste projeto é criar um dispositivo que possa monitorar parâmetros importantes da água marinha, como temperatura e turbidez, fornecendo dados que possam ser usados para avaliar a saúde dos ecossistemas marinhos.

## Materiais Utilizados

- **ESP32**: Um microcontrolador com capacidade de conexão Wi-Fi, utilizado para enviar dados coletados para uma plataforma online.
- **Protoboard**: Uma placa de ensaio utilizada para montar e testar circuitos eletrônicos de forma temporária.
- **DS18B20**: Um sensor de temperatura digital, utilizado para medir a temperatura da água.
- **Sensor de Turbidez**: Utilizado para medir a turbidez da água, que é um indicador de partículas em suspensão.

## Instalação e Configuração

1. **Clonar o repositório**:
    ```bash
    git clone https://github.com/usuario/repositorio.git
    ```
2. **Montar o circuito**:
   - Conectar o ESP8266 à protoboard.
   - Ligar o sensor DS18B20 ao ESP8266 conforme o esquema fornecido no diretório `schematics`.
   - Conectar o sensor de turbidez ao ESP8266 conforme o mesmo esquema.
3. **Carregar o código para o ESP8266**:
   - Abra o Arduino IDE.
   - Carregue o arquivo `.ino` do projeto.
   - Configure as bibliotecas necessárias (OneWire, DallasTemperature, etc.).
   - Carregue o código para o ESP8266.
4. **Configurar a conexão Wi-Fi**:
   - No código, insira as credenciais de sua rede Wi-Fi.
   - Defina o servidor ou a plataforma onde os dados serão enviados (por exemplo, ThingSpeak).

## Como Usar

1. **Ligar o dispositivo**:
   - Conecte o ESP8266 a uma fonte de energia (bateria ou USB).
2. **Monitorar os dados**:
   - Acesse a plataforma online configurada para visualizar os dados de temperatura e turbidez da água em tempo real.

## Contribuições

Sinta-se à vontade para contribuir com este projeto enviando pull requests ou abrindo issues com sugestões e melhorias.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

---

Desenvolvido com dedicação peloestudante Gustavo Prando da FECAP para um futuro marinho mais sustentável. 🌊

---

Para mais detalhes sobre a meta 14 da ONU, consulte [Objetivos de Desenvolvimento Sustentável da ONU](https://www.un.org/sustainabledevelopment/oceans/).
