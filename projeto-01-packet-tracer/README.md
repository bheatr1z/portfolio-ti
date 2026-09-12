# Projeto 01 — Comunicação entre 3 Redes Distintas

## Objetivo

Construir e configurar uma topologia de rede utilizando o Cisco Packet Tracer, permitindo a comunicação entre três redes IPv4 distintas.

## Ferramenta utilizada

- Cisco Packet Tracer

## Topologia

O projeto foi desenvolvido em grupo e utilizou:

- 1 roteador Cisco 2911
- 3 switches Cisco 2960
- 6 computadores
- Conexões Ethernet

## Redes utilizadas

### Rede A
- Rede: 10.0.0.0/8
- Gateway: 10.0.0.1

### Rede B
- Rede: 172.16.0.0/16
- Gateway: 172.16.0.1

### Rede C
- Rede: 192.168.1.0/24
- Gateway: 192.168.1.1

## Configuração dos computadores

| Computador | Endereço IP | Máscara | Gateway |
|---|---|---|---|
| PC A1 | 10.0.0.2 | 255.0.0.0 | 10.0.0.1 |
| PC A2 | 10.0.0.3 | 255.0.0.0 | 10.0.0.1 |
| PC B1 | 172.16.0.2 | 255.255.0.0 | 172.16.0.1 |
| PC B2 | 172.16.0.3 | 255.255.0.0 | 172.16.0.1 |
| PC C1 | 192.168.1.2 | 255.255.255.0 | 192.168.1.1 |
| PC C2 | 192.168.1.3 | 255.255.255.0 | 192.168.1.1 |

## Configuração do roteador

Foram configuradas três interfaces do roteador:

- GigabitEthernet0/0 → 10.0.0.1
- GigabitEthernet0/1 → 172.16.0.1
- GigabitEthernet0/2 → 192.168.1.1

## Testes

Após a configuração dos dispositivos, foram realizados testes de conectividade entre as redes para verificar a comunicação através do roteador.

## Resultado

A topologia foi configurada no Cisco Packet Tracer e os testes foram utilizados para verificar a comunicação entre as três redes distintas.

## O que aprendi

Com este projeto, pratiquei conceitos fundamentais de redes, incluindo:

- Endereçamento IPv4
- Máscaras de sub-rede
- Gateway padrão
- Comunicação entre redes distintas
- Configuração básica de roteadores
- Configuração e utilização de switches
- Testes de conectividade
- Utilização do Cisco Packet Tracer

## Participação

Projeto desenvolvido em grupo durante a formação em Redes e Cibersegurança.
