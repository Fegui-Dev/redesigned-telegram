# 🤖 Chatbot Interativo com PDFs 📄

Este projeto consiste em um chatbot interativo que responde perguntas com base no conteúdo de arquivos PDF. Utiliza IA generativa e busca vetorizada para fornecer respostas contextualizadas. 🚀

## Estrutura do Projeto 📂

- **inputs/**: Contém os arquivos PDF e documentos de texto para testar a funcionalidade de busca e resposta. 📑
  
- **output/**: Diretório de resultados gerados. 📊

- **src/**: Contém o código do projeto, incluindo a leitura de PDFs, indexação e geração de respostas. 💻

## Como Funciona 🛠️

1. **Carregar Arquivos PDF** 📤: 
   O usuário pode carregar seus próprios arquivos PDF ou documentos de texto para análise. Basta colocar os arquivos na pasta **`inputs/`** e o sistema começará a processá-los! 📄
   
   ![Aprendixado de Maquina](https://github.com/user-attachments/assets/0672367d-3689-4e43-981e-b9581d86ebae))  

2. **Busca Vetorizada** 🔍:
   O sistema utiliza **embeddings** para indexar e buscar informações relevantes nos PDFs carregados. Com isso, ele encontra rapidamente as partes mais importantes dos documentos e facilita a busca por tópicos específicos. 🌐
   
   ![GPT - 3](https://github.com/user-attachments/assets/8139078c-c187-4f1c-953e-f230c707117e)) 
3. **IA Generativa** 🤖✨:
   Após a busca, o modelo de linguagem entra em ação! Ele gera respostas inteligentes e relevantes com base no conteúdo dos documentos, respondendo às suas perguntas de forma precisa e contextualizada. 🤯

4. **Chat Interativo** 💬:
   O chatbot interativo permite que você faça perguntas sobre o conteúdo dos documentos e obtenha respostas detalhadas. A conversa pode ser iniciada e você receberá respostas baseadas nos dados carregados. 💡

## Como Usar 📝

1. **Instale as dependências** 📦:
   Antes de começar, instale as dependências do projeto utilizando o `requirements.txt`. Execute o comando abaixo:

   ```bash
   pip install -r requirements.txt
