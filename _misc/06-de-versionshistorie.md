---
layout: article
title: Versionshistorie
menu_title: Versionshistorie
description: Versionshistorie
lang: de
ref: misc-06
---

## 1.0.20.9 (30.04.2018)

* Scroll- und Zoom Eigenschaft wurde dem Weiview Control zugefügt
* Lua Runtime Eigenschaft Screen Scale wurde hinzugefügt
* Fix für S7 benutzerdefinierte Variablen

## 1.0.20.6 (24.04.2018)

* Das manuelle Update wurde umgebaut und erlaubt nun auch das Updaten mehrerer Boxen
* Timer Skripte können nun deaktiviert werden
* Fix für die Formatierung einer einzeiligen Tabelle

## 1.0.19.7 (17.04.2018)

* OPC UA Datenquelle ermöglicht den Zugriff auf Event Methoden
* Peakbord IO Portal Benutzer kann nun mit Peakboard-Boxen gekoppelt werden
* Skript Performance Updates
* Siemens S7:
  * Verbindungsstabilität verbessert
  * Alle primitiven Datentypen aller PLCs werden nun unterstützt
  * Data Validator wurde dem Designer hinzugefügt
  * Variablen können nun in Gruppen verwaltet werden (Strukturen)
* Timer Skripte sind nun global
* Controls können animiert werden
* Screen Animation hinzugefügt
* Paketverschlüsselung wurde optimiert
* Peakboard Bridge läuft nun auf .NET Version 4.6 anstelle von 4.5
* Fix für das Hinzufügen neuer Controls über existierende
* Fix für Programmabsturz bei Web Controls wenn C++ Bibliotheken nicht installiert sind
* Fix dass ein neues Paket nicht mehr modified startet
* Fix für Toggle Switch Control, dass dieses nicht initial ein Event triggert
* Fix für das Validieren neu angelegter Skripte
* Fix für Ressourcen die in den Screens angezeigt werden
* Fix für das Aufrufen von LUA Funktionen wenn diese klein geschrieben sind
* Fix für das hinzufügen eines Screens ohne Titel
* Fix für SAP Datenquelle, die einen Thread Fehler anzeigte


## 1.0.18.0 (06.03.2018)

* Screen Titel ist nun verpflichtend
* Erweiterungen bei der OPC UA Datenquelle
* Neue Icons
* Fix für das Logging der Bridge
* Fix für das Logging der Runtime
* Fix für Box Properties
* Fix für die Mail Datenquelle
* Fix für die Script Validierung

## 1.0.17.0 (16.02.2018)

* Fix beim Öffnen einer pbmx Datei, für den Zugriff auf Templates und globale Scripte
* Fix für den Select File Dialog

## 1.0.16.0 (13.02.2018)

* Excel Datenquelle unterstützt nun .xlsm Dateien
* Das Fehlerhandling von Webtabellen und Webviews wurde optimiert
* Fix für das Kopieren von Controls mit nicht existenten Schriftarten
* Fixes für Peakboard IO Tabellen

## 1.0.15.0 (09.02.2018)

* Verbesserungen für die Peakboard-Bridge
* Verbesserungen für die OPC UA Datenquelle
* Ribon Bar Icons wurden ersetzt

## 1.0.14.4 (02.02.2018)

* Verbesserungen für die Peakboard-Bridge

## 1.0.13.4 (30.01.2018)

* Fix für Twitter/ Instagram mit Bilder

## 1.0.13.0 (30.01.2018)

* OPC UA unterstützt nun Methodenaufrufe
* Peakboard-Bridge Stabilität Optimierungen

## 1.0.12.9 (22.01.2018)

* Interne Änderungen ohne Auswirkungen

## 1.0.12.0 (19.01.2018)

* Peakboard IO Pages veröffentlicht
* OPC UA unterstützt Zertifikate
* OPC UA Erweiterungen
* Top und Left Einstellungen im Property Panel
* Screen-Reihenfolge änderbar
* S7 unterstützt nun String-Variablen
* Textticker Fixes und Erweiterungen

## 1.0.11.6 (16.01.2018)

* OPC UA Datenquelle wurde erweitert

## 1.0.10.0 (12.01.2018)

