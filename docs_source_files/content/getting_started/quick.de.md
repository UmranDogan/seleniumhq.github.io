---
title: "Kurze Einführung"
weight: 1
---

Selenium ist nicht ein einzelnes Tool oder eine API, es besteht aus mehreren Tools

## WebDriver

Startest Du mit dem automatisieren von Websiten, dann wirst Du die WebDriver APIs verwenden.
_[WebDriver]({{< ref "/webdriver/_index.md" >}})_ verwendet die von den Browsern
Herstellern zur Verfügung gestellten APIs um den Browser zu steuern und Test
auszuführen. Die Ausführung simuliert einen echten Benutzer. Da der WebDriver eigenständig
ist und nicht mit der Applikation kompiliert werden muss, handelt es sich um eine minimal 
invasive Methode. Es kann exakt die Applikation getestet werden die später veröffentlicht wird.  

## IDE

_[IDE](https://selenium.dev/selenium-ide)_ (Integrated Development Environment = Entwicklungsumgebung)
ist ein Werkzeug um Seleniumtests zu erstellen. Es ist eine einfach zu handhabende 
Erweiterung für Chrome und Firefox und in der Regel ist dies die effizienteste Weg
um Testfälle zu erstellen. Benutzerinteraktionen werden aufgezeichnet mit Hilfe von 
bestehenden Selenium Befehlen. Diese werden mit den entsprechenden Parametern versehen.
Das ist nicht nur zeitsparend sondern auch ein guter Weg um sich mit der Seleniumsyntax 
vertraut zu machen.

## Grid

Sehr bald nachdem Du die ersten WebDriver Tests erstellt hast, wirst Du Dir 
wünschen Deine Tests auf unterschiedlichen Browsern und Betriebssystemkombinationen
auszuführen. Das ist der Moment an dem _[Grid]({{< ref "/grid/_index.md" >}})_ ins 
Spiel kommt.
