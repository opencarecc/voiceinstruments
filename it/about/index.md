---
layout: default
title: About
published: true
ref: about
lang: it
---

# About
<b>Voice Instruments</b> è un'interfaccia open source concepita per la lettura vocale di valori numerici e messaggi di servizio utili a soddisfare i bisogni di persone <b>impossibilitate alla lettura</b> o di persone operanti in contesti <b>dove risulta scomodo usare la vista</b> per leggere i valori su di un monitor.
<br><br>
Il progetto è nato perchè lavorando in un laboratorio di chimica ho sentito la necessità di realizzare un <b>PH-metro parlante</b> la cui tecnologia potrà essere replicata in altri contesti e permettere ad altri di connettere altri device all'interfaccia vocale.
<img src='{{ site.baseurl }}/assets/VI-about-img-02.jpg'>
<blockquote><i>Il primo prototipo del pH-metro parlante di Voice Instruments</i></blockquote>

### SCENARIO
La stragrande maggioranza degli elettrodomestici e della strumentazione elettronica attualmente presenti sul mercato si serve di un <b>dispositivo di output</b> il più delle volte <b>visivo</b> per comunicare e per poter interagire con l’utente.
<p>
Tuttavia, alcuni apparecchi  oltre all’output visivo dispongono anche di un <b>sistema d’interazione vocale</b> per consentire agli utenti di poter utilizzare queste tecnologie senza l’uso della vista.
Ciò nonostante, la cerchia di questi dispositivi elettronici dotati di tale interfaccia alternativa è molto ristretta e spesso riguarda dispositivi popolari di uso comune come telefoni cellulari, bilance domestiche, medicali mentre invece può essere più difficile reperire almeno in Italia <b>strumenti parlanti</b> come stazioni meteo, termostati domestici lavatrici o multimetri digitali.
</p>

### JOURNEY
<img src='{{ site.baseurl }}/assets/VI-post-img-01.jpg'>
<blockquote><i>Giulio Berretta mentre presenta all'Arduino User Group il pH-metro parlante</i></blockquote>
Inizialmente, lavorando in un laboratorio di chimica, ho subito pensato di costruire uno strumento di misura molto utile in tali contesti, ossia un <b>pH-metro parlante</b>.
<p>
Durante il programma <a href='http://wemake.cc/opencare/maker-in-residence-en/' target='_blank'>opencare Maker in Residence</a> ho realizzato, insieme allo staff ed ai makers di WeMake, il primo prototipo di un pH-metro parlante secondo i requisiti definiti all’inizio del percorso ed inoltre sono state sviluppate <b>due librerie complete di guidelines</b> per la gestione della lettura vocale di valori numerici e di messaggi di servizio funzionanti con i moduli audio più diffusi utilizzabili con la maggior parte dei sensori e dei dispositivi presenti sul mercato.
</p>
Per realizzare il primo prototipo del pH-metro parlante è stato analizzato il progetto sperimentale e successivamente sono state condotte varie ricerche di mercato per selezionare i componenti più adeguati allo scopo ed infine, in base ad essi è stato disegnato il PCB.

Dopo aver definito le specifiche di quest’ultimo è stato disegnato un case capace di racchiudere il PCB ed i componenti.
<p>
La versione corrente del case è stata realizzata in compensato tagliato a laser, il materiale è stato scelto principalmente per  il  suo basso costo ed all’elevata affinità acustica.

Le librerie sono state concepite principalmente per la <b>lettura di valori numerici e messaggi di servizio</b> e per funzionare con due dei più diffusi moduli audio. Tuttavia, l’algoritmo utilizzato per la lettura dei valori, può essere adattato per funzionare con qualsiasi altro modulo.
</p>

### NEXT STEPS
Attualmente, tali valori numerici vengono letti da questa interfaccia in lingua italiana, tuttavia, i principali sviluppi futuri di questo progetto consistono nell’utilizzo di componentistica sempre più spinta, nell’aggiunta del <b>supporto per altre lingue straniere</b> ed eventualmente la realizzazione di un reale <b>sistema di sintesi vocale</b> basato su microcontrollore.

### TEAM
<img src='{{ site.baseurl }}/assets/VI-about-img-01.jpg'>
<blockquote><i>Giulio Berretta all'Arduino User Group</i></blockquote>
<p>
Mi chiamo <b>Giulio Berretta</b>, ho 27 anni e sono diplomato come Perito chimico industriale e laurea magistrale in ingegneria elettronica presso il Politecnico di Milano.
</p>
Lavoro come insegnante tecnico pratico in un laboratorio di chimica e di fisica. Dal 2008 sono socio dell'<b>Unione Italiana dei Ciechi e degli Ipovedenti</b>, dal 2017 sono socio onorario dell'Accademia della Luce.
