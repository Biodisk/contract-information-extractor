# Histórico do Projeto

## Contexto

Projeto desenvolvido para automatizar a extração de informações de contratos PDF utilizando processamento local, OCR e modelos de linguagem.

## Problema

A análise manual de contratos demanda tempo e está sujeita a erros de digitação e interpretação.

Além disso, os documentos podem possuir formatos variados:

- PDFs digitais
- PDFs escaneados
- Contratos com baixa qualidade de imagem

## Solução Proposta

Pipeline automatizado composto por:

1. Leitura do PDF
2. Detecção de camada de texto
3. OCR quando necessário
4. Extração estruturada por IA
5. Exportação dos resultados

## Tecnologias Avaliadas

- Python
- Docling
- EasyOCR
- Ollama
- Qwen

## Benefícios Esperados

- Redução do trabalho manual
- Maior velocidade de processamento
- Padronização das informações extraídas
- Operação totalmente local

## Situação Atual

Protótipo funcional em desenvolvimento contínuo.
