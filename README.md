# Repositório de Análises sobre Ética e Inteligência Artificial na Educação

Este repositório reúne os materiais produzidos no contexto de uma **revisão da literatura** que investigou **a presença, o foco e a profundidade da discussão ética** sobre o uso da Inteligência Artificial (IA) no campo da educação brasileira. A análise foi conduzida com base em publicações disponíveis na plataforma **SBC OpenLib (SOL)**, considerando o período de 2020 a 2025.

---

## Objetivo da Revisão

O estudo teve como objetivo identificar e analisar **como a dimensão ética tem sido abordada** nas publicações acadêmicas que tratam da aplicação da IA na educação. A partir dessa análise, buscou-se compreender:

* Quais aspectos éticos são discutidos (privacidade, viés, equidade, regulação, desinformação, etc.);
* Qual o nível de profundidade com que esses temas são tratados;
* Em que medida a ética é tratada como foco central, secundário ou ausente.

---

## Recorte da Pesquisa

* **Fonte**: [SBC OpenLib (SOL)](https://sol.sbc.org.br/) — Biblioteca Digital da Sociedade Brasileira de Computação
* **Período analisado**: de **1º de janeiro de 2020** até **31 de maio de 2025**
* **Área de interesse**: Interseção entre Ética, Inteligência Artificial e Educação

---

## Estratégia de Busca Utilizada

Para localizar os trabalhos relevantes, foi utilizada a seguinte **string de busca**, aplicada aos campos de **título, resumo, palavras-chave e corpo do texto**:

```text
(ethi* OR étic*) AND educa* AND ("intelig* artificial" OR "artificial intelligence" OR I.A OR IA)
```

Essa expressão buscou capturar variações linguísticas e conceituais nos dois idiomas predominantes (português e inglês), envolvendo os seguintes termos:

* **Ética**: ética, ético, ethics, ethical
* **Educação**: educação, educacional, education
* **IA**: inteligência artificial, IA, I.A., artificial intelligence

---

## Processo de Triagem e Classificação

* **91** publicações identificadas inicialmente
* **29** artigos únicos após eliminação de duplicatas
* Cada artigo foi **avaliado manualmente** quanto ao seu foco ético, segundo três categorias:

  * **Sim**: foco principal na discussão ética (6 artigos)
  * **Sim, parcialmente**: abordagem ética transversal ou secundária (22 artigos)
  * **Não**: ausência de discussão ética relevante (1 artigo)

---

## Critérios de Análise

Cada artigo analisado foi estruturado com base nos seguintes critérios:

| Critério                            | Descrição                                                               |
| ----------------------------------- | ----------------------------------------------------------------------- |
| **Critério Avaliado**               | O texto tem como foco principal a discussão ética sobre IA na educação? |
| **Resultado da Análise**            | Sim / Sim, parcialmente / Não — com justificativa clara                 |
| **1. Foco Geral do Texto**          | Objetivo principal e abordagem do estudo                                |
| **2. Tratamento da Dimensão Ética** | Presença, profundidade e eventuais limitações                           |
| **3. Trechos Relevantes**           | Citações que evidenciam ou ilustram a abordagem ética                   |
| **4. Classificação Final**          | Tipo de foco + justificativa sintética                                  |
| **Conclusão**                       | Síntese avaliativa em 2 ou 3 frases                                     |

---

## Estrutura do Repositório

Para cada artigo analisado, disponibilizamos:

* O **PDF original** da publicação (em `/data/classificados/ID.pdf`)
* Um arquivo `.md` com a análise detalhada (em `/review/id_ID.md`)

---

## Acesso às Análises

## Tabela de Análises por Artigo

| ID | Título | Evento | Análise (.md) | PDF Original |
|----|--------|--------|----------------|----------------|
| 1 | Oficina de Pensamento para Inteligência Artificial: Um Relato do Projeto Corte de Lovelace | SBIE | [id_1.md](review/id_1.md) | [1.pdf](data/classificados/1.pdf) |
| 2 | Educação midiática como alternativa a desinformação e a deepfake | Ética em IA | [id_2.md](review/id_2.md) | [2.pdf](data/classificados/2.pdf) |
| 3 | Construção do conhecimento por meio de deepfake: desafios éticos da inteligência artificial na educação | Ética em IA | [id_3.md](review/id_3.md) | [3.pdf](data/classificados/3.pdf) |
| 4 | Ensinando Ética em IA com um Jogo de Cartas... | WEI | [id_4.md](review/id_4.md) | [4.pdf](data/classificados/4.pdf) |
| 5 | Educação Climática 4.0: Como Potencializar o Papel dos Professores com PLN e KG? | Ética em IA | [id_5.md](review/id_5.md) | [5.pdf](data/classificados/5.pdf) |
| 6 | IA como aliada no processo de ensino na Engenharia Civil da UFF | Ética em IA | [id_6.md](review/id_6.md) | [6.pdf](data/classificados/6.pdf) |
| 7 | Explorando Affordances do ChatGPT no Ensino Superior Brasileiro | Ética em IA | [id_7.md](review/id_7.md) | [7.pdf](data/classificados/7.pdf) |
| 8 | Pensamento Computacional e Educação em IA na Educação STEAM | CBIE (Estendido) | [id_8.md](review/id_8.md) | [8.pdf](data/classificados/8.pdf) |
| 9 | Desafios e Aplicabilidades da IA Generativa na Educação | Ética em IA | [id_9.md](review/id_9.md) | [9.pdf](data/classificados/9.pdf) |
| 10 | Percepções da IA Generativa na Educação: estudo entre universitários | ERI-MT | [id_10.md](review/id_10.md) | [10.pdf](data/classificados/10.pdf) |
| 11 | Potencial das IAs Generativas no Ensino de Matemática | WETIE | [id_11.md](review/id_11.md) | [11.pdf](data/classificados/11.pdf) |
| 12 | Uso de Técnicas de IA num Sistema de Mesa Tangível | WIE | [id_12.md](review/id_12.md) | [12.pdf](data/classificados/12.pdf) |
| 13 | Responsible Use of LLM Models for Labor Market Foresight | Ética em IA | [id_13.md](review/id_13.md) | [13.pdf](data/classificados/13.pdf) |
| 14 | Por uma formação ética não prescritiva | Ética em IA | [id_14.md](review/id_14.md) | [14.pdf](data/classificados/14.pdf) |
| 15 | Entre Algoritmos e Emoções | WEI | [id_15.md](review/id_15.md) | [15.pdf](data/classificados/15.pdf) |
| 16 | Impactos da IA em cursos de graduação em computação | EDUCOMP | [id_16.md](review/id_16.md) | [16.pdf](data/classificados/16.pdf) |
| 17 | Perceptions of Faculty on Guidelines for Text Gen AI | Ética em IA | [id_17.md](review/id_17.md) | [17.pdf](data/classificados/17.pdf) |
| 18 | Ética e IA na Sala de Aula: Experiência com o Jogo AI-Audit | WEI | [id_18.md](review/id_18.md) | [18.pdf](data/classificados/18.pdf) |
| 19 | Cibersegurança, sociedade e futuro | Computação Brasil | [id_19.md](review/id_19.md) | [19.pdf](data/classificados/19.pdf) |
| 20 | Modelo Matemático para ECG Sintético com Hardware de Baixo Custo | SBCAS | [id_20.md](review/id_20.md) | [20.pdf](data/classificados/20.pdf) |
| 21 | Speculative Design com IA: estudo interdisciplinar | SBSI | [id_21.md](review/id_21.md) | [21.pdf](data/classificados/21.pdf) |
| 22 | Como Maximizar o Uso da IA Generativa na Educação? | URCA | [id_22.md](review/id_22.md) | [22.pdf](data/classificados/22.pdf) |
| 23 | Preparando Estudantes para a Era da IA (UNESCO Framework) | WEI | [id_23.md](review/id_23.md) | [23.pdf](data/classificados/23.pdf) |
| 24 | Educational Dimensions in the Age of GenAI | WEI | [id_24.md](review/id_24.md) | [24.pdf](data/classificados/24.pdf) |
| 25 | Design Ético na Educação Básica | SBSI (Estendido) | [id_25.md](review/id_25.md) | [25.pdf](data/classificados/25.pdf) |
| 26 | Learning Analytics explicáveis e justos na graduação | SBIE | [id_26.md](review/id_26.md) | [26.pdf](data/classificados/26.pdf) |
| 27 | Comunicação e Democracia na Era Digital | SemiEdu | [id_27.md](review/id_27.md) | [27.pdf](data/classificados/27.pdf) |
| 28 | Sistemas de Recomendação e Etnoeducação | WICS | [id_28.md](review/id_28.md) | [28.pdf](data/classificados/28.pdf) |
| 29 | Assistente Virtual Inteligente (IFBot) com RAG | WICS | [id_29.md](review/id_29.md) | [29.pdf](data/classificados/29.pdf) |


---

> **Nota**: Este `README.md` é apenas um resumo do trabalho que fizemos com alguns detalhes das pesquisas e caminhos.

