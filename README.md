🎙️ Easy GencaTTS per Grid3 – Guida all’uso
🔧 Cos’è
Easy GencaTTS è una Web App che permette di:

🧠 Correggere automaticamente testi con GPT (OpenAI),

🔊 Convertire il testo in voce realistica con ElevenLabs,

✅ Usarla facilmente da Grid 3 tramite comandi da tastiera emulati dalle celle.

🚀 1. Preparazione
Prima di iniziare, ti servono:
Una chiave API di ElevenLabs 👉 https://www.elevenlabs.io

Una chiave API GPT (OpenAI) 👉 https://platform.openai.com (se vuoi usare anche la funzione di correzione o altra elaborazione del testo)

Gli ID di una voce ElevenLabs (es. EXAVITQu4vr4xnSDxMaL) e il modello TTS (es. eleven_turbo_v2)

🖥️ 2. Avvio
Quando apri la pagina:
Il cursore va subito nel campo di testo.

Puoi scrivere o incollare un testo direttamente.

🎛️ 3. Configurazione iniziale
Fai clic su ⚙️ Settings e inserisci:
🔑 API ElevenLabs
ElevenLabs API Key

Voice ID (ID voce)

Model TTS (es. eleven_turbo_v2)

Stability, Similarity Boost, Speed

🔑 API GPT
GPT API Key

Modello GPT (es. gpt-3.5-turbo)

Prompt GPT: puoi lasciare quello presente (che serve per correzione avanzata del testo scritto) oppure aggiungerne un altro.

👉 Clicca su "Salva Impostazioni"

Le impostazioni vengono salvate nel browser (localStorage), non devi reinserirle ogni volta.

✍️ 4. Scrivere e correggere un testo
Scrivi o incolla un testo nel campo principale

🧠 Per correggerlo:
Clicca su "GPT: ctrl + i"

Oppure premi Ctrl + I sulla tastiera (eventualmente da emulare con attività cella di Grid3)

Il testo verrà elaborato da GPT rispetto al prompt assegnato. Con il prompt di default vengono corretti ortografia, punteggiatura, grammatica, spazi, refusi. 

🔊 5. Generare la voce
Dopo aver scritto (o corretto) il testo:
🔈 Per ascoltarlo:
Clicca su "PARLA: ctrl + 0"

Oppure premi Ctrl + 0 (eventualmente da emulare con attività cella di Grid3)

Verrà generato un audio con la voce di ElevenLabs e riprodotto automaticamente.

🧹 6. Comandi rapidi da tastiera
Comando	Funzione
Ctrl + 0 -	Genera voce
Ctrl + I -	Correggi testo
F11 -	Attiva/Disattiva schermo intero

🧩 7. Integrazione con Grid3
In Grid3 puoi:

Usare tastiera alfabetica che scrive testo nel campo della pagina.

Collegare tasti che simulano i comandi da tastiera (es. Ctrl + 0 per parlare e Ctrl + i per attivare prompt GPT sul testo).

Usare la pagina a schermo intero.

💡 Suggerimento: configura una cella per correggere e una per parlare, assegnando le scorciatoie da tastiera.


