# 🚗 AutoPreço

> Plataforma web para estimativa inteligente de preços de veículos utilizando **Machine Learning**, **Python** e uma interface moderna desenvolvida em **React**.

<p align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs)

</p>

---

# 📖 Sobre o Projeto

O **AutoPreço** é uma aplicação web desenvolvida como projeto final do curso **Fundamentos de IA e Análise de Dados** do **SENAI Americana**.

O sistema utiliza um modelo de **Machine Learning** treinado em **Python** para estimar o valor de veículos usados com base nas informações fornecidas pelo usuário.

A aplicação integra um **Front-End moderno desenvolvido em React** com uma **API REST em Flask**, responsável por processar os dados, executar a predição e retornar o valor estimado em tempo real.

Além da estimativa, a interface oferece uma experiência mais intuitiva através de um modelo 3D interativo do veículo e uma apresentação visual dos resultados.

---

# 🌐 Links do Projeto

| Plataforma | Link |
|------------|------|
| 🚗 Front-End | https://car-price-decoder.lovable.app/ |
| ⚙️ API REST | https://fundamentos-ia-projeto-final-dados.onrender.com/ |
| 📂 GitHub | https://github.com/samiadail/Fundamentos_IA-Projeto_final_dados |

---

# ✨ Funcionalidades

- 🚗 Estimativa inteligente do valor de veículos usados
- 🤖 Modelo de Machine Learning treinado em Python
- 🌐 API REST utilizando Flask
- 🎨 Interface moderna e responsiva
- 🧊 Visualização 3D interativa do veículo
- 📊 Exibição do nível de confiança da previsão
- 📉 Estimativa de depreciação
- 📋 Copiar resultado
- 📤 Compartilhar resultado
- 📱 Compatível com computadores, tablets e smartphones

---

# 🧠 Modelo de Machine Learning

O modelo foi desenvolvido utilizando o algoritmo **Linear Regression** da biblioteca **Scikit-Learn**.

Durante o treinamento foram utilizadas informações de veículos usados para que o modelo aprendesse a identificar padrões capazes de estimar o valor de mercado de um automóvel.

As variáveis utilizadas pelo modelo são:

- Ano de fabricação
- Quilometragem
- Motorização
- Quantidade de revisões

O resultado da previsão é retornado em formato JSON pela API e apresentado automaticamente na interface.

---

# 📊 Base de Dados

O treinamento do modelo foi realizado utilizando o arquivo:

```
dataset_carros_usados.csv
```

O conjunto de dados contém registros de veículos usados e suas respectivas características, permitindo o treinamento do modelo de regressão linear.

---

# 🏗 Arquitetura do Sistema

```text
                 Usuário
                     │
                     ▼
      Interface Web (React + TypeScript)
                     │
           Requisição HTTP (POST)
                     │
                     ▼
             API REST (Flask)
                     │
                     ▼
     Modelo de Machine Learning
        (Linear Regression)
                     │
                     ▼
        Resposta JSON da API
                     │
                     ▼
      Exibição da estimativa no Front-End
```

---

# 🛠 Tecnologias Utilizadas

## Front-End

- React
- TypeScript
- Vite
- Tailwind CSS
- Three.js
- React Three Fiber
- React Three Drei
- Framer Motion

## Back-End

- Python
- Flask
- Flask-CORS
- python-dotenv

## Machine Learning

- Scikit-Learn
- Pandas

## Banco de Dados

- Supabase

## Deploy

- Lovable
- Render

---

# 🚀 Como Executar Localmente

## 1. Clonar o repositório

```bash
git clone https://github.com/samiadail/Fundamentos_IA-Projeto_final_dados.git
```

---

## 2. Acessar a pasta

```bash
cd Fundamentos_IA-Projeto_final_dados
```

---

## 3. Criar um ambiente virtual

```bash
python -m venv .venv
```

---

## 4. Ativar o ambiente virtual

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

---

## 5. Instalar as dependências

```bash
pip install -r requirements.txt
```

---

## 6. Configurar o arquivo `.env`

Crie um arquivo `.env` na raiz do projeto contendo as credenciais necessárias para conexão com o Supabase.

---

## 7. Executar a aplicação

```bash
python app.py
```

O servidor será iniciado em:

```
http://localhost:5000
```

---

# 📂 Estrutura do Projeto

```text
Fundamentos_IA-Projeto_final_dados/

├── .venv/
├── .env
├── .gitignore
├── app.py
├── dataset_carros_usados.csv
├── requirements.txt
└── README.md
```
<!-- 
---

# 📷 Capturas de Tela

## Página Inicial

> Adicionar screenshot da tela inicial.

---

## Visualização 3D

> Adicionar screenshot do modelo 3D.

---

## Resultado da Estimativa

> Adicionar screenshot do resultado.

---

# 🔮 Melhorias Futuras

- Histórico de consultas
- Consulta automática por placa
- Comparação entre veículos
- Exportação dos resultados em PDF
- Dashboard com gráficos estatísticos
- Integração com a Tabela FIPE
- Explicação detalhada da previsão utilizando IA (Explainable AI) -->

---

# 👨‍💻 Autor

**Sami Adail**

GitHub: https://github.com/samiadail

---

# 📄 Licença

Projeto desenvolvido para fins educacionais durante o curso **Fundamentos de IA e Análise de Dados** do **SENAI Americana**.