* Erste Version des Peakboard IO Portals veröffentlicht
* IMAP Mail Datenquelle wurde hinzugefügt
* Control Icons wurden überarbeitet
* CSV Datenquelle kann nun Daten über die Bridge beziehen
* CSV Datenquelle kann nun definierbare Trennzeichen verwenden
* Neue Textformatierung für Prozentangaben
* Bridge Stabilität verbessert
* Fixes für Lua Json Parsing
* Fix für Table Grid Spalten mit Sonderzeichen
* Fix für SAP Query Abfragen ohne Rückgabewerte
* Fixes für S7 Datenquelle

1.0.9.0 (22.12.2017)

* Neues Control: Live Tiles
* Erste Preview Version für die OPC UA Datenquelle
* XML Daten können nun aus dem Netzwerk bezogen werden
* Über Strg + L kann in der Runtime das aktuelle Log angezeigt werden
* Fixes für Map Control, Image Control, Websnippet Control, Animierte Gifs

## 1.0.8.17 (15.12.2017)

* Fix für das Ändern von Schriftarten über einen Lua-Skript

## 1.0.8.7 (27.11.2017)
* Fix für lokale PDF Dateien

## 1.0.8.4 (23.11.2017)

* Globales Event Key Down wurde hinzugefügt
* Globales Event Key Input wurde hinzugefügt
* Fix Änderungen in Ressourcen während der Laufzeit

## 1.0.8.0 (23.11.2017)

* Excel Chart Control
* Web Resourcen wurden hinzugefügt
* Bridge Ressourcen wurden hinzugefügt
* Performance Verbesserungen für Lua Skripte
* SAP Message-Server werden nun unterstützt
* Lua Snippets wurden um Waiting Screen erweitert
* SAP über Bridge wird nicht mehr unterstützt

## 1.0.7.3 (08.11.2017)

* Zwei neue Templates wurden hinzugefügt
* Fix für tablejoin Lua Funktionen
* Fix für math.tonumber() und string.tostring() Lua Funktionen

## 1.0.7.0 (06.11.2017)

* Grundsätzliche Änderungen für die Lizenzierung
* Fenster werden abhängig von der Bildschirmgröße geöffnet
* Tabellen Performance Verbesserungen
* Tabellenspalten-Änderungen lassen sich nun zurücksetzen
* Fix für das Ändern des Passworts einer Box vom Designer

## 1.0.6.5 (26.10.2017)

* Settings- und Variablendialoge wurden überarbeitet
* Fixes für Gauges bei gleichem Maximal, Minimal und aktuellem Wert
* Fixes für Intellisense

## 1.0.6.3 (19.10.2017)

* Insert Kategorie wurde im Menüband hinzugefügt
* Peakboard Bridge Datenqullen lassen sich über Lua reloaden
* Einfügeassistent für Bilder
* Syntaxeditor wurde überarbeitet
* Neue Codesnippets wurden hinzugefügt
* Fix für Max, Min und Sum Function

## 1.0.5.0 (06.10.2017)

* Es können Pop-Up Benachrichtigungen angezeigt werden
* Überarbeitung der Fehleranzeige im Preview
* Neue Templates wurden hinzugefügt
* Lua Objekte und Funktionen lassen sich nun in Kleinschrift aufrufen
* Skriptvorschläge sind nun alle kleingeschrieben
* Änderungen von IP Adressen von Peakboard Boxen werden automatisch aktualisiert
* Fix für Excel mit sprachenabhängigen Kommazahlen
* Fixes für Script Validierung und Script Editor

## 1.0.4.0 (29.09.2017)

* Der Template Dialog wurde in Kategorien unterteilt
* Abfragen in Excel Datenquellen bieten nun die Möglichkeit Bereiche zu definieren
* Excel Dateien können nun als Ressource angelegt werden
* Ein Wartebalken kann nun über Lua eingeblendet werden
* Die Schriftart im Skripteditor wurde geändert
* Doppelklick auf einen Button öffnet nun den Skripteditor
* Datenänderungen die Änderungen in Controls nach sich ziehen kann nun deaktiviert werden
* Weitere Templates wurden hinzugefügt
* Dropbox API V.1 Verwendung durch V.2 ersetzt
* Fix für Globale Lua Funktionen
* Fix für den Validator in Globalen Lua Skripten

## 1.0.3.1 (22.09.2017)

* Script Editor Dialog wurde überarbeitet
* Versionshistorie wurde im Aboutdialog verlinkt

## 1.0.3.0 (22.09.2017)

