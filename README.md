# Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados
# 📚 Projeto de Ingestão e Indexação de Documentos com IA

Este repositório contém a documentação do laboratório prático da DIO sobre ingestão de dados, indexação inteligente e mineração de informações com uso de ferramentas de Inteligência Artificial.

## 🎯 Objetivo

Demonstrar na prática como:
- Ingerir documentos em uma plataforma de IA
- Criar índices pesquisáveis com embeddings e chunking
- Realizar consultas inteligentes sobre os dados

## 🧠 Ferramentas Utilizadas

- Azure Cognitive Search ou LangChain (dependendo do laboratório)
- Vetorização de documentos (embeddings)
- Armazenamento em índice vetorial
- Análise com IA generativa (RAG)

## 🛠️ Etapas Realizadas

### 1. Ingestão de Documentos

- Upload de arquivos .pdf e .txt
- Normalização e divisão em trechos (chunks)

### 2. Indexação Inteligente

- Geração de embeddings dos trechos
- Armazenamento em índice vetorial com metadados

### 3. Exploração com IA

- Consultas realizadas:
  - "Qual o tema principal do documento?"
  - "Liste os tópicos abordados no capítulo 3"
  - "Quais são os principais termos técnicos usados?"

- IA retornou respostas contextualizadas com base no conteúdo ingerido

## 💡 Insights Obtidos

- A qualidade do chunking e da vetorização afeta diretamente a precisão das respostas.
- Documentos com boa estrutura (títulos, subtítulos) geram melhores resultados.
- Ideal para empresas que querem transformar bases de conhecimento em assistentes inteligentes.


## 📁 Organização

- `/docs`: arquivos de entrada usados na ingestão
- `/indexacao`: registros de como a indexação foi configurada
- `/queries`: exemplos de perguntas feitas à IA e as respostas recebidas

---

> Projeto desenvolvido como parte da formação de IA para Documentos na DIO.
