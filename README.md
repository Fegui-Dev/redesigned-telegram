# Chatbot Interativo com PDFs

Este projeto consiste em um chatbot interativo que responde perguntas baseadas no conteúdo de arquivos PDF. Utiliza IA generativa e busca vetorizada para fornecer respostas contextualizadas.

## Estrutura do Projeto

- **inputs/**: Contém os arquivos PDF e documentos de texto para testar a funcionalidade de busca e resposta.
- **output/**: Diretório de resultados gerados.
- **src/**: Contém o código do projeto, incluindo a leitura de PDFs, indexação e geração de respostas.

## Como Funciona

1. **Carregar Arquivos PDF**: O usuário pode carregar seus próprios arquivos PDF ou documentos de texto para análise.
2. **Busca Vetorizada**: O sistema usa embeddings para indexar e buscar informações dos documentos.
3. **IA Generativa**: O modelo de linguagem responde às perguntas feitas com base no conteúdo dos documentos carregados.
4. **Chat Interativo**: O chatbot permite ao usuário fazer perguntas e receber respostas contextualizadas.

## Como Usar

1. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
