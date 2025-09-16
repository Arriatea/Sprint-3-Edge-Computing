<h1 align="center">⚽ Sistema IoT de Monitoramento de Gols</h1>
<h3 align="center">Projeto desenvolvido pela <strong>Nova Tech Global</strong></h3>

<p align="center">
  <img src="https://img.shields.io/badge/Node--RED-Automação-red?style=for-the-badge&logo=nodered&logoColor=white">
  <img src="https://img.shields.io/badge/Sensores-Gol-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Câmeras-Replay-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/MQTT-Comunicação-purple?style=for-the-badge">
</p>

---

## 📌 <span style="color:#4169E1">Objetivo do Projeto</span>

Trazer **profissionalismo e inovação** aos campeonatos do Passa a Bola, utilizando aplicações de **IoT em tempo real**, permitindo:

- Captura da **velocidade do chute** das jogadoras  
- **Detecção automática de gols** por sensores instalados no gol  
- Sistema de câmeras capaz de **clippar os últimos 15 segundos antes do gol**  
- Exibição instantânea do **replay do lance**, junto com:
  - Velocidade do chute ⚡  
  - Confirmação do gol ✅  
  - Nome da jogadora responsável 🏃‍♀️  

---

## ⚙️ <span>Tecnologia e Componentes</span>

| Componente            | Função                                                                 |
|------------------------|------------------------------------------------------------------------|
| 🟥 **Node-RED**            | Plataforma IoT para orquestração dos dispositivos e fluxos de dados |
| 📡 **Sensores no Gol**     | Detectam a passagem da bola e calculam a velocidade do chute        |
| 🎥 **Sistema de Câmeras**  | Registra e clippa automaticamente os 15s anteriores ao gol          |
| 🌐 **MQTT Broker**         | Protocolo de comunicação entre sensores e plataforma IoT            |
| 🖥 **Dashboard IoT**       | Exibe velocidade, replay e informações do gol em tempo real          |

---

##  <span>Como Funciona</span>

### Captura do Gol

1. **Sensores instalados no gol** detectam a entrada da bola e medem a velocidade.  
2. Os dados são enviados via **MQTT** para a plataforma **Node-RED**.  
3. A jogadora responsável pelo gol é identificada e registrada no sistema.  

### Replay Automático

- Ao confirmar o gol, o sistema de câmeras:  
  - Clippa os últimos **15 segundos de jogo**  
  - Gera o replay com informações sobre:  
    - Nome da jogadora  
    - Velocidade do chute  
    - Status da validação do gol  

---

## <span style="color:#2F4F4F">Interface IoT</span>

O **Dashboard do Node-RED** exibirá em tempo real:

1. **Velocidade do chute**  
2. **Nome da jogadora**  
3. **Status do gol** (Validado / Não validado)  
4. **Replay dos 15 segundos anteriores**  

⏱️ **Atualização instantânea a cada evento de gol.**

---

## 🚨 <span style="color:#FF6347">Alertas e Funcionalidades</span>

| Situação                    | Ação no Sistema                                               |
|-----------------------------|--------------------------------------------------------------|
| Gol confirmado              | ✅ Registro + Replay + Velocidade exibida no dashboard        |
| Gol não confirmado           | ❌ Notificação de erro no dashboard                          |
| Velocidade acima da média    | ⚡ Destaque especial no replay (chute mais forte)             |
| Jogadora identificada        | 🏃‍♀️ Nome exibido junto ao replay do lance                   |

---

## Simulação

<p align="center">
  <a href="https://" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" width="160">
  </a>
</p>

<p align="center"><strong>🎬 Demonstração do Sistema Passa a Bola IoT</strong></p>

## 🖼️ Imagem da Arquitetura

<p align="center">
  <img src="./imgs/ width="600">
</p>

---

## 👥 Integrantes do Grupo

| [<img loading="lazy" src="./imgs/Vitor.png" width=115><br><sub>Vitor Alcantara</sub>](https://github.com/VitorAlcantara-tech) | [<img loading="lazy" src="./imgs/Thiago.png" width=115><br><sub>Thiago Lima</sub>](https://github.com/thiagolima-tech) | [<img loading="lazy" src="./imgs/Matheus.png" width=115><br><sub>Matheus Vasques</sub>](https://github.com/maatvasques) | [<img loading="lazy" src="./imgs/Marco.png" width=115><br><sub>Marco Aurélio</sub>](https://github.com/Arriatea) | [<img loading="lazy" src="./imgs/Bernardo.png" width=115><br><sub>Bernardo Hanashiro</sub>](https://github.com/BernardoYuji) |
| :---: | :---: | :---: | :---: | :---: |
