# 🤖 Miniguia de Estudos: Inteligência Artificial & Machine Learning
### Caderno Temático criado com NotebookLM — Desafio de Projeto DIO

> **Autor:** Lorena Oliveira
> **Data:** Maio de 2026
> **Plataforma de IA utilizada:** [Google NotebookLM](https://notebooklm.google.com/)
> **Nível:** Iniciante

---

## 📌 Contexto e Objetivos

### Por que escolhi este tema?

A Inteligência Artificial deixou de ser ficção científica e se tornou parte do cotidiano: dos assistentes de voz aos algoritmos de recomendação do YouTube e Netflix, passando pelos modelos de linguagem como o próprio Claude e o ChatGPT. Como iniciante na área de tecnologia, entender os fundamentos de IA e Machine Learning é um diferencial competitivo essencial no mercado atual.

### Objetivos de Estudo

- ✅ Compreender o que é Inteligência Artificial e como ela se diferencia de Machine Learning e Deep Learning
- ✅ Conhecer os principais tipos de aprendizado de máquina (supervisionado, não supervisionado e por reforço)
- ✅ Identificar casos de uso reais de IA no mercado
- ✅ Entender o conceito de modelos, datasets, treinamento e inferência
- ✅ Construir um vocabulário técnico básico para continuar os estudos com autonomia

---

## 📚 Curadoria de Fontes

Abaixo estão as 5 fontes abertas selecionadas, todas em texto ou PDF, que foram carregadas no NotebookLM para compor o caderno temático:

| # | Título | Fonte | Formato | Link |
|---|--------|--------|---------|------|
| 1 | **Machine Learning — Wikipedia EN** | Wikipedia | Texto/Web | [🔗 Acessar](https://en.wikipedia.org/wiki/Machine_learning) |
| 2 | **Artificial Intelligence: A Modern Approach (Capítulo 1 — Preview)** | Russell & Norvig / AIMA | PDF | [🔗 Acessar](http://aima.cs.berkeley.edu/) |
| 3 | **Introdução ao Machine Learning — Google for Developers** | Google | Texto/Web | [🔗 Acessar](https://developers.google.com/machine-learning/intro-to-ml) |
| 4 | **A Brief History of Artificial Intelligence** | AAAI | PDF | [🔗 Acessar](https://ojs.aaai.org/index.php/aimagazine/article/view/1904) |
| 5 | **Elements of AI — Parte 1** | University of Helsinki / Reaktor | Texto/Web | [🔗 Acessar](https://course.elementsofai.com/) |

> 💡 **Critério de seleção:** priorizei fontes gratuitas, em inglês e português, com linguagem acessível para iniciantes, produzidas por instituições reconhecidas (Google, universidades, Wikipedia).

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Esta seção documenta a jornada de elaboração de prompts no NotebookLM — incluindo o que funcionou, o que não funcionou e os ajustes realizados.

---

### 🔬 Experimento 1 — Prompt Vago (versão inicial)

**Prompt testado:**
```
O que é IA?
```

**Resposta obtida:** Uma resposta genérica e curta, sem referência às fontes carregadas. O NotebookLM trouxe uma definição básica, mas não aproveitou o material enviado.

**❌ Problema identificado:** O prompt era amplo demais e não direcionava a IA para as fontes do caderno.

**🔧 Ajuste realizado:** Especificar o contexto e pedir que a resposta cite as fontes carregadas.

---

### 🔬 Experimento 2 — Prompt Estruturado (versão melhorada)

**Prompt testado:**
```
Com base nas fontes carregadas neste caderno, explique o conceito de 
Inteligência Artificial para um iniciante, usando uma analogia simples 
e citando pelo menos duas das fontes.
```

**Resposta obtida:** O NotebookLM produziu uma explicação clara, comparou IA com "ensinar uma criança" por meio de exemplos, e citou trechos do material do Google for Developers e do Elements of AI.

**✅ O que funcionou:** Especificar o público-alvo ("iniciante"), pedir analogia e exigir citação das fontes.

---

### 🔬 Experimento 3 — Prompt de Comparação

**Prompt testado:**
```
Qual é a diferença entre Inteligência Artificial, Machine Learning 
e Deep Learning? Crie uma tabela comparativa com as principais características de cada um.
```

**Resposta obtida:** Uma tabela com 3 colunas bem estruturada, diferenciando escopo, técnicas e exemplos.

**✅ O que funcionou:** Pedir formato específico (tabela) e comparação estruturada.

---

### 🔬 Experimento 4 — Prompt de Glossário

**Prompt testado:**
```
Liste os 10 termos técnicos mais importantes presentes nas fontes deste caderno 
relacionados a Machine Learning. Para cada termo, forneça: nome, definição 
em até 2 linhas e um exemplo prático.
```

**Resposta obtida:** Lista organizada dos termos com definições acessíveis. Alguns termos vieram sem exemplos práticos reais.

**⚠️ Dificuldade encontrada:** O NotebookLM às vezes ignorava o campo "exemplo prático", retornando apenas definições teóricas.

**🔧 Solução:** Reformular pedindo explicitamente: *"Para o exemplo, use situações do dia a dia como Netflix, Spotify ou aplicativos de banco."*

---

### 🔬 Experimento 5 — Prompt de Quiz para Revisão

**Prompt testado:**
```
Crie 5 perguntas de múltipla escolha (com 4 alternativas cada) sobre os 
conceitos de Machine Learning presentes nas fontes deste caderno. 
Inclua o gabarito ao final.
```

**Resposta obtida:** 5 questões bem formuladas, com gabarito. Útil para autoavaliação.

**✅ O que funcionou:** Especificar o número de alternativas e pedir gabarito separado.

---

### 📝 Lições Aprendidas (Troubleshooting)

| Problema | Causa | Solução |
|----------|-------|---------|
| Resposta genérica sem citar fontes | Prompt muito vago | Adicionar "com base nas fontes carregadas" e pedir citação explícita |
| Resposta longa e confusa | Pergunta com múltiplos assuntos | Dividir em prompts separados por tópico |
| Formato ignorado (ex: tabela) | IA interpretou como sugestão | Usar linguagem imperativa: "Crie uma tabela com as colunas X, Y e Z" |
| Exemplos práticos ausentes | IA priorizou teoria | Especificar o domínio do exemplo: "use exemplos de apps do cotidiano" |
| Definições muito técnicas | Padrão das fontes é acadêmico | Adicionar ao prompt: "explique como se fosse para alguém sem formação técnica" |

---

## 📖 Miniguia de Estudo — Entrega Final

---

### 🗂️ Parte 1: Resumos Estruturados

---

#### 1.1 O que é Inteligência Artificial?

Inteligência Artificial (IA) é um campo da Ciência da Computação dedicado a criar sistemas capazes de realizar tarefas que normalmente exigiriam inteligência humana: reconhecer padrões, tomar decisões, entender linguagem natural e aprender com experiências.

**A hierarquia da IA:**

```
Inteligência Artificial (conceito amplo)
└── Machine Learning (aprende com dados)
    └── Deep Learning (redes neurais profundas)
```

**Linha do tempo simplificada:**
- **1950** — Alan Turing propõe o "Teste de Turing"
- **1956** — O termo "Artificial Intelligence" é cunhado por John McCarthy
- **1980s** — Sistemas especialistas dominam o campo
- **2012** — Deep Learning vence a ImageNet, marca uma virada
- **2022–hoje** — Era dos Large Language Models (LLMs) como GPT e Claude

---

#### 1.2 Machine Learning: aprender com dados

Machine Learning (ML) é um subcampo da IA onde sistemas aprendem padrões a partir de dados, sem serem explicitamente programados para cada tarefa.

**Analogia:** Imagine ensinar uma criança a identificar gatos. Você não escreve regras como "tem bigodes + quatro patas + orelhas pontudas = gato". Você mostra centenas de fotos de gatos e não-gatos, e ela aprende sozinha a distinguir.

**Os 3 tipos principais de aprendizado:**

| Tipo | Como funciona | Exemplo |
|------|--------------|---------|
| **Supervisionado** | Aprende com exemplos rotulados (input + resposta certa) | Detectar spam no e-mail |
| **Não supervisionado** | Encontra padrões em dados sem rótulos | Segmentação de clientes |
| **Por reforço** | Aprende por tentativa e erro, com recompensas | Robôs e jogos (ex: AlphaGo) |

---

#### 1.3 Componentes de um Sistema de ML

1. **Dataset (conjunto de dados):** Os exemplos usados para treinar o modelo
2. **Features (características):** As variáveis de entrada (ex: altura, peso, cor)
3. **Label/Target (rótulo):** A resposta que queremos prever (ex: "spam" ou "não spam")
4. **Modelo:** O algoritmo que aprende os padrões
5. **Treinamento:** O processo de ajustar os parâmetros do modelo com os dados
6. **Inferência:** Usar o modelo treinado para fazer previsões em novos dados
7. **Avaliação:** Medir o desempenho do modelo (acurácia, precisão, recall...)

---

#### 1.4 Casos de uso reais

| Área | Aplicação | Tipo de ML |
|------|-----------|-----------|
| **Streaming** | Recomendação de filmes (Netflix) | Não supervisionado |
| **E-mail** | Filtro de spam | Supervisionado |
| **Saúde** | Diagnóstico de imagens médicas | Supervisionado (Deep Learning) |
| **Finanças** | Detecção de fraudes em cartão | Supervisionado |
| **Jogos** | IA que vence campeões humanos | Reforço |
| **Linguagem** | Tradução automática, chatbots | Deep Learning (LLMs) |

---

### 📚 Parte 2: Glossário de Conceitos

| Termo | Definição | Exemplo |
|-------|-----------|---------|
| **Inteligência Artificial (IA)** | Campo da computação que cria sistemas capazes de simular capacidades cognitivas humanas | Assistentes de voz como Alexa |
| **Machine Learning (ML)** | Subcampo da IA que usa dados para treinar modelos sem programação explícita | Recomendações do YouTube |
| **Deep Learning** | ML que usa redes neurais com muitas camadas para aprender representações complexas | Reconhecimento facial no celular |
| **Algoritmo** | Conjunto de instruções passo a passo que o computador segue para resolver um problema | Receita de bolo: etapas definidas para um resultado |
| **Dataset** | Coleção de dados usada para treinar ou avaliar um modelo de ML | Milhares de e-mails rotulados como spam/não spam |
| **Feature (Característica)** | Variável de entrada usada pelo modelo para fazer previsões | Tamanho do arquivo, número de links (para detectar spam) |
| **Label (Rótulo)** | A saída esperada que o modelo aprende a prever | "spam" ou "não spam" |
| **Treinamento** | Processo em que o modelo ajusta seus parâmetros com base nos dados | Uma rede neural aprendendo a reconhecer dígitos manuscritos |
| **Inferência** | Uso do modelo treinado para fazer previsões em dados novos | Aplicar o modelo de detecção de tumor em uma nova radiografia |
| **Overfitting** | Quando o modelo memoriza os dados de treino e perde generalização | Aluno que decora as respostas mas não entende o conteúdo |
| **Underfitting** | Quando o modelo é simples demais e não aprende nem os dados de treino | Aluno que não estudou o suficiente |
| **Acurácia** | Porcentagem de previsões corretas do modelo | Modelo acertou 92 de 100 classificações → acurácia de 92% |
| **Rede Neural** | Arquitetura inspirada no cérebro humano, composta por neurônios artificiais em camadas | Base dos modelos de visão computacional |
| **Parâmetro** | Valor interno do modelo ajustado durante o treinamento | Pesos de uma rede neural |
| **Hiperparâmetro** | Configuração do modelo definida antes do treinamento | Taxa de aprendizado, número de camadas |

---

### 🔁 Parte 3: Prompts Reutilizáveis para Revisão Futura

Use os prompts abaixo em qualquer sessão futura no NotebookLM (ou outro LLM) para revisar e aprofundar os estudos:

---

**Prompt 1 — Revisão de conceito:**
```
Explique [CONCEITO] de forma simples para um iniciante, usando uma analogia 
do cotidiano e citando aplicações práticas no mercado.
```
*Substitua [CONCEITO] por: Machine Learning / Overfitting / Rede Neural / etc.*

---

**Prompt 2 — Comparação:**
```
Crie uma tabela comparando [CONCEITO A] e [CONCEITO B] com as colunas: 
definição, quando usar, vantagens e limitações.
```

---

**Prompt 3 — Autoavaliação:**
```
Crie 5 perguntas de múltipla escolha sobre [TEMA] com 4 alternativas cada. 
As perguntas devem variar entre nível fácil (2), médio (2) e difícil (1). 
Apresente o gabarito comentado ao final.
```

---

**Prompt 4 — Mapa mental textual:**
```
Crie um mapa mental em formato de lista hierárquica sobre [TEMA], 
com no mínimo 3 níveis de profundidade.
```

---

**Prompt 5 — Conexão com o mercado:**
```
Liste 5 empresas que usam [CONCEITO/TECNOLOGIA] na prática, descrevendo 
brevemente como cada uma aplica essa tecnologia em seus produtos.
```

---

**Prompt 6 — Simplificação extrema:**
```
Explique [CONCEITO] como se eu tivesse 10 anos de idade, sem usar 
nenhum jargão técnico.
```

---

**Prompt 7 — Plano de estudos:**
```
Crie um plano de estudos de 4 semanas para aprender [TEMA] do zero, 
com sugestão de recursos gratuitos (cursos, vídeos, artigos) para cada semana.
```

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- [Google NotebookLM](https://notebooklm.google.com/) — Caderno temático com IA
- [GitHub](https://github.com/) — Versionamento e portfólio
- [DIO](https://www.dio.me/) — Plataforma de desafio

---

## 🚀 Próximos Passos

- [ ] Estudar Python para IA (bibliotecas: NumPy, Pandas, Scikit-learn)
- [ ] Realizar o curso "Machine Learning Crash Course" do Google
- [ ] Implementar um modelo simples de classificação no Google Colab
- [ ] Explorar o Kaggle para praticar com datasets reais
- [ ] Adicionar novos módulos ao caderno (Deep Learning, NLP, Computer Vision)

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usar e adaptar o material.

---

*Projeto desenvolvido como parte do Desafio de Projeto da [DIO — Digital Innovation One](https://www.dio.me/) 🚀*
