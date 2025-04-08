=== Importatore e Aggiornatore Categorie con Tag Groups ===
Contributors: Salvatore Iovino (salvatoresalvo)
Tags: categories, import, csv, taxonomy, term meta
Requires at least: 5.0
Tested up to: 6.4
Stable tag: 1.2.0
Requires PHP: 7.2
License: GPL v3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Importa e aggiorna facilmente le categorie WordPress da file CSV, con supporto per campi personalizzati come Tag Gruppo.

Quando viene caricato il file .csv con le categorie sembra che il plugin non stia funzionando, in realtà sta lavorando, tant'è vero che il pulsante del caricamento viene disattivato per permettere il caricamento. Ci vogliono pochi secondi. Attendere la fine del caricamento e la risposta dei risultati.

== Description ==

Il **Category Importer & Updater Personalizzato** è un plugin WordPress che semplifica il processo di importazione e aggiornamento delle categorie da file CSV, consentendo di gestire efficacemente la tassonomia del sito senza mai eliminare categorie esistenti.

**Caratteristiche principali:**

* Interfaccia intuitiva per il caricamento e l'elaborazione di file CSV
* Importazione selettiva: scegli se aggiornare le categorie esistenti o aggiungerne solo di nuove
* Creazione automatica delle categorie genitore mancanti
* Supporto per campi personalizzati, come Tag Gruppo
* Feedback dettagliato sui risultati dell'importazione

**Ideale per:**

* Siti con un gran numero di categorie da gestire
* Migrazione di contenuti da altre piattaforme
* Aggiornamenti in blocco delle informazioni delle categorie
* Sincronizzazione di categorie tra siti diversi

== Installation ==

1. Carica la cartella `category-importer-updater` nella directory `/wp-content/plugins/` del tuo sito WordPress.
2. Attiva il plugin attraverso il menu 'Plugin' in WordPress.
3. Vai a 'Importatore Categorie' nel menu di amministrazione per utilizzare lo strumento.

== Frequently Asked Questions ==

= Quali sono i formati CSV supportati? =

Il plugin supporta file CSV standard con virgole come separatori. La prima riga deve contenere le intestazioni delle colonne.

= Il plugin eliminerà le mie categorie esistenti? =

No, questo plugin è progettato specificamente per non eliminare mai le tue categorie esistenti. Può solo creare nuove categorie o aggiornare quelle esistenti.

= Quali campi sono supportati per l'importazione? =

I campi supportati sono: Nome (obbligatorio), Descrizione, Slug, Tag Gruppo e Categoria genitore.

== Screenshots ==

1. L'interfaccia principale del plugin con le opzioni di importazione con Esempio di risultati dettagliati dopo un'importazione.
2. Istruzioni sulla struttura del file .csv
3. Risultati dell'importazione

== Changelog ==

= 1.2.0 =
* Migliorata la gestione dei meta dati delle categorie
* Corretta la mappatura delle colonne del CSV

= 1.1.0 =
* Aggiunto supporto per la creazione automatica di categorie genitore
* Migliorate le prestazioni per importazioni di grandi dimensioni

= 1.0.0 =
* Prima versione pubblica del plugin

== Upgrade Notice ==

= 1.2.0 =
Questa versione corregge la mappatura delle colonne CSV e migliora la gestione dei meta dati.
