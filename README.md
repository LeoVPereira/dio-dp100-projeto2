# 🤖 Chatbot Inteligente com PDFs (Usando IA)

Este projeto demonstra como construir um chatbot que responde perguntas com base no conteúdo de documentos PDF ou texto.

## 📁 Estrutura
- `inputs/`: Pasta com textos de entrada (exemplo.txt)
- `app.py`: Código principal do chatbot (em Python)
- `README.md`: Documentação do projeto

## 🛠️ Como Funciona
1. O conteúdo de arquivos `.pdf` ou `.txt` é carregado
2. As sentenças são convertidas em **embeddings vetoriais**
3. O usuário faz perguntas via chat
4. A IA busca vetorialmente a resposta mais próxima do conteúdo e responde com contexto

## 📷 Prints
### 📌 Upload de Arquivo
![upload](prints/upload_exemplo.png)

### 🧠 Resposta Gerada
![resposta](prints/resposta_exemplo.png)

## 💡 Insights
- A divisão do texto em chunks é essencial para garantir boas respostas
- Embeddings tornam a busca extremamente precisa e rápida
- Mesmo sem PDF, arquivos `.txt` simples já permitem testes poderosos

## 🚀 Futuras Melhorias
- Suporte a múltiplos PDFs
- Interface web com Streamlit
- Geração automática de resumos ou mapa mental
