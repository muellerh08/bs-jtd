---
layout: default
title: Eingaben
nav_order: 4
has_children: true
permalink: /docs/incal
---

# Eingaben zu Rechnungen

04.03.24: Neu angelegt. Ziel sind möglichst einheitliche Eingaben zu Rechnungen.

## Einleitung

26.05.21: Das ist ein Versuch, alle Text-Files mit Eingaben zu Rechnungen zusammenzufassen, um einfach deren Anzahl zu reduzieren. Da in einem *.md File Links möglich sind, sollte auch eine schnelle Erreichbarkeit über das Inhaltsverzeichnis möglich sein. Auch Links zu den jeweils aufgerufenen Funktionen dürften nützlich sein.
Die Aufrufe erfolgen, wie in den einzelnen Abschnitten angegeben, oder als Job z.B.:

- start-job -filepath $env:BSTD\Work\Ps\Sy.ps1 -ArgumentList 'Sy,Rdm,Sys,S1' '-Mp Tq -debS 11'
- Alle Jobs stoppen: ````Get-Job | Stop-Job````
- Job mit Namen 'Job1' stoppen: Stop-Job -Name Job1
- Receive-Job -name Job1 -Keep: Ergebnisse erhalten, die in powershell geschrieben werden.

04.03.24: Nur noch Run.ps1 verwenden, sowohl für ````*.int````, als auch ````*.mac```` Files.
