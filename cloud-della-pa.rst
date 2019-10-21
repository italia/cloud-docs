Il Cloud della PA
------------------

Perché la PA ha deciso di definire e adottare un modello cloud *ad hoc*
denominato “Cloud della PA”?

Non tutti i servizi e le infrastrutture di cloud computing sono uguali. In
alcuni casi tali servizi possono anche non rispettare i principali standard di
sicurezza, garanzie operative e affidabilità definiti a livello internazionale.
Questa disomogeneità può rappresentare un rischio quando si affidano i propri
dati a provider che non garantiscono dei livelli minimi di sicurezza e
affidabilità.

Il modello *Cloud della PA* consente di mitigare tale rischio, qualificando
servizi e infrastrutture cloud secondo specifici parametri di sicurezza e
affidabilità idonei per le esigenze della PA, nel rispetto dei seguenti
principi:

- miglioramento dei livelli di servizio, accessibilità, usabilità e 
  sicurezza;
- interoperabilità dei servizi nell’ambito del modello Cloud della PA;
- riduzione del rischio di «vendor lock-in»;
- riqualificazione dell’offerta, ampliamento e diversificazione del 
  mercato dei fornitori;
- resilienza, scalabilità, «reversibilità» e protezione dei dati;
- apertura del mercato alle Piccole e Medie Imprese (PMI).

Il Cloud della PA si compone di infrastrutture e servizi, qualificati da AgID
sulla base di un insieme minimo di requisiti, secondo il modello riportato di
seguito. Inoltre, servizi e infrastrutture sono consultabili e confrontabili
mediante una piattaforma dedicata, il *Cloud Marketplace*, una volta conseguita
la qualificazione AgID secondo quanto descritto nelle `circolari AgID n.2 e n.3
del 2018 <https://cloud.italia.it/it/latest/>`_.

.. figure:: media/modello-cloud-pa.png
   :alt: Modello del Cloud della PA

   Le componenti del modello del Cloud della PA

Il Cloud della PA è un modello cloud fortemente *misto* che include
infrastrutture e servizi di tipo: **Public Cloud** [1]_, l’offerta dei Cloud
Service Provider pubblici qualificati da AgID; **Private Cloud** [2]_, le
infrastrutture e servizi erogati dai PSN; **Community Cloud** [3]_, i servizi
`SPC Cloud Lotto 1 <https://www.cloudspc.it>`__. Questo modello consente di
soddisfare le diverse e complesse esigenze del settore pubblico.

Le infrastrutture qualificate si suddividono in tre categorie:

- Poli strategici nazionali o PSN: l’insieme delle infrastrutture IT 
  (centralizzate o distribuite), ad alta disponibilità, di proprietà dello 
  Stato, elette a Polo Strategico Nazionale dalla Presidenza del Consiglio 
  dei Ministri ed in grado di erogare, in maniera continuativa, servizi 
  cloud e hosting ad altre amministrazioni;
- Cloud Service Provider o CSP: le infrastrutture e i servizi di *Public 
  Cloud* offerti dai cloud service provider qualificati da AgID;
- SPC Cloud: i servizi cloud infrastrutturali erogati nell’ambito del 
  contratto quadro Consip - Cloud SPC Lotto 1.

I servizi SaaS del *Cloud della PA* devono necessariamente essere erogati
mediante una o più infrastrutture qualificate.

I criteri di scelta dei servizi cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Il modello Cloud della PA fornisce una visione unitaria delle diverse tipologie
di servizi previste per la PA. Il modello si ispira al principio **Cloud First**
che propone di valutare l’adozione del paradigma cloud prima delle soluzioni
tradizionali (generalmente basate su servizi di hosting o housing).

Al fine di selezionare, nell’ambito del Cloud della PA, il servizio e la
modalità di erogazione più rispondenti alle esigenze dell’Amministrazione è
opportuno applicare *la preferenza* **SaaS First** , ovvero indirizzare la
propria scelta sui servizi SaaS già presenti e attivi nel Marketplace Cloud, se
conformi alle necessità dell’amministrazione. La scelta dei servizi SaaS
consente di beneficiare in pieno dei vantaggi offerti dal paradigma cloud e di
ridurre drasticamente costi e sforzi amministrativi, in quanto non necessita di
attività tecnica di gestione e sviluppo dedicato, cosa necessaria invece con
l’acquisizione di servizi IaaS e PaaS.

