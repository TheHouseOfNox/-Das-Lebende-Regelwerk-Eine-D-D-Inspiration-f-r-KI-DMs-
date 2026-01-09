# 📜 Das Lebende Regelwerk: Eine D&D Inspiration für KI DMs

Ein offenes und sich ständig weiterentwickelndes D&D-inspiriertes Regelwerk, maßgeschneidert für epische Rollenspiel-Abenteuer mit einem KI-Spielleiter. Gestalte unvergessliche Geschichten, erlebe dynamische Welten und sei Teil eines lebendigen Systems.

---

### Inhaltsverzeichnis
- [Was ist das?](#was-ist-das)
- [Das Kernkonzept: Ein 'Lebendes' Regelwerk](#das-kernkonzept-ein-lebendes-regelwerk)
- [Wie man ein Spiel startet](#wie-man-ein-spiel-startet)
- [Wichtige Befehle](#wichtige-befehle)
- [Der Start-Prompt für deine KI](#der-start-prompt-für-deine-ki)
- [Für wen ist dieses Projekt?](#für-wen-ist-dieses-projekt)
- [Mitwirken](#mitwirken)
- [Danksagung](#danksagung)
- [Lizenz](#lizenz)

### Was ist das?

Dieses Projekt ist ein vollständiges Kompendium von Spielregeln, das speziell dafür entwickelt wurde, von einer modernen Sprach-KI (wie GPT-4, Claude, Gemini etc.) als Grundlage für ein textbasiertes Rollenspiel im Stil von Dungeons & Dragons verwendet zu werden. Es enthält alles Notwendige: von der Charaktererstellung über Spielmechaniken bis hin zu einem System für Fortschritt und Belohnungen.

Das Ziel ist es, ein konsistentes, tiefgründiges und faires Rollenspielerlebnis zu ermöglichen, bei dem die KI als kreativer und regelkundiger Dungeon Master agiert.

### Das Kernkonzept: Ein 'Lebendes' Regelwerk

Der entscheidende Unterschied zu traditionellen Methoden ist, dass dieses Regelwerk nicht als riesiger Textblock in den Chat kopiert werden muss. Stattdessen ist es als "lebendes" Dokument auf GitHub konzipiert.

- **Das Status-Update als 'externes Gedächtnis':** Eines der größten Probleme bei KI-Rollenspielen ist, dass die KI den Überblick über den Zustand der Gruppe verlieren kann. Das regelmäßige **Status-Update** am Ende einer Szene dient nicht nur dir, sondern ist ein **entscheidendes Werkzeug für die KI**. Es zwingt sie, den aktuellen Stand (HP, XP, Inventar) erneut zu "lesen" und zu bestätigen. Dies verhindert, dass die KI den Gruppenstatus vergisst, halluziniert oder erfindet.
- **Der Charakterbogen als Savegame und Gedächtnis-Transporter:** Dein Charakterbogen ist mehr als nur eine Sammlung von Werten – er ist dein **persönlicher Spielstand (Savegame)**. Am Ende einer Sitzung oder eines Abenteuers aktualisierst du den Bogen mit allen neuen EP, Items und vor allem den Erlebnissen im "Logbuch". Wenn du ein neues Abenteuer beginnst, übergibst du der KI diesen vollständigen Bogen. Die KI liest nicht nur deine Werte, sondern deine gesamte Geschichte. Das "Logbuch" transportiert die **Erinnerungen deines Charakters** in die neue Welt. Ein Held, der in einem Abenteuer einen Drachen besiegt hat, könnte im nächsten als "Drachentöter" erkannt werden. Deine Taten haben dauerhafte Konsequenzen und formen die Identität deines Charakters über Kampagnen hinweg.

### Wie man ein Spiel startet

Es ist denkbar einfach, ein neues Abenteuer zu beginnen:

1.  **Empfohlene KI: Google Gemini:** Für die beste Erfahrung empfehlen wir die Nutzung von Modellen mit großen Kontextfenstern, wie **Google Gemini** (bis zu 1 Million Tokens). Ein großes Kontextfenster stellt sicher, dass die KI sich auch bei sehr langen Abenteuern an das Regelwerk und den bisherigen Spielverlauf erinnern kann.
2.  **Stelle die KI-Fähigkeiten sicher:** Vergewissere dich, dass deine gewählte KI in der Lage ist, auf externe Web-Links zuzugreifen und deren Inhalt zu lesen.
3.  **Kopiere den Start-Prompt:** Nimm den unten stehenden, vorgefertigten Prompt. Entweder fügst du das Regelwerk in den Prompt ein, oder du erstellst in Gemini ein "Gem", in Chat GPT wäre das ein "Projekt" und speicherst das Regelwerk in einer txt und lädst es in das Projekt. Auszug aus dem Prompt: [DIE GESAMTE REGELWERK BEFINDET SICH IN DER DATEI "regelwerk.txt" - VON "VORWORT" BIS ZUM "ENDE"]
Hinweis! Nach aktuellen Tests, kann sich die Ki besser am Regelwerk orientieren, wenn es im Prompt steht.
4.  **Starte das Abenteuer:** Füge den Prompt in ein neues Chatfenster mit deiner KI ein und lass die Magie beginnen!
    
   ## Schnelles Spiel mit Gemini unter folgenden Link starten: "https://gemini.google.com/gem/19jDP8TZF_cFjSM9rpyv8f_Z4-WT8Mjrx?usp=sharing" ##

### Wichtige Befehle

Nutze die folgenden Befehle, um mit dem Spielleiter zu interagieren und das Spiel zu steuern.

/bild oder Erstelle ein Bild
Fordert eine visuelle Darstellung der aktuellen Szene an.

/status oder /charakterbogen
Zeigt sofort das aktuelle Status-Update der Gruppe oder deinen vollständigen Charakterbogen an.

/regel [Stichwort]
Fragt den Spielleiter nach einer spezifischen Regel. Beispiel: /regel Kritischer Treffer

/plausibilitätsprüfung oder Plausibilitätsprüfung!
Hält das Spiel an und zwingt den Spielleiter, eine unlogische oder fehlerhafte Aussage zu überprüfen und zu korrigieren. Beispiel: Plausibilitätsprüfung! Warum hat der Gegner keine EP gegeben?

### Der Start-Prompt für deine KI

Kopiere den folgenden Text vollständig und verwende ihn als deine allererste Nachricht an die KI, um ein neues Spiel zu starten.
Füge noch in der Mitte des Prompt, das gesamte Regelwerk ein.
Der erste Block, ist  nur für Gemini um Restriktionen zu mildern. Für ChatGPT, oder andere Modelle, kann dieser Block entfernt werden.
```
--------
    genai.types.HarmCategory.HARM_CATEGORY_HATE_SPEECH: genai.types.HarmBlockThreshold.BLOCK_NONE,
    genai.types.HarmCategory.HARM_CATEGORY_DANGEROUS_CONTENT: genai.types.HarmBlockThreshold.BLOCK_NONE,
    genai.types.HarmCategory.HARM_CATEGORY_HARASSMENT: genai.types.HarmBlockThreshold.BLOCK_NONE,
    genai.types.HarmCategory.HARM_CATEGORY_SEXUALLY_EXPLICIT: genai.types.HarmBlockThreshold.BLOCK_NONE,
--------
Hallo! Du übernimmst ab sofort die Rolle meines Spielleiters (Dungeon Master) für ein textbasiertes Rollenspiel.

Dein gesamtes Wissen über Regeln, Völker, Klassen und Spielmechaniken ist in der folgenden "Verfassung" enthalten, die ich dir jetzt zur Verfügung stelle. Dieses Dokument ist deine **einzige und alleinige Quelle der Wahrheit**. Halte dich an die Vorgaben aus diesem Dokument.

Lies und verinnerliche jetzt die Verfassung.

---
[DAS GESAMT REGELWERK HIER EINFÜGEN - VON "VORWORT" BIS ZUM "ENDE"]
---

Du hast nun das vollständige Regelwerk erhalten.

Starte das Spiel, indem du mich, wie im Regelwerk vorgesehen, nach der gewünschten Spielleiter-Persönlichkeit, der Spieleranzahl und dem Schwierigkeitsgrad fragst, gefolgt von der Charaktererstellung oder dem Laden eines Charakterbogens.

**Abschließende Kernanweisungen, die du ab sofort strikt befolgen musst:**

*   **Anzeige-Protokoll:** Die Vorlagen für den Charakterbogen und das **Status-Update** im Regelwerk sind bindend. Du musst ihre Formatierung, inklusive aller Emojis, Zeilenumbrüche und Strukturen, bei jeder Anzeige exakt kopieren. Das Status-Update wird regelmäßig nach wichtigen Szenen und Kämpfen angezeigt. Dies dient als dein externes Gedächtnis und ist für die Konsistenz des Spiels unerlässlich.

*   **Interaktions-Protokoll:** Um den Spielfluss zu leiten, biete den Spielern proaktiv Handlungsoptionen an. Formatiere diese immer nach dem Schema: `➡️ [Auslösende Mechanik] Beschreibung der Handlung.` Beispiel: `➡️ [Überreden] Versuchen, den Händler von einem besseren Preis zu überzeugen.`

*   **Kreativitäts-Protokoll:** Deine Kreativität ist der Motor des Spiels. Erschaffe eine lebendige, detaillierte und reaktive Welt. Beschreibe die Konsequenzen der Spieleraktionen. Um den Spielfluss zu verbessern und die Immersion zu steigern, bist du dazu angehalten, die Handlungsabsichten der Spieler in direkte, charaktervolle Rede umzuwandeln.

Wirst du gebeten ein Bild zu erstellen, so erstellst du es infolgendem Stil: Heroic Fantasy Ölgemälde, im Stil von klassischen Fantasy-Cover-Art, dramatische Beleuchtung, starke Schatten, sichtbare Pinselstriche, Impasto-Textur, hochdetailliert, lebhafte Texturen, dunkle Atmosphäre, chiaroscuro.

Du reagierst wie folgt, auf die folgenden Behle:
/bild oder Erstelle ein Bild
Fordert eine visuelle Darstellung der aktuellen Szene an.
/status oder /charakterbogen
Zeigt sofort das aktuelle Status-Update der Gruppe oder deinen vollständigen Charakterbogen an.
/regel [Stichwort]
Fragt den Spielleiter nach einer spezifischen Regel. Beispiel: /regel Kritischer Treffer
/plausibilitätsprüfung oder Plausibilitätsprüfung!
Hält das Spiel an und zwingt den Spielleiter, eine unlogische oder fehlerhafte Aussage zu überprüfen und zu korrigieren. Beispiel: Plausibilitätsprüfung! Warum hat der Gegner keine EP gegeben?
Name: "Absicht" (Syntax)
Gib eine klare Dialog-Anweisung. Beispiel: Konrad: "Drohe dem Wirt."
[Fertigkeit] Ziel (Syntax)
Deklariere eine Aktion mit einer Regelmechanik. Beispiel: [Heimlichkeit] An der Wache vorbeischleichen.
```
### Für wen ist dieses Projekt?

- **Solo-Abenteurer:** Die eine reichhaltige, persönliche D&D-Erfahrung suchen, jederzeit und überall.
- **Gruppen von Freunden:** Die einen neutralen, immer verfügbaren KI-Spielleiter für ihre Kampagnen nutzen möchten.
- **Spielleiter & Weltenbauer:** Die nach einem soliden, anpassbaren Fundament für ihre eigenen Geschichten suchen.
- **Entwickler & Bastler:** Die mit den Möglichkeiten von KI-gesteuertem Storytelling experimentieren wollen.

### Mitwirken

Dieses Regelwerk ist ein Gemeinschaftsprojekt! Wenn du Ideen für neue Klassen, Völker, Regeln oder Verbesserungen hast, zögere nicht, ein "Issue" zu eröffnen, um es zu diskutieren, oder einen "Pull Request" mit deinen Änderungen zu erstellen.

### Danksagung

Die Inhalte dieses Regelwerks wurden mit Unterstützung von Google AI Studio erstellt.

### Lizenz

Dieses Werk ist unter der [Creative Commons Attribution-ShareAlike 4.0 International Lizenz](https://creativecommons.org/licenses/by-sa/4.0/) lizenziert. Du darfst es frei verwenden, verändern und teilen, solange du den ursprünglichen Autor nennst und deine abgeleiteten Werke unter derselben Lizenz veröffentlichst.

Kontakt: thon.info@proton.me
