# [S03] Segundo Relatório de Feedback dos Projetos

- **Aluno Avaliador:** Caio Semblano Silva (`caiosemblano`)
- **Equipe do Avaliador (Excluída da Avaliação):** Gerenciador de Partidas ([S03-2026-2/gerenciador-de-partidas](https://github.com/S03-2026-2/gerenciador-de-partidas))
- **Organização Avaliada:** [S03-2026-2](https://github.com/S03-2026-2)
- **Disciplina:** Arquitetura e Desenho de Software (S03)
- **Data da Avaliação:** 29 de Outubro de 2026
- **Total de Equipes Avaliadas:** 10 (todas as aplicações do enunciado, exceto Gestão de Partidas)

---

## Metodologia e Critérios de Avaliação

Este relatório complementa o primeiro feedback de 01/10/2026 com uma nova inspeção dos repositórios públicos da organização `S03-2026-2`, feita em 29/10/2026. Foram analisados a branch `main` e as branches secundárias quando o trabalho principal ainda não estava na `main`. Cada ponto cita o arquivo, o diagrama ou a classe correspondente, para que a equipe possa localizar e aplicar a sugestão.

A organização é um **único sistema distribuído** de cartas Pokémon (SOA + Broker), não onze projetos isolados. Por isso, além da qualidade de cada repositório, o relatório cobra se a documentação e o código realmente permitem que as outras aplicações integrem.

Os feedbacks seguem os critérios de Arquitetura e Desenho de Software (S03):

1. **Documentação e modelagem:** clareza do `README.md`, casos de uso, diagrama de classes, sequência, atividades, componentes e aderência entre o desenho e o que está no repositório.
2. **Arquitetura e princípios de projeto:** recorte de responsabilidade (bounded context), SOLID, camadas, MVC/SPA, MOM (Broker) e contratos entre serviços.
3. **Integração no ecossistema:** identificadores, payloads, tópicos de evento, APIs publicadas e o que ainda impede o Gerenciador de Partidas (e as demais apps) de se conectar.

Cada seção traz pelo menos três pontos positivos e três pontos negativos com sugestão objetiva. No final há um bloco extra, transversal, sobre contratos e ids ainda divergentes.

---

## Sumário das Equipes Avaliadas

1. [Jogadores](#1-jogadores)
2. [Distribuição de Cartas](#2-distribuição-de-cartas)
3. [Trocas](#3-trocas)
4. [Visualização de Cartas](#4-visualização-de-cartas)
5. [Visualização de Trocas](#5-visualização-de-trocas)
6. [Painel de Administração](#6-painel-de-administração)
7. [Batalha](#7-batalha)
8. [Pokédex](#8-pokédex)
9. [Recomendação de Cartas](#9-recomendação-de-cartas)
10. [Broker](#10-broker)

---
