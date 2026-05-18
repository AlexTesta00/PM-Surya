# Issue Log e Trello

## 1. Struttura Issue Log

L’Issue Log registra problemi, blocchi e anomalie. È fondamentale in un progetto breve, perché anche piccoli ritardi possono compromettere il go-live del 1 giugno 2026.

## 2. Campi

| Campo | Descrizione |
|---|---|
| ID | Codice issue |
| Data | Data apertura |
| Descrizione | Problema |
| Priorità | Critica, alta, media, bassa |
| Impatto | Tempi, costi, qualità o scope |
| Owner | Responsabile |
| Stato | Colonna Trello |
| Deadline | Data risoluzione |
| Azione | Prossimo passo |

## 3. Issue

| ID | Data | Descrizione | Priorità | Impatto | Owner | Stato | Deadline | Azione |
|---|---|---|---|---|---|---|---|---|
| ISS-01 | 10/04/2026 | Template scheda prodotto non approvato | Alta | Ritardo catalogo | Content Specialist | `Review Surya` | 12/04 | Approvazione rapida |
| ISS-02 | 17/04/2026 | 30 prodotti senza immagini idonee | Alta | Qualità catalogo | E-commerce Specialist | `In Progress` | 24/04 | Sostituire prodotti |
| ISS-03 | 22/04/2026 | Varianti non uniformi | Media | Errori prodotto | E-commerce Specialist | `In Progress` | 30/04 | Normalizzare SKU |
| ISS-04 | 28/04/2026 | App proposta supera budget ricorrente | Alta | Budget annuo | PM | `Backlog` | 02/05 | Valutare alternativa gratuita |
| ISS-05 | 04/05/2026 | Policy resi incompleta | Alta | Compliance/go-live | Legal/GDPR | `To Do` | 08/05 | Revisione finale |
| ISS-06 | 08/05/2026 | Tariffe spedizione da validare | Media | Checkout | Shopify Specialist | `Testing` | 12/05 | Ordini test |
| ISS-07 | 12/05/2026 | Analytics non registra evento checkout | Alta | KPI | Marketing Specialist | `In Progress` | 16/05 | Verifica tracking |

Tutte le issue in fase di closing sono state risolte.

## 4. Trello

| Colonna | Significato |
|---|---|
| Backlog | Attività registrate ma non pianificate |
| To Do | Attività da eseguire nell’iterazione corrente |
| In Progress | Attività in lavorazione |
| Review Surya | Richiede approvazione Surya |
| Testing | Completata ma da verificare |
| Done | Completata secondo Definition of Done |
| Blocked | Bloccata da dipendenza o decisione |

## 5. Regole WIP

Regola la quantità di flusso di lavoro massimo

| Colonna | Limite |
|---|---:|
| To Do | 8 |
| In Progress | 4 |
| Review Surya | 4 |
| Testing | 4 |
| Blocked | Review obbligatoria entro 24 ore |

Con una sola persona interna formata, il WIP deve restare basso per evitare sovraccarico.

## 6. Criteri passaggio stati

| Passaggio | Criterio |
|---|---|
| Backlog → To Do | Priorità confermata |
| To Do → In Progress | Owner assegnato |
| In Progress → Review Surya | Output pronto |
| Review Surya → Testing | Approvazione ricevuta |
| Testing → Done | Test superato |
| Qualsiasi → Blocked | Dipendenza non risolta |
| Blocked → In Progress | Blocco rimosso |

## 7. Gestione blocchi

Un blocco deve indicare:

- Causa;
- Impatto;
- Owner;
- Decisione richiesta;
- Deadline.

Esempio:

~~~text
ISS-08 - Catalogo fermo a 132 prodotti
Causa: mancano immagini idonee.
Impatto: rischio go-live.
Owner: E-commerce Specialist.
Azione: sostituire 18 prodotti con articoli già fotografati.
Deadline: 19 maggio 2026.
~~~