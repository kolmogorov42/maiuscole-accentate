# Maiuscole accentate - Layout italiano di Debian per Windows

Un layout di tastiera in lingua italiana per Windows che ricalca quello presente su Debian GNU/Linux, ovviando così alla mancanza di alcuni caratteri fondamentali sul sistema di casa Microsoft.

## Schema

![Schema riassuntivo tastiera Linux con dead keys](pics/LinuxDeadKeys.jpg?raw=true)

Su ogni tasto sono riportati 4 simboli:
* in basso a sinistra il carattere prodotto dal tasto senza modificatori, es: <kbd>A</kbd>
* in alto a sinistra il carattere ottenuto con la pressione del tasto **Shift**, es: <kbd>Shift</kbd>+<kbd>A</kbd>
* in basso a destra il carattere ottenuto con **AltGr**, es: <kbd>AltGr</kbd>+<kbd>A</kbd>
* in alto a destra il carattere ottenuto con la pressione simultanea di **Shift** e **AltGr**, es: <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>A</kbd>

Ogni combinazione valida sul consueto layout italiano di Windows è valida anche su questo e produce gli stessi simboli.

I simboli che nello schema non sono evidenziati corrispondono a caratteri che, come di consueto, vengono inviati al sistema non appena digitata la combinazione.
Quelli evidenziati in rosa, invece, sono detti _dead keys_ e consentono di attivare alcuni  **modificatori** dei caratteri. Eseguire la combinazione non comporta l'invio di un carattere, ma il successivo simbolo digitato, se compatibile, verrà modificato opportunamente.

### Elenco dei dead keys e relativi modificatori

* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>2</kbd>: **doppio accento acuto**. Esempio: Ő, ő, Ű, ű.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>3</kbd>: **tilde**. Esempio: Ã, ñ.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>0</kbd>: **ogonek**. Esempio: ą, Ų.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>ì</kbd>: **accento circonflesso**. Esempio: ô, Ê.
* <kbd>AltGr</kbd>+<kbd>J</kbd>: **hook**. Esempio: Ủ, ỏ.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>J</kbd>: **horn**. Esempio: ư, ơ.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>ò</kbd>: **cedilla**. Esempio: Ç.
* <kbd>AltGr</kbd>+<kbd>ù</kbd>: **accento grave**. Esempio: Ỳ, È.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>ù</kbd>: **vocale breve**. Esempio: ă, Ŏ.
* <kbd>AltGr</kbd>+<kbd>,</kbd>: **accento acuto**. Esempio: á, í, ú.
* <kbd>Shift</kbd>+<kbd>AltGr</kbd>+<kbd>.</kbd>: **dieresi**. Esempio: Ä, ö, ü.
* <kbd>AltGr</kbd>+<kbd>-</kbd>: **vocale lunga** (o _macron_). Esempio: ā, Ē.

### Caps Lock per lettere accentate comuni

Tenendo <kbd>CapsLock</kbd> attivo, è possibile digitare à, è, ì, ò, ù per ottenere le corrispondenti maiuscole senza fare uso dei dead keys.
Premendo inoltre <kbd>Shift</kbd>+<kbd>è</kbd> si può ottenere É.

## Istruzioni

È sufficiente scaricare la [release](https://github.com/kolmogorov42/maiuscole-accentate/releases), decomprimerla e installare il layout eseguendo setup.exe.

## Sviluppo

Tramite il tool [MSKLC](https://www.microsoft.com/en-us/download/details.aspx?id=102134) della Microsoft è possibile importare e modificare il nostro sorgente ItaLinux.klc per produrre un nuovo layout.
