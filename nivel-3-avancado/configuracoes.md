# ⚙️ Configurações Expert - Nível 3
*Precisão Científica e Performance Máxima*

## 🎯 Filosofia das Configurações Expert

**Princípio Central**: Cada parâmetro é calibrado cientificamente baseado em dados reais do seu aprendizado, não em teorias genéricas.

## 📊 Setup Inicial: Coleta de Dados

### 🔍 Antes de Configurar - Análise Profunda

**Execute este prompt no Claude primeiro:**

```
Analise meu relatório do Anki (anexar .csv) e identifique:

1. Padrões de esquecimento por tipo de conteúdo
2. Correlações entre intervalo e taxa de acerto
3. Performance por horário/dia da semana
4. Cards problemáticos (muitos lapses)
5. Configurações ideais recomendadas

Forneça configurações específicas para:
- Conteúdo fácil (conceitos simples)
- Conteúdo médio (aplicações práticas) 
- Conteúdo difícil (abstrações complexas)
- Conteúdo crítico (não pode esquecer)
```

## 🚀 Configurações por Tipo de Conteúdo

### 📚 Deck 1: Conceitos Básicos (Fácil)
*Para: definições, fórmulas simples, fatos*

**Opções do Baralho > Novo:**
- Passos: `1 10 60 180`
- Ordem: Mostrar novos cards em ordem aleatória
- Novos cards/dia: `25-30`
- Intervalo de formação: `4 dias`
- Facilidade inicial: `250%`
- Facilidade mínima: `130%`

**Revisões:**
- Facilidade máx.: `300%`
- Bônus intervalo: `130%`
- Modificador intervalo: `110%` (otimista para fácil)
- Intervalos máximos: `36500` (100 anos)

**Lapsos:**
- Passos: `10 60`
- Novo intervalo: `70%` (generoso para fácil)
- Facilidade mínima: `130%`
- Sanguessuga: `8 lapses` em `30 dias`

### 🧠 Deck 2: Aplicações Práticas (Médio)
*Para: exercícios, casos práticos, conexões*

**Novo:**
- Passos: `1 10 30 180 1440` (6 passos)
- Novos cards/dia: `15-20`
- Intervalo de formação: `6 dias`
- Facilidade inicial: `240%`

**Revisões:**
- Modificador intervalo: `100%` (padrão)
- Bônus intervalo: `120%`
- Facilidade máx.: `280%`

**Lapsos:**
- Passos: `10 30 180`
- Novo intervalo: `50%`
- Sanguessuga: `6 lapses` em `20 dias`

### 🔬 Deck 3: Conceitos Complexos (Difícil)
*Para: abstrações, teorias avançadas, conexões complexas*

**Novo:**
- Passos: `1 10 30 180 1440 2880` (7 passos)
- Novos cards/dia: `8-12`
- Intervalo de formação: `8 dias`
- Facilidade inicial: `220%`

**Revisões:**
- Modificador intervalo: `85%` (conservador)
- Bônus intervalo: `110%`
- Facilidade máx.: `250%`

**Lapsos:**
- Passos: `10 30 180 1440`
- Novo intervalo: `30%` (rigoroso)
- Facilidade mínima: `130%`
- Sanguessuga: `4 lapses` em `15 dias`

### 🚨 Deck 4: Conhecimento Crítico (Não pode esquecer)
*Para: informações vitais, certificações, segurança*

**Novo:**
- Passos: `1 5 10 30 180 1440 2880 7200` (8 passos)
- Novos cards/dia: `5-8`
- Intervalo de formação: `12 dias`
- Facilidade inicial: `200%`

**Revisões:**
- Modificador intervalo: `70%` (muito conservador)
- Bônus intervalo: `105%`
- Facilidade máx.: `220%`

**Lapsos:**
- Passos: `5 10 30 180 1440`
- Novo intervalo: `20%` (muito rigoroso)
- Facilidade mínima: `140%`
- Sanguessuga: `3 lapses` em `10 dias`

## 🎯 Configurações Globais Expert

### ⚡ Preferências Gerais

**Interface:**
- Mostrar próxima conta de revisão: ✅
- Mostrar barra de progresso: ✅
- Interromper timer: ✅
- Mostrar tempo restante: ✅
- Novo spread: `3` (distribui novos)

**Revisão:**
- Mostrar ambos os lados: ✅
- Pedir para digitar: ❌ (só para idiomas)
- Tocar sons automaticamente: ✅
- Alertas de tempo: `60` segundos

**Rede:**
- Sincronizar mídia: ✅
- Check automático: ✅

### 🔧 Add-ons Essenciais Expert

#### 📊 Análise e Estatísticas
```
True Retention by Card Maturity - ID: 613684242
Advanced Browser - ID: 874215009  
Review Heatmap - ID: 1771074083
Speed Focus Mode - ID: 1046608507
Progress Bar - ID: 2091361802
```

