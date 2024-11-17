# Aula 5 - Representação de Texto

Nesta aula, aprendemos a converter textos em representações numéricas, um passo fundamental para aplicar técnicas de machine learning em Processamento de Linguagem Natural (PLN). Exploramos métodos simples e interpretáveis, como Bag of Words (BoW) e TF-IDF, que são amplamente utilizados para transformar palavras em vetores numéricos.

## Conteúdo Abordado:

### 1. Introdução às Técnicas de Representação de Texto
- Explicação sobre a importância de converter textos em números, para que possam ser utilizados como entrada em modelos de machine learning.
- Discussão sobre como as técnicas de representação numérica ajudam a capturar informações semânticas e sintáticas do texto.

### 2. Bag of Words (BoW)
- Implementação do modelo BoW usando `CountVectorizer` do scikit-learn.
- Demonstração da criação de uma matriz BoW, onde cada linha representa um documento e cada coluna representa a contagem de ocorrências de palavras.
- Visualização do vocabulário gerado e análise da matriz resultante.

### 3. TF-IDF (Term Frequency - Inverse Document Frequency)
- Introdução ao conceito de TF-IDF, uma técnica que pondera a frequência das palavras considerando sua importância em diferentes documentos.
- Implementação prática usando `TfidfVectorizer` do scikit-learn.
- Comparação entre a matriz BoW e a matriz TF-IDF, destacando como o TF-IDF pode reduzir a influência de palavras comuns e dar mais peso às palavras significativas.

### 4. Pipeline Completo de Pré-processamento e Vetorização
- Construção de um pipeline que integra as etapas de pré-processamento (limpeza de texto, tokenização, remoção de stopwords e lematização).
- Vetorização dos documentos processados usando o modelo BoW, com análise do vocabulário e da matriz resultante.
- Demonstração de como o pipeline facilita a transformação de texto em representações numéricas para uso em modelos de PLN.

Este README fornece uma visão abrangente das técnicas de representação de texto abordadas na aula e serve como material de apoio para os alunos aplicarem essas técnicas em seus próprios projetos.
