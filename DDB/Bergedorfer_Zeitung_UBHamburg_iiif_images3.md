## Beschreibung: 
Versuch eine Zeitung mit vier Seiten zu gestalten. 


### Beobachtung:
BSB benutzt nicht das Label description, welches sogar durch den Editor angeboten wird


Sparte: Bibliotek

Provider: Staats- und Universitätsbibliothek Hamburg Carl von Ossietzky

Ursprungsformat: METS/Newspaper METS

DDB-Objekt (URL): https://dev-ddb.fiz-karlsruhe.de/ddb-current/item/xml/Z72P4R3XISH4HMGD5H4VJ6HWBPEV3GZA


### Vorgehen:
Die Bilder wurde über den [IIIF Editor](https://digital.bodleian.ox.ac.uk/manifest-editor/#/?_k=w7lpka) kreiert, die Links zu den IIIF-Bildern
wurden einem Zeitungsportalobjekt der UB Hamburg entnommen

DDB-ID: Z72P4R3XISH4HMGD5H4VJ6HWBPEV3GZA
Link zum Testsystem: https://dev-ddb.fiz-karlsruhe.de/ddb-current/item/xml/Z72P4R3XISH4HMGD5H4VJ6HWBPEV3GZA

Header METS:
 ```
 <OAI-PMH xmlns="http://www.openarchives.org/OAI/2.0/" xmlns:mods="http://www.loc.gov/mods/v3" xmlns:dv="http://dfg-viewer.de/" xmlns:mets="http://www.loc.gov/METS/" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xlink="http://www.w3.org/1999/xlink" xsi:schemaLocation="http://www.openarchives.org/OAI/2.0/ http://www.openarchives.org/OAI/2.0/OAI-PMH.xsd">
 <responseDate>2020-02-17T07:23:24Z</responseDate> 
  <request verb="GetRecord" identifier="PPN1012343960_18800101" metadataPrefix="mets">https://digitalisate.sub.uni-hamburg.de/oai-zeitungen.html</request> 
- <GetRecord>
- <record>
- <header>
  <identifier>PPN1012343960_18800101</identifier> 
  <datestamp>2020-02-14T12:57:09Z</datestamp> 
  <setSpec>HamburgensienZeitungen</setSpec> 
  <setSpec>Zeitung</setSpec> 
  </header>
```
Das automatisch kreierte Manifest wurde händisch ergänzt, oriente habe ich mich dabei an folgendem iiif-cookbook Rezept: https://preview.iiif.io/cookbook/0068-newspaper/recipe/0068-newspaper/newspaper_title-collection.json
Sowie an der BSB iiif Collextion
https://api.digitale-sammlungen.de/iiif/presentation/v2/bsb10502296_00225_u001/manifest

