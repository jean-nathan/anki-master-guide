# 📊 Prompts para Análise de Progresso
*Transforme dados do Anki em insights acionáveis*

## 🎯 Prompt Principal - Análise Completa

### 📈 Template de Análise Geral

```
Você é um especialista em análise de dados de aprendizado e otimização do Anki.

CONTEXTO:
Preciso analisar meu progresso no Anki dos últimos [período] e receber recomendações específicas para otimizar meu estudo.

DADOS DO ANKI:
[Cole aqui o relatório .csv ou estatísticas exportadas]

INFORMAÇÕES COMPLEMENTARES:
- Tempo disponível para estudo: [X horas/dia]
- Principais matérias estudadas: [lista]
- Objetivos de aprendizado: [específicos]
- Dificuldades percebidas: [descreva]

ANÁLISE SOLICITADA:
1. **Performance Geral**: Taxa de acerto, consistência, tendências
2. **Identificação de Padrões**: Horários, dias, tipos de card problemáticos
3. **Análise por Deck**: Performance comparativa entre matérias
4. **Otimizações**: Configurações e estratégias específicas
5. **Plano de Ação**: Próximos passos concretos para próximo mês

FORMATO DE RESPOSTA:
📊 **RESUMO EXECUTIVO**
🔍 **INSIGHTS PRINCIPAIS**  
⚙️ **RECOMENDAÇÕES TÉCNICAS**
🎯 **PLANO DE AÇÃO**
📈 **METAS PRÓXIMO PERÍODO**
```

## 📊 Prompts Especializados por Tipo de Análise

### 🎯 Análise de Performance

```
ANALISTA DE PERFORMANCE DE APRENDIZADO:

DADOS DE REVISÃO DOS ÚLTIMOS 30 DIAS:
[Cole suas estatísticas do Anki]

MÉTRICAS ESPECÍFICAS:
- Cards revisados: [número]
- Taxa de acerto geral: [%]
- Tempo médio por card: [segundos]
- Cards em aprendizado: [número]
- Cards maduros: [número]
- Streak atual: [dias]

ANÁLISE DETALHADA SOLICITADA:

1. **PERFORMANCE TRENDS**
   - Evolução da taxa de acerto ao longo do tempo
   - Variações por dia da semana
   - Correlação entre volume de cards e performance
   
2. **EFICIÊNCIA TEMPORAL**
   - Análise do tempo por card vs. taxa de acerto
   - Identificação de cards "lentos"
   - Recomendações para otimizar velocidade
   
3. **PADRÕES DE ESQUECIMENTO**
   - Tipos de card mais problemáticos
   - Intervalos com maior taxa de lapso
   - Identificação de knowledge gaps

FORNEÇA:
✅ **Pontos fortes identificados**
❌ **Áreas que precisam atenção**  
🎯 **Top 3 ações para próximos 7 dias**
📈 **Métricas específicas para acompanhar**
```

### 🧠 Análise de Retenção

```
ESPECIALISTA EM RETENÇÃO E MEMÓRIA:

FOCO: Análise profunda de retenção e curva de esquecimento

DADOS DISPONÍVEIS:
[Cole dados de retenção por intervalo, lapses, etc.]

CONTEXTO DE ESTUDO:
- Matérias estudadas: [lista]
- Tempo de uso do Anki: [meses]
- Frequência de estudo: [X dias/semana]
- Configurações atuais: [descreva brevemente]

ANÁLISE DE RETENÇÃO SOLICITADA:

1. **CURVA DE ESQUECIMENTO PERSONALIZADA**
   - Análise da retenção por intervalo
   - Comparação com curva padrão de Ebbinghaus
   - Identificação do seu padrão único de memória

2. **EFETIVIDADE DAS CONFIGURAÇÕES**
   - Performance dos intervals atuais
   - Taxa de success por modificador de facilidade
   - Impacto das configurações de lapso

3. **OTIMIZAÇÃO BASEADA EM DADOS**
   - Ajustes recomendados para intervalos
   - Configurações personalizadas por tipo de conteúdo
   - Estratégias para reduzir lapses

RESULTADO ESPERADO:
🧠 **Perfil da sua memória**
📊 **Configurações otimizadas personalizadas**
⚙️ **Ajustes específicos para implementar**
🎯 **Previsão de melhoria esperada**
```