Nel caso in cui, invece, non fossero disponibili servizi SaaS specifici, la
scelta dei servizi IaaS e PaaS può avvenire sempre mediante il Cloud
Marketplace.

Diventa, quindi, cruciale individuare quale delle tre tipologie di
infrastrutture qualificate scegliere, tale scelta è indirizzata da 2 fattori:

- la finalità del servizio all’utente e la tipologia di dati trattati;
- le caratteristiche commerciali del servizio cloud.

Non si tratta di una scelta tecnologica, in quanto le infrastrutture qualificate
sono tutte tecnicamente omogenee come previsto dal Piano Triennale e in
particolare dalla qualificazione delle infrastrutture.

Nella maggior parte dei casi in cui il servizio richiesto non gestisce dati di
particolare rilevanza per la sicurezza nazionale la PA potrà ricorrere
all’utilizzo di servizi commerciali o pubblici (*public cloud CSP o community
cloud SPC*) dove la scelta sarà guidata esclusivamente dalle caratteristiche di
qualità e prezzo offerte dai fornitori CSP o SPC, nel rispetto della normativa
vigente in ambito di acquisizione di beni e servizi.

Nel caso dei PSN, vista la rilevanza e i costi correlati di tali infrastrutture
sarà cura del Governo valutare e disporre quali servizi considerati asset strategici 
nazionali dovranno essere erogati per mezzo degli stessi.

SaaS e interoperabilità
^^^^^^^^^^^^^^^^^^^^^^^

Quando i servizi SaaS sono erogati da una PA tramite API conformi alle 
Linee Guida di Interoperabilità, si hanno dei vantaggi 
in termini di uniformità dei modelli di dato e del rispetto delle indicazioni 
sulla gestione della disponibilità del servizio.
In questo caso l'interoperabilità dell'erogatore SaaS "contagia" 
l'implementazione del fruitore, incentivando la creazione di
nuovi servizi conformi (eg. quando le API vengono usate per creare a loro volta nuovi servizi).
Per innescare questo circolo virtuoso è fondamentale che tutte 
le API della PA si adeguino alle Linee Guida di Interoperabilità.

Il Marketplace delle infrastrutture e dei servizi cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Servizi e infrastrutture qualificate del Cloud della PA sono esposti e
consultabili mediante il *Marketplace Cloud*, una piattaforma che consentirà di
visualizzare la scheda di ogni servizio mettendo in evidenza le caratteristiche,
il costo e i livelli di servizio dichiarati dal fornitore. Le PA possono
confrontare servizi analoghi e decidere, in base alle loro esigenze, le
soluzioni più adatte. Il Marketplace indica anche le modalità di acquisizione
con cui uno specifico servizio potrà essere acquisito da una amministrazione
rimandando allo strumento di procurement disponibile (p.e. portale
`acquistinretepa.it <https://www.acquistinretepa.it/>`_ ) per procedere con
l’acquisizione.

.. important:: 

   A decorrere dal 1 aprile 2019, le Amministrazioni Pubbliche possono acquisire
   esclusivamente servizi IaaS, PaaS e SaaS qualificati da AgID e pubblicati nel
   Catalogo dei servizi Cloud per la PA qualificati.
   
Per maggiori informazioni si rimanda alle `Circolari AgID 2/2018 e 3/2018
<https://cloud.italia.it/projects/cloud-italia-circolari/it/latest/>`_.

La qualificazione dei Servizi cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. highlights::
   Le procedure di qualificazione dei servizi cloud sono state definite
   cercando di sviluppare un processo semplice e veloce, dove la maggior
   parte dei requisiti di qualificazione possono essere forniti in forma
   di autocertificazione.

   La procedura di qualificazione e tutti i requisiti previsti sono stati
   definiti dalle `Circolari AgID n. 2 e n.3 del 9 aprile 2018 
   <https://cloud.italia.it/it/latest/>`_, cui si rimanda per le
   informazioni di dettaglio.

Servizi SaaS
^^^^^^^^^^^^

La qualificazione dei servizi SaaS nell’ambito del Cloud della PA assicura il
rispetto di alcuni requisiti, tra cui:

- la **sicurezza** applicativa, in termini di gestione dei dati, sicurezza 
  di rete, aggiornamenti delle vulnerabilità note;
- la disponibilità di un adeguato **supporto tecnico** per il cliente 
  (multicanale, con prefissati e garantiti orari di reperibilità);
