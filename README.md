# Chatbot Treinado com Dataset de Autismo do Reddit

Este projeto utiliza um modelo GPT-2 para treinar um chatbot com um dataset específico de autismo retirado do huggingface. 
O código permite carregar, treinar e validar o modelo utilizando dados textuais, além de salvar o modelo treinado para uso futuro.

## Estrutura do Projeto

- O Arquivo finetune gera o treinamento do modelo.
- O Arquivo Chatbot execulta a IA e gera respstas para as perguntas em inglês(obs: as perguntas devem ser feitas em inglês)
- Configuração de argumentos de treinamento e treinamento do modelo.
- Salvamento do modelo e do tokenizador treinados.

## Requisitos

- Python 3.x
- Bibliotecas necessárias: `torch`, `transformers`, `datasets`, `icecream`, `trl`

## Instalação

Clone o repositório e instale as bibliotecas necessárias:

```bash
git clone https://github.com/FelixGustav/chatbot.git
cd chatbot
pip install -r requirements.txt