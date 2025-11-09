# LLM Roadmap Dateien
Dieses Repository enthält Markdown-Dateien mit speziellen YAML-Headern („Frontmatter“), um relevante Informationen für KI-Systeme (LLMs) bereitzustellen.  

## Ordnerstruktur

- `docs/` – Alle Beispiele und Dokumentationen
- Jede Datei im `docs/`-Ordner startet mit folgendem Frontmatter:
  ```
  ---
jahrgang: "schuljahr"
fach: "fachbezeichnung"
thema: "thema"
title: "titel des dokuments"
tags: "tags"
date: "datum"
description: "kurzbeschreibung des Inhalts"
---
  ```

## Verwendung

LLMs können semantisch und lexikalisch nach Jahrgang, Fach, Thema, Tags und Inhalten suchen, um relevante Dateien zu identifizieren.