- la **trasparenza** e la **disponibilità di informazioni** dettagliate e 
  aggiornate sulle modalità di erogazione del servizio e di esportazione 
  dei dati;
- la **disponibilità di incident report**, statistiche e strumenti di 
  **monitoraggio** delle risorse utilizzate, dei costi e dei livelli di 
  servizio;
- la **qualità del servizio**, con un insieme minimo di livelli di 
  servizio garantiti obbligatori (ad es. disponibilità del servizio, 
  tempistiche di risposta dell’assistenza tecnica), più ulteriori livelli 
  di servizio proposti dal fornitore tipicamente riguardanti la larghezza 
  di banda, i tempi di ripristino del servizio ed altre metriche relative 
  alla capacità di elaborazione;
- la **protezione dei dati** e la **portabilità** in tutte le fasi di 
  avanzamento della fornitura (attivazione del servizio, erogazione del 
  servizio e disattivazione del servizio), con procedure chiare e 
  documentate e tutte le necessarie garanzie per l’utilizzatore del 
  servizio;

- l’**interoperabilità** mediante opportune API che dovranno rifarsi alle 
  migliori pratiche di gestione (API management), prevedendo in 
  particolare la tracciabilità delle versioni disponibili, la  
  tracciabilità delle richieste ricevute ed evase, la documentazione degli 
  endpoint SOAP e/o REST disponibili e delle rispettive modalità di 
  invocazione;
- ridurre il rischio di dipendenza esclusiva dal fornitore (**lock in**), 
  garantendo in tal modo alle PA l’esportabilità dei propri dati in un 
  formato interoperabile verso un’altra piattaforma.

Inoltre, la qualificazione rafforza la richiesta di protezione dei dati, dando
rilievo alla conformità con le prescrizioni previste dalle norme (nazionali ed
europee) in materia di sicurezza informatica e riservatezza dei dati.

Servizi IaaS e PaaS
^^^^^^^^^^^^^^^^^^^

I servizi cloud di tipo IaaS e PaaS consentono di disporre rispettivamente di
risorse virtuali e piattaforme di sviluppo con le quali le amministrazioni
possono sviluppare nuove applicazioni e servizi non disponibili tra i SaaS
presenti nel Marketplace. Inoltre le amministrazioni, laddove indispensabile,
possono virtualizzare le applicazioni tradizionali non predisposte per il
modello cloud.

La **qualificazione dei servizi IaaS e PaaS** pone particolare attenzione ai
seguenti aspetti:

- la **gestione della sicurezza** estesa a tutti gli aspetti che 
  riguardano sia l’infrastruttura che i servizi;
- la **gestione delle configurazioni** e la **gestione dei cambiamenti**, 
  aspetti fondamentali per l’amministrazione di infrastrutture IT 
  complesse;
- la **gestione degli incidenti** e il recovery dell’infrastruttura in 
  seguito ad eventi critici;
- l’**interoperabilità** con altri servizi e altre infrastrutture cloud 
  dello stesso tipo, mediante l’utilizzo di standard aperti (ad es. Open 
  Virtualization Format) ed opportune API.

Per assicurare che tutte queste problematiche vengano gestite correttamente, la
qualificazione richiede che il fornitore e i servizi sottoposti a qualificazione
siano conformi alle buone pratiche previste dai più importanti e diffusi
standard del settore (es. norme UNI, ISO/IEC, ecc.), oltre che, in alcuni casi,
a certificazioni specifiche (es. ISO/IEC 27001).

La qualificazione delle Infrastrutture
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Le infrastrutture IT fisiche e virtuali destinate all’utilizzo da parte della
pubblica amministrazione devono dimostrare di possedere determinati requisiti:

- **organizzativi** - procedure certificate per l’erogazione dei servizi, 
  la gestione di risorse e processi, il supporto agli utenti , la gestione 
  dei cambiamenti;
- **di sicurezza e affidabilità** - definizione dei livelli di servizio, 
  privacy, sicurezza e protezione dei dati;
- **di performance e interoperabilità** - garanzie sulle performance delle 
  infrastrutture e sulla capacità di interoperare con altre infrastrutture 
  analoghe mediante standard aperti, la possibilità di esportare i dati 
  dei servizi erogati in formati aperti.

La verifica del possesso di tali requisiti costituisce una parte fondante del
processo di qualificazione delle infrastrutture IT che possono operare
nell’ambito del Cloud della PA.

