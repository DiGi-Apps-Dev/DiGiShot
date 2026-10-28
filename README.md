# UltraShot

**Per installare: scarica il file `UltraShot-Setup-1.1.3.exe` dalla sezione Releases di questa pagina.**

UltraShot è un programma per **Windows 11 (64 bit)** che fa screenshot e registra lo schermo. L'ha costruito Dome per uso personale. Il file da usare pesa circa 7,3 MB. Basta un doppio clic.

Questo file spiega le tre cose che possono sembrare strane la prima volta.

## 1. Avviso di Windows: «Windows ha protetto il PC»

L'installer non ha la firma digitale (costa ogni anno e non serve per uso personale), quindi Windows la prima volta mostra una finestra blu.

1. Clicca su **Ulteriori informazioni** (è una scritta sotto il testo, non un pulsante grande).
2. Compare il pulsante **Esegui comunque**: cliccalo.

Succede una volta per ogni PC. Poi Windows chiede se consentire all'app di apportare modifiche: rispondi **Sì**, serve per installare nella cartella Programmi.

## 2. L'antivirus dice che il file è sconosciuto

Alcuni antivirus avvisano con file nuovi e non firmati anche se sono sani. Se blocca `UltraShot-Setup-1.1.3.exe`, scegli «Consenti», «Ripristina dalla quarantena» o «Aggiungi un'eccezione» (i nomi cambiano da antivirus ad antivirus). Se invece l'antivirus indica il nome preciso di un virus, non andare avanti.

## 3. Prima installazione: il componente .NET

UltraShot ha bisogno di un componente gratuito di Microsoft, **.NET Desktop Runtime 10**. Se sul PC c'è già, l'installer non fa niente di più. Se manca, mostra questo messaggio:

> Per funzionare UltraShot ha bisogno di «.NET Desktop Runtime 10», che non è installato su questo PC. Lo scarico dal sito di Microsoft (circa 57 MB, serve internet) e lo installo ora. Procedo?

- **Sì**: scarica il componente dal sito di Microsoft e lo installa da solo, poi continua. Servono internet e qualche minuto.
- **No**: l'installazione si ferma, perché senza il componente UltraShot non parte.

Senza internet: scarica prima «.NET Desktop Runtime 10 (x64)» da https://dotnet.microsoft.com/download/dotnet/10.0 su un altro PC, installalo, poi lancia `UltraShot-Setup-1.1.3.exe`.

## Dopo l'installazione

- Si apre dall'icona sul desktop (se lasci la spunta) o dal menu Start.
- Il tasto **Ins** fa lo screenshot, **Ctrl+Ins** registra il video. Si cambiano in Impostazioni.
- L'icona è vicino all'orologio: il clic mostra il menu. Da lì si accende anche «Avvia con Windows».
- Per disinstallare: Impostazioni di Windows > App > App installate > UltraShot.
