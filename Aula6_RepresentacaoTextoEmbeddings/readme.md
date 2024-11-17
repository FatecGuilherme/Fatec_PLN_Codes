# Aula 6 - Representação de Texto com Embeddings

Nesta aula, aprendemos sobre técnicas avançadas de representação de texto usando embeddings, que transformam palavras em vetores densos, preservando relações semânticas. Exploramos diferentes modelos de embeddings, como Word2Vec, GloVe e FastText, e discutimos suas aplicações no Processamento de Linguagem Natural (PLN).

## Conteúdo Abordado:

### 1. Introdução aos Embeddings
- Explicação sobre a importância dos embeddings para capturar significado e relações semânticas entre palavras.
- Comparação entre modelos baseados em contagem (BoW, TF-IDF) e modelos de embeddings, que utilizam aprendizado profundo para criar representações vetoriais.

### 2. Word2Vec
- Implementação do modelo Word2Vec usando a biblioteca Gensim.
- Discussão sobre os dois métodos de treinamento: CBOW (Continuous Bag of Words) e Skip-gram.
- Exemplo prático de treinamento com um corpus simples, incluindo a obtenção de vetores de palavras e a medição de similaridades.
- Comparação de similaridade entre palavras, como "cachorro" e "gato", utilizando o modelo treinado.

### 3. GloVe (Global Vectors for Word Representation)
- Introdução ao modelo GloVe, que combina informações globais de coocorrência para criar vetores de palavras.
- Instruções para download e uso de modelos pré-treinados disponíveis pela Stanford NLP.
- Exemplo prático de cálculo de similaridade e obtenção de palavras mais próximas usando embeddings do GloVe.

### 4. FastText
- Explicação sobre o modelo FastText, que considera subpalavras para criar embeddings, melhorando o desempenho com palavras desconhecidas e variações morfológicas.
- Instruções para download do modelo pré-treinado em português.
- Exemplo prático de cálculo de similaridade e análise de palavras próximas utilizando o modelo FastText.

Este README oferece uma visão abrangente sobre o uso de embeddings para representar textos, facilitando a aplicação dessas técnicas em projetos de PLN.

---

#### Nome do Commit
