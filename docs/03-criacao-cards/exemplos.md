# 🎨 20+ Exemplos de Cards Prontos

*Cards testados e aprovados para programação front-end*

## 🎯 Como Usar Este Arquivo

1. **Copie os exemplos** que fazem sentido para você
2. **Adapte** para seu contexto específico  
3. **Teste** antes de adicionar ao seu deck
4. **Use como template** para criar cards similares

---

## 💻 **JavaScript - Fundamentos**

### 🧠 **Conceitos Básicos**

```
CARD 1:
Front: O que é uma variável em JavaScript?
Back: Container para armazenar dados que podem ser alterados durante a execução do programa.
Tags: javascript, conceitos, variaveis
```

```
CARD 2:
Front: O que é hoisting em JavaScript?
Back: Comportamento onde declarações de var e function são "movidas" para o topo do escopo antes da execução.
Tags: javascript, conceitos, hoisting
```

```
CARD 3:
Front: Qual a diferença entre null e undefined em JavaScript?
Back: undefined = variável declarada mas sem valor; null = variável com valor "vazio" intencionalmente.
Tags: javascript, conceitos, tipos
```

### 🔧 **Sintaxe Essencial**

```
CARD 4:
Front: Como declarar uma função arrow em JavaScript?
Back: const nomeFuncao = (parametros) => { return resultado; }
Tags: javascript, sintaxe, funcoes, arrow
```

```
CARD 5:
Front: Como criar um array vazio em JavaScript?
Back: const array = []; ou const array = new Array();
Tags: javascript, sintaxe, arrays
```

```
CARD 6:
Front: Como desestruturar um array em JavaScript?
Back: const [primeiro, segundo] = array;
Tags: javascript, sintaxe, destructuring
```

### 💡 **Métodos Importantes**

```
CARD 7:
Front: Qual método de array retorna um novo array com elementos transformados?
Back: map() - executa função em cada elemento e retorna novo array
Tags: javascript, arrays, map
```

```
CARD 8:
Front: Como filtrar elementos de um array em JavaScript?
Back: array.filter(elemento => condicao) - retorna novo array com elementos que passam no teste
Tags: javascript, arrays, filter
```

```
CARD 9:
Front: Como somar todos os valores de um array numérico?
Back: array.reduce((acc, valor) => acc + valor, 0)
Tags: javascript, arrays, reduce
```

---

## 🎨 **CSS - Essenciais**

### 📐 **Layout Básico**

```
CARD 10:
Front: Como centralizar texto horizontalmente em CSS?
Back: text-align: center;
Tags: css, texto, alinhamento
```

```
CARD 11:
Front: Como centralizar uma div horizontalmente com margin?
Back: margin: 0 auto; (div deve ter largura definida)
Tags: css, layout, centralizacao
```

```
CARD 12:
Front: Qual propriedade CSS ativa o flexbox?
Back: display: flex;
Tags: css, flexbox, layout
```

### 🔄 **Flexbox**

```
CARD 13:
Front: No flexbox, qual propriedade alinha itens no eixo principal?
Back: justify-content
Tags: css, flexbox, alinhamento
```

```
CARD 14:
Front: No flexbox, qual propriedade alinha itens no eixo cruzado?
Back: align-items
Tags: css, flexbox, alinhamento
```

```
CARD 15:
Front: Como centralizar completamente um item com flexbox?
Back: display: flex; justify-content: center; align-items: center;
Tags: css, flexbox, centralizacao
```

### 📱 **Grid CSS**

```
CARD 16:
Front: Como definir 3 colunas iguais no CSS Grid?
Back: grid-template-columns: 1fr 1fr 1fr; ou grid-template-columns: repeat(3, 1fr);
Tags: css, grid, layout
```

```
CARD 17:
Front: Como fazer um item ocupar 2 colunas no CSS Grid?
Back: grid-column: span 2;
Tags: css, grid, span
```

---

## ⚛️ **React - Essenciais**