### 📚 Análise por Matéria/Deck

```
ANALISTA DE PERFORMANCE POR MATÉRIA:

OBJETIVO: Comparar performance entre diferentes matérias e otimizar estudo por área

DADOS POR DECK:
Deck 1: [Nome] - [estatísticas]
Deck 2: [Nome] - [estatísticas]  
Deck 3: [Nome] - [estatísticas]
[adicione quantos tiver]

INFORMAÇÕES COMPLEMENTARES:
- Prioridade de cada matéria: [alta/média/baixa]
- Dificuldade percebida: [1-10 para cada]
- Tempo ideal de dedicação: [% para cada matéria]
- Prazos específicos: [provas, certificações, etc.]

ANÁLISE COMPARATIVA SOLICITADA:

1. **PERFORMANCE RELATIVA**
   - Ranking de decks por taxa de acerto
   - Análise de eficiência (aprendizado/tempo)
   - Identificação de matérias problemáticas

2. **ALOCAÇÃO DE TEMPO OTIMIZADA**  
   - Sugestão de % tempo por matéria
   - Identificação de over/under-study
   - Balanceamento baseado em urgência vs. dificuldade

3. **ESTRATÉGIAS ESPECÍFICAS**
   - Configurações diferenciadas por deck
   - Métodos de estudo complementares
   - Cronograma semanal otimizado

ENTREGUE:
📊 **Dashboard comparativo**
⚖️ **Rebalanceamento recomendado**  
🎯 **Estratégia específica por matéria**
📅 **Cronograma semanal otimizado**
```

### ⏰ Análise Temporal

```
ESPECIALISTA EM OTIMIZAÇÃO TEMPORAL:

FOCO: Análise de padrões temporais e otimização de horários de estudo

DADOS TEMPORAIS DISPONÍVEIS:
[Cole dados de horários de estudo, performance por período, etc.]

CONTEXTO PESSOAL:
- Horários disponíveis: [manhã/tarde/noite]
- Rotina atual de estudos: [descreva]
- Energia/concentração por período: [manhã alta, tarde média, etc.]
- Outras atividades/compromissos: [trabalho, curso, etc.]

ANÁLISE TEMPORAL SOLICITADA:

1. **PERFORMANCE POR HORÁRIO**
   - Taxa de acerto por período do dia
   - Velocidade de resposta por horário
   - Correlação entre horário e dificuldade percebida

2. **PADRÕES SEMANAIS**
   - Performance por dia da semana
   - Consistência vs. variabilidade
   - Impacto de fins de semana

3. **OTIMIZAÇÃO DE CRONOGRAMA**
   - Horários ideais para tipos diferentes de conteúdo
   - Distribuição otimizada ao longo da semana  
   - Estratégias para manter consistência

RESULTADO DESEJADO:
🕐 **Cronograma personalizado otimizado**
📈 **Previsão de melhoria com novo horário**
⚡ **Estratégias para manter energia/foco**
📅 **Plano semanal detalhado**
```

### 🔄 Análise de Lapses e Dificuldades

