@@ -0,0 +1,82 @@
# 💧 Sistema de Consumo de Água

## 📋 Sobre o projeto

Este projeto foi desenvolvido em Python para uma companhia de saneamento, com o objetivo de classificar o perfil de consumo de água de diferentes tipos de imóveis.

O programa solicita ao usuário o tipo de imóvel e o consumo mensal de água em metros cúbicos (m³). Em seguida, aplica regras de negócio para apresentar uma classificação e uma mensagem educativa.

## 🎯 Objetivo

Classificar o consumo de água de acordo com o tipo de imóvel e o consumo mensal informado pelo usuário.

### 🏠 Tipos de imóveis

* 🏢 Comercial
* 🏠 Casa
* 🏙️ Apartamento

## 📊 Regras de classificação

* 🏢 **Comercial:** tarifa comercial aplicada.
* 🏙️ **Apartamento com consumo menor que 10 m³:** consumo econômico.
* 🏠 **Casa ou apartamento com consumo de até 25 m³:** consumo moderado.
* ⚠️ **Demais situações:** consumo excessivo.

## 💻 Tecnologias utilizadas

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-black?logo=github)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/fredavelino/Fred_ag7_DS_l.git
```

### 2. Acesse a pasta do projeto

```bash
cd consumo-agua
```

### 3. Execute o programa

```bash
python app.py
```

## 🧪 Exemplo de execução

```text
======================================
   SISTEMA DE CONSUMO DE ÁGUA
======================================

Digite o tipo de imóvel (comercial, casa ou apartamento): apartamento
Digite o consumo mensal de água em m³: 8

Consumo econômico – excelente controle de água!
```

## 📁 Estrutura do projeto

```text
consumo-agua/
│
├── app.py
└── README.md
```

## 👨‍💻 Desenvolvedor

Projeto desenvolvido como atividade acadêmica do curso de Desenvolvimento de Sistemas – DS I.

## 🌱 Conscientização

💧 Economizar água é uma responsabilidade de todos.

Pequenas mudanças nos hábitos de consumo podem contribuir para a preservação desse recurso essencial.
