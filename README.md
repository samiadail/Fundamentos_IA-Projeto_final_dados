# 🚗 AutoPreço

> Plataforma web para estimativa inteligente de preços de veículos utilizando **Machine Learning**, **Python** e uma interface moderna desenvolvida em **React**.

<p align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render)

</p>

---

# 📖 Sobre o Projeto

O **AutoPreço** é uma aplicação web desenvolvida para estimar o valor de veículos usados utilizando técnicas de **Machine Learning**.

O sistema recebe informações do veículo fornecidas pelo usuário, envia esses dados para uma API desenvolvida em **Flask**, realiza a predição utilizando um modelo treinado com **Scikit-Learn** e retorna uma estimativa do valor do veículo em tempo real.

A aplicação possui uma interface moderna, responsiva e integrada a um modelo 3D interativo para proporcionar uma melhor experiência ao usuário.

---

# 🌐 Links do Projeto

| Plataforma | Link |
|------------|------|
| 🚗 Front-End | https://car-price-decoder.lovable.app/ |
| ⚙️ API REST | https://fundamentos-ia-projeto-final-dados.onrender.com/ |
| 📂 GitHub | https://github.com/samiadail/Fundamentos_IA-Projeto_final_dados |

---

# ✨ Funcionalidades

- Estimativa inteligente do preço de veículos
- Modelo de Machine Learning treinado em Python
- API REST utilizando Flask
- Interface moderna e responsiva
- Modelo 3D interativo
- Exibição do nível de confiança da previsão
- Estimativa de depreciação
- Compartilhamento dos resultados
- Cópia rápida da estimativa
- Compatível com Desktop e dispositivos móveis

---

# 🧠 Variáveis utilizadas pelo Modelo

O modelo de Machine Learning utiliza quatro variáveis para realizar a estimativa:

- Ano de fabricação
- Quilometragem
- Motorização
- Quantidade de revisões

---

# 🏗 Arquitetura

```
                Usuário
                    │
                    ▼
        Interface Web (React)
                    │
          Requisição HTTP (POST)
                    │
                    ▼
          API REST (Flask)
                    │
                    ▼
      Modelo de Machine Learning
                    │
                    ▼
        Resposta JSON com o valor
                    │
                    ▼
      Interface apresenta o resultado
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

## Machine Learning

- Scikit-Learn
- Pandas
- NumPy

## Banco de Dados

- Supabase

## Deploy

- Render
- Lovable

---

# 🚀 Como Executar

## Clonar o projeto

```bash
git clone https://github.com/samiadail/Fundamentos_IA-Projeto_final_dados.git
```

---

## Front-End

```bash
npm install

npm run dev
```

---

## Back-End

```bash
pip install -r requirements.txt

python app.py
```

---

# 📂 Estrutura do Projeto

```
AutoPreço/

├── frontend/
│   ├── public/
│   ├── src/
│   ├── assets/
│   └── components/
│
├── backend/
│   ├── app.py
│   ├── model.pkl
│   ├── requirements.txt
│
└── README.md
```

---

# 📷 Capturas de Tela

## Página Inicial

> Adicionar screenshot

---

## Resultado da Estimativa

> Adicionar screenshot

---

## Modelo 3D

> Adicionar screenshot

---

# 🔮 Melhorias Futuras

- Histórico de consultas
- Comparação entre veículos
- Consulta automática por placa
- Exportação em PDF
- Dashboard com gráficos
- Integração com Tabela FIPE
- Explicação detalhada da previsão utilizando IA

---

# 👨‍💻 Autor

**Sami Adail**

GitHub:
https://github.com/samiadail

---

# 📄 Licença

Projeto desenvolvido para fins educacionais durante o curso **Fundamentos de IA e Análise de Dados** no **SENAI Americana**.