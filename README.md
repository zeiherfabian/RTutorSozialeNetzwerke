Dieses Paket beinhaltet ein interaktives R Problemset, welches auf dem Paket RTutor basiert (https://github.com/skranz/RTutor). 

Das Problemset beschäftigt sich mit dem Artikel "Social Networks as Contract Enforcement: Evidence from a Lab Experiment in the Field" von Arun G. Chandrasekhar, Cynthia Kinnan und Horacio Larreguy. Es wurde untersucht, ob die Netzwerkposition von Vertragspartnern dazu beiträgt, dass Verträge auch unter fehlender staatlicher Kontrolle eingehalten werden. Dazu wurden in einem Experiment ermittelte Daten analysiert. Nachfolgend findest du den Link zum Artikel: https://www.aeaweb.org/articles?id=10.1257/app.20150057

## 1. Installation

RTutor und dieses Paket werden auf Github gehostet. Um alles zu installieren, führe den folgenden Code in deiner R-Konsole aus.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("zeiherfabian/RTutorSozialeNetzwerke")
```

## 2. Anzeigen und Bearbeiten des Problemsets

Um mit dem  Problemset zu starten, erstelle zunächst ein Arbeitsverzeichnis, in dem Dateien wie die Datensätze und deine Lösung gespeichert werden. Passe anschließend den folgenden Code an und führe ihn aus.

```s
library(RTutorSozialeNetzwerke)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorSozialeNetzwerke")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorSozialeNetzwerke",
       auto.save.code=TRUE, clear.user=FALSE)
```
Wenn alles gut funktioniert, sollte sich ein Browserfenster öffnen. Du kannst nun mit der Bearbeitung des Problemsets starten. 
