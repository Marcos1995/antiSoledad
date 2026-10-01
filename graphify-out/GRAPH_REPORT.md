# Graph Report - antiSoledad  (2026-10-01)

## Corpus Check
- 13 files · ~8,000 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 2 file(s) not represented in the graph (top: .mdc 2)

## Summary
- 53 nodes · 40 edges · 13 communities (8 shown, 5 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `18cda6a7`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Web design
- Debug
- Contexto del proyecto
- Verify (UI)
- Agent rules
- Build judgments with Laya
- Laya
- Review
- antiSoledad
- DESIGN.md
- DECISIONES.md

## God Nodes (most connected - your core abstractions)
1. `Web design` - 8 edges
2. `Debug` - 6 edges
3. `Contexto del proyecto` - 6 edges
4. `Verify (UI)` - 4 edges
5. `Build judgments with Laya` - 3 edges
6. `Laya` - 3 edges
7. `Review` - 3 edges
8. `Agent rules` - 3 edges
9. `antiSoledad` - 2 edges
10. `1. Root cause` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (13 total, 5 thin omitted)

### Community 0 - "Web design"
Cohesion: 0.22
Nodes (8): 0. Brief (30 s, don't ask the user), 1. Style = `DESIGN.md`, 2. Tokens (pick, don't invent), 3. Layout recipes, 4. Starter CSS (adapt; delete what you don't use), 5. Build rules, 6. Before HECHO, Web design

### Community 1 - "Debug"
Cohesion: 0.29
Nodes (6): 1. Root cause, 2. Compare, 3. Hypothesis, 4. Fix, Debug, Red flags → back to step 1

### Community 2 - "Contexto del proyecto"
Cohesion: 0.29
Nodes (6): Comandos utiles, Contexto del proyecto, Estado, Notas para el agente, Produccion, Stack

### Community 3 - "Verify (UI)"
Cohesion: 0.40
Nodes (4): 1. Screenshots, 2. Look, 3. Fix and repeat, Verify (UI)

### Community 4 - "Agent rules"
Cohesion: 0.50
Nodes (3): Agent rules, Flujo, Think → Simple → Surgical → Verify (Karpathy)

### Community 5 - "Build judgments with Laya"
Cohesion: 0.50
Nodes (3): Build judgments with Laya, Call, Design

### Community 6 - "Laya"
Cohesion: 0.50
Nodes (3): Laya, Reply (decision-only requests), Steps

### Community 7 - "Review"
Cohesion: 0.50
Nodes (3): Check, Do, Review

## Knowledge Gaps
- **31 isolated node(s):** `1. Root cause`, `2. Compare`, `3. Hypothesis`, `4. Fix`, `Red flags → back to step 1` (+26 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 44 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `1. Root cause`, `2. Compare`, `3. Hypothesis` to the rest of the system?**
  _31 weakly-connected nodes found - possible documentation gaps or missing edges._