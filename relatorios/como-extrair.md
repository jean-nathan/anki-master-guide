# 📊 Como Extrair Relatórios do Anki Desktop
*Guia completo para coletar dados e gerar análises poderosas*

## 🎯 Por Que Extrair Relatórios?

Os relatórios são a **chave** para evolução científica no Anki. Com eles você:
- **Identifica padrões** no seu aprendizado
- **Otimiza configurações** baseado em dados reais  
- **Detecta problemas** antes que se tornem grandes
- **Mede progresso** de forma objetiva
- **Toma decisões** baseadas em evidências, não intuição

## 📈 Tipos de Dados Disponíveis

### 🔢 Estatísticas Básicas (Built-in)
- Taxa de acerto geral
- Cards revisados por dia
- Tempo médio por card
- Cards em cada etapa (novo/aprendendo/revisão)
- Streak atual

### 📊 Dados Avançados (Exportação)
- Performance individual por card
- Histórico detalhado de revisões
- Intervalos e facilidades específicas
- Timestamps de cada revisão
- Taxa de lapsos detalhada

### 🧠 Métricas Especiais (Add-ons)
- True retention por maturidade
- Heat map de estudos
- Análise temporal detalhada
- Performance por tag/deck
- Predição de carga futura

## 🛠️ Métodos de Extração

### 📱 Método 1: Estatísticas Nativas (Mais Fácil)

**Passo a passo:**

1. **Abra o Anki Desktop**

2. **Acesse as Estatísticas:**
   - Menu: `Ferramentas` > `Estatísticas`
   - Ou tecle `T`

3. **Configure o Período:**
   - Mês atual: Para análise mensal
   - Últimos 3 meses: Para análise trimestral  
   - Toda vida: Para análise completa

4. **Capture as Informações:**
   - **Screenshot** das estatísticas principais
   - **Anote manualmente** os números-chave:
     - Taxa de acerto: ___%
     - Cards/dia média: ___
     - Tempo médio: ___s
     - Streak: ___ dias

**✅ Vantagens:**
- Rápido e simples
- Sempre disponível
- Dados confiáveis

**❌ Limitações:**
- Dados superficiais
- Pouco customizável
- Sem histórico detalhado

---

### 💻 Método 2: Exportação de Collection (Intermediário)

**Passo a passo:**

1. **Backup Primeiro (Importante!):**
   - `Arquivo` > `Exportar`
   - Marque: "Incluir agendamento e histórico de revisão"
   - Salve como backup: `backup_[data].colpkg`

2. **Exporte Dados para Análise:**
   - `Arquivo` > `Exportar`
   - Formato: "Anki Collection Package (*.colpkg)"
   - ✅ Incluir mídia (se necessário)
   - ✅ Incluir agendamento e histórico de revisão
   - ✅ Suporte para versões mais antigas

3. **Dados Exportados Incluem:**
   - Todos os cards com metadados
   - Histórico completo de revisões
   - Configurações atuais
   - Estatísticas detalhadas

**Para Análise no Claude:**
```
Dados da minha collection exportada em [data]:
- Total de cards: [número]
- Taxa de acerto último mês: [%] 
- Deck 1: [nome] - [cards] cards - [%] acerto
- Deck 2: [nome] - [cards] cards - [%] acerto
- Tempo médio por card: [segundos]
- Principais dificuldades observadas: [liste]
```

---

### 🔧 Método 3: Add-on "Advanced Browser" (Avançado)

**Instalação:**

1. **Instale o Add-on:**
   - Código: `874215009`
   - `Ferramentas` > `Add-ons` > `Obter Add-ons`
   - Cole o código e instale
   - Reinicie o Anki

2. **Use o Browser Avançado:**
   - `Procurar` ou `Ctrl+B`
   - Veja colunas adicionais:
     - Overdue (em atraso)
     - Interval (intervalo atual)  
     - Ease (facilidade)
     - Lapses (resetadas)
     - Reviews (revisões totais)

3. **Exporte Dados Específicos:**
   - Selecione cards problemáticos
   - `Ctrl+A` para selecionar tudo
   - Copie dados relevantes

**Dados Úteis para Análise:**
- Cards com mais lapses
- Cards com intervals muito baixos/altos
- Cards com facilidade anormal
- Cards não revisados há muito tempo

---

### 📊 Método 4: Add-on "True Retention" (Expert)

**Para usuários que querem dados científicos precisos**

**Instalação:**
- Código: `613684242`
- Reinicie após instalar

**Como Usar:**

1. **Acesse True Retention:**
   - Menu: `Ferramentas` > `True Retention`

2. **Configure Parâmetros:**
   - Período: Últimos 30/90 dias
   - Maturidade mínima: 21 dias (padrão)
   - Grouping: Por deck ou tag

3. **Analise Métricas Científicas:**
   - **True Retention**: Retenção real vs. aparente
   - **R1 (Retention 1)**: Taxa após 1º intervalo maduro
   - **R2 (Retention 2)**: Taxa após intervalos subsequentes
   - **Maturity**: Distribuição por maturidade

**Dados para Claude:**
```
Análise True Retention últimos 30 dias:

DECK: [Nome]
- True Retention: [%]
- R1: [%] 
- R2: [%]
- Cards maduros analisados: [número]
- Intervalo médio: [dias]

DECK: [Nome 2]
[repetir formato]
```

---

## 📋 Dados Específicos para Coletar

### 📊 Para Análise Mensal Básica

