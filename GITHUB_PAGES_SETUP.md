# GitHub Pages Setup Guide

## Steg 1: Aktiver GitHub Pages

1. Gå til GitHub-repoet: `https://github.com/eon-as/html-presentation`
2. Klikk på **Settings** (innstillinger)
3. Scroll ned til **Pages** i venstre meny
4. Under **Source**, velg:
   - Branch: `main`
   - Folder: `/ (root)`
5. Klikk **Save**

## Steg 2: Vent på deploy

- GitHub Pages tar vanligvis 1-2 minutter å deploye
- Du får en URL som: `https://eon-as.github.io/html-presentation/`

## Steg 3: Test på iPhone

1. Åpne URL-en i Safari på iPhone
2. Presentasjonen skal nå fungere perfekt (ingen preview-problemer!)

## Oppdatering

Hver gang du pusher endringer til `main`-branchen, oppdateres GitHub Pages automatisk.

## Custom Domain (valgfritt)

Hvis du vil bruke eget domene (f.eks. `presentasjon.eon-as.no`):
1. Legg til en `CNAME`-fil i root med domenet
2. Oppdater DNS-innstillinger hos din domeneleverandør

