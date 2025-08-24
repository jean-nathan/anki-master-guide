# 🤖 Prompts para Claude - Anki Master

*Prompts prontos para criar cards de qualidade com Claude*

## 🎯 Como Usar Estes Prompts

1. **Copie** o prompt desejado
2. **Substitua** [TÓPICO] pelo seu tema específico
3. **Cole** no Claude e execute
4. **Revise** os cards gerados
5. **Ajuste** conforme necessário

---

## ⚡ **Prompt Universal - Geração de Cards**

### 📋 **Prompt Base**
```
Crie 10 cards de Anki sobre [TÓPICO] seguindo estas regras:

FORMATO:
Front: [Pergunta específica]
Back: [Resposta direta e clara]
Tags: [tecnologia, tipo, específico]

REGRAS:
1. Uma pergunta = uma resposta
2. Perguntas específicas e claras
3. Respostas diretas (máximo 2 linhas)
4. Tags em 3 níveis: tecnologia, tipo (conceito/sintaxe/exemplo), específico
5. Focar no essencial, não em detalhes obscuros

TIPOS DE CARDS:
- 3 cards de conceitos (o que é...)
- 3 cards de sintaxe (como fazer...)
- 4 cards de exemplos práticos

EXEMPLO:
Front: Como declarar uma função arrow em JavaScript?
Back: const nomeFuncao = (params) => { return resultado; }
Tags: javascript, sintaxe, funcao

Agora crie para: [TÓPICO]
```

---

## 💻 **Prompts Específicos por Tecnologia**

### 🟨 **JavaScript**
```
Crie 10 cards de Anki sobre [TÓPICO EM JAVASCRIPT] (ex: Array methods, Promises, etc).

FOQUE EM:
- Sintaxe exata dos métodos/conceitos
- Diferenças entre alternativas
- Casos de uso práticos
- Comportamentos importantes

INCLUA:
- 3 cards sobre "O que é..." (conceitos)
- 4 cards sobre "Como usar..." (sintaxe)
- 3 cards sobre "Quando usar..." (exemplos)

Use tags: javascript, [conceito/sintaxe/exemplo], [tópico específico]

Tópico: [TÓPICO]
```

### 🎨 **CSS**
```
Crie 10 cards de Anki sobre [TÓPICO EM CSS] (ex: Flexbox, Grid, Positioning).

FOQUE EM:
- Propriedades e valores exatos
- Efeitos visuais das propriedades
- Diferenças entre valores similares
- Casos práticos de uso

INCLUA:
- 2 cards conceituais (o que faz...)
- 5 cards de propriedades (qual propriedade para...)
- 3 cards de exemplos (como fazer... com CSS)

Use tags: css, [conceito/propriedade/exemplo], [tópico específico]

Tópico: [TÓPICO]
```

### ⚛️ **React**
```
Crie 10 cards de Anki sobre [TÓPICO EM REACT] (ex: Hooks, State Management, Components).

FOQUE EM:
- Sintaxe correta dos hooks/conceitos
- Regras e limitações importantes
- Padrões e anti-padrões
- Casos de uso específicos

INCLUA:
- 3 cards sobre conceitos (o que é/como funciona)
- 4 cards sobre sintaxe (como usar/implementar)
- 3 cards sobre boas práticas (quando/por que usar)

Use tags: react, [conceito/sintaxe/exemplo], [tópico específico]

Tópico: [TÓPICO]
```

---

## 🎯 **Prompts por Tipo de Conteúdo**

### 📚 **Para Estudar Documentação**
```
Estou lendo a documentação sobre [TÓPICO]. 

Cole aqui a parte da documentação que quer transformar em cards, então crie cards de Anki focando em:

1. Conceitos principais explicados
2. Sintaxe ou APIs mencionadas
3. Exemplos práticos mostrados
4. Diferenças ou comparações feitas

REGRAS:
- Cards específicos, não genéricos
- Uma informação por card
- Linguagem clara e direta
- Tags apropriadas por tecnologia

Documentação: [COLE AQUI]
```

### 🐛 **Para Erros/Debugging**
```
Crie 5 cards sobre erros comuns em [TECNOLOGIA] relacionados a [TÓPICO].

FORMATO DOS CARDS:
Front: Qual erro indica [SITUAÇÃO]?
Back: [Nome do erro] - [Como resolver]

EXEMPLO:
Front: Qual erro indica tentativa de acessar propriedade de null em JS?
Back: TypeError: Cannot read property 'X' of null - Verificar se objeto existe antes de acessar

Foque nos erros mais comuns que iniciantes enfrentam.

Tecnologia: [TECNOLOGIA]
Tópico: [TÓPICO]
```

