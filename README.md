# 🚀 Missão Aurora Siger – Relatório Operacional de Pré-Decolagem

**FIAP – Fase 1: Decolagem da Missão**
**Atividade Integradora**
**Aluno:** Paulo Roberto Faulstich Rego
**E-mail:** paulo.faulstich@gmail.com
**Grupo:** 58
**Prazo de entrega:** 31/03/2026

---

## 📋 Sobre o Projeto

Este projeto implementa o **Sistema de Verificação Operacional de Pré-Decolagem** da nave Aurora, no contexto da Missão Aurora Siger. O objetivo é simular o papel de um analista responsável por validar os parâmetros técnicos da nave antes do lançamento, combinando telemetria, algoritmos de decisão, análise energética e inteligência artificial.

A atividade integra os conteúdos do curso de Ciência da Computação da FIAP: fundamentos de algoritmos, programação em Python, lógica condicional, eficiência energética e IA.

---

## 🗂️ Estrutura do Repositório

```
missao-aurora-siger/
├── README.md                               # Este arquivo
├── aurora_siger_pre_decolagem.ipynb        # Notebook Python com todo o código
└── relatorio_aurora_siger_fiap.pdf         # Relatório completo em PDF
```

---

## 🎯 Conteúdo do Notebook

O notebook está organizado nas seguintes seções:

**1.1 – Organização e Descrição da Telemetria**
Tabela com os 8 parâmetros monitorados, seus valores, faixas seguras e status.

**1.2 – Algoritmo de Verificação**
Pseudocódigo e fluxogramas do sistema de decisão de pré-decolagem.

**1.3 – Script Python**
Implementação em Python das verificações. O script lê os dados de telemetria e imprime o resultado final: **PRONTO PARA DECOLAR** ou **DECOLAGEM ABORTADA**.

**1.4 – Análise Energética**
Cálculo da autonomia inicial considerando capacidade total, carga atual, consumo na decolagem e perdas energéticas.

**1.5 – Análise Assistida por IA**
Classificação dos dados, identificação de anomalias e sugestões de risco geradas pelo sistema de IA.

**1.6 – Reflexão Crítica**
Texto sobre ética em decisões algorítmicas, impacto social da exploração espacial e sustentabilidade tecnológica.

---

## ⚙️ Como Executar o Código

### Pré-requisitos

- Python 3.8 ou superior
- Jupyter Notebook ou JupyterLab (ou Google Colab)

### Opção 1 – Executar localmente

```bash
# 1. Clone o repositório
git clone https://github.com/paulo-faulstich/missao-aurora-siger.git

# 2. Acesse a pasta
cd missao-aurora-siger

# 3. (Opcional) Crie um ambiente virtual
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows

# 4. Instale as dependências (apenas biblioteca padrão do Python)
# Nenhuma instalação adicional necessária!

# 5. Inicie o Jupyter
jupyter notebook aurora_siger_pre_decolagem.ipynb
```

### Opção 2 – Google Colab (sem instalação)

1. Acesse [colab.research.google.com](https://colab.research.google.com)
2. Clique em **"Arquivo" → "Fazer upload de notebook"**
3. Selecione o arquivo `aurora_siger_pre_decolagem.ipynb`
4. Execute todas as células com **"Runtime" → "Run all"**

---

## 📊 Dados de Telemetria Utilizados

| Parâmetro | Valor | Faixa Segura | Status |
|---|---|---|---|
| Temperatura Interna | 22.5°C | 15°C – 28°C | ✅ NOMINAL |
| Temperatura Externa | -45.2°C | -60°C – -10°C | ✅ NOMINAL |
| Integridade Estrutural | 1 (OK) | 1 | ✅ NOMINAL |
| Nível de Energia | 87.3% | ≥ 70% | ✅ NOMINAL |
| Pressão dos Tanques | 342 kPa | 300 – 400 kPa | ✅ NOMINAL |
| Módulo de Propulsão | 1 (Operacional) | 1 | ✅ NOMINAL |
| Módulo de Navegação | 1 (Operacional) | 1 | ✅ NOMINAL |
| Módulo de Comunicação | 1 (Operacional) | 1 | ✅ NOMINAL |

---

## ⚡ Resultado da Análise Energética

| Parâmetro | Valor |
|---|---|
| Capacidade total da bateria | 450 kWh |
| Carga atual | 87,3% |
| Energia disponível | 392,85 kWh |
| Consumo estimado na decolagem | 85 kWh |
| Perdas energéticas (5%) | 4,25 kWh |
| Energia restante após decolagem | 303,60 kWh |
| Consumo médio em missão | 12 kWh/h |
| **Autonomia estimada** | **25,3 horas** |

---

## 🤖 Resultado da Verificação

```
=================================================================
   DECISÃO FINAL: PRONTO PARA DECOLAR
   Todos os sistemas estão dentro dos parâmetros seguros.
   Autorização de decolagem concedida.
=================================================================
```

---

## 📚 Tecnologias Utilizadas

- **Python 3** – Linguagem de programação principal
- **Jupyter Notebook** – Ambiente de desenvolvimento e documentação
- **Biblioteca padrão Python** – Nenhuma dependência externa necessária

---

## 📝 Licença

Projeto desenvolvido para fins acadêmicos – FIAP 2026.

---

*"A computação embarcada atua como o sistema nervoso da nave. Durante a decolagem, milhares de sinais digitais são processados continuamente."* – FIAP, Fase 1
