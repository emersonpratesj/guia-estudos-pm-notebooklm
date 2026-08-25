# 🛡️ Miniguia de Estudos Ativos com NotebookLM: Preparatório Polícia Militar

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![DIO Project](https://img.shields.io/badge/Plataforma-DIO-orange)
![Foco](https://img.shields.io/badge/Objetivo-Carreira_Policial-blue)

## 📌 Contexto e Objetivos

Este repositório documenta a criação de um **Caderno Temático no Google NotebookLM** estruturado para otimizar a preparação para concursos da **Polícia Militar (PMESP / Carreiras Policiais)**. O projeto foi desenvolvido para o desafio prático da **DIO (Digital Innovation One)**, aplicando a Inteligência Artificial como uma ferramenta de aprendizagem ativa, organização de legislação, engenharia de prompts e geração de simulados.

- **Tema de Estudo:** Preparatório para Concurso Público – Polícia Militar (Legislação, Direito Constitucional e Estratégia de Prova).
- **Objetivos de Aprendizagem:**
  1. Centralizar o edital e as principais legislações constitucionais em uma base consultável via IA.
  2. Mapear os conceitos jurídicos de maior incidência e peso cobrados por bancas como VUNESP e Cebraspe.
  3. Criar e documentar prompts reutilizáveis para geração de resumos, tabelas comparativas e questões comentadas.

---

## 📑 Curadoria de Fontes

Para compor a base de conhecimento no NotebookLM, foram selecionadas 4 fontes oficiais e estratégicas em formato de texto e PDF:

1. **[Constituição Federal de 1988 - Art. 5º ao 14](https://www.planalto.gov.br/ccivil_03/constituicao/constituicao.htm)** – Mapeamento dos Direitos e Deveres Individuais, Coletivos e Garantias Fundamentais.
2. **[Constituição Federal de 1988 - Art. 144](https://portal.stf.jus.br/constituicao-supremo/artigo.asp?abrirBase=CF&abrirArtigo=144)** – Normas constitucionais aplicáveis à Segurança Pública e atribuições das forças policiais.
3. **[Código Penal Brasileiro (Decreto-Lei nº 2.848/1940)](https://www.planalto.gov.br/ccivil_03/decreto-lei/del2848compilado.htm)** – Base jurídica sobre infrações penais, excludentes de ilicitude e dosimetria da pena.
4. **[Edital de Concurso Público - Polícia Militar / VUNESP](https://www.vunesp.com.br/PMES2601)** – Edital oficial contendo o conteúdo programático, distribuição de questões e critérios de avaliação.

---

## 🧠 Engenharia de Prompts & Troubleshooting ("Cicatrizes")

Durante os testes no NotebookLM, foram refinadas perguntas para garantir que a IA respondesse rigorosamente de acordo com o texto normativo da lei e a orientação das bancas examinadoras.

### 🎯 Evolução de Prompts

#### **Tentativa 1 (Muito genérico):**
> *"Resuma a lei de segurança pública para a PM."*
- **Resultado:** A resposta trouxe conceitos genéricos sobre segurança pública, sem citar os artigos específicos e sem destacar pegadinhas de prova.

#### **Tentativa 2 (Refinado e Contextualizado):**
> *"Com base no artigo 144 da Constituição Federal carregado nas fontes, explique em tópicos as atribuições da Polícia Militar em comparação com as da Polícia Civil. Destaque os termos que costumam ser pegadinhas em bancas de concursos."*
- **Resultado:** Resposta precisa, diferenciando o policiamento ostensivo e a preservação da ordem pública (PM) da polícia judiciária e investigação (PC), com pontos de atenção jurídicos claros.

---

### 🪵 Troubleshooting (Dificuldades e Soluções)

| Dificuldade Encontrada | Causa | Solução Aplicada |
| :--- | :--- | :--- |
| **Respostas com interpretações genéricas da web** | O prompt original permitia inferências amplas. | Adicionou-se ao prompt: *"Responda estritamente com base no texto normativo do PDF anexado."* |
| **Confusão nas atribuições dos órgãos** | Termos parecidos (ex: preservação da ordem pública x investigação). | Solicitou-se a criação de uma tabela comparativa com verbos-chave de cada órgão. |
| **Dificuldade de fixação rápida** | Textos e resumos prolixos. | Exigiu-se a saída em tópicos (*bullet points*) e a elaboração de questões de múltipla escolha com gabarito. |

---

## 🚀 Miniguia de Estudo (Entrega Final)

### 📖 1. Resumo Estruturado: Tópicos de Maior Incidência e Peso

A análise cruzada dos editais e provas anteriores (VUNESP e Cebraspe) aponta os seguintes pontos focais em Direito Constitucional para carreiras policiais:

1. **Artigo 5º (Direitos e Garantias Fundamentais / Direitos e Deveres Individuais e Coletivos):**  
   - *Status:* Principal "campeão de cobrança".  
   - *Foco:* Direito à vida, liberdade, igualdade, segurança e propriedade; remédios constitucionais (*habeas corpus*, *habeas data*, mandado de segurança); garantias e inviolabilidade de domicílio (art. 5º, XI).

2. **Artigo 144 (Segurança Pública):**  
   - *Status:* Altíssima incidência na área de segurança.  
   - *Foco:* Atribuições e estrutura dos órgãos federais (PF, PRF, PFF), estaduais (Polícia Civil, Polícia Militar, Corpo de Bombeiros, Polícia Penal) e municipais (Guardas Municipais).

3. **Administração Pública e Militares (Artigos 37 a 43):**  
   - *Status:* Relevante para PMESP e cargos da PF.  
   - *Foco:* Princípios constitutivos (LIMPE: Legalidade, Impessoalidade, Moralidade, Publicidade e Eficiência), regras de investidura, acumulação de cargos e normas específicas dos militares estaduais.

4. **Defesa do Estado e das Instituições Democráticas:**  
   - *Status:* Recorrente em cenários de exceção.  
   - *Foco:* Regras, restrições de direitos e garantias durante intervenção federal, estado de defesa e estado de sítio.

---

### 🔤 2. Glossário de Termos Essenciais

- **Policiamento Ostensivo:** Atividade policial fardada e ostensiva visando à prevenção de delitos e à manutenção imediata da ordem pública.
- **Inviolabilidade de Domicílio:** Garantia constitucional (Art. 5º, XI) que protege a casa, permitindo ingresso apenas com consentimento, flagrante delito, desastre, para prestar socorro ou por determinação judicial (durante o dia).
- **Flagrante Delito:** Situação processual penal em que o agente está cometendo a infração, acabou de cometê-la, é perseguido logo após ou encontrado com instrumentos do crime.
- **Polícia Judiciária:** Função voltada à investigação de infrações penais e fornecimento de elementos para a ação penal (atribuição da Polícia Civil nos estados e da Polícia Federal na União).

---

### 🛠️ 3. Conjunto de Prompts Reutilizáveis para Revisão

```text
[PROMPT 1 - GERADOR DE QUESTÕES DA BANCA]
"Atue como uma banca examinadora de concurso militar. Elabore 5 questões inéditas de múltipla escolha sobre o Artigo 144 da CF/88, com 5 alternativas cada e gabarito comentado ao final."

[PROMPT 2 - SIMULADOR DE PEGADINHAS DE LEI SECA]
"Analise o texto da legislação no caderno e liste 5 trechos onde a banca examinadora costuma trocar palavras para confundir o candidato (ex: trocar 'exclusivamente' por 'preferencialmente')."

[PROMPT 3 - RESUMO EM TABELA COMPARATIVA]
"Crie uma tabela comparativa resumindo as diferenças de competência entre a Polícia Militar, Polícia Civil, Polícia Penal e Guarda Municipal, com base nas fontes do caderno."
