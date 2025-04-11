# Aprendendo Regressão Linear com PyTorch

Este projeto demonstra como usar o PyTorch para resolver problemas de regressão linear e não-linear, focando na implementação de redes neurais para ajustar funções matemáticas.

## O que aprendi

### Conceitos Básicos
- **Regressão Linear**: Como modelar relações lineares entre variáveis usando PyTorch
- **Regressão Não-Linear**: Como modelar relações quadráticas usando redes neurais
- **Redes Neurais**: Implementação de modelos com diferentes arquiteturas

### Ferramentas e Bibliotecas
- **PyTorch**: Framework de aprendizado de máquina para construção de modelos
- **Matplotlib**: Criação de visualizações para análise de resultados

### Componentes das Redes Neurais
- **Camadas Lineares**: Transformações lineares dos dados
- **Funções de Ativação**: Uso de ReLU para introduzir não-linearidade
- **Funções de Perda**: Mean Squared Error (MSE) para medir o erro
- **Otimizadores**: SGD (Stochastic Gradient Descent) para atualização de pesos

### Processo de Treinamento
- **Forward Pass**: Geração de previsões pelo modelo
- **Backward Pass**: Cálculo de gradientes para atualização dos pesos
- **Otimização**: Ajuste iterativo dos parâmetros do modelo
- **Monitoramento**: Acompanhamento da perda durante o treinamento

## Experimentos Realizados

### Regressão Linear
- Implementação de um modelo simples para ajustar uma linha reta (y = 2x + 1)
- Análise do impacto da taxa de aprendizado na convergência do modelo

### Regressão Não-Linear
- Implementação de modelos para ajustar uma função quadrática (y = 3x² - 10x + 6)
- Comparação de diferentes arquiteturas:
  - Modelo simples: Uma camada oculta com 10 neurônios
  - Modelo complexo: Arquitetura mais profunda com camadas de 32 e 16 neurônios

## Conclusões

- Redes neurais, mesmo as mais simples, podem aproximar funções complexas
- A escolha da arquitetura e hiperparâmetros afeta significativamente o desempenho
- A taxa de aprendizado é crucial para a estabilidade e velocidade do treinamento
- Modelos mais complexos têm maior capacidade, mas também podem ser mais difíceis de treinar

