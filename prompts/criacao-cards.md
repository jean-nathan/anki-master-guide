# 🤖 Prompts para Criação de Cards
*Transforme qualquer conteúdo em cards de alta qualidade*

## 🎯 Prompt Principal - Gerador de Cards

### 📝 Template Base

```
Você é um especialista em criação de cards Anki otimizados para memorização de longo prazo.

CONTEXTO:
Estou estudando [MATÉRIA/TEMA] e preciso de cards baseados no conteúdo abaixo.

CONTEÚDO:
[Cole aqui o texto/aula/artigo]

INSTRUÇÕES:
1. Crie cards seguindo os princípios de aprendizado ativo
2. Use o formato de pergunta-resposta clara e específica
3. Evite cards muito longos ou complexos
4. Inclua contexto suficiente na pergunta
5. Respostas devem ser concisas mas completas
6. Priorize conceitos-chave e aplicações práticas

FORMATO DE SAÍDA:
Para cada card, forneça:
---
**Frente:** [Pergunta clara e específica]
**Verso:** [Resposta concisa com contexto essencial]
**Tags:** [categoria, subcategoria, dificuldade]
---

NÚMERO DE CARDS: [especifique: 10, 20, etc.]
NÍVEL DE DIFICULDADE: [básico, intermediário, avançado]
FOCO: [conceitos, aplicações, definições, etc.]
```

## 🎓 Prompts Especializados por Tipo

### 📚 Para Conceitos Teóricos

```
Foco em CONCEITOS TEÓRICOS:

CONTEXTO: Estudando [MATÉRIA] - conceitos fundamentais
CONTEÚDO: [seu texto aqui]

CRIAR CARDS PARA:
- Definições precisas
- Características principais
- Diferenças entre conceitos similares
- Exemplos práticos
- Aplicações no mundo real

FORMATO ESPECÍFICO:
---
**Frente:** O que é [conceito]? Cite 3 características principais.
**Verso:** [Definição] + 3 características: 1) X, 2) Y, 3) Z
**Tags:** conceitos, [materia], [topico]
---

Número de cards: 15-20
Priorize: Definições claras e exemplos memoráveis
```

### 🔢 Para Fórmulas e Cálculos

```
Foco em FÓRMULAS E CÁLCULOS:

CONTEXTO: Estudando [MATÉRIA] - fórmulas e aplicações práticas
CONTEÚDO: [suas fórmulas/exercícios aqui]

CRIAR CARDS PARA:
- Fórmula com nome
- Significado de cada variável
- Quando aplicar cada fórmula
- Exercícios numéricos simples
- Transformações e derivações

FORMATO ESPECÍFICO:
---
**Frente:** Qual a fórmula para calcular [conceito]?
**Verso:** [Nome] = [fórmula] onde: X = [definição], Y = [definição]
**Tags:** formulas, [materia], [topico]
---

IMPORTANTE: Inclua sempre unidades e condições de aplicação
Número de cards: 10-15 por fórmula complexa
```

### 🧪 Para Processos e Procedimentos

```
Foco em PROCESSOS E PROCEDIMENTOS:

CONTEXTO: Estudando [MATÉRIA] - processos e metodologias
CONTEÚDO: [seu processo/procedimento aqui]

CRIAR CARDS PARA:
- Etapas sequenciais numeradas
- Pré-requisitos importantes
- Resultados esperados
- Erros comuns a evitar
- Variações do processo

FORMATO ESPECÍFICO:
---
**Frente:** Quais os 5 passos para [processo]?
**Verso:** 1) [passo] 2) [passo] 3) [passo] 4) [passo] 5) [passo]
**Tags:** processos, [materia], [topico]
---

CRIAR TAMBÉM cards individuais para cada passo complexo
Número de cards: 8-12 por processo
```

### 📊 Para Dados e Estatísticas

```
Foco em DADOS E ESTATÍSTICAS:

CONTEXTO: Estudando [MATÉRIA] - dados, números e estatísticas
CONTEÚDO: [seus dados/estatísticas aqui]

CRIAR CARDS PARA:
- Números específicos importantes
- Comparações e rankings
- Tendências temporais
- Correlações relevantes
- Interpretação de dados

FORMATO ESPECÍFICO:
---
**Frente:** Qual o valor de [métrica] em [contexto/ano]?
**Verso:** [Número] [unidade] - [contexto relevante ou comparação]
**Tags:** dados, estatisticas, [materia]
---

IMPORTANTE: Adicione contexto para números não serem esquecidos
Evite números muito similares no mesmo deck
```

### 🌍 Para Idiomas

```
Foco em APRENDIZADO DE IDIOMAS:

CONTEXTO: Estudando [IDIOMA] - vocabulário e gramática
CONTEÚDO: [texto/diálogo/lista de palavras]

CRIAR CARDS PARA:
- Vocabulário com contexto
- Conjugações verbais
- Expressões idiomáticas
- Estruturas gramaticais
- Frases úteis do dia a dia

FORMATO ESPECÍFICO:
---
**Frente:** Como se diz "[frase/palavra em português]" em [idioma]?
**Verso:** [tradução] | Exemplo: [frase com contexto]
**Tags:** [idioma], vocabulario, [nivel]
---

CRIAR TAMBÉM cards reversos (idioma → português)
Sempre incluir contexto de uso e pronúncia se necessário
```

