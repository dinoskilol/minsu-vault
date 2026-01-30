---
title: "Anforderungsanalyse"
description: "Konzise, prüfungsorientierte Darstellung der Anforderungsanalyse für die AP2"
author: "Minsu (Automated study vault)"
publish_ready: true
---

# Anforderungsanalyse

## Einleitung
Die Anforderungsanalyse ist ein grundlegender Schritt im Softwareentwicklungsprozess. Ihr Zweck besteht darin, die Bedürfnisse der Stakeholder systematisch zu erfassen, in umsetzbare Anforderungen zu überführen und als Grundlage für Entwurf, Implementierung und Test bereitzustellen. Für die Abschlussprüfung ist nicht nur die Kenntnis der Begriffe wichtig, sondern auch das Verständnis konkreter Vorgehensweisen, Artefakte und wie Anforderungen verifiziert werden.

## Definitionen
**Anforderung (Requirement):** Aussage über das, was ein System tun soll (funktional) oder wie es sich verhalten soll (nicht-funktional).

**Stakeholder:** Personen oder Institutionen, die Anforderungen an das System stellen oder von dessen Funktionalität betroffen sind.

**Akzeptanzkriterium:** Messbare Bedingung, unter der eine Anforderung als erfüllt gilt.

## Detaillierte Erklärung
Die Anforderungsanalyse umfasst mehrere Schritte:

1. **Stakeholder identifizieren:** Bestimmen, wer Anforderungen stellt (z. B. Kunde, Endnutzer, Betreiber).
2. **Anforderungen erheben:** Methoden sind Interviews, Workshops, Beobachtungen, Fragebögen oder Analyse bestehender Systeme.
3. **Spezifizieren:** Anforderungen in einer verständlichen, überprüfbaren Form dokumentieren (z. B. User Stories, Use Cases, Lasten- und Pflichtenheft).
4. **Priorisieren:** Klassifizierung nach Must/Should/Could/Won't oder numerischer Priorität.
5. **Validieren und Abnehmen:** Sicherstellen, dass Anforderungen korrekt, vollständig und testbar sind; Definition von Akzeptanzkriterien.
6. **Rückverfolgbarkeit (Traceability):** Verknüpfung von Anforderungen zu Entwurfsdokumenten und Testfällen, um Änderungen nachzuverfolgen.

Praktisch bedeutet das: Aus einer Anforderung wie "Der Benutzer kann sich mit E-Mail und Passwort anmelden" werden Testfälle (z. B. "erfolgreiches Login", "falsches Passwort") sowie Entwurfsartefakte wie ein Sequenzdiagramm abgeleitet. Die Spezifikation sollte so formuliert sein, dass ein Entwickler ohne Rückfragen implementieren kann.

## Beispiele und Muster
**User Story (Beispiel):** Als registrierter Benutzer möchte ich mich mit E-Mail und Passwort anmelden, damit ich Zugang zu meinem Profil habe.

**Akzeptanzkriterien (Beispiel):**
- Der Benutzer wird nach fehlerhaften Login-Versuchen nach 5 Fehlversuchen gesperrt.
- Die Passwortlänge muss mindestens 8 Zeichen betragen.

**Artefakte:** Lastenheft, Pflichtenheft, User Stories, Use-Case-Diagramme, Mockups/Prototypen.

## Prüfungsübungen (Beispiele)
1. Schreiben Sie drei User Stories für einen einfachen Login- und Registrierungs-Workflow und definieren Sie pro Story zwei Akzeptanzkriterien.
2. Erklären Sie, wie Traceability zwischen Anforderung, Entwurf (UML) und Testfällen realisiert werden kann (Kurzantwort, 4–6 Sätze).

## Weiterführende Literatur und Quellen (gesammelt)
Siehe `../Research/Anforderungsanalyse-Sources.md` für PDF-Links, Tutorials und IHK-Materialien.

## Verwandte Themen
- [[Softwareentwicklungslebenszyklus]]
- [[Datenbanken-SQL]]
- [[Testing-Debugging]]


---

_Note: Diese Notiz wurde erweitert und mit Quellen verlinkt. Nächster Schritt: vollständige Quellen in Research/Anforderungsanalyse-Sources.md und ggf. ein kurzes Mockup in Diagrams/._
