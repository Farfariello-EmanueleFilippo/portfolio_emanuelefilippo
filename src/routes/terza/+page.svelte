<script>
    import Nav from "../../lib/components/nav.svelte";
    import PdfViewr from "../../lib/components/pdf_viewr.svelte";
</script>

<html lang="it">
<head>
    <meta charset="UTF-8">
    <title>La mia descrizione</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            font-size: 18px;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            margin: 0;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 800px;
            margin: auto;
        }
        h2 {
            font-family: "Georgia", serif;
            font-size: 32px;
            color: #5D5C61;
            margin-bottom: 20px;
        }
        h4 {
            font-family: "Georgia", serif;
            font-size: 32px;
            color: #5D5C61;
            margin-bottom: 20px;
        }
        p {
            margin: 20px 0;
        }
       

    </style>
</head>
<body>
    <div class="container">
        <h2> anno 2021 - 2022 </h2>
        <p>
            Nel terzo anno del mio percorso di formazione presso l'Istituto Agnelli, abbiamo approfondito una serie di argomenti di grande importanza e attualità. In particolare, ci siamo concentrati su tre temi principali: la mafia, l'emancipazione femminile e la cittadinanza digitale.
        </p>

        <hr> 

        <h4>la mafia Falcone e Borsellino </h4>
        <p>
            La mafia è stata analizzata non solo dal punto di vista storico, ma anche attraverso lo studio delle sue dinamiche attuali e del suo impatto sulla società. Questo approfondimento ci ha permesso di studiare e ricordare due grandissimi magistrati siciliani che hanno dedicato la loro intera vita nella lotta contro la mafia.
        </p>
        
        <div style="width: 100%; height: 500px; margin-top: 20px;">
            <iframe src="presentazione-falcone-e-borsellino.pdf" width="100%" height="500"></iframe>
        </div>

        <p> inoltre abbiamo avuto la fortuna di conoscere Salvatore Borsellino attraverso una meet, poichè Esso è un componente importantissimo in agende rosse </p>

        <hr>

        <h4>Emancipazione femminile</h4>
        <p>
            L'emancipazione femminile è stato un altro tema centrale. Abbiamo esplorato le lotte e le conquiste delle donne per ottenere pari diritti e opportunità. Questo argomento ha stimolato riflessioni profonde sul ruolo delle donne nella società moderna e sulle sfide ancora presenti per raggiungere una reale parità di genere.
        </p>
        <p> (il testo qui sotto riportato, sono appunti presi in classe.)</p>

        <div class="container">
            <h1>Appunti sull’emancipazione femminile</h1>
            <p>
                L'emancipazione femminile cominciò a prendere forma significativa verso la fine del XIX secolo e continuò a svilupparsi nei primi decenni del XX secolo in paesi come l'Inghilterra e gli Stati Uniti d'America. In questi contesti, le donne iniziarono a lottare attivamente per ottenere il diritto di voto e per raggiungere una parità di trattamento rispetto agli uomini, in particolare per quanto riguarda le condizioni lavorative nelle fabbriche e nei mestieri manuali.
            </p>
            <p>
                Con l'avanzare dell'industrializzazione, la situazione delle donne iniziò a cambiare notevolmente. Le donne non erano più viste solo come "angeli del focolare", relegati a ruoli domestici all'interno delle mura di casa, ma cominciavano a ottenere una certa indipendenza economica. Sempre più donne trovavano impiego come operaie nelle fabbriche, segretarie negli uffici, insegnanti nelle scuole e infermiere negli ospedali, guadagnandosi così un ruolo più attivo nella società.
            </p>
            <p>
                Anche tra la borghesia, le donne iniziarono a reclamare il diritto di accedere a un'istruzione superiore per poter diventare scienziate, giornaliste e professioniste in vari campi. Tuttavia, alcune professioni, come quella di avvocato, rimasero a lungo precluse alle donne, persino nei paesi più avanzati come la Gran Bretagna, che pure aveva aperto le porte delle università alle donne già a metà del XIX secolo. Ancora più arduo fu il percorso delle donne verso la professione medica, che richiedeva di superare numerosi pregiudizi e ostacoli.
            </p>
            <p>
                Nonostante le numerose difficoltà, queste nuove donne, più istruite e attivamente coinvolte nella vita sociale, non erano disposte a rimanere cittadine di serie B. Chiedevano pari diritti anche all'interno della famiglia, salari equi paragonati a quelli dei loro colleghi maschi e, soprattutto, il diritto di voto. Alla fine del XIX secolo, infatti, il diritto di voto per le donne era concesso solo in Nuova Zelanda, un privilegio che le donne di altri paesi occidentali guardavano con grande interesse e speranza.
            </p>
            <p>
                Di conseguenza, iniziarono a formarsi i primi movimenti femministi negli Stati Uniti, in Gran Bretagna, in Francia e anche in Italia. Le prime attiviste di questi movimenti vennero chiamate Suffragette, dal termine "suffragio" che significa "voto". Queste donne coraggiose erano spesso malviste dalla società del tempo, ancora profondamente radicata in una mentalità maschilista. Le Suffragette erano spesso derise e considerate esaltate, ma la loro determinazione non venne mai meno.
            </p>
            <p>
                Il primo paese europeo a riconoscere il diritto di voto alle donne fu la Finlandia, nel 1906, segnando un importante traguardo nella lotta per i diritti delle donne e aprendo la strada a ulteriori conquiste in altri paesi.
            </p>
        </div>

        <hr> 

        <h4>la cittadinanza digitale</h4>
        <p>
            la cittadinanza digitale ha rappresentato un tema di grande rilevanza nel contesto contemporaneo. Abbiamo esaminato l'importanza della competenza digitale e della responsabilità online, comprendendo come navigare in modo sicuro e consapevole nel mondo digitale. Questo argomento ci ha preparati ad affrontare le sfide del futuro in un mondo sempre più interconnesso.
        </p>

        <div style="width: 100%; height: 500px; margin-top: 20px;">
            <iframe src="Cittadinanza-Digitale-_4_-_2_.pdf" width="100%" height="500"></iframe>

        </div>

        <hr>
        <h4>il diritto delle donne</h4>
        <p>
            Infine, abbiamo visto i diritti delle donne
        </p>

        <p>Oggi si discute molto dei diritti degli uomini, ma è fondamentale parlare soprattutto dei diritti delle donne. Le notizie riportano quotidianamente episodi terribili di violenza contro le donne, spesso omicidi commessi da uomini. Spesso i colpevoli sono mariti o fidanzati e in tutti questi casi le vittime sono sempre donne innocenti. Gli uomini sono i responsabili e le donne sono le vittime della violenza.

            Si parla di delitti d’amore, ma l’amore non è violento. L’amore è dolcezza. Purtroppo, la violenza contro le donne e gli omicidi sono in aumento, soprattutto negli ultimi anni. Fortunatamente, anche i dibattiti su questo grave fenomeno sociale sono cresciuti.
            
            Negli anni Novanta, la violenza e lo stupro sono stati riconosciuti come reati da condannare, ma ciò non ha diminuito i casi di violenza grave. La violenza sulle donne è spesso anche psicologica, come dimostrano i numerosi casi di stalking e mobbing. In tutti questi episodi, le donne sono vittime della cattiveria e dell'arroganza degli uomini che le trattano come oggetti.
            
            L'attrice Franca Rame e l'attore Dario Fo hanno combattuto contro questo tipo di violenza. Franca Rame ha scritto e recitato testi contro lo stupro per sensibilizzare l’opinione pubblica sulla gravità di questa violenza.
            
            Oggi si discute molto di questo tema. Ci sono dibattiti in televisione e nelle scuole, dove si parla di questo grave problema. Credo sia fondamentale far capire ai ragazzi fin da piccoli che la violenza è sempre un reato da condannare. Tuttavia, il problema più difficile da risolvere è l’esempio che i giovani ricevono nelle famiglie. Se hanno esempi negativi, è facile che crescano nella violenza. È quindi importante che i ragazzi siano educati in famiglie dove i genitori si rispettano e nessuno è violento, affinché comprendano il valore del rispetto e del dialogo.
            
            Credo che la violenza, soprattutto quella sulle donne, provenga da uomini che da piccoli non hanno capito quanto sia sbagliata e grave. Personalmente, condanno tutte le forme di violenza: sulle donne, sui più deboli, sui poveri e su chi non può difendersi, e sono grato di essere cresciuto in una famiglia che mi ha insegnato l’importanza del rispetto reciproco.
            
            VIDEO TRATTO DALLA CONFERENZA GUIDATA DAL PROF. GIOVANNI SACCANI
            DAL TITOLO: DA LUCREZIA AL CODICE ROSSO
            26 Novembre 2021
            Il 25 novembre di ogni anno si celebra la Giornata internazionale contro la violenza sulle donne. Per l’occasione, al dibattito hanno partecipato la prof.ssa Silvia Giorcelli e la prof.ssa Silvia Cavicchioli. Il problema è molto grave. Le donne sono penalizzate rispetto agli uomini per molti motivi:
            - La disparità salariale
            - La violazione delle pari opportunità
            Fortunatamente, nel 1981 è stato abolito il delitto d’onore, ma il problema non è solo creare difese per le donne, bensì puntare sull’educazione degli uomini.
            
            Interessante è stato il racconto di Silvia Giorcelli su una figura simbolo della storia romana: il modello di Lucrezia che, dopo essere stata vittima di stupro, si suicida.
            
            Alle origini del problema:
            - Genesi antica di una mentalità che sopravvive e condiziona i modi di pensare e agire.
            - Importanza dell'analisi dei contesti storici e storiografici per cogliere la profondità e lo sviluppo del tema.
            - Centralità dell'uso pubblico della storia: divulgazione, disseminazione.
            - Responsabilità etica e culturale degli storici nella narrazione del passato, specie quando la comunicazione dei non addetti ai lavori rischia di prevalere.
            
            «Indispensabili straniere»
            - Sono storie orrende e tragiche che mirano a riconciliare e rassicurare che sia la civitas sia il suo ius sono in grado di fronteggiare il pericolo e ripristinare l'ordine.
            - Le donne stanno ai primordi della civitas, alla base delle norme e degli istituti che costituiscono Roma e dei momenti più delicati: esse incarnano un modello esemplare, in positivo o in negativo, da riproporre all'ammirazione o al ludibrio collettivo.
            - Le donne rappresentano le zone torbide dove cessa l'influenza civilizzatrice del mondo cittadino.
            
            Vita e morte di una matrona romana:
            - Storia/mito denso di significati perché intorno alla vicenda si strutturano questioni di estrema rilevanza per capire la società romana, la mentalità, il patriarcato.
            - La natura delle donne.
            - Il ruolo delle donne nella famiglia e nella società.
            - Importanza della famiglia, della gens.
            - Comportamento corretto di donne e uomini.
            - Violenza sessuale, il corpo.
            - Colpa, vergogna, punizione.
            - Modello esemplare che fissa per sempre il comportamento delle donne.
            
            La vicenda e i protagonisti:
            - Molte fonti ne parlano.
            - Il contesto è quello della fine della monarchia e della cacciata dei Tarquini (509 a.C., 243 ab Urbe condita): lo stupro innesca la rivolta e segna la nascita della repubblica.
            - Spurio Lucrezio Tricipitino, il padre.
            - Lucrezia, la vittima.
            - Tarquinio Collatino, il marito.
            - Sesto Tarquinio, lo stupratore.
            - Il concilium dei parenti (maschi).
            
            Il punto di vista maschile:
            - Il controllo sulle donne (comportamento, vino).
            - In teoria, Sesto ha il diritto di controllare Lucrezia e di ucciderla (per vendicare l'oltraggio inflitto a un parente).
            - Non ha però il diritto di stuprarla proprio perché ha il compito di tutelare l'integrità del talamo di Collatino.
            - Collatino non è tuttavia innocente: delle donne NON si parla, mai; e avrebbe dovuto avvisare prima di tornare a casa.
            - Lucrezia convoca i parenti maschi, un necessariorum concilium, quello che ha tradizionalmente il compito di giudicare ed eventualmente condannare.
            - Ci sono altri maschi nella vicenda, soprattutto Lucio Giunio Bruto.
            
            Il punto di vista femminile (forse):
            - Adulterium, adulterare/alterare, ad alterare da alter.
            - Che cosa si adultera? Il sangue delle donne attraverso il seme maschile.
            - Lo stuprum compromette totalmente e definitivamente Lucrezia nella sua essenza di futura madre legittima della gens; il suo sangue alterato da un seme non legittimo compromette la discendenza di Collatino.
            - A causa dello stupro, Lucrezia è in realtà 'socialmente' morta: non vale più nulla.
            - Si uccide come un uomo, nel modo più violento.
            - L'esibizione del suo corpo straziato, che le donne non devono esibire neanche da morte, ha il compito di accendere la rivolta.
            - Poi Lucrezia sparisce, e la storia continua: protagonisti solo gli uomini.
            
            STORIA DI LUCREZIA
            Lucrezia muore suicida a Roma nel 509 avanti Cristo dopo aver subito una violenza sessuale, e la sua morte provoca la caduta della monarchia dell’ultimo re Tarquinio il Superbo e la conseguente instaurazione della Repubblica Romana.
            
            Secondo quanto riportato dallo storico Tito Livio, Lucrezia è una bellissima donna romana, moglie di Lucio Tarquinio Collatino. Mentre Tarquinio il Superbo, ultimo re di Roma, si trova con le sue truppe ad Ardea per l’assedio della città, i figli e i parenti del re tornano sovente di nascosto a Roma per verificare la fedeltà delle loro mogli. Sembra che la più fedele e virtuosa sia proprio Lucrezia, trovata a filare la lana con le sue ancelle.
            
            Sesto Tarquinio, figlio del re Tarquinio il Superbo, si invaghisce di Lucrezia, così bella ma allo stesso tempo casta e pudica, e una sera si reca da lei con l’inganno dichiarando il suo amore. Di fronte all’irremovibilità della donna, la minaccia con una spada, dicendo che se non avesse soddisfatto la sua passione, l'avrebbe uccisa posizionando nel suo letto il corpo di uno schiavo nudo per accusarla di adulterio.
            
            Lucrezia, temendo per la sua vita, cede alla passione di Sesto Tarquinio. Il mattino seguente, dopo aver convocato il marito e il padre, racconta loro la violenza subita e si suicida trafiggendosi il cuore con un pugnale.
            </p>
        <hr>
        
        <p>
            Questo terzo anno è stato particolarmente significativo per la mia crescita personale e accademica, arricchendomi di conoscenze fondamentali e di una maggiore consapevolezza sociale.
        </p>


    </div>
</body>
</html>
    