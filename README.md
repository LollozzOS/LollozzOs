<p align="center">
  <img src="docs/assets/logo-192.png" width="96" height="96" alt="LollozzOS">
</p>

<h1 align="center">LollozzOS</h1>

<p align="center">
  <b>Il tuo PC, pronto per giocare.</b><br>
  Ottimizzazione di Windows 10 e 11 per il gaming, in un’app sola. Ogni modifica si annulla.
</p>

<p align="center">
  <a href="https://lollozzos.github.io/LollozzOs/"><b>Sito</b></a> ·
  <a href="#novita"><b>Novità</b></a> ·
  <a href="https://github.com/LollozzOS/LollozzOs/releases/latest"><b>Scarica</b></a> ·
  <a href="https://discord.gg/gd5cT3Jw9M"><b>Discord</b></a> ·
  <a href="#english">English</a>
</p>

<p align="center">
  <img src="docs/assets/home.jpg" alt="La schermata principale di LollozzOS" width="900">
</p>

---

<a id="novita"></a>

## Novità

*Aggiornato al 7 ottobre 2026.* L’app controlla da sola gli aggiornamenti: quando esce una versione nuova te lo dice, la scarica e apre l’installazione (licenza, impostazioni e backup restano).

- **LollozzOS Debloat, una schermata sola** *(nuovo)*: privacy, pubblicità,
  funzioni IA, Start, barra e prestazioni, 119 voci in una schermata. Le voci
  doppie sono diventate una sola, la più completa. Applica solo quello che
  spunti, quelle già fatte sono segnate “Già eseguito” e ognuna si annulla. È
  anche dentro Ottimizza con un click, con la stessa schermata.
- **Windows AI tolta davvero** *(nuovo)*: Copilot, Recall e le altre funzioni
  IA tolte da Windows, non solo spente. Ognuna delle 12 voci dice se sul tuo PC
  c’è ancora o è già tolta. Il preset Sicuro lascia stare le 3 che possono far
  fallire Windows Update, e “Rimetti l’IA com’era” riporta tutto.
- **Riparazioni che funzionano** *(nuovo)*: 54 riparazioni divise in 11 gruppi,
  nella loro pagina e con la ricerca. Prima vedi i passi, poi l’esito di
  ognuno. Lo Store si reinstalla anche se era stato tolto, Edge si rimette, e
  DISM, SFC e il controllo del disco dicono il risultato vero.
- **Gestione attività con i consigli** *(nuovo)*: accanto a ogni programma il
  consiglio, priorità alta ai giochi, bassa a chi lavora in background, chiudi
  a chi mangia processore o memoria. Lo scegli tu con un clic: LollozzOS non fa
  niente da solo.
- **Affinità della scheda video**: gli interrupt della scheda video vanno
  sull’ultimo core, di solito il meno occupato, invece che sul Core 0. Su
  alcuni PC i frametime diventano più regolari, con meno picchi; su altri non
  cambia niente, per questo l’app misura prima e dopo. È già in Ottimizza con
  un click.
- **Otto ottimizzazioni in più**: niente manutenzione automatica che parte
  mentre giochi, meno telemetria, niente registro energetico in background,
  LLMNR spento e circa 7 GB di spazio riservato liberati. Ognuna ha il suo
  interruttore, con scritto cosa perdi.
- **Il Livello LollozzOS**: le ottimizzazioni accese e la salute del PC in un
  numero solo. Se un aggiornamento di Windows ne annulla qualcuna il numero
  scende, e Ottimizza con un click te lo propone di nuovo.
- **Ottimizza con un click, più sicuro**: lo puoi interrompere mentre lavora,
  le ottimizzazioni già fatte restano e il PC non si riavvia.

## Cos’è

LollozzOS mette in un’app sola quello che di solito è sparso fra decine di
script, guide e programmi: meno processi in background, rete e scheda video
impostate per il gioco, configurazioni pronte per i tuoi giochi. Prima di ogni
modifica l’app salva com’era, quindi tutto si può annullare.

