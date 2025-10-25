# RevaroRP – LSPD Apply Script  
### A modern FiveM in-game application system for LSPD | Ein modernes Bewerbungs-System für FiveM

---

## 📝 Beschreibung | Description

Das **LSPD Apply Script** ist ein modernes und benutzerfreundliches Bewerbungssystem für FiveM-Server.  
Spieler können sich direkt im Spiel bewerben, indem sie **E** drücken, ein Formular ausfüllen und ihre Daten automatisch an einen **Discord-Webhook** senden.  
Es wurde ursprünglich für das **LSPD** entwickelt, kann aber leicht für jede andere Fraktion angepasst werden.

The **LSPD Apply Script** is a modern and easy-to-use application system for FiveM servers.  
Players can apply directly in-game by pressing **E**, filling out a form, and sending their data automatically to a **Discord webhook**.  
It was originally created for the **LSPD**, but can easily be adapted for any faction.

---

## ⚙️ Installation

### 🇩🇪 Deutsch
1. Lade den Ordner `rev_apply` in deinen `resources`-Ordner hoch.  
2. Füge in deiner `server.cfg` folgende Zeile hinzu:
   ```
   ensure rev_apply
   ```
3. Öffne die Datei `config.lua` und trage deinen Discord-Webhook ein:
   ```lua
   Config.Webhook = "https://discord.com/api/webhooks/DEIN_WEBHOOK_HIER"
   ```
4. Starte deinen Server neu oder lade die Ressource neu:
   ```
   restart rev_apply
   ```

### 🇬🇧 English
1. Upload the folder `rev_apply` to your `resources` directory.  
2. Add this line to your `server.cfg`:
   ```
   ensure rev_apply
   ```
3. Open `config.lua` and insert your Discord webhook:
   ```lua
   Config.Webhook = "https://discord.com/api/webhooks/YOUR_WEBHOOK_HERE"
   ```
4. Restart your server or reload the resource:
   ```
   restart rev_apply
   ```

---

## 🎮 Nutzung im Spiel | In-game Usage

- Gehe zur eingestellten Position (z. B. LSPD).  
- Drücke **E**, um das Bewerbungsformular zu öffnen.  
- Fülle die Felder (Vorname, Nachname, Alter, Geschlecht, Motivation) aus.  
- Klicke auf **Abschicken**.  
- Die Bewerbung wird automatisch an Discord gesendet.

- Go to the configured location (e.g. LSPD).  
- Press **E** to open the application form.  
- Fill in the fields (first name, last name, age, gender, motivation).  
- Click **Submit**.  
- The application will automatically be sent to Discord.

---

## 💬 Beispiel Discord-Nachricht | Example Discord Message

```
Neue LSPD-Bewerbung eingegangen!

👤 Name: Max Mustermann
🎂 Alter: 24
🚹 Geschlecht: Männlich
💬 Motivation: Ich möchte das LSPD-Team unterstützen und Los Santos sicherer machen!
```

```
New LSPD Application received!

👤 Name: Max Mustermann
🎂 Age: 24
🚹 Gender: Male
💬 Motivation: I want to help the LSPD keep Los Santos safe!
```

---

## 🛠️ Anpassung | Customization

- **Position:** Ändere die Koordinaten in der `client.lua`.  
- **Texte & Farben:** Bearbeite die `html`-Datei.  
- **Webhook:** Trage ihn in der `config.lua` ein.  
- **Fraktion:** Ersetze „LSPD“ durch eine andere Organisation, z. B. „LSMD“ oder „BCSO“.

- **Position:** Change coordinates inside `client.lua`.  
- **Texts & colors:** Edit the `html` file.  
- **Webhook:** Configure it in `config.lua`.  
- **Faction:** Replace “LSPD” with your own faction (e.g., “LSMD” or “BCSO”).

---

## 🌍 Sprache | Language

🇩🇪 Das Script ist standardmäßig **auf Deutsch**.  
Wenn du es auf **Englisch oder eine andere Sprache** umstellen möchtest, musst du die Texte **manuell im Code** (z. B. HTML oder LUA) anpassen.  
Es gibt keine automatische Sprachumschaltung.

🇬🇧 This script is written **in German by default**.  
If you want to use it in **English or another language**, you must **manually translate** the text in the code (HTML or LUA).  
There is **no automatic language selection**.

---

## 📜 Nutzungsbedingungen | Terms of Use

### 🇩🇪 Deutsch
- Dieses Script darf **frei genutzt und angepasst**, aber **nicht verkauft** werden.  
- Es ist **nicht erlaubt**, dieses Script als eigenes Werk auszugeben oder den Autor zu entfernen.  
- Bitte gib immer den ursprünglichen Autor an:
  > Script erstellt von **R. Cosa** für **RevaroRP**  
- Fairness und Respekt gegenüber anderen Entwicklern sind Pflicht.

### 🇬🇧 English
- You may **use and modify** this script freely, but you **may not sell it**.  
- You **must not claim** it as your own or remove the author’s credit.  
- Please always credit the original creator:
  > Script created by **R. Cosa** for **RevaroRP**  
- Respect and fairness towards other developers are essential.

---

## 👤 Credits

- **Author / Entwickler:** R. Cosa  
- **Project / Projekt:** RevaroRP  
- **Version:** 1.0.0  
- **Discord:** *https://discord.gg/ddWU2hbMUq*

---

## 📘 Lizenz | License

© 2025 RevaroRP – erstellt von R. Cosa  
Dieses Script ist **kostenlos für nicht-kommerzielle FiveM-Projekte**.  
Jegliche Vervielfältigung, Veröffentlichung oder Weitergabe **ohne Nennung des Autors** ist untersagt.  
Das Script darf verwendet, angepasst und geteilt werden, **solange der ursprüngliche Credit erhalten bleibt**.

© 2025 RevaroRP – created by R. Cosa  
This script is **free for non-commercial FiveM projects**.  
Any re-upload or redistribution **without crediting the original author** is not allowed.  
You may use, modify, and share it **as long as proper credit remains**.

---

### ❤️ Danke fürs Nutzen von RevaroRP Scripts!  
**Enjoy developing – and keep Los Santos safe.**
