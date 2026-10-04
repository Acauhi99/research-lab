# Research Lab

## Objetivo

Este repositório registra minha preparação para uma futura candidatura ao **Mestrado em Ciência da Computação (PPGCC/UFJF)**. Vou usá-lo para ler e comparar trabalhos, formular perguntas de pesquisa e documentar pequenos experimentos. O objetivo é chegar a um projeto de mestrado com uma pergunta clara e um método consistente.

## Contexto

Sou formado em **Análise e Desenvolvimento de Sistemas** e pretendo seguir carreira acadêmica, começando pelo mestrado e, depois, pelo doutorado.

Em **2027**, pretendo:

- disciplinas isoladas no PPGCC/UFJF;
- aproximação com professores e grupos de pesquisa;
- leitura de dissertações e artigos;
- desenvolvimento de projetos experimentais;
- escolha gradual de uma linha de pesquisa.

Planejo me candidatar para ingresso em **2028**. Considerarei uma oportunidade anterior se o calendário do programa permitir.

---

## Áreas de interesse iniciais

Neste momento, três eixos se destacam.

### 1. Engenharia de Software / Sistemas Adaptativos

Interesses possíveis:

- arquitetura de software;
- manutenção e evolução;
- desenvolvimento distribuído;
- sistemas adaptativos e autônomos;
- qualidade de software;
- decisão arquitetural;
- integração de dados e sistemas.

### 2. Sistemas Distribuídos / Cloud / Edge

Interesses possíveis:

- cloud computing;
- edge/fog computing;
- sistemas distribuídos;
- autoscaling;
- observabilidade;
- desempenho;
- IoT;
- alocação e otimização de recursos.

### 3. IA aplicada à Engenharia de Software

Interesses possíveis:

- LLMs aplicados ao desenvolvimento;
- recomendação de desenvolvedores e especialistas;
- análise de issues, commits e pull requests;
- revisão automática de código;
- detecção e previsão de defeitos;
- recuperação de conhecimento em repositórios;
- agentes aplicados ao ciclo de desenvolvimento.

Os eixos podem se cruzar. As leituras devem ajudar a escolher quais deles vale aprofundar.

---

# Fase 1 — Exploração por dissertações

Antes de escolher um projeto, quero conhecer **problemas já pesquisados no PPGCC/UFJF**.

Não é necessário ler cada dissertação integralmente na primeira passagem.

## Protocolo de primeira leitura

Para cada dissertação:

1. ler o resumo;
2. ler a introdução;
3. localizar o problema e os objetivos;
4. ler a conclusão;
5. registrar o que chamou atenção;
6. registrar o que não ficou claro;
7. anotar termos e referências que parecem importantes;
8. decidir se o tipo de problema desperta vontade de investigar mais.

A pergunta desta fase é: eu teria curiosidade de investigar esse tipo de problema por meses? Não é necessário entender toda a metodologia na primeira leitura.

---

## Reading Set inicial

### Eixo A — Engenharia de Software / Sistemas Adaptativos

#### A1. A model-driven methodology to support runtime assurance of open and adaptive systems

**Autor:** Luis Felipe de Almeida Nascimento  
**Orientador:** André Luiz de Oliveira  
**Coorientadora:** Regina Maria Maciel Braga  
**Ano:** 2024

Tema central: garantia de propriedades em tempo de execução de sistemas abertos e adaptativos, com abordagem orientada a modelos.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/17790

Perguntas para a leitura:

- O que torna um sistema adaptativo difícil de garantir?
- Qual problema é resolvido em runtime?
- Qual é o papel da modelagem?
- Eu me interesso mais pelo desenho da arquitetura ou pela verificação do comportamento?

#### A2. An IoT Architecture for Decision Support System in Precision Livestock

**Autor:** Jonas Silva Gomes  
**Orientador:** José Maria Nazar David  
**Coorientadora:** Regina Maria Maciel Braga  
**Ano:** 2023

