# RAG e Vetores

RAG (Retrieval Augmented Generation) conecta o modelo a dados externos.

## Pipeline

1. Embeddings: transforma texto em vetores
2. Chunking: divide documentos em partes menores
3. Busca semântica: encontra trechos relevantes
4. Banco vetorial: armazena conhecimento (ex: Pinecone)

## Conceito principal
Em vez de buscar palavras, o sistema busca significado.

## Exemplo
Pergunta do usuário → convertido em vetor → busca similaridade → resposta gerada
