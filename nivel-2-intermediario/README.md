# 🟡 Nível 2: Intermediário
*Otimizando e organizando seu sistema*

## 🎯 Objetivo deste Nível

Transformar seu hábito básico em um sistema otimizado e organizado, com múltiplos baralhos, configurações específicas e análise de progresso.

## ✅ Metas do Nível 2

- [ ] Organizar conhecimento em baralhos temáticos
- [ ] Configurar settings específicos por tipo de conteúdo
- [ ] Implementar sistema de tags eficiente
- [ ] Analisar progresso semanalmente
- [ ] Dominar cards avançados (Cloze, Imagem, Áudio)
- [ ] Aumentar eficiência (40+ cards/dia)
- [ ] Reduzir tempo por card (< 5 segundos)

## 📊 Evolução do Nível 1 → Nível 2

| Aspecto | Nível 1 | Nível 2 |
|---------|---------|---------|
| Baralhos | 1 único | Múltiplos organizados |
| Cards/dia | 10-20 | 30-40 |
| Tipos de cards | Básicos | Cloze, Imagem, Áudio |
| Configurações | Uma para tudo | Específicas por tipo |
| Análise | Nenhuma | Semanal com relatórios |
| Tags | Nenhuma | Sistema organizado |
| Tempo/card | 10 segundos | < 5 segundos |

## 🗂️ Nova Estrutura de Baralhos

### Organização Recomendada
```
📚 Anki Principal/
├── 🌍 Idiomas/
│   ├── 🇬🇧 Inglês
│   └── 🇪🇸 Espanhol
├── 💻 Programação/
│   ├── Python
│   ├── JavaScript
│   └── Conceitos
├── 📖 Estudos/
│   ├── Matemática
│   ├── História
│   └── Ciências
├── 💼 Profissional/
│   ├── Habilidades
│   └── Conhecimento Técnico
└── 🧠 Desenvolvimento Pessoal/
    ├── Livros
    └── Cursos
```

### Como Criar Sub-baralhos
1. Crie baralho pai: "📚 Anki Principal"
2. Para sub-baralhos use: "📚 Anki Principal::🌍 Idiomas"
3. Para sub-sub-baralhos: "📚 Anki Principal::🌍 Idiomas::🇬🇧 Inglês"

## 🏷️ Sistema de Tags

### Tags Principais
```
#prioridade-alta    → Revisar com mais frequência
#prioridade-media   → Normal
#prioridade-baixa   → Pode esperar

#fonte-livro        → Veio de um livro
#fonte-video        → Veio de vídeo/curso
#fonte-pratica      → Experiência prática

#tipo-conceito      → Definições e conceitos
#tipo-formula       → Fórmulas e cálculos
#tipo-exemplo       → Exemplos práticos
#tipo-vocabulario   → Palavras e termos

#revisar           → Precisa melhorar o card
#importante        → Crítico para dominar
```

### Como Usar Tags Eficientemente
1. Máximo 3 tags por card
2. Use tags para criar baralhos filtrados
3. Revise cards com tag #revisar semanalmente

## 🎴 Tipos Avançados de Cards

### 1. Cloze Deletion (Mais Eficiente)
```
Texto: A capital do Brasil é {{c1::Brasília}} e foi fundada em {{c2::1960}}
Gera 2 cards:
→ Card 1: A capital do Brasil é [...] e foi fundada em 1960
→ Card 2: A capital do Brasil é Brasília e foi fundada em [...]
```

### 2. Cards com Imagem
```
Frente: [Imagem de uma célula]
        Identifique esta estrutura
Verso: Mitocôndria - responsável pela produção de energia (ATP)
```

### 3. Cards com Áudio
```
Frente: 🔊 [Áudio: "Hello, how are you?"]
        Traduza
Verso: Olá, como você está?
```

### 4. Cards Reversos
```
Card 1: Capital do Brasil? → Brasília
Card 2: Brasília é capital de? → Brasil
(Gerados automaticamente)
```

## 📈 Análise Semanal de Progresso

### Toda Segunda-feira
1. **Exporte Estatísticas**
   - Ferramentas → Estatísticas
   - Print ou exporte os dados

2. **Analise com Claude**
   - Use o prompt em [analise-progresso.md](../prompts/analise-progresso.md)
   - Envie suas estatísticas
   - Receba análise e recomendações

3. **Métricas Chave**
   - Taxa de retenção (meta: > 85%)
   - Cards/dia (meta: aumentar 10% ao mês)
   - Tempo médio (meta: < 5 seg/card)
   - Distribuição de intervalos

## ⚙️ Configurações por Tipo de Conteúdo

### 🌍 Idiomas (Alta frequência)
- Novos/dia: 30
- Multiplicador: 200% (mais revisões)
- Graduação: 1 dia

### 💻 Programação (Prática)
- Novos/dia: 20
- Multiplicador: 250%
- Graduação: 2 dias