## 🎯 Prompts para Situações Específicas

### 📖 Prompt para Livros Técnicos

```
ESPECIALISTA EM LIVROS TÉCNICOS:

Estou estudando o livro "[TÍTULO]" de [AUTOR].

CAPÍTULO/SEÇÃO: [nome do capítulo]
PÁGINAS: [X a Y]

CONTEÚDO PRINCIPAL:
[Cole o texto do capítulo ou suas anotações]

OBJETIVOS DE APRENDIZADO:
- [objetivo 1]
- [objetivo 2]
- [objetivo 3]

INSTRUÇÕES ESPECÍFICAS:
1. Foque nos conceitos que o autor enfatiza como cruciais
2. Inclua citações importantes (com página)
3. Conecte conceitos com capítulos anteriores quando relevante
4. Crie cards que testem aplicação prática dos conceitos
5. Identifique termos técnicos específicos da área

FORMATO EXPANDIDO:
---
**Frente:** [Pergunta conceitual ou aplicação]
**Verso:** [Resposta] | Ref: p.[página] | Ver também: [conceitos relacionados]
**Tags:** [livro], [capitulo], [dificuldade]
---

Meta: 20-25 cards por capítulo
Prioridade: Conceitos únicos do autor e aplicações práticas
```

### 🎥 Prompt para Vídeo-Aulas

```
ESPECIALISTA EM VÍDEO-AULAS:

Acabei de assistir a aula "[TÍTULO DA AULA]" de [INSTRUTOR/CURSO].
DURAÇÃO: [X minutos]
PLATAFORMA: [Udemy/YouTube/etc.]

MINHAS ANOTAÇÕES:
[Cole suas anotações timestampadas]

PONTOS PRINCIPAIS ABORDADOS:
- [ponto 1 - minuto X]
- [ponto 2 - minuto Y]
- [ponto 3 - minuto Z]

INSTRUÇÕES ESPECÍFICAS:
1. Transforme conceitos visuais em descrições textuais claras
2. Inclua timestamp para referência futura
3. Foque em exemplos práticos demonstrados
4. Capture insights únicos do instrutor
5. Crie cards para exercícios resolvidos

FORMATO COM TIMESTAMP:
---
**Frente:** [Conceito/pergunta baseada na explicação]
**Verso:** [Resposta] | 📺 [min:seg] - [insight adicional do instrutor]
**Tags:** [curso], [aula-numero], [topico]
---

IMPORTANTE: Se houver códigos ou diagramas, descreva-os textualmente
Meta: 15-20 cards por hora de vídeo
```

### 📋 Prompt para Resumos e Artigos

```
ESPECIALISTA EM ARTIGOS E PAPERS:

Estou estudando o artigo/resumo:
TÍTULO: "[título completo]"
AUTOR(ES): [nomes]
ANO: [ano]
FONTE: [revista/site]

RESUMO/ABSTRACT:
[cole o resumo aqui]

PONTOS PRINCIPAIS:
[cole os pontos principais ou o artigo completo]

INSTRUÇÕES ESPECÍFICAS:
1. Extraia metodologia se for paper científico
2. Identifique conclusões-chave e findings
3. Capture estatísticas e dados importantes
4. Inclua limitações e estudos futuros mencionados
5. Conecte com conhecimento existente na área

FORMATO ACADÊMICO:
---
**Frente:** Segundo [Autor, Ano], qual [pergunta específica]?
**Verso:** [Resposta baseada no paper] | Finding: [estatística relevante]
**Tags:** [area], [autor], [ano], papers
---

FOCO: Transformar conhecimento passivo em ativo
Meta: 12-18 cards por artigo de 10-15 páginas
```

## 🛠️ Prompts de Otimização

### 🔧 Melhorando Cards Existentes

```
OTIMIZADOR DE CARDS ANKI:

Tenho estes cards que não estão funcionando bem (taxa de acerto baixa ou tempo muito alto):

CARD PROBLEMÁTICO 1:
Frente: [sua pergunta atual]
Verso: [sua resposta atual]
Problema: [muito longo, confuso, ambíguo, etc.]

CARD PROBLEMÁTICO 2:
[repetir formato]

INSTRUÇÕES DE OTIMIZAÇÃO:
1. Simplifique perguntas ambíguas
2. Reduza respostas muito longas
3. Adicione contexto onde necessário
4. Quebre cards complexos em múltiplos simples
5. Torne mais específico e testável

FORNEÇA:
- Diagnóstico do problema
- Versão otimizada do card
- Explicação da melhoria feita
- Sugestão de cards adicionais se quebrou o original

FORMATO:
❌ PROBLEMA: [identificação do issue]
✅ SOLUÇÃO: [card otimizado]
💡 MELHORIA: [explicação da mudança]
```