### 🎣 **Hooks Básicos**

```
CARD 18:
Front: Como criar um estado local no React?
Back: const [estado, setEstado] = useState(valorInicial);
Tags: react, hooks, useState
```

```
CARD 19:
Front: Como executar código após o componente renderizar no React?
Back: useEffect(() => { /* código */ }, []);
Tags: react, hooks, useEffect
```

```
CARD 20:
Front: Como fazer useEffect executar apenas uma vez no React?
Back: useEffect(() => { /* código */ }, []); - array de dependências vazio
Tags: react, hooks, useEffect, mounting
```

### 🧩 **Componentes**

```
CARD 21:
Front: Como passar dados do pai para filho no React?
Back: Via props - <ComponenteFilho prop={valor} />
Tags: react, componentes, props
```

```
CARD 22:
Front: Como criar um componente funcional básico no React?
Back: const NomeComponente = () => { return <div>conteudo</div>; };
Tags: react, componentes, functional
```

```
CARD 23:
Front: Como renderizar condicionalmente no React?
Back: {condicao && <Componente />} ou {condicao ? <A /> : <B />}
Tags: react, renderizacao, condicional
```

---

## 🌐 **HTML - Semântica**

### 🏷️ **Tags Essenciais**

```
CARD 24:
Front: Qual tag HTML representa o cabeçalho principal de uma página?
Back: <header>
Tags: html, semantica, header
```

```
CARD 25:
Front: Qual atributo HTML torna um campo obrigatório?
Back: required
Tags: html, forms, required
```

```
CARD 26:
Front: Como criar um link que abre em nova aba no HTML?
Back: <a href="url" target="_blank">texto</a>
Tags: html, links, target
```

---

## 🎯 **Templates para Criar Seus Cards**

### 📝 **Template: Sintaxe**
```
Front: Como [ação] em [linguagem/tecnologia]?
Back: [código exato]
Tags: [linguagem], sintaxe, [categoria]
```

### 🧠 **Template: Conceito**
```
Front: O que é [conceito] em [contexto]?
Back: [explicação clara em suas palavras]
Tags: [tecnologia], conceitos, [categoria]
```

### ⚖️ **Template: Comparação**
```
Front: Qual diferença entre [A] e [B]?
Back: [A]: [características]; [B]: [características]
Tags: [tecnologia], diferenças, [categoria]
```

### 🔧 **Template: Método/Propriedade**
```
Front: Qual [método/propriedade] faz [ação específica]?
Back: [nome] - [descrição breve]
Tags: [tecnologia], [categoria], [subcategoria]
```

---

## 💡 **Dicas para Adaptar os Exemplos**

### 🎯 **Personalize para Seu Nível**
- **Iniciante**: Use os exemplos como estão
- **Intermediário**: Adicione mais contexto/detalhes
- **Avançado**: Combine conceitos, adicione edge cases

### 🏷️ **Sistema de Tags Sugerido**
```
Nível 1: Tecnologia (javascript, css, react, html)
Nível 2: Categoria (sintaxe, conceitos, metodos)  
Nível 3: Específico (arrays, flexbox, hooks)
```

### 📊 **Métricas de Qualidade**
- **Tempo de resposta**: <15 segundos
- **Taxa de acerto**: >90%
- **Clareza**: Não precisa "interpretar" a pergunta

### 🔄 **Processo de Melhoria**
1. Use o exemplo como base
2. Teste com 3-5 revisões
3. Ajuste se estiver difícil/fácil demais
4. Delete se nunca usar

---

## 🚀 **Próximos Passos**

1. **Escolha 5 exemplos** relacionados ao que você está estudando
2. **Adapte** para seu contexto específico
3. **Adicione** ao seu deck
4. **Teste** nas próximas revisões
5. **Crie cards similares** usando os templates

---

*💡 Lembre-se: Estes são pontos de partida. Adapte sempre para seu contexto e necessidades!*