- **Sistema:** Windows 10 e Windows 11, 64 bit
- **Avvio:** come amministratore (cambia impostazioni di sistema)
- **Lingua dell’app:** italiano e inglese (segue la lingua di Windows; si cambia dal globo in basso a sinistra)
- **Prova gratuita:** 24 ore, una volta per computer

## Ottimizza con un click

Il primo passo consigliato: punto di ripristino, servizi superflui, LollozzOS
Debloat, ottimizzazioni per il gaming, energia, rete e l’aspetto LollozzOS,
poi un riavvio.

- Prima di partire vedi i processi di adesso, contati sul tuo PC, e la stima di quelli con LollozzOS. “Vedi dettagli” mostra tutto quello che cambia, gruppo per
  gruppo.
- Qualche domanda (Wi-Fi, Bluetooth, stampa, Store, Xbox, colori…) decide cosa
  resta, con la risposta consigliata già segnata; con “Personalizza” accendi e
  spegni le voci una per una.
- La copia delle impostazioni attuali c’è sempre, ed è quella che permette di
  annullare tutto. Il punto di ripristino di Windows parte già segnato.
- L’avanzamento lo vedi nel riquadro della Home: la percentuale, il passo in
  corso e le fasi.
- Alla fine il PC si riavvia da solo dopo 20 secondi: salva prima il lavoro
  aperto. Dopo il riavvio LollozzOS si riapre e ti mostra processi, servizi e
  avvio di Windows prima e dopo.

<p align="center"><img src="docs/assets/oneclick.jpg" alt="Il piano di Ottimizza con un click" width="820"></p>
<p align="center"><img src="docs/assets/installa.jpg" alt="L’avanzamento di Ottimizza con un click nella Home" width="820"></p>

## Modalità competitiva intelligente

La accendi una volta e non devi fare altro. Quando parte un gioco gli dà la
precedenza, quando lo chiudi rimette tutto com’era. Funziona anche con
LollozzOS chiusa, dopo il riavvio e con qualunque launcher.

- Gioco a priorità alta su tutti i core, scheda video più potente, Modalità
  gioco e timer di Windows a 0,5 ms.
- Tutte le altre app in risparmio: Discord, OBS e i programmi delle periferiche restano aperti e funzionano, ma lasciano il processore al gioco (se registri o trasmetti in x264, OBS può perdere fluidità). I browser a
  priorità bassa.
- Game Bar spenta, servizi che non servono per giocare in pausa, accelerazione del mouse spenta, piano energetico Lollozz Gaming, notifiche spente.
- Non mette mai in risparmio i processi di Windows, Microsoft Defender, gli anti-cheat, la catena audio, i driver video e i programmi che rimappano tastiera e controller; chi usa troppo processore viene solo rallentato, e a fine partita torna tutto com’era.
- A fine partita il resoconto: FPS medi, 1% e 0,1% low, scatti, latenza e
  consigli. Lo salvi sul desktop o lo mandi a Lollozz.

<p align="center"><img src="docs/assets/competitiva.jpg" alt="Il resoconto di una partita" width="820"></p>

## Cosa c’è dentro

