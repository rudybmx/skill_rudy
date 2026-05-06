# Project Planning Framework

## Princípio central
Projetos falham por falta de clareza no início, não por falta de esforço no meio.
Defina antes de executar. Sempre.

---

## Template de projeto (mínimo viável)

```
PROJETO: [nome]
OBJETIVO: [resultado específico e mensurável]
CRITÉRIO DE SUCESSO: [como você sabe que está pronto?]
DEADLINE: [data real, não "assim que possível"]
RESPONSÁVEL: [pessoa única — não "o time"]
DEPENDÊNCIAS: [o que precisa estar pronto antes?]
RISCOS: [top 3 que podem atrasar ou matar o projeto]
PRÓXIMA AÇÃO: [ação física específica, não "pensar sobre"]
```

---

## Framework de execução (90-Day Rocks — EOS)

Ciclo trimestral:
1. **Define 3-5 "rocks"** — projetos que, se concluídos, movem o negócio significativamente
2. **Cada rock tem** dono único + critério de conclusão + data (final do trimestre)
3. **Review semanal** — cada rock é "on track" ou "off track" (sem meio-termo)
4. **Desbloqueio imediato** — off track → o que está bloqueando? Resolva essa semana

---

## Sprint rápido (para agentes e automações)

Para projetos de 1-4 semanas (como a maioria dos projetos Qózt):

**Semana 1:** Define + prototipa mínimo funcional
**Semana 2:** Integra + testa com dado real
**Semana 3:** Ajusta + documenta
**Semana 4:** Entrega + monitora

Anti-padrão: semana 4 vira semana 8 porque o "mínimo" cresceu.
Regra: congele o escopo na Semana 1. Tudo novo entra no próximo ciclo.

---

## Decomposição de projetos complexos

Para projetos com mais de 1 semana de trabalho:

1. **Epic** → objetivo grande
2. **Features** → capacidades que compõem o epic
3. **Tasks** → ações físicas específicas (verbos de ação: "criar", "configurar", "testar")

Nunca escreva task como "pensar em X" ou "analisar Y" — essas são pseudo-tarefas.
Task real: "Escrever o SQL query para X" | "Configurar webhook Y no n8n"

---

## Gestão de contexto para agentes

Quando criando projetos de agentes IA para clientes:

**Pré-projeto (define com cliente):**
- Qual o processo atual? (mapear o fluxo manual)
- Qual o gatilho de entrada? (WhatsApp, formulário, evento?)
- Qual o output esperado? (mensagem, registro, ação?)
- Quais são os edge cases críticos? (top 3)
- Como mede sucesso? (tempo poupado? erros reduzidos? leads convertidos?)

**Durante o projeto:**
- Documente as decisões tomadas (não só o código)
- Teste com dado real desde o dia 1
- Identifique o que vai quebrar na escala 10x

**Pós-entrega:**
- Defina quem monitora
- Documente o runbook (o que fazer quando quebrar)
- Agende revisão em 30 dias

---

## Priorização quando tudo parece urgente

1. Liste tudo que está "urgente"
2. Para cada item: "Se eu não fizer isso esta semana, o que acontece?"
3. Itens onde a resposta é "nada grave" → não são urgentes
4. Dos realmente urgentes: qual tem maior impacto × menor esforço? Começa por aí.

Ferramenta: matriz de impacto × esforço
```
        BAIXO ESFORÇO    ALTO ESFORÇO
ALTO    | Quick wins    | Projetos grandes
IMPACTO | (faça logo)   | (planeje bem)
BAIXO   | Fill-ins      | Evite
IMPACTO | (se sobrar)   | (não faça)
```
