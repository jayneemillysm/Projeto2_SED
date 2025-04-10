# Modelagem de um Sistema de Manufatura com Quatro Células

Este repositório é referente ao Projeto 02 da disciplina Sistemas a Eventos Discretos, no período 2024.2, pela Universidade Federal de Campina Grande (UFCG).

---

## Equipe
- Arthur de Queiroz Tavares Borges Mesquita (120110246)
- Ivan da Silva Filho (120110348)
- Jayne Emilly Silva de Melo (121210548)

---

## Descrição
O projeto consiste na modelagem e simulação de um sistema de manufatura composto por quatro células, utilizando Redes de Petri Coloridas através da ferramenta CPN Tools.

---

## Objetivos

O objetivo é modelar, analisar e validar o comportamento operacional de quatro células de manufatura, cada uma contendo:

1. Um depósito de entrada e um depósito de saída da célula;

2. Três máquinas sequenciais com depósitos próprios de entrada e saída (cada um com capacidade máxima de 4 itens);

3. Três robôs responsáveis pela movimentação dos itens entre os depósitos internos de cada célula.

Cada célula possui duas rotas possíveis de produção, garantindo flexibilidade operacional sem ocorrer bloqueios no sistema.

---

## Funcionalidades e Estrutura do Sistema

Cada célula contém:

Robô 1: Transporta itens do depósito de entrada da célula até o depósito de entrada da Máquina 1.

Robô 2: Transporta itens do depósito de saída da Máquina 1 para os depósitos de entrada das Máquinas 2 e 3.

Robô 3: Transporta itens dos depósitos de saída das Máquinas 2 e 3 até o depósito de saída da célula.

O modelo garante o controle adequado das filas, respeitando a capacidade máxima de cada depósito (4 itens), e evita a ocorrência de deadlocks.

---

## Modelagem

Redes de Petri Coloridas para representação detalhada do fluxo dos processos produtivos, implementadas na ferramenta CPN Tools.

---

## Diagrama do Modelo

Abaixo está o modelo das células 1, 2, 3 e 4 representadas no CPN Tools:

<p align="center">
  <img src="Célula1.png" width="400"/>
  <img src="Célula2.png" width="388"/>
</p>


