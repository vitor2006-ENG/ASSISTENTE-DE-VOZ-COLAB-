# Assistente de Voz com Inteligência Artificial

Este projeto implementa um **assistente de voz inteligente**, capaz de ouvir o usuário, transcrever a fala, gerar uma resposta usando Inteligência Artificial e retornar essa resposta em áudio.

O fluxo funciona da seguinte forma:
**Fala → Texto → IA → Texto → Voz**

O projeto foi desenvolvido em **Python**, utilizando **Google Colab**, e integra tecnologias modernas de **Speech-to-Text**, **IA generativa** e **Text-to-Speech**.

---

## Funcionalidades

- Gravação de áudio diretamente pelo navegador
- Transcrição automática de fala com Whisper
- Geração de respostas usando a API da OpenAI
- Conversão de texto em áudio (resposta falada)
- 🇧🇷 Suporte para língua portuguesa (pt-BR)

---

## Tecnologias Utilizadas

- **Python 3**
- **Google Colab**
- **Whisper (Speech-to-Text)**
- **OpenAI API (Chat)**
- **gTTS (Text-to-Speech)**
- **JavaScript (MediaRecorder API)**

---

## Estrutura do Projeto

```text
assistente-voz-com-ia/
├── assistente_voz_colab.ipynb   # Notebook principal do projeto
├── README.md                   # Documentação
├── requirements.txt            # Dependências do projeto
└── .gitignore                  # Arquivos ignorados pelo Git
