# 🌐 Lab 01 — Fundamentos de Redes e Modelo TCP/IP

## 📌 Objetivo

Este laboratório tem como objetivo compreender os fundamentos da comunicação em redes de computadores, apresentando os principais conceitos utilizados para que dispositivos possam trocar informações dentro de uma rede.

Durante este laboratório serão abordados conceitos essenciais de Redes e Segurança da Informação, criando uma base para análise de comunicação, diagnóstico de problemas e entendimento de protocolos.

---

# 🖥️ Ambiente

Sistema operacional:

Ubuntu Linux

Ambiente:

Máquina Virtual

Ferramentas utilizadas:

- Terminal Linux
- Comandos TCP/IP
- Ferramentas de diagnóstico de rede

---

# 🌐 1. Conceito de Redes de Computadores

Uma rede de computadores é formada por dispositivos conectados que permitem a troca de informações e compartilhamento de recursos.

Os dispositivos podem se comunicar através de:

- computadores;
- servidores;
- roteadores;
- switches;
- dispositivos móveis;
- equipamentos IoT.

A comunicação ocorre através de protocolos, que definem regras para envio e recebimento de informações.

---

# 🔗 2. Modelo TCP/IP

O modelo TCP/IP é utilizado como base para comunicação na Internet e em redes corporativas.

Ele é dividido em quatro camadas:

## Aplicação

Responsável pela interação com os usuários e serviços de rede.

Exemplos:

- HTTP/HTTPS;
- DNS;
- FTP;
- SSH.

---

## Transporte

Responsável pela comunicação entre aplicações.

Principais protocolos:

### TCP

Características:

- orientado à conexão;
- garante entrega dos dados;
- realiza controle de transmissão.

Exemplos:

- HTTP;
- HTTPS;
- SSH.

### UDP

Características:

- comunicação mais rápida;
- não garante entrega;
- utilizado quando velocidade é prioridade.

Exemplos:

- DNS;
- streaming;
- jogos online.

---

## Internet

Responsável pelo endereçamento e roteamento dos pacotes.

Protocolos:

- IP;
- ICMP.

Nesta camada ocorre a identificação dos dispositivos através dos endereços IP.

---

## Acesso à Rede

Responsável pela comunicação física e enlace.

Exemplos:

- Ethernet;
- Wi-Fi;
- endereço MAC.

---

# 📦 3. Encapsulamento de Dados

Durante uma comunicação, os dados passam por diferentes camadas.

Cada camada adiciona informações necessárias para o transporte.

Processo:

Aplicação:

Dados

↓

Transporte:

Segmentos

↓

Internet:

Pacotes

↓

Acesso à Rede:

Quadros

Esse processo permite que diferentes dispositivos consigam interpretar e encaminhar as informações corretamente.

---

# 🔢 4. Endereçamento e Comunicação

Cada dispositivo conectado a uma rede precisa possuir uma identificação.

Principais identificadores:

## Endereço IP

Identifica um dispositivo dentro de uma rede.

Exemplo:

192.168.1.10

## Endereço MAC

Identifica a interface física de rede.

Exemplo:

00:0c:29:xx:xx:xx

---

# 🚪 5. Portas e Serviços

As portas permitem identificar diferentes serviços executados em um dispositivo.

Exemplos:

| Serviço | Porta |
|---|---|
| HTTP | 80 |
| HTTPS | 443 |
| SSH | 22 |
| DNS | 53 |

Um servidor pode executar vários serviços utilizando portas diferentes simultaneamente.

---

# 🛠️ 6. Ferramentas de Diagnóstico

Durante os próximos laboratórios serão utilizadas ferramentas para análise de rede.

Principais comandos:

## ip

Exibe informações das interfaces de rede.

Exemplo:

ip addr


## ping

Testa comunicação entre dispositivos utilizando ICMP.

Exemplo:

ping 8.8.8.8


## ss

Analisa conexões e portas abertas.

Exemplo:

ss -tuln


## traceroute

Analisa o caminho percorrido pelos pacotes.

Exemplo:

traceroute google.com

---

# 🔐 7. Relação com Segurança da Informação

O conhecimento de redes é fundamental para Segurança da Informação.

Através da análise de redes é possível:

- identificar serviços expostos;
- analisar comunicações;
- detectar comportamentos suspeitos;
- investigar incidentes;
- aplicar controles de segurança.

Profissionais de SOC e Blue Team precisam compreender como os sistemas se comunicam para identificar ameaças.

---

# 📸 Evidências

As imagens e resultados dos comandos realizados durante o laboratório serão armazenados na pasta:

imagens/

---

# 📚 Conhecimentos Praticados

- Fundamentos de redes;
- Modelo TCP/IP;
- Comunicação entre dispositivos;
- Protocolos de rede;
- Portas e serviços;
- Conceitos iniciais de segurança de redes.

---

# ✅ Laboratório concluído

Este laboratório iniciou a etapa de Redes dentro da trilha de Segurança da Informação.

Próximo laboratório:

🌐 Lab 02 — Endereçamento IP e Subnetting
