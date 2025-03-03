# Redes Neurais Artificiais: Perceptron

## Descrição
Este projeto implementa um Perceptron simples para classificar dados em duas classes. O modelo é treinado usando dados de um arquivo CSV e validado com outro conjunto de dados.

## Referência
- SILVA, Ivan Nunes da; SPATTI, Danilo Hernane; FLAUZINO, Rogério Andrade. **Redes neurais artificiais:** para engenharia e ciências aplicadas. São Paulo: Artliber, 2010.

## Arquitetura do Perceptron
O Perceptron possui uma camada de entrada com três neurônios (x1, x2, x3) e uma camada de saída com um neurônio. A função de ativação utilizada é a função degrau bipolar.

## Dados
- Os dados de treinamento estão no arquivo `apendice1.csv`.
- Os dados de validação estão no arquivo `tabela3_3.csv`.

## Como executar
1. Importe as bibliotecas necessárias: `pandas`, `numpy`, `matplotlib`, e `plotly`.
2. Carregue os dados de treinamento e validação.
3. Crie uma instância da classe `Perceptron`.
4. Treine o modelo usando os dados de treinamento.
5. Classifique os dados de validação usando o modelo treinado.
6. Visualize os erros do modelo durante o treinamento.

## Resultados
O modelo atingiu uma acurácia de 100% nos dados de treinamento. Os resultados da classificação dos dados de validação são exibidos no console.

## Observações
- O código foi desenvolvido em Python.
- A semente para geração de números aleatórios não é essencial para o algoritmo, podendo ser excluída sem prejuízo.
