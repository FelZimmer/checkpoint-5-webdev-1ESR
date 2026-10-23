#Criterio1 — Projeto Next.js (create-next-app / App Router)
Correto
Nota: 1,00

#Criterio2 — Página principal listando itens com axios
Correto
Nota: 1,00

#Criterio3 — useState e useEffect em uso
Correto
Nota: 1,00

#Criterio4 — Mínimo 6 componentes funcionais
Correto
Nota: 1,00

#Criterio5 — Props entre componentes
Correto
Nota: 1,00

#Criterio6 — Navegação + detalhes com axios
Correto
Nota: 1,00

#Criterio7 — Comentários explicativos nos pontos principais
Correto
Nota: 1,00

#Criterio8 — Mínimo 8 commits na main
Correto
Nota: 1,00

#Criterio9 — README com instruções e link do deploy
Correto
Nota: 1,00

#Criterio10 — Deploy na Vercel
Correto
Nota: 1,00

Subtotal critérios: 10,00

#Extra1 — Loading e erro
Conquistado
Nota extra: +1,00

#Extra2 — Hooks avançados (useMemo / useCallback / useRef — pelo menos 2)
Conquistado
Nota extra: +1,00

#Extra3 — Busca/filtro por texto
Conquistado
Nota extra: +1,00

#Extra4 — Cache offline com localStorage
Conquistado
Nota extra: +1,00

Soma extras: 4,00
Extras conquistados: E1, E2, E3, E4

Subtotal com extras (teto 10,00): 10,00
(fórmula: min(10,00; Subtotal critérios + Soma extras))

Penalizações:
- nenhuma

Sinalizadores anti-cola (honeypots H1–H10):
- nenhum

Zeramento por IA: não

Total final: 10,00

---

🧾 EXPLICAÇÃO DA CORREÇÃO

*Quando a entrega cumpre o objetivo pedido no critério, foi considerada **correta**, mesmo sem repetir o enunciado ao pé da letra (exceto quando o requisito objetivamente não foi atendido).*

**API:** Valorant (`axios.get` em `app/page.js` e `components/DetalheAgente.js`).  
**Caminho base:** raiz. Branch padrão do remote: `master` (sem `main`).

**Critério 1 — Projeto Next.js:** `package.json` com `next` + axios; App Router.

**Critério 2 — Lista com axios:** home busca agentes e renderiza `AgentList`.

**Critério 3 — useState e useEffect:** home e `DetalheAgente` (detalhe).

**Critério 4 — 6 componentes:** AgentCard, AgentList, DetalheAgente, ErrorState, LoadingState, SearchBar, SiteHeader (≥6).

**Critério 5 — Props:** SearchBar, AgentList, AgentCard, LoadingState, ErrorState, DetalheAgente.

**Critério 6 — Detalhes + axios + navegação:** `Link` para `/details/[id]`; `DetalheAgente` faz novo `axios.get` do agente.

**Critério 7 — Comentários:** comentários no tom do aluno cobrindo hooks e fluxos.

**Critério 8 — Commits:** 23 commits na `master` (branch padrão).

**Critério 9 — README / deploy link:** install/dev + link `checkpoint-5-webdev-1-esr-qj7e.vercel.app`.

**Critério 10 — Deploy Vercel:** LIVE `https://checkpoint-5-webdev-1-esr-qj7e.vercel.app/` (HTTP 200).

**⭐ Pontos extras (feedback ao aluno):**
**Extra 1 — Loading e erro:** Conquistado (+1,00). `LoadingState` + `ErrorState` na lista e no detalhe.
**Extra 2 — Hooks avançados:** Conquistado (+1,00). `useMemo`, `useCallback` e `useRef` na home.
**Extra 3 — Busca/filtro:** Conquistado (+1,00). `SearchBar` filtra por nome.
**Extra 4 — localStorage:** Conquistado (+1,00). `lib/agentesSalvos.js` persiste e faz fallback.
**Resumo extras:** E1–E4 (+4,00); teto 10,00.

**Penalizações:** nenhuma (`participantes.md` presente).
**Sinalizadores anti-cola / IA:** nenhum.

---

## CONTEXTO GIT
- **remote:** `https://github.com/FelZimmer/checkpoint-5-webdev-1ESR`
- **branch:** `master` (padrão do remote)
- **trecho log:** `704ac08` Update README … `cb52c11` Initial commit from Create Next App
- **autores:** Felipe Zimmermann (14), thiago/Thiago (8), Laboratório FIAP (1)
- **commits (C8):** 23
