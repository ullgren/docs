---
title: Debugging app
linktitle: Debugging
description: Når man kjører applikasjonene lokalt kan man ved hjelp av forskjellige verktøy debugge.
weight: 100
---

Følgende beskrivelse forutsetter at du har clonet applikasjonen fra Altinn Studio Repositories og har filene liggende på lokal harddisk. 

## Debugging i Visual Studio Code

For å debugge applikasjonen lokalt må du åpne applikasjonsprosjektet i Visual Studio Code.
Velg åpne folder og bla deg frem til hvor repostoriet er lagret på din maskin.

Velg debugging knappen til venstre i vertikal meny. 

![debug](debug1a.png "Starte debugging")

Det er to måter å starte debugging av en applikasjon lokalt.

### Starte applikasjon fra Visual Studio Code (.Net Core Laucn)
Denne metoden er den enkleste. Her vil Visual Studio Code starte applikasjonen og koble seg til i en og samme prosess

Vegt .Net Core Launc og trykk på den grønne "play" knappen.

Applikasjonen vil da starte og han vil spørre om du skal starte en browser. Velg bare close.

![debug](debug1aa.png "Debugging startet")

Åpne et browservindu og gå til Altinn3local.no (forutsetter at du har startet lokal utviklingsplattform)


### Starte applikasjonen fra commando vindu.

Dette forutsetter at du har startet applikasjonen allerde. 
Gå til folderen hvor applikasjonen ligger og kjør kommando for å starte dotnet prosessen

![debug](debug1.png "Starte .Net applikasjon")


I Visual Studio Code ha åpnet folderen med applikasjonsprosjektet. Attach deg til prosessen som heter Altinn.App.exe


![debug](debug2.png "Koble til applikasjonsprosess")


### Legg til Breakpoints og analysere kode

Sett breakpoints i code der du vil at debugger skal stoppe 

![debug](debug3.png "Legge til breakpoint")


Der debugger stopper kan du analysere lokale verdier på objekter for å finne ut hvordan kode fungerer og eventuelt finne feil.

![debug](debug4.png "Se på lokale verdier")





[Les mer om debugging i Visual Studio Code i dokumentasjonen til verktøyet](https://code.visualstudio.com/docs/editor/debugging)