Tema central: arquitetura de software auto-adaptativa que combina IoT, modelos semânticos e machine learning para apoio à decisão.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/15455

Perguntas para a leitura:

- Onde termina “construção de sistema” e começa “problema de pesquisa”?
- Como uma arquitetura é avaliada academicamente?
- Como IA e arquitetura de software aparecem juntas?
- O domínio de aplicação me importa ou o problema arquitetural é o que realmente chama atenção?

---

### Eixo B — Sistemas Distribuídos / Cloud / Edge

#### B1. Um estudo da arquitetura Edge-Fog-Cloud com foco na otimização distribuída do processamento e na redução da latência

**Autor:** Thiago Goldoni Thomé  
**Orientador:** Mario Antonio Ribeiro Dantas  
**Coorientador:** Victor Ströele de Andrade Menezes  
**Ano:** 2024

Tema central: avaliação de diferentes configurações Edge–Fog–Cloud e seus efeitos sobre latência e capacidade de processamento.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/17261

Perguntas para a leitura:

- Quais variáveis do sistema foram manipuladas?
- Como desempenho e latência foram medidos?
- O que caracteriza o experimento?
- Eu gostaria de montar e medir sistemas desse tipo?

#### B2. Um estudo experimental streaming-fog-cloud

**Autor:** Lucas Otaviano Larcher  
**Orientador:** Victor Ströele de Andrade Menezes  
**Coorientadores:** Mario Antonio Ribeiro Dantas e Felipe Schneider Costa  
**Ano:** 2023

Tema central: processamento de streaming em ambientes Fog/Cloud, consumo de recursos, capacidade computacional e conectividade.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/15339

Perguntas para a leitura:

- Como o trabalho transforma uma questão de infraestrutura em experimento?
- Quais métricas são utilizadas?
- Como são comparadas configurações diferentes?
- O processo de benchmarking e medição me interessa?

---

### Eixo C — IA aplicada à Engenharia de Software

#### C1. DevFinder: an architecture for recommending software development specialists with industry-specific expertise in desired technologies

**Autor:** Vitor Queiroz de Campos  
**Orientador:** José Maria Nazar David  
**Coorientador:** Victor Ströele de Andrade Menezes  
**Ano:** 2024

Tema central: recomendação de especialistas em desenvolvimento de software com base em conhecimento técnico e experiência.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/17419

Perguntas para a leitura:

- Como “quem é o melhor desenvolvedor para esta tarefa?” vira uma pergunta computacional?
- De onde vêm os dados?
- Como é medida a qualidade de uma recomendação?
- Eu gostaria de trabalhar com dados extraídos de atividade de desenvolvimento?

#### C2. Recomendação de revisores de código no desenvolvimento distribuído de software

**Autor:** Vinicius Junqueira Schettino  
**Orientador:** Victor Ströele de Andrade Menezes  
**Coorientador:** Marco Antônio Pereira Araújo  
**Ano:** 2019

Tema central: recomendação de revisores utilizando dados históricos de repositórios open source no GitHub e relações entre desenvolvedores.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/12138

Perguntas para a leitura:

- Como dados do GitHub são transformados em evidência?
- Que heurísticas ou modelos são comparados?
- Como a recomendação é avaliada?
- Eu teria vontade de reproduzir ou atualizar esse estudo usando técnicas atuais?

---

## Leitura complementar / ponte

### An architectural framework for expert identification based on social network analysis

**Autor:** Tales Lopes Silva  
**Orientador:** Victor Ströele de Andrade Menezes  
**Coorientadora:** Regina Maria Maciel Braga  
**Ano:** 2022

Tema central: identificação de especialistas em Desenvolvimento Global de Software usando redes sociais, análise semântica, machine learning e dados do GitHub.

Repositório:

https://repositorio.ufjf.br/jspui/handle/ufjf/15518

Leia este trabalho se o eixo de IA aplicada a software estiver entre os favoritos. Ele combina Engenharia de Software, análise de dados, machine learning, ontologias e recomendação.

