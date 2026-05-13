# Analisi dei rischi

## 1. Metodologia

L’analisi utilizza una matrice probabilità/impatto da 1 a 5.

| Valore | Probabilità | Impatto |
|---:|---|---|
| 1 | Molto bassa | Trascurabile |
| 2 | Bassa | Limitato |
| 3 | Media | Moderato |
| 4 | Alta | Significativo |
| 5 | Molto alta | Critico |

Livello rischio = Probabilità x Impatto.

| Livello | Categoria |
|---:|---|
| 1 - 5 | Basso |
| 6 - 10 | Medio |
| 11 - 15 | Alto |
| 16 - 25 | Critico |

## 2. Risk Register

| ID | Rischio | Prob. | Imp. | Livello | Categoria | Mitigazione | Owner |
|---|---|---:|---:|---:|---|---|---|
| R1 | Catalogo prodotti incompleto | 4 | 5 | 20 | Critico | Selezione anticipata, template schede, priorità ai prodotti pronti | E-commerce specialist |
| R2 | Fotografie non coerenti | 4 | 4 | 16 | Critico | Usare standard minimo e rimandare prodotti non idonei | Content Specialist |
| R3 | Sottostima lavoro contenutistico | 4 | 4 | 16 | Critico | Limitare descrizioni, usare template, controlli settimanali | PM |
| R4 | Budget setup insufficiente | 3 | 5 | 15 | Alto | Bloccare Could, evitare custom, usare tema standard | PM |
| R5 | Budget ricorrente oltre 3.000 euro | 3 | 4 | 12 | Alto | App approval, revisione costi annuali, limitare app | PM |
| R6 | Una sola persona formata | 4 | 4 | 16 | Critico | Manuale operativo, video guida, supporto esterno leggero | PM |
| R7 | Resistenza operativa interna | 3 | 3 | 9 | Medio | Formazione pratica e processi semplici | Proprietà Surya |
| R8 | Problemi GDPR/cookie | 3 | 5 | 15 | Alto | Coinvolgere consulente legale entro aprile | Legal/GDPR |
| R9 | Problemi pagamento | 2 | 5 | 10 | Medio | Ordini test e fallback metodo pagamento | Shopify Specialist |
| R10 | Problemi spedizione/resi | 3 | 4 | 12 | Alto | Policy chiare e test tariffe | Shopify Specialist |
| R11 | Dipendenza da Shopify | 3 | 3 | 9 | Medio | Export dati, documentazione, limitare personalizzazioni | PM |
| R12 | Personalizzazione limitata | 3 | 3 | 9 | Medio | Accettare tema MVP, roadmap futura | UX/UI |
| R13 | Traffico iniziale insufficiente | 4 | 4 | 16 | Critico | Newsletter, social organico, campagne leggere, SEO base | Marketing |
| R14 | Stock non sincronizzato con store fisici | 4 | 4 | 16 | Critico | Stock dedicato o aggiornamento manuale giornaliero | E-commerce specialist |
| R15 | Ritardi fornitore | 3 | 4 | 12 | Alto | Milestone brevi e deliverable settimanali | PM |
| R16 | Scope creep | 4 | 5 | 20 | Critico | Change control, MoSCoW, esclusione loyalty/multilingua | PM |
| R17 | Aspettative irrealistiche ricavi | 3 | 4 | 12 | Alto | Break-even 12-18 mesi, KPI realistici | PM |
| R18 | Errori prezzi/varianti | 3 | 4 | 12 | Alto | Revisione campione, checklist catalogo | E-commerce specialist |
| R19 | Mobile experience debole | 3 | 4 | 12 | Alto | Test mobile obbligatorio | UX/UI |
| R20 | Customer care non strutturato | 3 | 3 | 9 | Medio | FAQ e template risposta | E-commerce specialist |

## 5. Analisi rischi per alternativa

| Alternativa | Rischio tecnico | Rischio economico | Rischio operativo | Valutazione |
|---|---|---|---|---|
| Shopify | Basso/medio | Medio | Medio | Raccomandato con controllo app e scope |
| Custom | Alto | Molto alto | Alto | Non compatibile con vincoli |
| WooCommerce | Medio | Medio/alto | Medio/alto | Richiede presidio tecnico |
| Marketplace/social | Basso | Medio | Medio | Supporto utile, non proprietario |
| Do nothing | Basso tecnico | Basso breve termine | Alto strategico | Non raccomandato |

## 6. Strategie di mitigazione

| Strategia | Applicazione |
|---|---|
| Evitare | Escludere custom, loyalty, multilingua, integrazione POS dal MVP |
| Mitigare | Template catalogo, test, formazione, checklist |
| Trasferire | Usare Shopify per ridurre gestione tecnica |
| Accettare | Limiti di personalizzazione e canoni ricorrenti |
| Monitorare | Issue log, report settimanale, KPI post-lancio |

## 7. Rischi prioritari

I rischi da monitorare ogni settimana sono:

1. Catalogo incompleto;
2. Scope creep;
3. Budget ricorrente oltre 3.000 euro;
4. Una sola persona formata;
5. Stock non sincronizzato;
6. Traffico iniziale basso;
7. GDPR/cookie.