* Der Lua Script Editor wurde überarbeitet
* Spracheingabe wurde hinzugefügt (beta)
* Bridge Datenquelle Fehlerhandling wurde optimiert
* Bridge Datenquelle erlaubt nun dynamische Aufrufe
* Einige Dialoge von Datenquellen wurden überarbeitet
* Scripte in Ressourcen-Dateien können nun direkt vom Scripteditor aufgerufen werden
* Fix für Feed Datenquelle
* Fixes für Excel Datenquelle
* Fix für Bindings von Listen

## 1.0.2.1 (14.09.2017)

* Fix für Webpage Table Datenquelle ohne Authentifizierung

## 1.0.2.0 (05.09.2017)

* Peakboard kann nun Sprachbefehle über ein Mikrofon aufnehmen
* Peakboard kann nun Daten an eine S7 Steuerung senden
* Neue Templates wurden hinzugefügt und die vorhandenen Templates überarbeitet
* Werte von Variablen können nun auf der Box langfristig gespeichert werden
* Globale Properties für Boxen wurden hinzugefügt
* Globale Properties für Boards wurden hinzugefügt
* Einige Icons der GUI wurden überarbeitet
* Werte von Gauges können nun ausgeblendet werden
* Unnötige Einstellungen in den Gauges wurden entfernt
* Nummern werden nun unabhängig der Sprache des Betriebssystems dargestellt
* Skripte können nun direkt über die rechte Maustaste auf Resources hinzugefügt werden
* Variablen heißen nun „Variables“ und nicht mehr „General Data“
* Überarbeitung einiger Dialoge
* .NET Core Runtime V1.0 wurde auf V1.1 erhöht

## 1.0.1.2 (21.08.2017)

* Siemens S7 Datenquelle
* Send Mail Funktion für LUA um Emails zu versenden
* Drag and Drop um Datenquellen und Resourcen in Ordner zu verschieben
* Reaktivierung der Screen IsEnabled Property
* Löschen der Expand Collase Ordner Funktionen
* ODBC Datenbanken lassen sich nun mit Hilfe der Peakboard Bridge anbinden
* Fix für das Löschen leerer Ordner
* Fix für SQLSever mit leeren Spaltennamen
* Fix für erstellen neuer Pakete ohne Admin Rechte

## 1.0.0.486 (31.07.2017)

* Fix für die SQL Datenquelle bei double Werten
* Fix damit ein neues Steuerelement sofort an vorderster Position zu sehen ist
* Fix bei der Erkennung, ob sich in der Visualisierung etwas geändert hat

## 1.0.0.483 (28.07.2017)

* Fixe Tabellenspalten können nur noch mit validen Namen bezeichnet werden
* Fix für Probleme beim Verbindungsabbruch, während dem veröffentlichen eines Peakboards

## 1.0.0.482 (25.07.2017)

* Fix für das Selektionsfeld bei fixierten Elementen

## 1.0.0.481 (24.07.2017)

* Im Peakboard Designer können nun Elemente fixiert und damit unveränderbar gemacht werden
* Es können nun statische Tabellen die initial leer sind angelegt werden
* Für das Laden von Bildern aus einer URL kann nun eine Authentifizierung übergeben werden
* PDF Daten können nun von einer URL geladen werden
* Änderungen der Icons im Bereich Control Layout
* Das Selektionsfeld wurde umgestaltet
* Screens können nicht mehr deaktiviert werden

## 1.0.0.475 (21.07.2017)

* Neue Interaktive Steuerelemente (Date Picker, Time Picker)
* Es lässt sich nun ein Pop-Up-Dialog über Lua Script aufrufen
* Nach einem Http Push feuert die Datenquelle nun ein Refreshed-Event
* Über Lua kann nun mit RemoveAt ein Element an einem definierten Index entfernt werden
* Fix bei den Größen und Positionen beim Anzeigen von Fenstern im Peakboard Designer
* Änderungen der Icons einiger Steuerelemente

## 1.0.0.469 (18.07.2017)

* Neue Interaktive Steuerelemente (Flat Button, Repeat Button, Toggle Button, Toggle Switch, Check Box, Radio Button, Combo Box, Slider)
* Es lässt sich nun eine Basic Authentifizierung direkt im Lua Script generieren
* Fix für Zeit-Datenquelle mit internen NTP Servern
* Fix für die Authentifizierung bei der CSV und JSon Datenquelle
