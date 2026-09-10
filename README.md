# CaptionVault Support

[Italiano](#italiano) · [English](#english)

Public support and testing guide for CaptionVault. The extension source code is not hosted in this repository.

---

<a id="italiano"></a>

## Italiano

### Installare la versione di test su Chrome o Brave

1. Salva il file ZIP ricevuto dal publisher e decomprimilo in una cartella permanente.
2. Apri `chrome://extensions` in Chrome oppure `brave://extensions` in Brave.
3. Attiva **Modalità sviluppatore**.
4. Seleziona **Carica estensione non pacchettizzata**.
5. Scegli la cartella estratta che contiene `manifest.json`.
6. Fissa **CaptionVault** alla barra degli strumenti dal menu delle estensioni.

Non eliminare o spostare la cartella estratta mentre l'estensione è installata. Per installare una nuova build, sostituisci la cartella e premi **Aggiorna** nella pagina delle estensioni.

### Usare CaptionVault

1. Apri su Instagram il profilo che vuoi archiviare.
2. Apri CaptionVault dalla barra degli strumenti.
3. Usa **Full scan** la prima volta. Mantieni aperta la scheda Instagram durante la scansione.
4. Per le scansioni successive usa **Update**, che si ferma dopo 30 post già conosciuti.
5. Se Instagram carica i post in modo discontinuo, seleziona la velocità **Slow** e riprova.
6. Seleziona **Search local index** per cercare didascalie, profili o hashtag e riaprire i post originali.

### Backup e trasferimento

- **Share backup** crea un file ZIP portabile dell'archivio locale.
- **Import backup** importa o unisce un backup ZIP; sono compatibili anche i vecchi file JSON e CSV.
- Prima di usare **Clear index**, salva un backup se vuoi conservare i dati.
- L'[archivio web locale](https://insta-find.vercel.app/index.html) può importare lo stesso ZIP senza caricarlo su un server.

### Privacy

CaptionVault salva nomi dei profili, link, didascalie, date e miniature localmente nel browser. Contatta Instagram e i suoi CDN solo durante una scansione; non usa analytics, pubblicità o telemetria. Consulta la [Privacy Policy](https://insta-find.vercel.app/privacy.html).

### Segnalare un problema

Apri una [issue pubblica](https://github.com/webfdev/captionvault-support/issues/new) e indica:

- Chrome o Brave e relativa versione;
- versione di CaptionVault;
- operazione eseguita e risultato atteso;
- risultato ottenuto ed eventuale messaggio di errore;
- screenshot, se utile, dopo aver nascosto informazioni personali.

**Non allegare backup, password, cookie o altre informazioni private a un'issue pubblica.**

---

<a id="english"></a>

## English

### Install the test build on Chrome or Brave

1. Save the ZIP file received from the publisher and extract it to a permanent folder.
2. Open `chrome://extensions` in Chrome or `brave://extensions` in Brave.
3. Enable **Developer mode**.
4. Select **Load unpacked**.
5. Choose the extracted folder containing `manifest.json`.
6. Pin **CaptionVault** to the browser toolbar from the extensions menu.

Do not delete or move the extracted folder while the extension is installed. To install a newer build, replace the folder and select **Update** on the extensions page.

### Use CaptionVault

1. Open the Instagram profile you want to archive.
2. Open CaptionVault from the browser toolbar.
3. Use **Full scan** the first time. Keep the Instagram tab open while scanning.
4. For later scans, use **Update**, which stops after 30 already-known posts.
5. If Instagram loads posts unreliably, select **Slow** and try again.
6. Select **Search local index** to search captions, profiles, or hashtags and reopen original posts.

### Backups and transfer

- **Share backup** creates a portable ZIP file containing the local archive.
- **Import backup** imports or merges a ZIP backup; older JSON and CSV files remain compatible.
- Before using **Clear index**, save a backup if you want to keep the data.
- The [local web archive](https://insta-find.vercel.app/index.html) can import the same ZIP without uploading it to a server.

### Privacy

CaptionVault stores profile names, links, captions, dates, and thumbnails locally in the browser. It contacts Instagram and its CDNs only during a scan and uses no analytics, advertising, or telemetry. Read the [Privacy Policy](https://insta-find.vercel.app/privacy.html).

### Report a problem

Open a [public issue](https://github.com/webfdev/captionvault-support/issues/new) and include:

- Chrome or Brave and its version;
- CaptionVault version;
- the action performed and expected result;
- the actual result and any error message;
- a screenshot when useful, after hiding personal information.

**Do not attach backups, passwords, cookies, or other private information to a public issue.**

---

CaptionVault is not affiliated with or endorsed by Instagram or Meta.
