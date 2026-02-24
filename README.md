# 📘 Gerador de Questões com IA (Ollama + Python)

Este projeto gera automaticamente listas de exercícios
utilizando inteligência artificial rodando localmente via Ollama.

O usuário define a disciplina, assunto, nível e quantidade,
e o sistema cria as questões e exporta para Word.

---

## 🚀 Funcionalidades

- Geração automática de questões
- Controle de nível (básico, intermediário, avançado)
- Exportação para arquivo Word (.docx)
- Interface em terminal (CLI)
- IA local (offline)

---

## 🛠️ Tecnologias

- Python 3.10+
- Ollama
- Modelo: mistral
- python-docx

---

## 💻 Requisitos

### Software
- Python 3 instalado
- Ollama instalado

### Hardware (Recomendado)
- GPU NVIDIA com CUDA (opcional)

---

## 📦 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/Gustavo0606/gerador-questoes-ia.git
cd gerador-questoes-ia

2. Crie o ambiente virtual
python -m venv venv
venv\Scripts\activate
3. Instale as dependências
pip install -r requirements.txt
4. Baixe o modelo
ollama pull mistral
▶️ Como usar

Execute:

python main.py

Siga as instruções no terminal.

📄 Saída

O programa gera arquivos .docx com as questões.