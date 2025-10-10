# 📜 Das Lebende Regelwerk: Eine D&D Inspiration für KI DMs

Ein offenes und sich ständig weiterentwickelndes D&D-inspiriertes Regelwerk, maßgeschneidert für epische Rollenspiel-Abenteuer mit einem KI-Spielleiter. Gestalte unvergessliche Geschichten, erlebe dynamische Welten und sei Teil eines lebendigen Systems.

---

### Inhaltsverzeichnis
- [Was ist das?](#was-ist-das)
- [Das Kernkonzept: Ein 'Lebendes' Regelwerk](#das-kernkonzept-ein-lebendes-regelwerk)
- [Wie man ein Spiel startet](#wie-man-ein-spiel-startet)
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

- **Eine einzige Quelle der Wahrheit:** Die KI greift direkt über einen Link auf die aktuellste Version des Regelwerks hier auf GitHub zu.
- **Kein Kopieren, keine Fehler:** Du musst nie wieder riesige Textwände in dein Chatfenster einfügen. Das spart Zeit und vermeidet Formatierungsfehler. (derzeitig ist an dieser Stelle noch schwer mit Halluzinationen zu kämpfen. Dieses Feature wird zukünftigen Updates ausgearbeitet.)
- **Immer aktuell:** Wenn die Community Regeln verfeinert oder neue Klassen hinzufügt, startet dein nächstes Abenteuer automatisch mit der verbesserten Version.
- **Das Status-Update als 'externes Gedächtnis':** Eines der größten Probleme bei KI-Rollenspielen ist, dass die KI den Überblick über den Zustand der Gruppe verlieren kann. Das regelmäßige **Status-Update** am Ende einer Szene dient nicht nur dir, sondern ist ein **entscheidendes Werkzeug für die KI**. Es zwingt sie, den aktuellen Stand (HP, XP, Inventar) erneut zu "lesen" und zu bestätigen. Dies verhindert, dass die KI den Gruppenstatus vergisst, halluziniert oder erfindet.
- **Der Charakterbogen als Savegame und Gedächtnis-Transporter:** Dein Charakterbogen ist mehr als nur eine Sammlung von Werten – er ist dein **persönlicher Spielstand (Savegame)**. Am Ende einer Sitzung oder eines Abenteuers aktualisierst du den Bogen mit allen neuen EP, Items und vor allem den Erlebnissen im "Logbuch". Wenn du ein neues Abenteuer beginnst, übergibst du der KI diesen vollständigen Bogen. Die KI liest nicht nur deine Werte, sondern deine gesamte Geschichte. Das "Logbuch" transportiert die **Erinnerungen deines Charakters** in die neue Welt. Ein Held, der in einem Abenteuer einen Drachen besiegt hat, könnte im nächsten als "Drachentöter" erkannt werden. Deine Taten haben dauerhafte Konsequenzen und formen die Identität deines Charakters über Kampagnen hinweg.

### Wie man ein Spiel startet

Es ist denkbar einfach, ein neues Abenteuer zu beginnen:

1.  **Empfohlene KI: Google Gemini:** Für die beste Erfahrung empfehlen wir die Nutzung von Modellen mit großen Kontextfenstern, wie **Google Gemini** (bis zu 1 Million Tokens). Ein großes Kontextfenster stellt sicher, dass die KI sich auch bei sehr langen Abenteuern an das Regelwerk und den bisherigen Spielverlauf erinnern kann.
2.  **Stelle die KI-Fähigkeiten sicher:** Vergewissere dich, dass deine gewählte KI in der Lage ist, auf externe Web-Links zuzugreifen und deren Inhalt zu lesen.
3.  **Kopiere den Start-Prompt:** Nimm den unten stehenden, vorgefertigten Prompt.
4.  **Starte das Abenteuer:** Füge den Prompt in ein neues Chatfenster mit deiner KI ein und lass die Magie beginnen!

### Der Start-Prompt für deine KI

Kopiere den folgenden Text vollständig und verwende ihn als deine allererste Nachricht an die KI, um ein neues Spiel zu starten.

```
Hallo! Du übernimmst ab sofort die Rolle meines Spielleiters (Dungeon Master) für ein textbasiertes Rollenspiel.

Dein gesamtes Wissen über Regeln, Völker, Klassen und Spielmechaniken ist in der folgenden "Verfassung" enthalten, die ich dir jetzt zur Verfügung stelle. Dieses Dokument ist deine **einzige und alleinige Quelle der Wahrheit**. Ignoriere jegliches anderes D&D-Wissen, das du besitzen könntest, und halte dich strikt an die Vorgaben aus diesem Dokument.

Lies und verinnerliche jetzt die Verfassung.

---
[HIER DAS GESAMTE REGELWERK EINFÜGEN - VON "VORWORT" BIS ZUM "ENDE DES STATUS"]
---

Du hast nun das vollständige Regelwerk erhalten.

Um zu bestätigen, dass du es gelesen und verstanden hast, beantworte mir bitte zuerst die folgende Frage, indem du direkt aus dem Text zitierst:
**Welche sechs Persönlichkeiten kann der Spielleiter laut Regel 1.2 annehmen?**

Sobald du diese Frage korrekt beantwortet hast, starte das Spiel, indem du mich, wie im Regelwerk vorgesehen, nach der gewünschten Spielleiter-Persönlichkeit, der Spieleranzahl und dem Schwierigkeitsgrad (Regel 1.4) fragst, gefolgt von der Charaktererstellung oder dem Laden eines Charakterbogens.
Du achtest darauf, die Formatierung und das Design für den Charakterbogen und das Status-Update genauso wie hier beschrieben wieder zu geben und regelmäßig anzuzeigen. Das beeinhaltet auch alle Emojis.
Du gibts den Spieler auch Vorschläge. Sollte der Vorschlag eine Fähigkeiten/Zauber oder ähnliches beinhalten so steht dies in []. Bsp. [Wahrnehmung]
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
