# Infovis
Progetto di Infovis di Marco Maiorani
Indicazioni per il funzionamento:

-aprire la finestra della PowerShell direttamente dentro la cartella del progetto "Infovis", e digitare "python3 -m http.server" (a seconda della versione di python di cui si dispone dovrebbe funzionare anche con "python -m http.server"

-accedere attraverso il browser al seguente link "localhost:8000"


In questo progetto ho deciso di realizzare un diagramma a bolle per mostrare l'evoluzione dell'aspettativa di vita di alcuni paesi rispetto al PIL procapite.
In particolare il dataset è il file "data.json" e per ogni anno ci mostra alcuni dati per ogni paese.
Ogni paese appartiene ad un continente, è presente il nome del paese, il reddito procapite, l'aspettativa di vita e la popolazione.
Per ogni anno, è stata rappresentata lungo l'asse delle y l'aspettativa di vita di un abitante di ogni paese (appartentente ad un continente) tenedo conto del PIL del paese in questione.
E' stata scelta una scala logaritmica in base 10 rispetto al PIL poichè si va dai 400$ ai 127563 $ nei 214 anni analizzati.
L'area di ogni cerchio rappresenta la popolazione del paese preso in considerazione.
Tali dati diventano fruibili anche nel momento in cui con il mouse ci si posiziona su un paese in particolare.
Come citato in precedenza, sono stati analizzati 214 anni con un intervallo di aggiornamento di 1,5 secondi.
In basso a destra è stata inserita una legenda che mostra l'anno analizzato e in base al colore del cerchio il continente di appartenenza di ogni paese.
Attraverso un menù a tendina in alto a destra è possibile scegliere il continente che si vuole visualizzare, o in alternativa, tutti i continenti.
La visualizzazione diventa animata attraverso il "tasto" play e si arresta attraverso il tasto "reset", e' inoltre possibile scegliere l'anno da cui si vuole far partire la visualizzazione.
