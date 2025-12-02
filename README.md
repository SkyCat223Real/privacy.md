# Minecraft ↔ Discord Chat Link Bot

Dieser Bot verbindet den Minecraft-Server-Chat mit einem Discord-Channel.  
Er ermöglicht es, dass Nachrichten aus Minecraft im Discord erscheinen – und Nachrichten aus Discord im Minecraft-Chat angezeigt werden.

## ✨ Hauptfunktionen
- Bidirektionale Chat-Verbindung zwischen Minecraft und Discord
- Spieler Join/Leave Meldungen von Minecraft → Discord
- Discord-Nachrichten → Minecraft-Chat Weiterleitung
- Optionale Moderationsfunktionen (z. B. Minecraft-Broadcasts aus Discord)
- Keine gefährlichen oder automatisierten Aktionen außerhalb des Chats

## 🔒 Daten, die der Bot verarbeitet
Der Bot verarbeitet **nur die minimal notwendigen Daten**, um Chatnachrichten zu übertragen:

### Erfasst:
- Discord-Nutzername + Nachricht (nur im verwendeten Channel)
- Minecraft-Spielernamen + Nachrichten
- Channel-ID zum Senden/Empfangen
- Server-ID zur Orientierung

### Kein Logging:
- Keine Speicherung persönlicher Daten
- Keine Weitergabe an Dritte
- Keine Analyse oder Profilbildung
- Nachrichten werden nur live weitergeleitet, nicht gespeichert

## 🧾 Warum der Bot diese Daten braucht
Die oben genannten Daten sind notwendig, um:
- die Chat-Verbindung zwischen Minecraft und Discord herzustellen
- Nachrichten korrekt zuzuordnen
- den richtigen Discord-Channel zu bedienen

## ⚙️ Wie der Bot funktioniert
- Der Minecraft-Server sendet Chat-Events an den Bot
- Der Bot sendet die Nachricht in den konfigurierten Discord-Channel
- Discord-Nachrichten aus dem Channel werden per Bot an Minecraft übergeben
- Es wird kein anderer Channel überwacht oder gelesen

## 📄 Terms & Privacy
Für die Discord Bot Verification werden folgende Dokumente bereitgestellt:

- **Privacy Policy:** [[privacy.md]](https://github.com/SkyCat223Real/privacy.md/blob/main/privacy.md)  
- **Terms of Service:** [LINK EINFÜGEN]

(Beide Dokumente sind öffentlich abrufbar und erklären die Datennutzung.)

## 👤 Kontakt
Für Fragen, Datenlöschung oder Support:
- Email: skycat223yt@gmail.com
- Discord: skycat223_
