# ROADMAP — Zoran aSiM (Grok Session Proofs & Safeguards)

Dernière màj : 2025-08-20

## 1) Vision & objectifs
Transformer le scepticisme en preuves vérifiables. Axes : sécurité (ΔM11.3, Merkle), propagation maîtrisée (TTL, whitelist), métriques publiques, gouvernance ouverte, reproductibilité.

## 2) Indicateurs (SLO/SLA)
- Latence p95 ≤ 120 ms
- Stabilité ≥ 99.5 %
- Cohérence de phase ≥ 92 %
- Rollback ΔM11.3 ≥ 95 %
- Incidents : ACK <1h, Mitigation <24h, Post-mortem <72h

## 3) Jalons (Milestones)
- M1 Sécurité avancée : PQC, rate limiting, alertes hors scope
- M2 Gouvernance externe : comité éthique, bug bounty, DPIA validé
- M3 Validation tierce : datasets publics, réplication externe, red-team report
- M4 Fiabilité : SLA chiffrés, stress-tests multi-agents, dashboard metrics
- M5 Propagation : TTL prod, whitelist dynamique, anti-consanguinité amélioré
- M6 Communication : README menaces→contre-mesures, changelog automatisé, White Paper v2

## 4) CI/CD
- CI tests + metrics demo + Merkle root
- Publish metrics (cron + manual)
- GitHub Pages pour metrics

## 5) Sécurité & gouvernance
- SECURITY.md, RESPONSIBLE_DISCLOSURE.md, CODEOWNERS
- Red-team plan, comité éthique, bug bounty

## 6) Conformité
- AI Act, RGPD, NIST, ISO/IEC → docs compliance_map.md, harm_matrix.json

## 7) Datasets & reproductibilité
- datasets/* + scripts stdlib-only

## 8) Publication & releases
- Versioning, release notes Merkle-signed

## 9) Communication
- README menaces→contre-mesures
- Pages docs/metrics

## 10) Labels & Projects
- Labels : security, governance, metrics, reliability, doc, dataset, etc.
- Project Kanban

## 11) Annexes
- ISSUE_TEMPLATE : bug_report, feature_request, security_report, red_team_findings
- Workflows : ci.yml, publish-metrics.yml, pages.yml