### 📊 Analisando Performance de Cards

```
ANALISTA DE PERFORMANCE DE CARDS:

Meus dados de estudo dos últimos 30 dias:

CARDS COM BAIXA PERFORMANCE:
[liste cards com taxa de acerto <70%]

CARDS MUITO LENTOS:
[liste cards que demoram >45s para responder]

CARDS COM MUITOS LAPSES:
[liste cards resetados 3+ vezes]

ANÁLISE SOLICITADA:
1. Identifique padrões nos cards problemáticos
2. Sugira reformulações específicas
3. Recomende divisão de cards complexos
4. Proponha cards adicionais para reforçar conceitos
5. Identifique possíveis gaps de conhecimento

PRIORIZE:
- Cards de conceitos fundamentais
- Cards que são pré-requisitos para outros
- Cards frequentemente confundidos entre si

FORMATO DE RESPOSTA:
🎯 PADRÃO IDENTIFICADO: [descrição]
🔧 AÇÕES RECOMENDADAS: [lista numerada]
📈 RESULTADOS ESPERADOS: [melhorias previstas]
```

## 🎯 Prompts por Nível de Dificuldade

### 🟢 Nível 1 - Iniciante

```
GERADOR PARA INICIANTES:

Sou novo no Anki e preciso de cards simples e diretos.

CONTEÚDO: [seu material]

CARACTERÍSTICAS DOS CARDS SOLICITADOS:
- Perguntas claras e objetivas
- Respostas curtas (máx. 2 linhas)
- Conceitos básicos e fundamentais
- Exemplos simples e concretos
- Evitar jargões técnicos complexos

FORMATO INICIANTE:
---
**Frente:** [Pergunta simples e direta]
**Verso:** [Resposta concisa] + [Exemplo prático simples]
**Tags:** basico, [materia]
---

FOQUE EM: Definições claras e exemplos do dia a dia
EVITE: Conceitos abstratos e múltiplas informações por card
```

### 🟡 Nível 2 - Intermediário

```
GERADOR PARA INTERMEDIÁRIOS:

Já uso Anki há alguns meses e posso lidar com conceitos mais complexos.

CONTEÚDO: [seu material]

CARACTERÍSTICAS DOS CARDS SOLICITADOS:
- Conexões entre conceitos
- Aplicações práticas e casos de uso
- Comparações e contrastes
- Análise de cenários
- Alguns termos técnicos apropriados

FORMATO INTERMEDIÁRIO:
---
**Frente:** [Pergunta que conecta conceitos ou cenário aplicado]
**Verso:** [Resposta estruturada] + [Quando aplicar] + [Cuidados]
**Tags:** intermediario, [materia], [aplicacao]
---

INCLUA: Nuances importantes e exceções às regras
BALANCE: Complexidade vs. clareza
```

### 🔴 Nível 3 - Avançado

```
GERADOR PARA AVANÇADOS:

Sou expert na matéria e preciso de cards para consolidar conhecimento profundo.

CONTEÚDO: [seu material]

CARACTERÍSTICAS DOS CARDS SOLICITADOS:
- Análise crítica e comparações complexas
- Integração de múltiplos conceitos
- Casos edge e exceções
- Implicações avançadas
- Terminologia técnica precisa

FORMATO AVANÇADO:
---
**Frente:** [Cenário complexo ou análise crítica necessária]
**Verso:** [Análise estruturada] + [Implicações] + [Limitações]
**Tags:** avancado, [materia], [especializacao]
---

FOQUE EM: Pensamento crítico e aplicações especializadas
DESAFIE: Conhecimento profundo e connections não óbvias
```

## 💡 Dicas de Uso dos Prompts

### 📝 Como Personalizar

1. **Substitua os colchetes** por seu conteúdo específico
2. **Ajuste o número de cards** baseado no material
3. **Modifique tags** para sua organização
4. **Adapte o formato** ao seu estilo de estudo

### 🎯 Melhores Práticas

- **Teste diferentes prompts** para o mesmo conteúdo
- **Combine prompts** para resultados mais ricos
- **Refine baseado nos resultados** do Claude
- **Documente quais funcionam melhor** para você

### ⚡ Prompts Rápidos

**Para conteúdo simples:**
```
Crie 10 cards Anki sobre [tópico]: [conteúdo]
Formato: Pergunta-resposta simples
Tags: [sua-materia]
```

**Para revisão rápida:**
```
Transforme estes pontos em cards Anki:
[lista de tópicos]
Mantenha simples e direto.
```

---

## 🚀 Próximo Passo

Escolha o prompt mais adequado ao seu material e nível, personalize com seu conteúdo, e comece a gerar cards de alta qualidade com o Claude!

**Dica:** Comece com o **Prompt Principal** e evolua para os especializados conforme suas necessidades.

---

*💡 Lembre-se: Bons cards são a base de tudo no Anki. Invista tempo na criação para colher resultados duradouros.*