---

# Registro das leituras

Para cada trabalho, criar uma nota semelhante a:

```text
reading-notes/
└── autor-ano-titulo-curto.md
```

Template sugerido:

```markdown
# Título

## Referência

## Problema investigado

## Por que esse problema importa?

## Solução / abordagem proposta

## Como foi avaliada?

## O que achei interessante?

## O que não entendi?

## Conceitos que preciso estudar

## Trabalhos citados que parecem importantes

## Novas perguntas que surgiram

## Interesse pessoal

Nota de 0 a 5:

### Eu pesquisaria algo parecido?

### Eu gostaria de construir sistemas desse tipo?

### Eu gostaria de avaliar experimentalmente esse tipo de sistema?
```

---

# Decisão após as leituras

Depois das seis leituras principais, comparar os três eixos.

Ao final, quero conseguir dizer:

- quais tipos de problema mais despertaram curiosidade;
- quais métodos pareceram interessantes;
- se há preferência por software/arquitetura, infraestrutura/distribuição ou dados/IA;
- quais professores aparecem repetidamente nos trabalhos de maior interesse;
- quais conceitos merecem aprofundamento.

Só depois dessa comparação será escolhido o primeiro **Projeto Zero**.

---

# Fase 2 — Projeto Zero

A meta é passar de projetos focados apenas em implementação para projetos guiados por uma pergunta:

> Qual pergunta o experimento tenta responder?

Cada projeto deve, na medida do possível, registrar:

1. problema ou pergunta;
2. hipótese ou expectativa inicial;
3. trabalhos e referências relacionados;
4. desenho do experimento;
5. implementação;
6. dados coletados;
7. métricas;
8. resultados;
9. limitações;
10. conclusões.

Resultados negativos também fazem parte do processo.

## Estrutura sugerida para projetos

```text
projects/<nome-do-projeto>/
├── README.md
├── research/
│   ├── question.md
│   ├── related-work.md
│   └── experiment.md
├── src/
├── experiments/
├── data/
├── results/
└── conclusions.md
```

## Projetos candidatos — ainda não escolhidos

### IA aplicada a repositórios de software

Possível pergunta:

> Até que ponto diferentes abordagens conseguem recomendar o desenvolvedor mais adequado para resolver uma issue?

### Autoscaling e sistemas distribuídos

Possível pergunta:

> Qual estratégia de autoscaling mantém melhor latência sob diferentes padrões de carga sem aumentar excessivamente o consumo de recursos?

### Edge–Cloud

Possível pergunta:

> Em quais condições mover processamento da cloud para a edge reduz latência sem aumentar excessivamente o uso de recursos?

São opções de exploração, não compromissos. A escolha fica para depois do ciclo inicial de leituras.

---

# Roadmap

## Outubro–dezembro de 2026

1. Ler as seis dissertações do Reading Set em modo exploratório.
2. Registrar notas de cada trabalho.
3. Comparar os três eixos.
4. Escolher uma ou duas subáreas provisórias.
5. Mapear os professores associados aos trabalhos de maior interesse.
6. Só então escolher e iniciar o Projeto Zero.

## 2027

- acompanhar calendário e oferta de disciplinas do PPGCC/UFJF;
- cursar pelo menos uma disciplina isolada;
- conhecer professores e grupos de pesquisa;
- aprofundar literatura da área escolhida;
- aprender metodologia científica e experimental;
- revisar criticamente o Projeto Zero;
- executar projetos mais rigorosos;
- identificar possíveis orientadores;
- delimitar gradualmente um problema de pesquisa;
- preparar candidatura.

## Final de 2027 / início de 2028

- definir tema e problema de pesquisa;
- preparar projeto para o processo seletivo;
- organizar Currículo Lattes e documentação;
- obter referências acadêmicas, se exigidas;
- participar do processo seletivo do PPGCC/UFJF.

---

Este repositório registra meu processo de aprendizagem em pesquisa.