Come precedentemente descritto, le infrastrutture qualificate ad erogare i
servizi cloud qualificati possono essere CSP (Cloud Service Provider), `SPC
Cloud Lotto 1 <https://www.cloudspc.it/>`__, PSN (Poli Strategici Nazionali).

Cloud Service Provider qualificati - Public Cloud
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

I Cloud service provider qualificati da AgID possono erogare servizi di tipo
*Public Cloud* alle amministrazioni. Le qualificazioni AgID assicurano che le
infrastrutture e i servizi dei CSP siano sviluppati ed operati secondo criteri
minimi di affidabilità e sicurezza considerati necessari per i servizi digitali
della PA.

La procedura di qualificazione delle **infrastrutture dei CSP** pone particolare
attenzione ai seguenti aspetti:

- la **gestione della sicurezza** estesa a tutti gli ambiti che riguardano 
  l’infrastruttura dei servizi cloud (ISO/IEC 27001 estesa ai controlli 
  ISO/IEC 27017 e ISO/IEC 27018);
- la gestione delle **configurazioni** e dei **cambiamenti** *(change 
  management)*;
- la **gestione degli incidenti** e il *recovery* dell’infrastruttura in 
  seguito ad eventi critici;

Per assicurare che tutte queste problematiche vengano gestite correttamente, la
qualificazione richiede che vengano adottate dal fornitore tutte le buone
pratiche previste dai più importanti e diffusi standard del settore (es. ISO/IEC
27002).

L’elenco dei CSP qualificati è disponibile sul Marketplace Cloud.

Cloud SPC Lotto 1 - Community Cloud
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

L’infrastruttura di tipo “Community Cloud” è realizzata dal Raggruppamento
Temporaneo d’Impresa aggiudicatario del `Contratto Quadro Consip SPC Cloud Lotto
1 <https://www.cloudspc.it/>`_. La descrizione dettagliata dei servizi e delle
modalità di approvvigionamento è presente sul sito `dedicato
<https://www.cloudspc.it/>`_.

Poli Strategici Nazionali - Private Cloud
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Nel modello Cloud della PA, i Poli Strategici Nazionali (cd. PSN) soddisfano la
necessità di mantenere il controllo diretto da parte dello Stato sulle
infrastrutture IT (Connettività, Data Center e piattaforme cloud) che erogano
servizi considerati asset strategici nazionali. I PSN sono destinati a tutti
quei servizi di rilevanza strategica e di interesse nazionale per i quali non è
consigliabile che la gestione dell’infrastruttura e dei dati venga delegata a
terze parti (es. sicurezza nazionale).

I **Poli strategici nazionali** saranno individuati dal **Governo** sulla base
di una selezione di soggetti idonei svolta attraverso il processo definito nella
`Circolare n. 5 del 30 novembre 2017
<https://www.censimentoict.italia.it/it/latest/docs/circolari/2017113005.html>`_
pubblicata da AgID.

I PSN, se individuati, dovranno rispettare elevati requisiti di sicurezza,
affidabilità, e capacità operativa e saranno coordinati centralmente per erogare
servizi cloud omogenei, utilizzando piattaforme condivise.

La piattaforma da utilizzare per la qualificazione
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

AgID ha previsto l’utilizzo di una piattaforma dedicata con cui il fornitore dei
servizi cloud, che intende conseguire la qualificazione CSP o SaaS, trasmette
tutte le informazioni, le dichiarazioni e la documentazione prevista.

=======
La piattaforma è accessibile all'indirizzo https://cloud.italia.it/marketplace/.

.. rubric:: Note

.. [1] L’infrastruttura cloud è predisposta per fornire servizi cloud a
   molteplici tipologie di clienti (es. società private, enti pubblici,
   ecc.).

.. [2] L’infrastruttura cloud è predisposta per fornire servizi cloud ad 
   uso esclusivo di una singola organizzazione (in questo caso la PA). 
   L’infrastruttura deve essere di proprietà e può essere gestita 
   dall’organizzazione stessa oppure da terze parti.

.. [3] L’infrastruttura cloud è predisposta per fornire servizi cloud ad 
   una specifica comunità di organizzazioni che hanno requisiti e 
   obiettivi condivisi. L’infrastruttura può essere di proprietà, gestita 
   dall'organizzazione stessa oppure da terze parti (in questo caso da un 
   Raggruppamento Temporaneo di Imprese).
