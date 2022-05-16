# Scegliere un film su Netflix

Vado sul sito netflix
Seleziono l'account
SE scegliamo un film consigliato da un amico
    cerchiamo il film
    mettiamo play
ALTRIMENTI
    SE siamo soli
        SE vogliamo guardare qualcosa di lungo
            SE scegliamo una serie tv
                - vai sulla lista serie tv >1h
                - metti un episodio
            SE scegliamo un film
                - vai sulla lista film >1h
                - metti un film
        ALTRIMENTI
        guardiamo qualcosa di corto
            SE scegliamo una serie tv
                - vai sulla lista serie tv <1h
                - metti un episodio
            SE scegliamo un film
                - vai sulla lista film <1h
                - metti un film
    SE siamo in gruppo
        SE siamo d'accordo sul genere
            vai a riga 10
        SE non siamo d'accordo
            si vota
            SE un genere ha la maggioranza
              vai a riga 10
            ALTRIMENTI
                ripeti la votazione finché un genere non ha la maggioranza
                vai a riga 10