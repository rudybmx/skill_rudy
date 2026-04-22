# Business Scale Frameworks

## Princípios fundamentais de escala

**Lei central:** Um negócio que depende de você não é um negócio — é um emprego.
Tudo que você faz repetidamente mais de 3x deve virar sistema, processo ou agente.

---

## Frameworks principais

### EOS / Traction (Gino Wickman)
Seis componentes de um negócio saudável:
1. **Visão** — todos sabem para onde vão e por quê
2. **Pessoas** — pessoas certas nos lugares certos (não os melhores, os certos)
3. **Dados** — scorecard semanal com 5-15 números que dizem a verdade
4. **Issues** — problemas identificados, priorizados e resolvidos (IDS: Identify, Discuss, Solve)
5. **Processos** — os 20% dos processos que geram 80% dos resultados, documentados
6. **Tração** — disciplina de execução (90-day rocks, weekly meetings, quarterly reviews)

**Aplicação prática no Qózt:** Qual dos 6 está mais fraco agora? Comece por aí.

---

### OKR (Doerr / Google)
- **Objective:** qualitativo, inspirador, claro
- **Key Results:** 3-5 métricas mensuráveis que provam o objetivo foi atingido
- Ciclo: trimestral para empresa, semanal para revisão

**Regra:** Se não dói um pouco de escrever o KR, não é ambicioso o suficiente.
**Anti-padrão:** OKR como lista de tarefas → KR deve ser resultado, não ação.

---

### 80/20 (Pareto aplicado)
- 20% dos clientes → 80% da receita. Identifique. Sirva melhor.
- 20% das features → 80% do valor entregue. Construa isso primeiro.
- 20% das atividades → 80% dos resultados. Proteja esse tempo.

**Pergunta-gatilho:** "Se eu só pudesse fazer uma coisa hoje, qual moveria mais o ponteiro?"

---

### Flywheel (Jim Collins)
Não há um único momento de virada — é empurrão consistente na direção certa.
Identifique o volante do seu negócio: qual ação gera momentum que alimenta a próxima?

Exemplo Qózt:
```
Clientes satisfeitos → cases reais → novos clientes → mais dados → agentes melhores → clientes mais satisfeitos
```

---

### Second-Order Thinking (Dalio / Munger)
Antes de qualquer decisão importante: "E depois disso, o que acontece?"
Repita 2-3x.

Exemplo: "Vou cobrar mais barato para fechar logo"
→ 1ª ordem: fecha mais rápido
→ 2ª ordem: cliente não valoriza, demanda mais suporte, margem cai, menos energia para bons clientes
→ 3ª ordem: reputação de "barato", difícil reposicionar

---

### Inversão (Munger)
Em vez de "como ter sucesso?" pergunte "como garantir o fracasso?"
Liste o que destruiria o negócio → evite isso ativamente.

---

## Métricas que importam por estágio

**Early stage (Qózt atual):**
- MRR e crescimento MoM
- Churn rate
- CAC vs LTV
- NPS (qualitativo no começo)
- Horas do fundador em trabalho repetível (deve cair mês a mês)

**Growth stage:**
- Revenue per employee
- Payback period
- Net Revenue Retention
- Lead velocity rate

---

## Tecnologia como alavanca de escala

Cada processo humano repetível é candidato a automação.
Prioridade: alto volume + baixa variação → automatize primeiro.

Matrix de decisão:
```
Alta variação + Alto valor     → Humano + IA assistindo
Alta variação + Baixo valor    → Elimine ou simplifique
Baixa variação + Alto volume   → Automatize (n8n, agente)
Baixa variação + Baixo volume  → Template ou checklist
```
