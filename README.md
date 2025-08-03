# PAA_mestrado
Otimização de Sequências Coreográficas com Programação Dinâmica

## Projeto
Este repositório contém o código desenvolvido para a otimização de sequências coreográficas utilizando programação dinâmica. O objetivo é encontrar a melhor sequência de movimentos, respeitando restrições de pré-requisitos, limites de tempo e repetição, para maximizar a fluidez e minimizar o custo total da coreografia.

**[Base de dados](https://github.com/ludbruna/PAA_mestrado/blob/89810406974b63dd0da7d13a977d407f51ed499e/movimentos_ballet.csv)** : Dados dos movimentos, pré-requisitos e parâmetros (Arquivo CSV)
**[Parametros](https://github.com/ludbruna/PAA_mestrado/blob/2e02733fba4cf4f8d29ef78d716cc064a51d6a53/Parametros.pdf)** : Documento com as configurações experimentais
**[Codigo principal](https://github.com/ludbruna/PAA_mestrado/blob/2e02733fba4cf4f8d29ef78d716cc064a51d6a53/paa_trabalho.py)** : Implementação do algoritmo de programação dinâmica
**[Codigo resultados](https://github.com/ludbruna/PAA_mestrado/blob/2e02733fba4cf4f8d29ef78d716cc064a51d6a53/resultados.py)** : Análise e visualização dos resultados gerados
**[Imagens](https://github.com/ludbruna/PAA_mestrado/tree/2e02733fba4cf4f8d29ef78d716cc064a51d6a53/Imagens)** : Gráficos, visualizações de grafo e outputs dos testes
**[Resultados](https://github.com/ludbruna/PAA_mestrado/tree/2e02733fba4cf4f8d29ef78d716cc064a51d6a53/Resultados)** : Arquivos com os resultados dos experimentos

## Sobre o Código
O código implementa uma solução baseada em programação dinâmica para explorar eficientemente o espaço de busca das sequências possíveis, respeitando:
1. Pré-requisitos de movimentos
2. Limites máximos de repetição de certos movimentos
3. Tempo máximo total da coreografia