**Colete sempre:**
```
=== ESTATÍSTICAS BÁSICAS ===
Período: [mês/ano]
Taxa de acerto geral: ___%
Cards revisados/dia (média): ___
Tempo médio por card: ___s
Streak atual: ___ dias
Cards novos/dia: ___
Cards pendentes: ___

=== POR DECK ===
Deck 1: [nome]
- Cards totais: ___
- Taxa de acerto: ___%
- Tempo médio: ___s

[repetir para cada deck]

=== OBSERVAÇÕES ===
- Principais dificuldades:
- Mudanças realizadas no período:
- Objetivos para próximo mês:
```

### 📈 Para Análise Avançada

**Dados adicionais importantes:**
```
=== MÉTRICAS AVANÇADAS ===
True Retention (se disponível):
- Deck A: ___%
- Deck B: ___%

Cards Problemáticos (>3 lapses):
- Card 1: [frente] | Lapses: ___
- Card 2: [frente] | Lapses: ___

Distribuição de Intervalos:
- <1 semana: ___ cards
- 1-4 semanas: ___ cards  
- 1-6 meses: ___ cards
- >6 meses: ___ cards

Performance por Horário:
- Manhã (6-12h): ___%
- Tarde (12-18h): ___%  
- Noite (18-24h): ___%
```

### 🎯 Para Análise de Problemas Específicos

**Quando performance está ruim:**
```
=== DIAGNÓSTICO DE PROBLEMAS ===
Período analisado: [datas]
Taxa de acerto atual: ___% (meta: >85%)

CARDS MAIS PROBLEMÁTICOS:
1. [frente do card] | [verso] | Lapses: ___ | Última revisão: ___
2. [repetir 10-15 cards]

PADRÕES IDENTIFICADOS:
- Tipo de conteúdo mais difícil: ___
- Horário com pior performance: ___
- Deck com mais problemas: ___
- Intervalo médio dos cards problemáticos: ___

CONFIGURAÇÕES ATUAIS:
- Modificador de intervalo: ___%
- Facilidade inicial: ___%
- Novo intervalo (lapses): ___%
- Steps: [lista]
```

## 🕐 Cronograma de Extração

### 📅 Por Nível de Usuário

**🟢 Iniciante (0-3 meses):**
- **Semanal**: Estatísticas básicas (5 min)
- **Mensal**: Captura completa (15 min)

**🟡 Intermediário (3-12 meses):**
- **Semanal**: Estatísticas + problemas principais (10 min)
- **Mensal**: Análise completa com add-ons (30 min)

**🔴 Avançado (12+ meses):**
- **Semanal**: Métricas científicas detalhadas (15 min)
- **Mensal**: Análise profunda multi-dimensional (45 min)

### ⏰ Melhor Momento para Extrair

**Timing ideal:**
- **Final do mês**: Para análise mensal
- **Mesmo dia da semana**: Para comparabilidade
- **Após sessão de estudo**: Dados mais frescos
- **Antes de grandes mudanças**: Para benchmark

## 📱 Extração via Mobile (Limitada)

### AnkiDroid (Android)

**Estatísticas básicas disponíveis:**
1. Abra AnkiDroid
2. Menu ☰ > Estatísticas  
3. Veja dados básicos:
   - Cards devido hoje
   - Streak
   - Taxa de acerto recente

**Limitações:**
- Dados muito limitados
- Sem exportação
- Não substituí desktop para análises

### AnkiMobile (iOS)

**Ainda mais limitado:**
- Apenas estatísticas do dia
- Sem histórico detalhado
- Use apenas para acompanhamento diário

## 🤖 Preparando Dados para o Claude

### 📝 Template de Exportação para Análise

**Use este formato ao enviar dados para Claude:**

```
=== RELATÓRIO ANKI PARA ANÁLISE ===
Data da extração: [dd/mm/aaaa]
Período analisado: [período]
Usuário: [iniciante/intermediário/avançado]

DADOS PRINCIPAIS:
- Taxa de acerto geral: ___%
- Cards revisados (período): ___
- Tempo médio por card: ___s
- Streak: ___ dias
- Cards ativos: ___

PERFORMANCE POR DECK:
[liste todos os decks com stats]

OBJETIVOS ATUAIS:
[descreva seus objetivos de estudo]

DIFICULDADES PERCEBIDAS:
[liste problemas identificados]

ANÁLISE SOLICITADA:
[especifique que tipo de análise quer]
```

## ⚠️ Importante: Backup e Segurança

### 💾 Sempre Faça Backup Antes

**Procedimento obrigatório:**
1. **Backup completo** antes de qualquer análise
2. **Salve em local seguro** (Google Drive, Dropbox)
3. **Teste a restauração** pelo menos uma vez
4. **Mantenha múltiplas versões** (semanal/mensal)

### 🔒 Privacidade dos Dados

**Ao usar Claude ou outras ferramentas:**
- **Remova informações pessoais** sensíveis
- **Use apenas dados estatísticos** necessários
- **Não inclua conteúdo** dos cards se privado
- **Anonimize exemplos** quando necessário

## 🚀 Próximos Passos

1. **Escolha seu método** baseado no nível
2. **Extraia dados** seguindo o guia
3. **Use os prompts** de análise específicos
4. **Implemente melhorias** sugeridas
5. **Monitore resultados** nas próximas extrações

---

## 💡 Dicas Finais

### ✅ Boas Práticas
- **Consistência**: Extraia sempre no mesmo formato
- **Regularidade**: Mantenha cronograma de extrações
- **Documentação**: Anote mudanças implementadas
- **Comparação**: Use dados anteriores para context

### 🚫 Evite Estes Erros
- Extrair dados apenas quando há problemas
- Focar só em números, ignorar contexto
- Fazer muitas mudanças sem medir impacto
- Comparar períodos muito diferentes

---

*📊 Lembre-se: Dados são inúteis sem análise, e análise é inútil sem ação. Extraia, analise e implemente!*
