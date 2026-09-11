# SuperCAS 1.0 — downloads

*play & capture real MSX tapes* · [English](#english) · [Italiano](#italiano)

<a id="english"></a>
## English

SuperCAS turns MSX files (`.CAS`, `.TSX`, `.ROM`, `.BIN`, BASIC tokenized or
ASCII) into audio for the cassette port of a real MSX, and captures real
tapes back into files. It works with any MSX that has a cassette port (MSX1
and up; the turbo R has none), and it was proven on a real Philips VG-8010
from both builds, macOS and Windows.

### Requirements

- **macOS 11 Big Sur or later**, Intel and Apple Silicon (universal app,
  notarized by Apple). Nothing else to install. Tested on macOS 26.
- **Windows 10 / 11, 64-bit**. Nothing to install apart from SuperCAS
  itself: Python lives inside the package.

### Files — Release [v1.0](https://github.com/andreaferrinicode/SuperCAS-download/releases/tag/v1.0)

| File | For | Size |
|---|---|---|
| [`SuperCAS-1.0.dmg`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0.dmg) | macOS — open the disk, drag SuperCAS to Applications | 51.5 MB (51,518,714 bytes) |
| [`SuperCAS-1.0-Setup.exe`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Setup.exe) | Windows — installer, one file, no admin rights needed | 18.3 MB (18,292,736 bytes) |
| [`SuperCAS-1.0-Windows.zip`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Windows.zip) | Windows — portable: extract and double-click `SuperCAS.exe` | 21.3 MB (21,292,947 bytes) |

The manuals (Italian and English, PDF) are inside the disk image and the
Windows packages, and also attached to the Release on their own:
[`SuperCAS-1.0-Manual-EN.pdf`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Manual-EN.pdf)
· [`SuperCAS-1.0-Manuale-IT.pdf`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Manuale-IT.pdf).

**Windows SmartScreen**: the first time you run `SuperCAS.exe`, the Setup
or `Install SuperCAS.exe`, Windows may say "Windows protected your PC".
That is normal for a free program without a code-signing certificate, and
we chose not to buy one: SmartScreen measures reputation, not safety.
Click **More info**, then **Run anyway**.

**macOS**: the app is signed and notarized, so it opens with a double
click. The first time you capture a tape, macOS asks for microphone
access: that is the cassette input.

### SHA-256

```
f0a92eb2c648183bea92f8149244b10aa14a2883be872334682b6bca1681ad71  SuperCAS-1.0.dmg
df18fa5d17c66b467dbebc8e0032191bd8ce188a963ac6f4c0eb2f5820cc541d  SuperCAS-1.0-Setup.exe
1f40d91616c963ec9f4f013c730e16d2df42cb48628d5283941e77039e499a95  SuperCAS-1.0-Windows.zip
53cf26b371a1c15ec0a2b7e32c9d7c696925fbf479db4548ea75996d0529c37f  SuperCAS-1.0-Manual-EN.pdf
01538187f108ff7fd872253cf7b4763d2a075b5af539b5666d59aef00838dd55  SuperCAS-1.0-Manuale-IT.pdf
```

macOS: `shasum -a 256 <file>` · Windows: `certutil -hashfile <file> SHA256`

### Licence

Free of charge, not open source: use it and pass it on complete, unmodified
and free of charge; do not modify it or sell it. What you make with it is
yours. Full text in [LICENSE.txt](LICENSE.txt).

### What it contains, and what it does not

No third-party MSX software: no games, no ROMs, no tapes. Everything
SuperCAS sends to the MSX is built from the files you give it, and the Z80
loaders were written from scratch for this project. The cassettes you
capture and the files you play must be your own — and always keep the
original cassette.

### Credits

- The recorder key clacks are "Mechanical sounds emerge with a retro
  cassette recorder button press" by sounddogs, Envato Elements, licensed
  for SuperCAS under no. SJ87UVXY9B. They are part of the app: not to be
  extracted or reused.
- The logo was generated with GPT Image 2 via Higgsfield.
- The `.CAS` format and the FSK timings were verified against the source
  of CasLink3 3.3 (Alexey Podrezov) as the reference for the format;
  SuperCAS's code is written from scratch.

**MSX** is a registered trademark of MSX Licensing Corporation. SuperCAS is
not affiliated with, endorsed by, or sponsored by them, or by Philips, or by
any other manufacturer named in the program or its documentation. Those
names appear only to describe what the program works with.

---

<a id="italiano"></a>
## Italiano

SuperCAS trasforma i file MSX (`.CAS`, `.TSX`, `.ROM`, `.BIN`, BASIC
tokenizzato o ASCII) in audio per la porta cassette di un MSX vero, e
cattura i nastri veri riportandoli in file. Funziona con qualunque MSX
dotato di porta cassette (MSX1 in su; il turbo R non ce l'ha), ed è
collaudata su un Philips VG-8010 vero da entrambe le versioni, macOS e
Windows.

### Requisiti

- **macOS 11 Big Sur o più recente**, Intel e Apple Silicon (app
  universale, notarizzata da Apple). Non serve installare altro. Provata
  su macOS 26.
- **Windows 10 / 11 a 64 bit**. Niente da installare a parte SuperCAS:
  Python vive dentro il pacchetto.

### File — Release [v1.0](https://github.com/andreaferrinicode/SuperCAS-download/releases/tag/v1.0)

| File | Per | Dimensione |
|---|---|---|
| [`SuperCAS-1.0.dmg`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0.dmg) | macOS — apri il disco e trascina SuperCAS in Applicazioni | 51,5 MB (51.518.714 byte) |
| [`SuperCAS-1.0-Setup.exe`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Setup.exe) | Windows — installer, un file solo, niente permessi da amministratore | 18,3 MB (18.292.736 byte) |
| [`SuperCAS-1.0-Windows.zip`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Windows.zip) | Windows — portatile: estrai e doppio clic su `SuperCAS.exe` | 21,3 MB (21.292.947 byte) |

I manuali (italiano e inglese, PDF) sono dentro l'immagine disco e nei
pacchetti Windows, e anche allegati alla Release a parte:
[`SuperCAS-1.0-Manuale-IT.pdf`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Manuale-IT.pdf)
· [`SuperCAS-1.0-Manual-EN.pdf`](https://github.com/andreaferrinicode/SuperCAS-download/releases/download/v1.0/SuperCAS-1.0-Manual-EN.pdf).

**Windows SmartScreen**: la prima volta che apri `SuperCAS.exe`, il Setup o
`Install SuperCAS.exe`, Windows può dire "PC protetto da Windows". È
normale per un programma gratuito senza certificato di firma, e abbiamo
scelto di non comprarlo: SmartScreen misura la reputazione, non la
sicurezza. Clic su **Ulteriori informazioni** e poi **Esegui comunque**.

**macOS**: l'app è firmata e notarizzata, quindi si apre col doppio clic.
Alla prima cattura macOS chiede l'accesso al microfono: è l'ingresso della
cassetta.

### Impronte SHA-256

```
f0a92eb2c648183bea92f8149244b10aa14a2883be872334682b6bca1681ad71  SuperCAS-1.0.dmg
df18fa5d17c66b467dbebc8e0032191bd8ce188a963ac6f4c0eb2f5820cc541d  SuperCAS-1.0-Setup.exe
1f40d91616c963ec9f4f013c730e16d2df42cb48628d5283941e77039e499a95  SuperCAS-1.0-Windows.zip
53cf26b371a1c15ec0a2b7e32c9d7c696925fbf479db4548ea75996d0529c37f  SuperCAS-1.0-Manual-EN.pdf
01538187f108ff7fd872253cf7b4763d2a075b5af539b5666d59aef00838dd55  SuperCAS-1.0-Manuale-IT.pdf
```

macOS: `shasum -a 256 <file>` · Windows: `certutil -hashfile <file> SHA256`

### Licenza

Gratuita, non open source: si usa e si passa ad altri intera, non
modificata e gratis; non si modifica e non si vende. Quello che ci fai è
tuo. Testo completo in [LICENSE.txt](LICENSE.txt).

### Cosa contiene, e cosa no

Nessun software MSX di terzi: nessun gioco, nessuna ROM, nessun nastro.
Tutto quello che SuperCAS manda all'MSX lo costruisce lei dai file che le
dai, e i loader Z80 sono scritti da zero per questo progetto. Le cassette
che catturi e i file che riproduci devono essere i tuoi — e tieni sempre
la cassetta originale.

### Crediti

- I clack dei tasti del registratore sono "Mechanical sounds emerge with a
  retro cassette recorder button press" di sounddogs, Envato Elements,
  licenza per SuperCAS n. SJ87UVXY9B. Sono parte dell'app: non si
  estraggono e non si riusano.
- Il logo è generato con GPT Image 2 via Higgsfield.
- Il formato `.CAS` e i tempi dell'FSK sono verificati sul sorgente di
  CasLink3 3.3 (Alexey Podrezov) come riferimento del formato; il codice di
  SuperCAS è scritto da zero.

**MSX** è un marchio registrato di MSX Licensing Corporation. SuperCAS non
è affiliata a loro, a Philips o ad alcun altro produttore nominato nel
programma o nella sua documentazione, e non è approvata né sponsorizzata
da nessuno di essi. Quei nomi compaiono solo per descrivere con cosa
funziona il programma.
