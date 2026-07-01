[README.md](https://github.com/user-attachments/files/29549924/README.md)
# Divine Client

Launcher desktop standalone per Minecraft: Java Edition, con client di ottimizzazione
grafica integrato basato su Fabric — nello spirito di progetti come Prism Launcher o
HMCL, ma con un'identità visiva e un set di moduli propri.

## Cosa fa

- **Login Microsoft ufficiale** (OAuth2 Device Code Flow) — nessuna password transita
  dall'applicazione, il login avviene nel browser di sistema
- **Download e verifica automatica** di Minecraft e Fabric Loader dai server ufficiali
  Mojang/Fabric, con controllo hash SHA-1/SHA-256 di ogni file
- **Client di ottimizzazione FPS** integrato (Fabric): Entity Culling, Block Entity
  Culling, Dynamic Render Distance, Particle Limiter e altri moduli mirati a migliorare
  le performance su server con molte entità (es. server roleplay)
- **Nessuna funzionalità che dia vantaggi competitivi**: nessun cheat, nessuna
  informazione non disponibile al client vanilla, nessun automatismo di gioco

## Perché serve l'accesso alle API Xbox Live / Minecraft Services

L'applicazione autentica l'account Microsoft dell'utente esclusivamente per verificare
il possesso della licenza di gioco e recuperare il profilo (username, UUID), esattamente
come fa il launcher ufficiale Minecraft. Nessun dato dell'utente viene raccolto,
conservato o condiviso con terzi.

## Stato del progetto

Progetto personale in sviluppo attivo.

## Uso previsto

Uso personale e di test. L'app Azure è registrata con "Personal Microsoft accounts only".
