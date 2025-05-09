# Otimizacao-de-Hiperparametros-e-Metodos-Avancados-em-Redes-Neurais
Repositório do projeto desenvolvido na disciplina de Redes Neurais da pós-graduação em Inteligência Artificial

## Descrição do Projeto

Este projeto implementa uma rede neural capaz de aprender e realizar operações matemáticas básicas (adição, subtração, multiplicação e divisão). Utilizando técnicas de aprendizado profundo, o modelo é treinado para reconhecer padrões em operações matemáticas e prever resultados com alta precisão.

## Características

- **Geração de Dataset**: Criação automática de um conjunto de dados sintético com operações matemáticas variadas
- **Otimização de Hiperparâmetros**: Utilização do Keras Tuner para encontrar a melhor configuração de rede neural
- **Visualização de Resultados**: Gráficos detalhados para análise de desempenho do modelo
- **Exportação do Modelo**: Salvamento do modelo treinado para uso posterior


## Tecnologias Utilizadas

- TensorFlow/Keras
- Keras Tuner
- NumPy
- Pandas
- Matplotlib
- Plotly
- Scikit-learn


## Estrutura do Código

O código está organizado nas seguintes seções:

1. **Preparação e Validação dos Dados**: Geração do dataset, divisão em conjuntos de treino/validação/teste e normalização
2. **Arquitetura da Rede Neural**: Definição da estrutura do modelo com camadas densas
3. **Otimização de Hiperparâmetros**: Busca pela melhor configuração usando Keras Tuner
4. **Treinamento e Avaliação**: Treinamento do modelo e avaliação no conjunto de teste
5. **Análise e Visualização**: Gráficos e métricas para análise de desempenho


## Resultados

O modelo alcança um erro médio absoluto (MAE) de aproximadamente 0.55 no conjunto de teste, demonstrando alta precisão na realização de operações matemáticas. Os melhores hiperparâmetros encontrados foram:

- **Função de Ativação**: tanh
- **Taxa de Aprendizado**: 0.09500291095778272
- **Regularização L2**:0.003272939323057123
- **Dropout**: 0.0
- **Otimizador**: adagrad
- **Neurônios por Camada**: 128
- **Número de Camadas**: 5

*Note que em diferentes execuções, modelos diferentes foram gerados com precisões diferentes, nesse repositório também possui o arquivo do modelo gerado e o seu scaler

