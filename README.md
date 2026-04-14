# 🏠 Análise de Imóveis para Aluguel no Rio de Janeiro

Projeto de **Análise Exploratória de Dados (EDA)** utilizando a biblioteca Pandas, focado em um dataset de imóveis disponíveis para aluguel na cidade do Rio de Janeiro.

---

## 📋 Sobre o Projeto

Este notebook explora uma base de dados de anúncios de imóveis residenciais e comerciais para aluguel. O objetivo é realizar a limpeza, transformação e enriquecimento dos dados para facilitar análises futuras e tomada de decisão (ex: escolha de imóveis, cálculo de custos anuais, etc.).

---

## ✨ Principais Análises Realizadas

- Carregamento correto do arquivo CSV com separador `;`
- Exploração inicial dos dados (`head()`, `tail()`, `shape`, `info()`)
- Verificação e tratamento de dados ausentes
- Criação de novas colunas:
  - `Valor_por_mes` → Valor + Condomínio
  - `Valor_por_ano` → Valor anual (12 meses)
  - `Descricao` → Texto completo do imóvel
  - `Possui_suite` → Indicador binário (Sim/Não)
- Exportação dos dados limpos e enriquecidos para um novo arquivo CSV

---

## 🗂️ Dataset

- **Fonte:** Base de imóveis para aluguel (Rio de Janeiro)
- **Quantidade de registros:** 32.960
- **Colunas originais:**
  - `Tipo`, `Bairro`, `Quartos`, `Vagas`, `Suites`, `Area`, `Valor`, `Condominio`, `IPTU`

**Colunas criadas:**
- `Valor_por_mes`
- `Valor_por_ano`
- `Descricao`
- `Possui_suite`

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Pandas**
- **Jupyter Notebook**

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/nome-do-repositorio.git
