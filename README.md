# Redes Neurais Artificiais: Perceptron

## Descrição
Este projeto implementa um Perceptron simples para classificar dados em duas classes. O modelo é treinado usando dados de um arquivo CSV e validado com outro conjunto de dados.

### Projeto prático
- Pela análise de um processo de destilação fracionada de petróleo observou-se que determinado óleo poderia ser classificado em duas classes de pureza $P_1 \text{ e } P_2$ a partir da medição de três grandezas $x_1, x_2 \text{ e } x_3$, que representam algumas de suas propriedades físico-químicas. A equipe de engenheiros e cientistas pretende usar uma rede Perceptron para executar a classificação automática das duas classes.

## Referência
- SILVA, Ivan Nunes da; SPATTI, Danilo Hernane; FLAUZINO, Rogério Andrade. **Redes neurais artificiais:** para engenharia e ciências aplicadas. São Paulo: Artliber, 2010.

## Arquitetura do Perceptron
Figura 3.8 – Arquitetura do Perceptron para o projeto prático 

<img src="https://lh3.googleusercontent.com/pw/AP1GczMYzi2ugdKDyUZgBc3mS_s80LMpNmKGGX8lOVVAAQNsv-BEnJU9L5kFdzreNCAgi4LnXICLR4RpXG4oKSyD-cxpA8O241oepYrmlQKKDcDx1fz1_p2L94L9zPjGF-mX2QLO_sDLT0mwcgrJO_NfkfD2=w606-h289-s-no-gm?authuser=0" alt="Texto alternativo" width="400px" height="">

Fonte: SILVA; SPATTI; FLAUZINO (2010)

## Dados
- Os dados de treinamento estão no arquivo `dados_treinamento.csv`.
- Os dados de validação estão no arquivo `dados_validacao.csv`.

## Como executar
1. Importe as bibliotecas necessárias: `pandas`, `numpy`, `matplotlib`, e `plotly`.
2. Carregue os dados de treinamento e validação.
3. Crie uma instância da classe `Perceptron`.
4. Treine o modelo usando os dados de treinamento.
5. Classifique os dados de validação usando o modelo treinado.
6. Visualize os erros do modelo durante o treinamento.

## Observações
- O código foi desenvolvido em Python.
- A semente para geração de números aleatórios não é essencial para o algoritmo, podendo ser excluída sem prejuízo.
