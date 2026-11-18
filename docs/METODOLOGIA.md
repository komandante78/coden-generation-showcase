# Risultati e metodo

Campagna di sviluppo del18novembre2026:quattro compiti predisposti,mai eseguiti prima in quella campagna,con codice iniziale e test visibili. Non e un benchmark cieco o una valutazione indipendente di competenza generale.

Prima della generazione sono stati fissati sorgenti del motore,input,protocollo e criteri del valutatore. Un solo driver,una missione alla volta,tetti per token,chiamate,tempo e risorse. Test nascosti e valutatore forniti soltanto dopo la chiusura del generatore e dei modelli. Tutti gli esiti e costi conservati;nessun retry selettivo.

Ogni successo richiede:chiusura del Kernel,baseline iniziale rossa,test visibili+nascosti passati,file protetti invariati,corrispondenza fra artefatti e report,coerenza audit,costi riconciliati,fonti web,recupero ibrido,embedding reali e verifica isolata. La quarta missione richiede anche una ripresa fra processi.

Esiti4/4;17test di accettazione realmente eseguiti.154509token,21chiamate generative,36richieste HTTP embedding,1615.325secondi sommati delle missioni. La campagna precedentemente fallita3/4 non e stata cancellata e riguarda casi diversi.

Nessun bypass dei test individuato nell'ispezione dei quattro sorgenti candidati;questo non prova correttezza su ogni input. Le riparazioni partono da baseline difettose:questa campagna non dimostra recupero da qualsiasi candidato errato prodotto dal modello. Un caso ha avuto due build,entrambe registrate. La ripresa del quarto ha conservato una sola build.

Memoria:quattro osservazioni di esito,una ipotesi non verificata,zero nuovi metodi qualificati. Il richiamo di osservazioni negative e stato verificato offline;nessun richiamo negativo nuovo va attribuito a questo live. Vantaggio causale della memoria,della ricerca e della semantica NON MISURATO.

Hardware osservato:Unraid/Linux,NVIDIA RTX3060,modelli locali. Minima RAM disponibile host15.02GiB;minima VRAM libera2.08GiB;massima temperatura GPU65.72C. Questi dati non isolano il solo consumo CodeN. Nessun download o cambio driver per la campagna;modelli e immagini identificati da hash locali. Provenienza upstream dei modelli non nuovamente attestata.

Un primo controllo infrastrutturale delle fixture non ha eseguito test per stdin non collegato:INCONCLUSIVO,conservato;corretto prima della generazione,poi17test oracle su4suite effettivamente verdi. Le regressioni del motore erano rosse prima delle correzioni e verdi dopo. Nessun tentativo modello viene rimosso da questi riepiloghi.

I dati pubblicati sono selezionati e sanitizzati;il software e i log grezzi non sono pubblici. Non offriamo riproducibilita indipendente completa dal solo repository pubblico. Il digest del riepilogo privato nei dati pubblici e un riferimento d'integrita,non una verifica esterna della qualita.

## Confronto non JSON successivo

Sei missioni e due coppie identiche, con ordine controbilanciato: memoria prima per le directory, controllo prima per XML. Nel controllo vengono invalidati solo i metodi appena acquisiti, preservando le altre osservazioni. Ogni braccio riapre uno store indipendente derivato dallo stesso stato dopo le acquisizioni.

Criterio preregistrato: almeno 10% in meno sia nei token totali misurati sia nel tempo wall del worker, senza regressione dei candidati e con riuso qualificato completo in entrambe le coppie. Tutti i tentativi sono conservati. Acquisizione, correttezza del candidato, riuso ed efficienza hanno esiti distinti; un confronto invalido resta INCONCLUSIVO anche se un numero appare favorevole.

Cache RAM del prompt disabilitata e slot cancellato e ricontrollato prima di ogni missione. Il contatore del riuso del prompt e verificato nei probe; il prompt iniziale della chat non ha un contatore diretto registrato, quindi il suo stato freddo e inferito dai meccanismi. Cache di filesystem, ordine e latenza di rete non sono completamente isolati. Due coppie non consentono una stima di vantaggio generale. [Nuovi dati selezionati](../results/confronto-metodi-2026-11-18.json).
