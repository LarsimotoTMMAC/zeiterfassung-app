# Zeiterfassung (statische Webapp)

Single-File-Webapp für Zeiterfassung, Reiseplan und Monatsabrechnung.
Wird über GitHub Pages ausgeliefert.

Die App enthält keine Daten: Der komplette Datenstand wird zur Laufzeit per
GitHub Contents API aus einem privaten Repo geladen (Zugriff per fine-grained
Personal Access Token) und bei Änderungen dorthin zurückgeschrieben.
