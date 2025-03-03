Quest'applicazione si occupa di creare un BeatBox in grado di riprodurre una serie di suoni in base a
un file di testo.

1) iniziamo creando la classe MusicTest1 che crea l'oggetto SEQUENCER, l'oggetto in grado di fare partire la musica
2) Creiamo nel metodo un istanza di Sequence che rappresenta la canzone (come se fosse un CD, che contiente le canzoni)
3) Ora creiamo una track che rappresenta l'intera canzone
4) Infine si crea la vera musica, inserendo l'inizio della melodia, la fine e il volume. Questo avviene creando un **Messaggio**, poi bisogna dare l' **Istruzione** per creare la nota musicale attraverso il .setMessage, dopodiché si crea un nuovo **MidiEvent** e infine si aggiunge il **MidiEvent** alla **Track** (il meassage serve a dire cosa fare, mentre il MidiEvent specifica quando farlo)
    ° NOTE_ON rappresenta il numero 144, e NOTE_OFF è il 128, il secondo numero rappresenta il canale (pianista, chitarrista, ecc.), il terzo rappresenta la nota (0-127), il quarto rappresenta la velocità (0-100) )