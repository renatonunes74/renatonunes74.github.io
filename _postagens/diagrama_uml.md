---
title: diagramas UML
layout: post
---

# Diagramas Estruturais
## diagrama de classes
## diagrama de objetos
## diagrama de pacotes
### diagrama de modelos


# Diagramas Comportamentais
## caso de uso
## diagrama de fluxo de informação

## diagrama de atividade
- estado inicial
    ```plantuml!
    start
    ```
- estado final
    ```plantuml!
    stop
    ```
- atividade
    ```plantuml!
    : Atividade;
    ```
- flecha (fluxo)
- decisão
    ```plantuml!
    if (Condição)
    ```
- raias
    ```plantuml!
    |Raia 1|
    start
    |Raia 2|
    stop
    ```
- juncao (join)
    ```plantuml!
    fork
    fork again
    ```
- bifurcacao (fork)
    ```plantuml!
        fork
        endfork
    ```
- comentario
    ```plantuml!
    note left: Comentário
    ```
# diagrama de máquina de estado
## diagrama de estado Comportamental da máquina
### diagrama do protocolo de estado da máquina
# diagrama de interação
## diagrama de sequência
## diagrama de comunicação
## diagrama de tempo
## diagrama de visão de interação

# Links auxiliares
## PlantUML
- [Diagrama de atividade](https://plantuml.com/activity-diagram-beta)