### 📖 Conceitos (Compreensão)
- Novos/dia: 15
- Multiplicador: 300%
- Graduação: 3 dias

Detalhes completos em [configuracoes.md](./configuracoes.md)

## 🚀 Rotina Diária Nível 2

### Manhã (10-15 min)
```
06:00 - Acorde
06:05 - Anki: Baralhos prioritários
06:10 - Anki: Outros baralhos
06:15 - Registre dificuldades
06:20 - Planeje criação de cards do dia
```

### Noite (5-10 min)
```
20:00 - Crie cards do conteúdo do dia
20:05 - Use Claude para gerar cards extras
20:10 - Organize com tags
20:15 - Preview dos cards de amanhã
```

## 🤖 Uso Avançado do Claude

### Prompt para Cards Complexos
```
Crie cards do Anki tipo CLOZE sobre este conteúdo:
[seu conteúdo]

Regras:
- Use {{c1::}} para conceitos principais
- Use {{c2::}} para detalhes importantes
- Máximo 2 clozes por card
- Adicione contexto suficiente
```

### Prompt para Análise
```
Analise estas estatísticas do meu Anki:
[cole suas stats]

Identifique:
1. Pontos fortes e fracos
2. Baralhos problemáticos
3. Sugestões de otimização
4. Previsão de carga futura
```

## 📊 Baralhos Filtrados (Power Feature)

### Como Criar
1. Ferramentas → Criar Baralho Filtrado
2. Nome: "🔥 Revisão Intensiva"
3. Busca: "tag:importante is:due"
4. Limite: 100 cards

### Exemplos Úteis
- **Difíceis**: `prop:ivl<21 prop:reps>5`
- **Prioritários**: `tag:prioridade-alta`
- **Para revisar**: `tag:revisar`
- **Novos do dia**: `added:1`

## 🛠️ Complementos Recomendados

### Essenciais para Nível 2
1. **Heatmap**: Visualiza sua consistência
2. **True Retention**: Calcula retenção real
3. **Image Occlusion**: Para estudar com imagens
4. **Batch Editing**: Editar múltiplos cards

### Como Instalar
1. Ferramentas → Complementos
2. Procurar e Instalar
3. Reiniciar Anki

## 📈 Métricas de Sucesso Nível 2

### Mês 1
- [ ] 3+ baralhos organizados
- [ ] 100+ cards com tags
- [ ] 4 análises semanais feitas
- [ ] 30+ cards/dia consistente

### Mês 2-3
- [ ] 5+ baralhos temáticos
- [ ] Sistema de tags funcionando
- [ ] Taxa retenção > 85%
- [ ] Tempo < 5 seg/card

### Mês 4
- [ ] 1000+ cards ativos
- [ ] Análise preditiva funcionando
- [ ] 40+ cards/dia
- [ ] Pronto para Nível 3

## 💡 Dicas Pro Nível 2

### Sobre Organização
> "Um baralho desorganizado é como uma biblioteca bagunçada. Você tem o conhecimento, mas não consegue acessá-lo eficientemente."

### Sobre Tags
> "Tags são seu sistema de busca pessoal. Use-as para criar 'playlists' de estudo."

### Sobre Análise
> "Medir é melhorar. Sem dados, você está apenas adivinhando."

## ⚠️ Erros Comuns no Nível 2

### ❌ Evite
- Criar baralhos demais (máx 10)
- Tags muito específicas
- Ignorar estatísticas
- Cards muito complexos
- Configurações muito agressivas

### ✅ Faça
- Baralhos bem organizados
- Tags genéricas e úteis
- Análise semanal religiosa
- Cards claros e diretos
- Ajustes graduais

## 🎯 Quando Evoluir para Nível 3?

Você está pronto quando:
- ✅ 120+ dias de uso consistente
- ✅ 1000+ cards ativos
- ✅ 5+ baralhos organizados
- ✅ Sistema de tags eficiente
- ✅ Análise semanal automática
- ✅ Taxa retenção > 85%
- ✅ Domina todos os tipos de cards

## 🆘 Troubleshooting

### "Tenho muitos cards acumulados"
- Crie baralho filtrado com os atrasados
- Estude 100 extras por dia até zerar
- Reduza novos cards temporariamente

### "Minha retenção está baixa"
- Reduza novos cards
- Diminua multiplicador para 200%
- Revise cards problemáticos
- Melhore cards confusos

### "Demora muito tempo"
- Seja mais direto nas respostas
- Use atalhos de teclado
- Elimine cards desnecessários
- Foque no essencial

## 📚 Próximos Passos

1. **Reorganize** seus baralhos atuais
2. **Implemente** o sistema de tags
3. **Configure** settings específicos
4. **Comece** análise semanal
5. **Quando dominar**, veja [evolucao.md](./evolucao.md)

---

💪 **Lembre-se**: Nível 2 é sobre ORGANIZAÇÃO e OTIMIZAÇÃO. Transforme seu sistema básico em uma máquina de aprendizado!