| Sezione | Cosa fa |
|---|---|
| **Monitor di sistema** | CPU, GPU, RAM e dischi in tempo reale, il Livello LollozzOS, la Gestione attività per programma con i consigli, Ottimizza con un click, Modalità competitiva intelligente con il resoconto di ogni partita |
| **Debloat** | LollozzOS Debloat (privacy, pubblicità, funzioni IA, Start, barra, Esplora file e prestazioni: 119 voci in una schermata, con i preset, ognuna si annulla), app superflue, Rimuovi Windows AI (Copilot, Recall e le altre funzioni IA, voce per voce) e servizi di Windows uno per uno |
| **Tools e utility** | HWiNFO, CPU-Z, Autoruns, Intelligent Standby List Cleaner, Timer Resolution, FanControl e altri, divisi per categoria |
| **Giochi** | Configurazioni pronte per 9 giochi (e il prossimo Call of Duty in arrivo), con i valori del tuo PC dove servono; più gli interruttori che valgono per tutti i giochi |
| **GPU e grafica** | Driver video con l’ultima versione da scaricare, MPO, preemption, timeout e preset per NVIDIA, AMD e Intel, e l’Affinità: gli interrupt della scheda video sull’ultimo core, misurati prima e dopo |
| **Rete** | Rete impostata sulla latenza, test di 14 DNS, velocità, pacchetti persi, latenza sotto carico, priorità di rete per i giochi |
| **Audio** | Equalizzazione sonorità, volume che non si abbassa nelle chiamate, Nahimic spento, ritardo audio minimo |
| **Energia e prestazioni** | Piani Quotidiano e Gaming fatti per il tuo PC, timer e reattività, risparmio di CPU, USB e PCI Express, interrupt MSI |
| **Gestione app** | Programmi installati dalla fonte ufficiale con winget, disinstallazione, avvio automatico |
| **Personalizzazione visiva** | Sfondi e schermata di blocco, Windows nel colore che vuoi (accento, tema, selezione e 17 cursori), i suoni LollozzOS, schermi, menu del tasto destro del desktop con Strumenti rapidi, Piani energetici e Pad |
| **Diagnosi e manutenzione** | Salute dei dischi, spazio usato, Pulizia del disco e Prepara il PC, le misure del PC, registro di tutto quello che è stato fatto |
| **Fix e riparazioni** | 54 riparazioni divise in 11 gruppi (rete, audio, Update e Store, Esplora file…), con la ricerca: prima i passi, poi l’esito di ognuno |
| **BIOS** | Secure Boot, TPM, virtualizzazione e profilo della RAM letti dal PC, il BIOS più recente dal sito del produttore (scaricato e verificato; lo installi tu), una guida BIOS per la tua scheda madre, “Riavvia nel BIOS” |
| **Modifiche estreme** | Chiuse a chiave: tolgono difese di Windows e non servono per giocare meglio. Punto di ripristino prima |
| **Ripristino** | “Ripristina tutto” annulla tutte le modifiche dell’app; dalla cronologia una alla volta; i punti di ripristino di Windows li crei e li usi dall’app |

In più: una **guida scritta per il tuo PC** (componenti, giochi installati, cosa
conviene attivare e in che ordine) e il **pulsante dell’assistenza**: mandi una
segnalazione con tutto quello che serve per capire il problema, o apri la chat
con i file già pronti.

<p align="center"><img src="docs/assets/aspetto.jpg" alt="Windows nel colore che vuoi" width="820"></p>
<p align="center"><img src="docs/assets/bios.jpg" alt="La pagina BIOS" width="820"></p>

## Giochi

Il file tarato da Lollozz, importato con un clic. Dove serve, i valori che
dipendono dal computer si ricalcolano sul tuo: processore, schermo e scheda
video. Per Valorant, i programmi per la risoluzione allargata. Prima si salva il
tuo file, e “Rimetti com’erano” lo riporta indietro.

Call of Duty: Black Ops 7 e Warzone · Apex Legends · Counter-Strike 2 ·
Fortnite · Rainbow Six Siege · PUBG: Battlegrounds · ARC Raiders ·
Battlefield 6 · Valorant · Call of Duty, prossimo capitolo (in arrivo)

<p align="center"><img src="docs/assets/giochi.jpg" alt="La pagina Giochi" width="820"></p>

## Tutto reversibile

Ogni ottimizzazione è scritta come dati: il valore quando è accesa e quello
quando è spenta. Gli stessi dati servono ad applicarla, ad annullarla e a
leggere com’è davvero, quindi un interruttore mostra sempre quello che Windows
sta facendo.

- Prima di ogni modifica si salvano i valori di prima.
- **Ripristino** annulla tutte le modifiche dell’app, o una alla volta. Non
  riporta le app e i file eliminati, né tema, sfondo e colore.
- Le configurazioni dei giochi si salvano prima di essere sostituite.
- Ottimizza con un click e le modifiche estreme propongono anche un punto di
  ripristino di Windows, già segnato. I punti di ripristino li crei e li usi
  anche dall’app.
- Se Windows ha un aggiornamento da completare, LollozzOS aspetta prima di
  cambiare qualcosa.

Disinstallare l’app **non** annulla da solo le ottimizzazioni: il programma di
disinstallazione ti fa scegliere se togliere solo il programma, rimettere
Windows com’era e poi toglierlo, o togliere anche backup, impostazioni e registro attività (la licenza resta sul computer).