```
ESPECIALISTA EM DIAGNÓSTICO DE DIFICULDADES:

OBJETIVO: Identificar e resolver problemas específicos de cards/conceitos problemáticos

DADOS DE LAPSES:
[Cole dados de cards com múltiplos lapses, resetados frequentemente, etc.]

CARDS MAIS PROBLEMÁTICOS:
Card 1: [Frente] | [Verso] | Lapses: [X] | Último intervalo: [Y dias]
Card 2: [repita o formato]
[liste 10-20 cards mais problemáticos]

CONTEXTO:
- Há quanto tempo estuda estes tópicos: [tempo]
- Métodos complementares usados: [livros, vídeos, etc.]
- Dificuldades específicas percebidas: [conceituais, memória, etc.]

ANÁLISE DE DIFICULDADES SOLICITADA:

1. **DIAGNÓSTICO DOS PROBLEMAS**
   - Padrões nos cards problemáticos
   - Tipos de erro mais comuns
   - Possíveis gaps conceituais

2. **CAUSAS RAIZ**
   - Qualidade da formulação dos cards
   - Complexidade excessiva
   - Falta de contexto ou pré-requisitos
   - Problemas de configuração

3. **SOLUÇÕES PERSONALIZADAS**
   - Reformulação de cards específicos
   - Cards complementares necessários
   - Métodos de estudo adicionais
   - Ajustes de configuração

ENTREGUE:
🔍 **Diagnóstico detalhado**
🛠️ **Cards reformulados (exemplos)**
📚 **Plano de reforço conceitual**  
⚙️ **Ajustes técnicos recomendados**
```

## 🎯 Prompts por Nível de Experiência

### 🟢 Análise para Iniciantes

```
ANÁLISE PARA INICIANTE NO ANKI:

Uso o Anki há [X semanas/meses] e preciso entender se estou no caminho certo.

MEUS DADOS BÁSICOS:
- Cards totais: [número]  
- Cards/dia em média: [número]
- Taxa de acerto: [%]
- Dias de streak: [número]
- Tempo de estudo/dia: [minutos]

PRINCIPAIS DÚVIDAS:
- Estou criando cards da forma correta?
- Minhas configurações estão adequadas?
- Meu ritmo de estudo é sustentável?
- Como sei se estou progredindo bem?

ANÁLISE INICIANTE SOLICITADA:
1. **VALIDAÇÃO DO SETUP BÁSICO**
   - Se configurações estão adequadas para iniciante
   - Se ritmo está sustentável
   - Se métricas estão dentro do esperado

2. **IDENTIFICAÇÃO DE OPORTUNIDADES BÁSICAS**  
   - Ajustes simples de maior impacto
   - Hábitos a desenvolver
   - Erros comuns a evitar

3. **PLANO DE EVOLUÇÃO**
   - Próximos marcos a atingir
   - Quando/como evoluir configurações
   - Sinais de que está pronto para nível intermediário

FORMATO AMIGÁVEL PARA INICIANTE:
✅ **O que você está fazendo bem**
🎯 **3 melhorias fáceis de implementar**
📈 **Metas para próximas 4 semanas**  
🚦 **Sinais de alerta para ficar atento**
```

### 🟡 Análise para Intermediários

```
ANÁLISE PARA USUÁRIO INTERMEDIÁRIO:

Uso o Anki há [X meses] e já tenho o básico funcionando. Quero otimizar meu sistema.

SITUAÇÃO ATUAL:
- Cards ativos: [número]
- Decks organizados: [quantos]
- Configurações: [básicas/personalizadas]
- Taxa de acerto: [%]  
- Tempo médio/card: [segundos]

OBJETIVOS DE OTIMIZAÇÃO:
- Aumentar eficiência temporal
- Melhorar taxa de retenção
- Organizar melhor o sistema
- Preparar para crescimento

ANÁLISE INTERMEDIÁRIA SOLICITADA:

1. **OTIMIZAÇÕES DE EFICIÊNCIA**
   - Configurações mais precisas por tipo de conteúdo
   - Organização otimizada de decks
   - Automatização de processos

2. **ANÁLISE DE ESCALABILIDADE**
   - Como manter performance com mais cards
   - Estratégias para volume crescente  
   - Prevenção de sobrecarga

3. **EVOLUÇÃO TÉCNICA**
   - Add-ons recomendados para seu nível
   - Configurações avançadas seguras
   - Métricas mais sofisticadas para acompanhar

RESULTADO INTERMEDIÁRIO:
⚙️ **Configurações otimizadas específicas**
📊 **Dashboard de métricas avançadas**  
🚀 **Roadmap para próximos 3 meses**
🎯 **Critérios para evoluir ao nível avançado**
```

