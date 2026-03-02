# 🧠 IA para Detecção de Melanoma (PIBIC 2025/2026)

Repositório oficial do projeto de Iniciação Científica para desenvolvimento de uma Rede Neural Convolucional (CNN) capaz de auxiliar no diagnóstico de lesões de pele.

## 🎯 Objetivo
Desenvolver um modelo de Inteligência Artificial para classificar **Melanoma** e outras 7 lesões cutâneas utilizando o dataset **ISIC 2019**, visando alta precisão para futura integração em sistemas de triagem médica.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3.10+
- **Framework:** TensorFlow / Keras
- **Arquitetura:** Transfer Learning (MobileNetV2)
- **Ambiente de Treino:** Google Colab (GPU T4)

## 📊 Resultados (Versão Atual: V3)
A versão mais recente implementou a técnica de *Transfer Learning* com a rede **MobileNetV2**, superando as limitações das arquiteturas anteriores.

- **Acurácia de Treino:** ~70%
- **Acurácia de Validação:** ~68%
- **Status:** Modelo estável e pronto para integração com Back-end.
- **Evolução:** Aumento de precisão significativo em relação à versão V2 (que estagnou em 60%), demonstrando maior capacidade de generalização.

## 📂 Estrutura do Projeto
- `/notebooks`: Histórico de experimentos, pré-processamento e treinamento.
- `/models`: Arquivos `.keras` dos modelos treinados e otimizados.
- `/dataset`: Scripts de organização e limpeza do ISIC 2019.

---
*Projeto desenvolvido como parte do Programa Institucional de Bolsas de Iniciação Científica (PIBIC).*