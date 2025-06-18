# Simulador e Código do Robô - OBR

Este repositório reúne dois componentes principais desenvolvidos para a **Olimpíada Brasileira de Robótica (OBR)**:

-  Um simulador de rounds, útil para testar estratégias e comportamentos fora da arena física.
-  A programação do robô, com foco em navegação autônoma e um sistema de **navegação 2.5D** integrado.

---

## 📁 Estrutura do Projeto

OBR-Simulador-e-Robo/
├── simulador/ # Simulador em Python + Pygame
│ └── main.py # Arquivo principal do simulador
│
├── robo/ # Código Pybricks para LEGO Spike Prime
│ ├── navegacao.py # Sistema de navegação 2.5D
│ ├── sensores.py # Leitura de sensores
│ ├── atuadores.py # Controle dos motores
│ └── main.py # Execução geral do robô
│
├── docs/ # Documentação extra
│ ├── estrategia.md # Estratégia utilizada na navegação
│ ├── mapa_exemplo.png

## Sistema de Navegação 2.5D

O código do robô implementa uma navegação baseada em **mapa de grade com múltiplos níveis**, simulando rampas e terrenos instáveis em 2 dimensôes

Principais funcionalidades:

- Mapeamento local baseado em sensores
- Planejamento de rota com A*
- Atualização contínua com feedback dos sensores
- Retorno automático ao PID Conclusão do resgate

---

## Simulador da Arena

O simulador é uma ferramenta visual para testes rápidos com diferentes layouts de arena, obstáculos e lógicas de movimento.

### Requisitos:

Projeto por:
William Marinho, Elias Mateus, Maria Clara e Anthony