### 🔴 Análise para Avançados

```
ANÁLISE EXPERT PARA USUÁRIO AVANÇADO:

Sou usuário experiente do Anki ([X anos]) e busco otimização científica máxima.

PERFIL EXPERT:
- Cards ativos: [5000+]
- Sistema completamente organizado
- Configurações personalizadas avançadas  
- Automações implementadas
- Métricas detalhadas disponíveis

DADOS CIENTÍFICOS DISPONÍVEIS:
[Cole relatórios detalhados, estatísticas avançadas, dados de múltiplos meses]

ANÁLISE EXPERT SOLICITADA:

1. **ANÁLISE ESTATÍSTICA AVANÇADA**
   - Modelos preditivos de performance
   - Análise de correlações complexas
   - Identificação de padrões não-óbvios
   - Benchmarking com usuários elite

2. **OTIMIZAÇÃO ALGORÍTMICA**
   - Fine-tuning de parâmetros avançados
   - Configurações dinâmicas baseadas em performance
   - Algoritmos personalizados para diferentes tipos de conteúdo

3. **INOVAÇÃO E EXPERIMENTAÇÃO**
   - Hipóteses para testes A/B
   - Experimentos de configuração científicos
   - Integração com outras ferramentas/métodos

ENTREGUE ANÁLISE CIENTÍFICA:
🔬 **Insights estatísticos avançados**  
⚙️ **Configurações algorítmicas otimizadas**
🧪 **Protocolos experimentais para testes**
📈 **Modelos preditivos personalizados**
🏆 **Roadmap para performance de elite**
```

## 📈 Prompts para Situações Específicas

### 🎯 Preparação para Provas

```
OTIMIZAÇÃO PARA PREPARAÇÃO DE PROVAS:

CONTEXTO DA PROVA:
- Tipo: [concurso/certificação/vestibular/etc.]
- Data: [quando]
- Tempo disponível: [semanas/meses]  
- Matérias: [lista com pesos]
- Formato: [múltipla escolha/dissertativa/etc.]

SITUAÇÃO ATUAL NO ANKI:
[Cole dados de performance atual]

ANÁLISE ESPECÍFICA PARA PROVA:

1. **ESTRATÉGIA DE COBERTURA**
   - Priorização de tópicos por importância
   - Cronograma até a data da prova
   - Balance entre revisão e novo conteúdo

2. **OTIMIZAÇÃO PARA ALTA PRESSÃO**
   - Configurações para máxima retenção
   - Foco em recall ativo vs. reconhecimento  
   - Estratégias para stress de prova

3. **PLANO DE SPRINT FINAL**
   - Últimas 4 semanas antes da prova
   - Últimas 2 semanas (revisão intensiva)
   - Última semana (manutenção apenas)

CRONOGRAMA DETALHADO:
📅 **Semana a semana até a prova**
🎯 **Metas específicas por período**
⚙️ **Ajustes de configuração por fase**  
🚨 **Plano de contingência se atrasar**
```

### 💼 Otimização para Profissionais