#### 🚀 Produtividade
```
Image Resizer - ID: 1103084694
Frozen Fields - ID: 516643804
Quick Colour Changing - ID: 2491935955
Reset Ease - ID: 947935257
Load Balancer - ID: 1417170896
```

#### 🤖 Automação
```
AnkiConnect - ID: 2055492159
Batch Editing - ID: 291119185
Special Fields - ID: 1102281552
Hierarchical Tags - ID: 594329229
```

## 📈 Configurações Dinâmicas (Baseadas em Performance)

### 🎯 Sistema de Ajuste Automático

**Use este prompt mensal no Claude:**

```
Baseado no meu relatório mensal (anexar), ajuste minhas configurações:

DADOS ATUAIS:
- Taxa de acerto geral: X%
- Cards por dia: X
- Tempo médio: X segundos
- Taxa de lapsos: X%

SOLICITO:
1. Análise de performance por deck
2. Configurações específicas a ajustar
3. Métricas para monitorar próximo mês
4. Previsão de carga de trabalho
5. Identificação de cards problemáticos

Forneça ajustes precisos por categoria de dificuldade.
```

### ⚙️ Calibração por Métricas

#### 📊 Se Taxa de Acerto > 95%
**Ação**: Aumentar dificuldade
- Modificador intervalo: +10%
- Facilidade inicial: +10%
- Reduzir steps de lapso

#### 📊 Se Taxa de Acerto < 85%
**Ação**: Reduzir dificuldade  
- Modificador intervalo: -10%
- Facilidade inicial: -10%
- Aumentar steps de lapso
- Novo intervalo: +10%

#### ⏱️ Se Tempo Médio > 30s
**Ação**: Revisar qualidade dos cards
- Identificar cards lentos
- Reformular com Claude
- Considerar quebrar em cards menores

## 🔬 Experimentos Expert

### 🧪 A/B Testing de Configurações

**Protocolo Científico:**

1. **Baseline**: Documente performance atual (1 semana)
2. **Hipótese**: "Mudança X vai melhorar métrica Y em Z%"  
3. **Teste**: Implemente mudança em deck teste (2 semanas)
4. **Análise**: Compare resultados
5. **Decisão**: Manter, ajustar ou reverter

### 📊 Métricas para Cada Experimento

**Primárias:**
- Taxa de retenção verdadeira
- Tempo por card
- Taxa de facilidade
- Distribuição de intervalos

**Secundárias:**
- Satisfação subjetiva
- Motivação para estudar
- Consistência diária
- Stress cognitivo

## 🚀 Configurações de Sistema Operacional

### 🖥️ Performance Máxima

**Windows:**
- Prioridade alta para Anki no Gerenciador de Tarefas
- Desabilitar indexação na pasta do Anki
- SSD recomendado para collection.anki2

**Mac:**
- Adicionar Anki às exceções do Spotlight
- Configurar Energy Saver para performance máxima
- Usar terminal para backup automatizado

**Backup Expert:**
```bash
# Script diário automático
rsync -av ~/.local/share/Anki2/ ~/Backup/Anki/$(date +%Y%m%d)/
```

## 📱 Sincronização Expert

### ☁️ Configurações de Sync

**Desktop (Mestre):**
- Sync após cada sessão
- Upload de mídia: ✅
- Resolução de conflitos: Manter local

**Mobile (Escravo):**
- Sync antes e após uso
- Download automático: ✅
- Backup local habilitado

**Protocolo de Conflito:**
1. Sempre sincronize desktop primeiro
2. Mobile só para revisões emergenciais
3. Edições sempre no desktop
4. Backup antes de mudanças grandes

## 🏆 Configuração da Elite

### 💎 Profile do Top 1%

Quando você domina completamente as configurações expert:

- **10.000+** cards ativos
- **30 segundos** setup para qualquer novo conteúdo
- **95%+** taxa de retenção 
- **15-20 minutos/dia** independente do volume
- **Zero** problemas técnicos
- **Automação completa** de rotinas

**Próximo nível**: [Evolução Contínua](evolucao.md) 🚀

---

## ⚠️ Avisos Críticos

### 🚫 Não Faça Isso
- Mudar muitas configurações simultaneamente
- Copiar configurações sem analisar seus dados
- Ignorar métricas por mais de 1 mês
- Complicar desnecessariamente

### ✅ Sempre Faça Isso
- **Backup** antes de mudanças importantes
- **Teste** uma configuração por vez
- **Documente** mudanças e resultados
- **Analise** dados mensalmente

---

*🎯 Lembre-se: Configurações expert são cirurgia de precisão, não marteladas cegas. Cada ajuste deve ter propósito científico.*