### 🔄 **Para Comparações**
```
Crie 8 cards comparando [CONCEITO A] vs [CONCEITO B] em [TECNOLOGIA].

TIPOS DE CARDS:
- 2 cards sobre "Quando usar A vs B"
- 2 cards sobre "Diferenças principais entre A e B"
- 2 cards sobre "Vantagens de A sobre B"
- 2 cards sobre "Vantagens de B sobre A"

EXEMPLO:
Front: Quando usar map() vs forEach() em JavaScript?
Back: map() quando precisa de novo array; forEach() apenas para executar ação em cada elemento

Conceitos: [CONCEITO A] vs [CONCEITO B]
Tecnologia: [TECNOLOGIA]
```

---

## 📊 **Prompts de Qualidade e Revisão**

### 🔍 **Para Revisar Cards Existentes**
```
Analise estes cards de Anki e melhore conforme as regras:

REGRAS:
1. Pergunta específica = resposta específica
2. Máximo 2 linhas na resposta
3. Sem ambiguidade na pergunta
4. Tags úteis e consistentes

CARDS PARA REVISAR:
[COLE SEUS CARDS AQUI]

Para cada card, indique:
- ✅ GOOD: Se está bom
- 🔄 IMPROVE: Versão melhorada
- ❌ DELETE: Se é inútil/redundante
```

### 📈 **Para Preencher Lacunas**
```
Tenho [X] cards sobre [TÓPICO]. Analise e sugira 10 novos cards para preencher lacunas importantes.

MEUS CARDS ATUAIS:
[LISTE OS CARDS QUE JÁ TEM]

CRITÉRIOS PARA NOVOS CARDS:
- Complementem os existentes
- Cubram aspectos não abordados
- Sejam fundamentais para dominar o tópico
- Sigam o padrão de qualidade (específicos e claros)

Tópico: [TÓPICO]
```

---

## 🎨 **Prompts Especiais**

### 🧩 **Para Projetos Práticos**
```
Estou fazendo o projeto [NOME DO PROJETO] e quero criar cards sobre os conceitos que estou aprendendo.

DETALHES DO PROJETO:
[DESCREVA O PROJETO]

TECNOLOGIAS USADAS:
[LISTE AS TECNOLOGIAS]

Crie 15 cards focados em:
- Conceitos específicos que estou aplicando
- Soluções para problemas que encontrei
- Patterns e técnicas que usei
- Armadilhas que evitei

Cards devem ser práticos e aplicados, não teóricos.
```

### 🎓 **Para Preparação de Entrevistas**
```
Crie 12 cards para entrevista técnica sobre [ÁREA] nível [JÚNIOR/PLENO/SÊNIOR].

FOQUE EM:
- Perguntas que realmente são feitas em entrevistas
- Conceitos fundamentais que todo dev deve saber
- Diferenças e comparações importantes
- Exemplos práticos de código

FORMATO:
Front: [Pergunta típica de entrevista]
Back: [Resposta completa mas concisa]
Tags: entrevista, [tecnologia], [nível]

Área: [ÁREA]
Nível: [NÍVEL]
```

---

## 📝 **Templates Rápidos**

### ⚡ **Versão Minimalista**
```
10 cards sobre [TÓPICO]:
- Formato: Pergunta | Resposta | Tags
- Regra: 1 pergunta = 1 resposta específica
- Tags: tecnologia, tipo, específico
- Foque no essencial
```

### 🎯 **Versão Focada**
```
5 cards sobre [CONCEITO ESPECÍFICO]:
- Só o mais importante
- Perguntas diretas
- Respostas de 1 linha
- Para memorização rápida
```

---

## 💡 **Dicas para Usar os Prompts**

### 🔧 **Personalize Sempre**
- Substitua [TÓPICO] pelo seu tema específico
- Ajuste a quantidade de cards conforme necessário
- Adapte o nível de complexidade para seu conhecimento

### 🧪 **Teste e Ajuste**
- Gere 5 cards primeiro, teste no Anki
- Se a qualidade estiver boa, peça mais
- Refine o prompt baseado nos resultados

### 📊 **Combine Prompts**
- Use o prompt base + um específico
- Combine "geração" + "revisão"
- Misture diferentes tipos de conteúdo

### 🎯 **Monitore Qualidade**
- Cards devem ser específicos
- Respostas devem ser concisas
- Tags devem seguir seu sistema
- Teste sempre no Anki antes de adicionar muitos

---

## 📋 **Checklist de Qualidade**

Antes de adicionar os cards gerados pelo Claude:

- [ ] **Especificidade**: Cada pergunta tem uma resposta clara?
- [ ] **Concisão**: Respostas têm máximo 2 linhas?
- [ ] **Clareza**: Não há ambiguidade nas perguntas?
- [ ] **Tags**: Seguem meu sistema de 3 níveis?
- [ ] **Utilidade**: Vou realmente precisar dessa informação?
- [ ] **Teste**: Consigo responder em <15 segundos?

---

*💡 Lembre-se: Claude gera o conteúdo base, mas a qualidade final depende da sua revisão e ajustes!*
