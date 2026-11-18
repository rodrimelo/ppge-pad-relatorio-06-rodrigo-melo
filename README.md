# Relatório 06 — Conjuntos no Cruzamento de Bases da LEMA 🧩

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&logo=Jupyter&logoColor=white)

| Campo | Informação |
|---|---|
| **Aluno(a)** | Rodrigo Massao Yoshihara de Albuquerque Melo |
| **Matrícula** | 20261002321 |
| **Disciplina** | Programação e Análise de Dados com Python — PPGE/UFPB |
| **Professor** | Prof. Dr. Hilton Ramalho |

## 📌 Sobre
Este repositório contém a resolução das 10 questões referentes ao **Relatório 06**, com foco na estrutura de dados de conjuntos (`set` e `frozenset`), unicidade, operações algébricas e relações de contenção. Os exercícios simulam o cruzamento de diferentes bases de dados na *LEMA Consultoria Econômica*, aplicando a álgebra de conjuntos a problemas de deduplicação de cadastros, gestão de carteira de ativos, alcance de campanhas de marketing, análise de retenção e *churn* (CRM), conciliação contábil (ERP vs. banco), auditoria de *compliance* e segregação de funções (SoD), comércio exterior, triagem de currículos (RH) e segmentação de clientes.

### 🎯 Objetivos de Aprendizagem
- Criar conjuntos (`set`), eliminar duplicatas de coleções e manipular elementos com métodos específicos (`add`, `update`, `remove`, `discard`, `pop` e `clear`).
- Traduzir perguntas de negócio em operações de álgebra de conjuntos: união (`|`), interseção (`&`), diferença (`-`) e diferença simétrica (`^`).
- Avaliar relações de contenção e disjunção entre bases de dados utilizando `issubset()`, `issuperset()` e `isdisjoint()`.
- Utilizar *set comprehensions* para filtragem e transformação concisa de dados, além de aplicar conjuntos imutáveis (`frozenset`) em estruturas aninhadas.

## 📂 Arquivos
- `relatorio-06-rodrigo-melo.ipynb`: Notebook principal contendo todo o código-fonte, comentários explicativos, justificativas teóricas e as saídas das execuções.

## 🚀 Como visualizar e executar

Você pode interagir com este projeto de três formas:

### 1. Visualização Rápida (GitHub)
Basta clicar no arquivo `.ipynb` na lista de arquivos acima. O próprio GitHub renderizará o notebook com as saídas estáticas.

### 2. Execução Interativa (Google Colab)
Para rodar e modificar os códigos na nuvem, sem precisar instalar nada, clique no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rodrimelo/ppge-pad-relatorio-06-rodrigo-melo/blob/main/relatorio-06-rodrigo-melo.ipynb)

### 3. Execução Local
Caso prefira rodar localmente na sua máquina:
1. Clone este repositório:
   ```bash
   git clone https://github.com/rodrimelo/ppge-pad-relatorio-06-rodrigo-melo.git
   ```
2. Acesse a pasta do projeto e abra o arquivo no Jupyter Notebook ou VS Code:
   ```bash
   cd ppge-pad-relatorio-06-rodrigo-melo
   jupyter notebook relatorio-06-rodrigo-melo.ipynb
   ```