```
ANÁLISE PARA PROFISSIONAL OCUPADO:

CONTEXTO PROFISSIONAL:
- Área de trabalho: [sua área]
- Horas de trabalho/dia: [número]  
- Tempo disponível para estudo: [janelas específicas]
- Objetivos: [certificações/promoção/mudança de área]

DESAFIOS ESPECÍFICOS:
- Tempo limitado e fragmentado
- Energia variável após trabalho
- Necessidade de ROI alto no aprendizado
- Interrupções frequentes

OTIMIZAÇÃO PROFISSIONAL SOLICITADA:

1. **MÁXIMA EFICIÊNCIA TEMPORAL**
   - Aproveitamento de micro-momentos  
   - Configurações para sessões rápidas
   - Priorização baseada em impacto profissional

2. **ADAPTAÇÃO À ROTINA CORPORATIVA**
   - Horários otimizados para energia disponível
   - Estratégias para manter consistência  
   - Integração com agenda profissional

3. **ROI PROFISSIONAL**
   - Métricas ligadas a objetivos de carreira
   - Conteúdo com aplicação imediata
   - Cronograma alinhado com metas profissionais

RESULTADO EXECUTIVO:
⏰ **Cronograma executivo otimizado**
💡 **Estratégias de micro-aprendizado**
📊 **KPIs profissionais para acompanhar**
🎯 **Milestones de carreira vinculados**
```

### 🧪 Análise Experimental

```
DESIGNER DE EXPERIMENTOS DE APRENDIZADO:

OBJETIVO: Testar hipóteses específicas sobre otimização do meu aprendizado

HIPÓTESES PARA TESTAR:
Hipótese 1: [ex: "Estudar de manhã aumenta retenção em 15%"]
Hipótese 2: [ex: "Cards com imagens têm melhor performance"]  
Hipótese 3: [ex: "Intervalos mais conservadores melhoram taxa de acerto"]

DADOS BASELINE:
[Performance atual para usar como controle]

DESIGN EXPERIMENTAL SOLICITADO:

1. **PROTOCOLO CIENTÍFICO**
   - Metodologia para cada teste
   - Variáveis a controlar
   - Métricas específicas para medir
   - Duração adequada de cada experimento

2. **IMPLEMENTAÇÃO PRÁTICA**  
   - Como dividir decks para teste A/B
   - Configurações específicas para cada grupo
   - Cronograma de coleta de dados

3. **ANÁLISE DE RESULTADOS**
   - Como interpretar os dados coletados
   - Critérios para validar/rejeitar hipóteses  
   - Próximos experimentos baseados em resultados

PROTOCOLO CIENTÍFICO:
🧪 **Design experimental detalhado**
📊 **Métricas e KPIs específicos**  
⏰ **Cronograma de testes**
📈 **Framework de análise de resultados**
```

## 💡 Dicas para Usar os Prompts de Análise

### 📋 Preparação dos Dados

**Antes de usar qualquer prompt:**

1. **Extraia dados do Anki Desktop:**
   - Vá em Ferramentas > Estatísticas
   - Exporte dados detalhados
   - Salve em formato .csv quando possível

2. **Organize informações complementares:**
   - Objetivos específicos
   - Contexto pessoal/profissional  
   - Dificuldades percebidas
   - Tempo disponível

3. **Defina período de análise:**
   - Últimos 30 dias (análise mensal)
   - Últimos 90 dias (análise trimestral)
   - Desde o início (análise completa)

### 🎯 Personalizando os Prompts

**Para melhores resultados:**

- **Seja específico** nos seus objetivos
- **Inclua contexto** pessoal relevante
- **Mencione limitações** (tempo, recursos)
- **Defina métricas** que importam para você

### 📊 Interpretando Resultados

**Após receber a análise do Claude:**

1. **Implemente uma mudança por vez**
2. **Documente o que foi alterado**
3. **Monitore métricas por 2-4 semanas**
4. **Refaça análise para validar melhorias**

### 🔄 Frequência de Análise

**Recomendações por nível:**

- **Iniciante**: A cada 2 meses
- **Intermediário**: Mensalmente  
- **Avançado**: Quinzenalmente
- **Expert**: Semanalmente (análises específicas)

---

## 🚀 Próximo Passo

1. **Escolha o prompt** mais adequado ao seu nível e situação
2. **Colete seus dados** do Anki
3. **Personalize o prompt** com suas informações
4. **Execute no Claude** e implemente as recomendações

---

*📊 Lembre-se: Dados sem ação são apenas números. Use as análises para tomar decisões concretas de melhoria!*
