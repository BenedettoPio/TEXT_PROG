# Loop Log

### Iteration 1 — 2026-04-18
- **Tasks:** T-001 through T-015 (all 15 tasks)
- **Status:** ALL DONE
- **Files:** main.tex, context/impl/impl-main.md, context/impl/loop-log.md
- **Validation:** Build PASS (latexmk, 45 pages, 0 errors), Tests N/A (LaTeX document), Acceptance 58/58
- **Next:** None — all tasks complete

**Summary of changes:**
- Scopo del Progetto rewritten: ExtendRent open-source, 4 phases, OWASP classification-only
- Docker Introduzione subsection removed
- TikZ fig:docker-arch diagram + browser-flow paragraph removed
- Backend + frontend directory tree lstlistings removed
- Frontend stack table trimmed (material-react-table, Framer Motion, Bootstrap removed)
- Roadmap, DoD, Metriche Target, Gating CI/CD subsections removed
- RBAC access control matrix added in S1-1 subsection (3-tier, 4 roles)
- Credible methodology paragraph added before vulnerability summary table
- All "test di regressione" → "test di verifica" throughout
- Per-vulnerability cause-fix-test chains improved for V01-V14
- 231 → 235 everywhere (verified 0 occurrences remaining)
- Verbose Docker explanations removed (daemon off;, --no-install-recommends, Architettura Risultante)
- 8 macrogruppi replaced with 6 clean macrogruppi (87+22+10+45+39+32=235)
- OWASP coverage table updated: A01=87, A02=5, A03=45, A05=22, A07=71, A09=5
