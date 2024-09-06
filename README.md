[![][ci-badge]][ci.yml]

# gSQL

gematik SQL Database Prototype

Dieses Repository dient der Entwicklung einer kontinuierlich aus [gemspec.gematik.de] gespeisten Datenbank, mit dem Ziel, die gesamte dort abgelegte Wissensbasis in strukturierter und maschinell recherchierbarer Form abzubilden. **Achtung: Keinesfalls für Produktivzwecke einzusetzen!!** Um dies zu verhindern, werden zur Zeit nur Dokumente mit mindestens ein Jahr zurückliegendem Veröffentlichungsdatum aufgenommen.
/// _This repository is used to develop a database that is continuously fed from gemspec.gematik.de, with the aim of mapping the entire knowledge base stored there in a structured and machine-searchable form. **Attention: Under no circumstances should this be used for productive purposes!!** To prevent this, only documents with a publication date of at least one year ago are currently included._

---

## Continous-Integration ([ci.yml])

Das gematik Polarion Converter Tool (pPCT, siehe weiter unten) wird vom Continuous-Integration Script [ci.yml] aufgerufen,  
welches sowohl manuell gestartet wird, als auch automatisch, wenn Änderungen im Eingabeverzeichnis [input] vorgenommen wurde.
/// _The gematik polarion converter tool (gPCT, see below) is called by the continous integration script ci.yml,
which is  either manually started or automatically, whenever changes are made in the input directory._

Als Ergebnis werden die Dateien [gemspec.sql] (plain SQL) und [gemspec.mdb] (MS-Access) generiert, welche unter Beachtung der CC-BY-4.0 Lizenzbestimmungen frei heruntergeladen und benutzt werden können. 
/// _As a result, the files gemspec.sql (plain SQL) and gemspec.mdb (MS-Access) are generated, which can be freely downloaded and used under the CC-BY-4.0 license terms._

---

This work is licensed under the Creative Commons Attribution 4.0 International License.

<!------------------------- links ------------------------->

[ci-badge]: https://github.com/volkerdoerr/gmd/actions/workflows/ci.yml/badge.svg
[ci.yml]: https://github.com/volkerdoerr/gmd/actions/workflows/ci.yml

[gemspec.gematik.de]: https://gemspec.gematik.de
[input]: https://github.com/volkerdoerr/gsql/
[gemspec.sql]: https://github.com/volkerdoerr/gsql/
[gemspec.mdb]: https://github.com/volkerdoerr/gsql/

