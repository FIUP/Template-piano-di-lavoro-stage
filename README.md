# Come utilizzare questo template
0. **Prerequisito:** Devi avere un ambiente LaTeX installato e configurato correttamente.
1. Fai un fork di questo repository e successivamente fai una clone del tuo repository locale.
2. Apri il file "Dati.tex" e modificalo inserendo i dati necessari
3. Apri il file PianoDiLavoro.tex" e compilalo secondo le indicazioni riportate

## Struttura del template
Il template è diviso in sezioni, secondo la seguente struttura:

In caso non si vogliano utilizzare alcune sezioni, basterà commentarle nel file `PianoDiLavoro.tex`.

1. **Preface**: Definisce il frontespizio del Piano di Lavoro, non necessita di modifiche (prende i dati dal file `Dati.tex`); 
2. **Contatti**: Include la sezione di contatti, non necessita di modifiche; 
3. **ScopoStage**: Va personalizzata con una breve descrizione dello stage e dei compiti che lo studente andrà a ricoprire;
4. **InterazioneStudenteTutor**: Va personalizzata riportando le modalità di interazione tra studente e tutor aziendale, specificando le opportune modalità e tempistiche concordate;
5. **ProdottiAttesi**: Va personalizzata indicando in una lista i prodotti documentali e software che lo studente dovrà produrre durante lo stage. Per ogni prodotto va indicato nome e una breve descrizione;
6. **ContenutiFormativi**: Va personalizzata con le tecnologie e le conoscenze che lo studente avrà occasione di approfondire;
7. **PianificazioneLavoro**: Va personalizzata riportando un prospetto settimanale delle attività come lista e una ripartizione oraria di tali attività in forma tabellare;
8. **Obiettivi**: Riporta i requisiti obbligatori, desiderabili e facoltativi, cioè gli obiettivi da raggiungere durante lo stage. Non necessita di modifiche (prende i dati dal file `Dati.tex`);
9. **Diagramma**: mostra un diagramma di Gantt riportante la pianificazione iniziale delle attività da svolgere.

   L'immagine del diagramma viene presa dal file img/gantt.png, quindi per mostrare tale diagramma basterà inserire una immagine dal nome "gantt.png" dentro la cartella "img", sovrascrivendo quella esistente;
10. **Approvazione**: mostra una sezione che indica i membri che hanno approvato il piano, con i relativi campi per la firma e timbro aziendale.

**Nota:** _Le sezioni 5, 9 e 10 non sono obbligatorie ma potrebbero essere richieste dal tutor interno._

## Scelta dello stile
Il template offre la possibilità di scegliere tra 2 stili, ognuno personalizzerà l'header e il footer di ciascuna pagina, nello specifico:
1. **Stile Unipd**: Nell'header compaiono: Il logo Unipd, i dati dello studente (nome, cognome e matricola, la ragione sociale dell'azienda dove si fa lo stage). 
Nel footer, a destra viene indicato solamente il numero di pagina attuale rispetto al totale.
2. **Stile Aziendale**: Nell'header compaiono: Il logo aziendale, la ragione sociale dell'azienda e il sito internet aziendale. 
Nel footer, al centro viene indicato il numero di pagina attuale rispetto al totale e ai lati i dati dell'azienda con i relativi dati di contatto (ragione sociale, indirizzo, sito, telefono, email, P.IVA).

### Uso degli stili

Per usare lo stile aziendale, occorre:

0. Chiedere il consenso per l'utilizzo del logo degli altri dati aziendali al vostro tutor
1. Inserire nella cartella `img` il logo aziendale chiamandolo `logo_azienda.png`
2. Nel file `Layout.tex`, commentare `\stileUNIPD` (attivo di default) e decommentare `\stileAziendale`

# Attenzione!
Il seguente template serve per creare un file `.pdf` contenente il piano di lavoro dello studente ma per essere ufficialmente approvato, potrebbe essere necessario stamparlo su carta intestata dell'azienda, come se fosse un documento ufficiale. Lo stile UNIPD potrebbe non venir accettato da tutti i docenti, chiedete sempre conferma al vostro tutor interno.

# Crediti
- Template originale di Michele Caovilla (Mich)
- Rivisitazione completa del template da parte di Riccardo Montagnin
- Modfiche ulteriori al frontespizio, all'impaginazione, al prospetto settimanale e modularità del template Federico Silvio Busetto