# Geração Automática de Descrições para Imagens de Moda

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white) ![Topic](https://img.shields.io/badge/Topic-generative-ai-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## Descrição

CNN treinada no Fashion MNIST para classificação de peças de roupa combinada com GPT-2 para geração criativa de descrições de produtos de moda.

## Funcionalidades

- Classificação de roupas com CNN no Fashion MNIST
- Geração de descrições criativas com GPT-2
- Pipeline end-to-end: imagem → categoria → descrição
- Combinação de visão computacional e NLP generativo
- Útil para e-commerces de moda

## Stack Tecnológico

| Tecnologia | Descrição |
|---|---|
| Python | Linguagem principal |
| TensorFlow / Keras | CNN para classificação |
| HuggingFace Transformers | Modelo GPT-2 |
| NumPy | Processamento de imagens |

## Como Usar

1. Instale as dependências: `pip install tensorflow transformers`
2. Execute: `python gerar_descricoes.py`
3. Forneça uma imagem e o sistema classificará e gerará a descrição

## Estrutura de Pastas

```
├── gerar_descricoes.py
├── modelos/
├── exemplos/
└── requirements.txt
```

---

> Feito com ❤️ por Rone Bragaglia · ML Engineer & Fundador CobrançaAuto
