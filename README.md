# Starter guide til Linux

## Overview
- [Introduktion](#Introduktion)
- [Hvorfor Linux?](#hvorfor-linux)
- [Installation](#installation)
- [Terminalen](#terminalen)
- [Filsystemet](#filsystemet)
- [Ressourcer](#nyttige-ressourcer)
- [Package managers](#package-managers)

## Introduktion

Linux er et open source-operativsystem, der er kendt for sin stabilitet, sikkerhed og fleksibilitet. Operativsystemet anvendes af mange programmørere og systemadministratorer på grund af dets evne til at tilpasses og modificeres til forskellige formål.

## Hvorfor Linux?

**Open source:** Linux er et open-source operativsystem, hvilket betyder, at dets kildekode er tilgængelig for alle og kan tilpasses og distribueres frit. Det giver programmører og datateknikkere mulighed for at tilpasse og optimere deres systemer til deres specifikke behov.

**Stabilitet og sikkerhed:** Linux er kendt for sin stabilitet og sikkerhed, da det er mindre sårbart over for malware og hacking end Windows og macOS. Dette skyldes bl.a. den strenge adgangskontrol og adskillelse af brugerrettigheder, som er indbygget i Linux.

**Scaleable:** Linux kan køre på alt fra små enheder til store servere og supercomputere. Dette gør det ideelt til både små og store projekter, og det kan nemt skaleres op eller ned efter behov.

**Frihed til at vælge:** Med Linux har man frihed til at vælge og [tilpasse](https://www.reddit.com/r/unixporn/) sin software, herunder operativsystemet, [desktop environment](https://wiki.gentoo.org/wiki/Desktop_environment), programmer og værktøjer. Det giver programmører og datateknikkere mulighed for at arbejde med de værktøjer, de foretrækker og tilpasse deres arbejdsgange efter deres behov.

**Fællesskab og support:** Linux har et stort og aktivt [fællesskab](https://www.reddit.com/r/linux/) af udviklere og brugere, som tilbyder gratis support, hjælp og vejledning. Det kan være meget nyttigt for programmører og datateknikkere, der støder på tekniske udfordringer eller har brug for hjælp til at vælge de bedste værktøjer til deres arbejde.

## Installation

For at installere Linux, skal du først downloade en Linux-distribution. Nogle af de mest populære [distributioner](https://distrowatch.com/) inkluderer `Ubuntu`, `Debian`, `Fedora`, `Arch`, `Gentoo` og `CentOS`.

---

Når du har downloadet ISO filen, kan du "flashe" den på en USB. Det kan du gøre via [Rufus](https://rufus.ie/en/), eller [Balena Etcher](https://www.balena.io/etcher). Det kan være nødvendigt at slå [fast startup](https://help.uaudio.com/hc/en-us/articles/213195423-How-To-Disable-Fast-Startup-in-Windows-10) fra.

Når du har bootet fra USB, vil du blive typisk blive guidet igennem installationsprocessen. Det er MEGET vigtigt at vælge de rigtige partitions til installation af Linux, så sørg for at backupe din data, før du fortsætter.

> Backup, backup, backup!

## Grundlæggende Linux-funktioner

### Terminalen

Terminalen er en af de vigtigste funktioner i Linux, og den bruges til at kommunikere med operativsystemet via kommandoer. Du kan typisk [åbne terminalen](https://www.makeuseof.com/how-to-open-terminal-in-linux/) ved at trykke på `Ctrl + Alt + T` eller ved at søge efter den i startmenuen.
Typisk vil din terminal bruge `bash` som din [shell](https://www.gnu.org/software/bash/manual/html_node/What-is-a-shell_003f.html). Bash er mest udbredt og ses som "standarden". Der findes andre shells, som `fish` og`zsh`.


> With great power comes great responsibility.


### Filsystemet

Linux har et hierarkisk [filsystem](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/4/html/reference_guide/s1-filesystem-fhs), hvor alle filer og mapper er placeret under en root-mappe, som typisk er `/`. Andre vigtige mapper inkluderer `/home`, som indeholder brugerdata, og `/var`, som indeholder systemlogfiler.

### Package managers

[pakkehåndtering](https://itsfoss.com/package-manager/) er en vigtig funktion i Linux, der gør det muligt, nemt og for det meste sikkert  at installere og administrere software på din computer. Nogle af de mest populære package managers inkluderer `apt`, `yum`, `pacman`, `portage` og `dnf`.

## Nyttige ressourcer

- [Linux Journey](https://linuxjourney.com/) - En interaktiv tutorial om Linux-operativsystemet og dens komponenter.
- [Linux Survival](https://linuxsurvival.com/linux-tutorial-introduction/) - En omfattende introduktion til Linux og dens vigtigste funktioner og værktøjer.
- [Ubuntu Help](https://help.ubuntu.com/community/UsingTheTerminal) - En guide til at bruge terminalen på Ubuntu-operativsystemet, inklusive grundlæggende kommandoer og tip.
- [Linux Command Library](https://lym.readthedocs.io/en/latest/) - En lærebog i Linux-kommandoer og systemadministration.
- [Ryan's Tutorials](https://ryanstutorials.net/linuxtutorial/) - En praktisk guide til at lære Linux-terminalen fra bunden og opbygge gradvist kompleksitet.

