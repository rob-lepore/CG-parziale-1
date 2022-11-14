# Consegna primo elaborato per il corso Computer Graphics - Roberto Lepore - roberto.lepore2@studio.unibo.it

## Istruzioni per l'installazione

- Creare un nuovo progetto c++ su Visual Studio
- Scaricare lo zip di questa repo
- Copiare tutti i file e la cartella fonts nella directory del progetto
- Posizionare i file con estensione .cpp e .glsl nei file di origine
- Posizionare i file con estensione .h nei file di intestazione
- Installare i pacchetti NuGet nupengl.core e glm
- Installare la libreria Freetype

## Istruzioni per il gioco

Il giocatore può controllare un mago con l'obiettivo di sopravvivere e sconfiggere i nemici che compariranno in posizioni casuali.

I controlli per muoversi e combattere sono i seguenti:
 - a: passo verso sinistra
 - d: passo verso destra
 - spacebar: salto
 - e: sparo di una magia
 
Un nemico deve essere colpito con due magie per essere eliminato.
Quando un nemico tocca il mago, questo perde una vita e diventa invulnerabile per pochi secondi. Una volta perse tutte le vite il gioco terminerà e potrà essere chiuso premendo un tasto qualsiasi.
