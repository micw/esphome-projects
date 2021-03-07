# Meine ESPHome-Projekte

Ich stelle meine selbstgebauten Arduino-Projekte Stück für Stück auf ESPHome um. Das Ergebnis ist in diesem Respository zu finden.

## Badlicht

In unserem Bad ist ein Einbauschrank mit einem offenen Fach und zwei Fächern mit Glastüren. In allen drei Fächern sind LED-Streifen eingelassen. An den beiden Glastüren sind Reedschalter mit Magneten verbaut. Die Beleuchtung wird von einem ESP8266 und HomeAssistant gesteuert.

- HomeAssistant gibt je nach Tageszeit die Helligkeit für das offene Fach sowie die beiden Schränke vor
- öffnet man einen Schrank, so dimmt dieser auf 100%
- schließt man einen Schrank, so dimmt dieser auf die durch HomeAssistant vorgegebene Helligkeit

Realisiert wurde dies durch eine "virtuelle" Leuchte, welche ein Template-Output verwendet.