## Installazione

1. Scarica `LollozzOS_Setup_<versione>.exe` da
   [Releases](https://github.com/LollozzOS/LollozzOs/releases/latest).
2. Avvialo e segui i passi. L’app si installa per tutti gli utenti e parte come
   amministratore.

Il programma d’installazione non è firmato: al primo avvio Windows SmartScreen
può avvisare. Clicca **Ulteriori informazioni** e poi **Esegui comunque**.
Scaricalo solo da qui o dal sito.

## Licenza e prova

LollozzOS è un **software a pagamento**.

- **Prova gratuita di 24 ore**, una volta per computer (per attivarla chiede nome e cognome, email e telefono).
- Una licenza, **LollozzOS**: tutta l’app.
- La licenza vale per **un computer** ed è legata al suo hardware: non si
  rivende, non si condivide e non si trasferisce.
- Nell’app copia la richiesta di licenza (arriva anche a Lollozz),
  scrivi sul [Discord](https://discord.gg/gd5cT3Jw9M) e incolla il codice di
  sblocco che ricevi.

I termini completi si leggono durante l’installazione.

## Crediti

Alcune funzioni aprono programmi di altri autori, che restano loro e con le
loro licenze. Rimuovi Windows AI è RemoveWindowsAI con l’aspetto LollozzOS;
LollozzOS Debloat riunisce dentro LollozzOS le impostazioni e gli script di
WinUtil e Win11Debloat. Tutto con il permesso dei loro autori e la loro licenza
MIT accanto.

- [WinUtil](https://github.com/ChrisTitusTech/winutil) di Chris Titus Tech, MIT
- [Win11Debloat](https://github.com/Raphire/Win11Debloat) di Raphire, MIT
- [RemoveWindowsAI](https://github.com/zoicware/RemoveWindowsAI) di zoicware, MIT
- Sparkle
- Discord Debloat di insovs
- O&O ShutUp10++ di O&O Software
- TCP Optimizer di SpeedGuide
- NVIDIA Profile Inspector di Orbmu2k, MIT (il profilo NVIDIA parla con il
  driver come fa lui)
- [PresentMon](https://github.com/GameTechDev/PresentMon) 2.6.0 di Intel, MIT
  (FPS, scatti e latenza della Modalità competitiva intelligente)

E grazie alla comunità italiana del gaming competitivo, che ha provato,
segnalato e migliorato questo lavoro.

## Avvertenze

Il programma cambia valori del registro, servizi, impostazioni di rete, piani
energetici e impostazioni dei driver. È fornito così com’è, senza garanzia:
leggi cosa fa ogni interruttore prima di accenderlo e tieni il punto di
ripristino che l’app ti propone. LollozzOS non è affiliato a Microsoft né agli
editori dei giochi citati; nomi e immagini dei giochi appartengono ai rispettivi
proprietari.

## Community

[Discord](https://discord.gg/gd5cT3Jw9M) ·
[TikTok](https://www.tiktok.com/@_lollozz_) ·
[Instagram](https://www.instagram.com/_lollozz__) ·
[Twitch](https://www.twitch.tv/lollozz__)

Se LollozzOS ti è utile puoi [sostenerlo con una donazione su Ko-fi](https://ko-fi.com/lollozzos):
è libera e non sblocca niente, la licenza resta la stessa.

---

<a id="english"></a>

## English

**Your PC, ready to play.** LollozzOS puts in one app what is usually scattered
across dozens of scripts, guides and programs: fewer background processes,
network and graphics card set up for gaming, ready-made configs for your games.
The previous state is saved before each change, so everything can be undone.

- **System:** Windows 10 and Windows 11, 64-bit
- **Runs as:** administrator (it changes system settings)
- **App language:** Italian and English (follows the Windows language; switch it from the globe at the bottom left)
- **Free trial:** 24 hours, once per computer

### What’s new

*Updated on 7 October 2026.* The app checks for updates by itself: when a new version is out it tells you, downloads it and opens the installer (license, settings and backups stay).

- **LollozzOS Debloat on one screen** *(new)*: privacy, ads, AI features,
  Start, taskbar and performance, 119 items on one screen. Duplicate items
  became a single one, the most complete. It applies only what you tick, the
  ones already done are marked “Already done” and each one can be undone. It
  is also inside One-click optimize, with the same screen.
- **Windows AI really removed** *(new)*: Copilot, Recall and the other AI
  features removed from Windows, not just turned off. Each of the 12 items
  tells you whether it is still on your PC or already gone. The Safe preset
  leaves out the 3 that can make Windows Update fail, and “Bring the AI back”
  puts everything back.
- **Repairs that really work** *(new)*: 54 fixes in 11 groups, on their own
  page and with search. First you see the steps, then the result of each one.
  The Store reinstalls even if it had been removed, Edge comes back, and DISM,
  SFC and the disk check report the real result.
- **Task manager with tips** *(new)*: next to every program a tip, high
  priority for games, low for whatever works in the background, close it if it
  eats processor or memory. You choose with one click: LollozzOS never does
  anything by itself.
- **Graphics card Affinity**: the graphics card interrupts go to the last
  core, usually the least busy, instead of Core 0. On some PCs frametimes get
  steadier, with fewer spikes; on others nothing changes, so the app measures
  before and after. It is already in One-click optimize.
- **Eight more optimizations**: no automatic maintenance starting while you
  play, less telemetry, no energy log in the background, LLMNR off and about
  7 GB of reserved storage freed. Each one has its own switch, with what you
  give up written next to it.
- **The LollozzOS Level**: the optimizations that are on and the PC health in
  one number. If a Windows update undoes some of them the number drops, and
  One-click optimize is offered again.
- **One-click optimize, safer**: you can stop it while it works, the
  optimizations already done stay and the PC does not restart.

### What’s inside

- **One-click optimize:** restore point, unnecessary services, LollozzOS
  Debloat, gaming optimizations, power, network and the LollozzOS look, then a
  restart. You see
  and can edit the whole plan first; a copy of the current settings is always
  included and the restore point starts selected. At the end the PC restarts
  by itself after 20 seconds: save your open work first.
- **Games:** ready-made configs for 9 games (and the next Call of Duty on the
  way); where needed, the values that depend on the computer are recalculated
  for yours (processor, display, graphics card). Your file is backed up first.
- **Debloat** (LollozzOS Debloat, unneeded apps, Remove Windows AI,
  services), **GPU, network, audio, power, apps, appearance, BIOS, diagnosis
  and maintenance, fixes & repairs (54 fixes), tools**, each on its own page,
  plus Smart Competitive Mode, a guide written for your PC and one-click
  support.
- **Everything is reversible:** the previous values are saved before each
  change, and Restore undoes every change the app made, or one at a time (it
  doesn’t bring back deleted apps and files, or theme, wallpaper and color).
  Uninstalling the app does not undo the optimizations by itself: the
  uninstaller lets you choose.

### Install

Download `LollozzOS_Setup_<version>.exe` from
[Releases](https://github.com/LollozzOS/LollozzOs/releases/latest)
and run it. The installer is not signed: if Windows SmartScreen warns you,
choose **More info** and then **Run anyway**.

### License

LollozzOS is **paid software**, with a free 24-hour trial once per computer
(it asks for your first and last name, email and phone). One license,
**LollozzOS**, for the whole app. A
license covers **one computer** and is tied to its hardware; it cannot be
resold, shared or transferred. In the app, copy the license
request (Lollozz receives it too), write on
[Discord](https://discord.gg/gd5cT3Jw9M) and paste the unlock code you receive.

### Support

If LollozzOS is useful to you, you can [support it with a donation on Ko-fi](https://ko-fi.com/lollozzos):
it's optional and doesn't unlock anything, your license stays the same.

### Disclaimer

This program changes registry values, services, network settings, power plans
and driver settings. It is provided as is, without warranty. LollozzOS is not
affiliated with Microsoft or with the publishers of the games mentioned; game
names and images belong to their respective owners.

---

<p align="center"><b>LollozzOS</b> · made by Lollozz · Lollozz Labs</p>
