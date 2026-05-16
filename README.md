# TCOFLEET — Fleet TCO Dashboard

Dashboard self-contained per la gestione del Total Cost of Ownership della flotta aziendale.

## File principale

**`index.html`** — Versione più recente con tutte le funzionalità:
- ERP Handoff: export CSV/JSON strutturato per contabilità
- Cost Centre per veicolo (persistito in localStorage)
- Period Lock: snapshot di fine trimestre per riconciliazione
- Internal Targets CFO: obiettivi interni modificabili
- Action Triggers su ogni KPI
- Renegotiation Triggers: veicoli oltre soglia €500/anno
- Vintage Narrative: segnale di sostituzione per anno immatricolazione
- Smart Actions: swap veicoli, candidati all'acquisto
- Tab Drivers, Leasing Contracts, CFO View

## Utilizzo

Aprire `index.html` direttamente nel browser — nessun server necessario.

## Versioni precedenti

| File | Descrizione |
|------|-------------|
| `fleet_tco_smart_actions.html` | Versione con Smart Actions |
| `fleet_tco_en_leasing.html` | Versione con Leasing tab |
| `fleet_tco_dashboard.html` | Dashboard originale |
| `fleet_tco_dashboard_offline.html` | Versione offline |

## Dati sorgente

| File | Descrizione |
|------|-------------|
| `flotta_aziendale.csv` | Anagrafica flotta |
| `fatture_leasing.xlsx` | Fatture leasing |
| `fatture_carburante.xlsx` | Fatture carburante |
| `fatture_officina.xlsx` | Fatture officina |
| `riepilogo_trimestrale.xlsx` | Riepilogo Q2 2025 |
