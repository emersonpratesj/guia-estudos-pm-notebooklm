# 🛡️ Miniguia de Estudos Ativos com NotebookLM: Concurso da Polícia Militar

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![DIO Project](https://img.shields.io/badge/Plataforma-DIO-orange)
![Foco](https://img.shields.io/badge/Objetivo-Carreira_Policial-blue)

## 📌 Contexto e Objetivos

Este repositório documenta a criação de um **Caderno Temático no Google NotebookLM** estruturado para otimizar a preparação para o concurso da **Polícia Militar**. O projeto foi desenvolvido para o desafio prático da **DIO (Digital Innovation One)**, aplicando a Inteligência Artificial como uma ferramenta central de aprendizagem ativa, organização de legislação e resolução de questões.

- **Tema de Estudo:** Preparatório para Concurso Público – Polícia Militar (Legislação, Direito Constitucional e Estratégia de Prova).
- **Objetivos de Aprendizagem:**
  1. Centralizar o edital e as principais legislações em uma base de dados consultável via IA.
  2. Mapear os conceitos jurídicos e operacionais mais cobrados nas bancas examinadoras.
  3. Criar prompts reutilizáveis para geração de simulados, mapas mentais e resumos expressos.

---

## 📑 Curadoria de Fontes

Para compor a base de conhecimento no NotebookLM, foram adicionadas **4 fontes estratégicas**:

1. **[Edital do Concurso PM]** – Mapeamento de conteúdo programático, critérios de pontuação e requisitos.
2. **[Constituição Federal de 1988 - Art. 5º ao 14]** – Direitos fundamentais, garantias e direitos políticos.
3. **[Constituição Federal de 1988 - Art. 144]** – Da Segurança Pública e atribuições das forças policiais.
4. **[Legislação Penal e Extravagante]** – Leis de abuso de autoridade, crimes hediondos e código penal militar/comum.

---

## 🧠 Engenharia de Prompts & Troubleshooting ("Cicatrizes")

Durante os testes no NotebookLM, foram refinadas perguntas para garantir que a IA respondesse rigorosamente de acordo com a letra da lei e com o edital do concurso.

### 🎯 Evolução de Prompts

#### **Tentativa 1 (Muito genérico):**
> *"Resuma a lei de segurança pública para a PM."*
- **Resultado:** A resposta trouxe conceitos genéricos sobre segurança, sem citar os artigos específicos do edital.

#### **Tentativa 2 (Refinado e Contextualizado):**
> *"Com base no artigo 144 da Constituição Federal carregado nas fontes, explique em tópicos as atribuições da Polícia Militar em comparação com as da Polícia Civil. Destaque os termos que costumam ser pegadinhas em bancas de concursos."*
- **Resultado:** Resposta precisa, diferenciando o policiamento ostensivo/preservação da ordem pública (PM) da polícia judiciária/investigação (PC), com pontos de atenção claros.

---

### 🪵 Troubeshooting (Dificuldades e Soluções)

| Dificuldade Encontrada | Causa | Solução Aplicada |
| :--- | :--- | :--- |
| **Respostas com jurisprudências desatualizadas** | O modelo trazia interpretações gerais da web. | Adicionou-se ao prompt: *"Responda estritamente com base no texto normativo do PDF anexado."* |
| **Confusão entre atribuições das Polícias** | Termos parecidos (preservação da ordem x investigação). | Solicitou-se a criação de uma tabela comparativa no prompt. |
| **Resumos longos difíceis de memorizar** | Falta de formatação visual. | Exigiu-se a saída em tópicos curtos (*bullet points*) e mnemônicos. |

---

## 🚀 Miniguia de Estudo (Entrega Final)

### 📖 1. Resumo Estruturado do Conteúdo

#### **Módulo 1: Direito Constitucional Aplicado à Segurança**
- **Artigo 5º:** Direitos e garantias fundamentais (inviolabilidade do domicílio, prisão em flagrante, devido processo legal).
- **Artigo 144:** A Segurança Pública como dever do Estado, direito e responsabilidade de todos. A Polícia Militar destina-se ao policiamento ostensivo e à preservação da ordem pública.

#### **Módulo 2: Estratégia de Estudo e Resolução de Questões**
- **Ciclo de Estudos:** Alternância entre Leitura da Lei Seca ➔ Questões de Fixação ➔ Revisão por Inteligência Artificial.
- **Identificação de Pegadinhas:** Atenção a verbos como *"poderá"* vs. *"deverá"*, e às exceções da inviolabilidade do domicílio à noite.

---

### 🔤 2. Glossário de Termos Essenciais

- **Policiamento Ostensivo:** Ação policial fardada e visível com o objetivo de prevenir crimes e manter a ordem pública.
- **Inviolabilidade de Domicílio:** Regra constitucional que protege a casa, permitindo entrada apenas com consentimento, flagrante delito, desastre, socorro ou determinação judicial (durante o dia).
- **Flagrante Delito:** Situação em que o indivíduo está cometendo a infração penal, acabou de cometê-la ou é perseguido/encontrado logo após com instrumentos do crime.
- **Excesso de Poder:** Ocorre quando a autoridade pública atua fora dos limites de sua competência legal.

---

### 🛠️ 3. Conjunto de Prompts Reutilizáveis para Revisão

Guarde estes prompts para usar na reta final de preparação:

```text
[PROMPT 1 - GERADOR DE QUESTÕES DA BANCA]
"Atue como uma banca examinadora de concurso militar. Elabore 3 questões inéditas de múltipla escolha sobre o Artigo 5º da CF/88, com 5 alternativas cada e gabarito comentado ao final."

[PROMPT 2 - SIMULADOR DE PEGADINHAS DE LEI SECA]
"Analise o texto da legislação no caderno e liste 5 trechos onde a banca examinadora costuma trocar palavras para confundir o candidato (ex: trocar 'exclusivamente' por 'preferencialmente')."

[PROMPT 3 - RESUMO EM TABELA COMPARATIVA]
"Crie uma tabela comparativa resumindo as diferenças de competência entre a Polícia Militar, Polícia Civil e Guarda Municipal, com base nas fontes do caderno."
