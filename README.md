# waermeatlas
- Veröffentlichung: https://kwp-st.de/kvwmap/index.php

<table>
  <tr>
    <th>Berlin</th>
    <th>Hamburg</th>
    <th>München</th>
  </tr>
  <tr>
    <td>Miljöh</td>
    <td>Kiez</td>
    <td>Bierdampf</td>
   </tr>
   <tr>
     <td>Buletten</td>
     <td>Frikadellen</td>
     <td>Fleischpflanzerl</td>
   </tr>
</table>

<b> Ausgangsdaten: Bundesamt für Kartographie und Geodäsie:</b> 
- ALKIS-Dachformen
- ALKIS Gebäudefunktion
- ALKIS-Strassenfunktion
- ALKIS-Widmung-Strasse
<b> Ausgangsdaten: Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo)</b> 
- ALKIS®-Datensatz Gebäude [AGS24]
- 3D-Gebäudedaten LoD2 (3D-Modell mit standardisierten Dachformen)
- 3D-Gebäudedaten LoD1 (Klötzchen- bzw. Blockmodell)
- Basis-DLM: Siedlung: Wohnbaufläche, etc. --> Siedlungsblock
- Basis-DLM: Verkehr: Straßenachse, Fahrbahnachse
<b> Statistische Ämter des Bundes und der Länder (Zensus 2022) </b>
- Gebäude mit Wohnraum nach Baujahr in Mikrozensus-Klassen (100m Gitter)
- Gebäude mit Wohnraum nach Gebäudetyp (Größe) (100m Gitter)
- Gebäude mit Wohnraum nach Energieträger der Heizung (100m Gitter)
- Gebäude mit Wohnraum nach überwiegender Heizungsart (100m Gitter)
<b> Ministerium für Infrastruktur und Digitales Sachsen-Anhalt (MID) </b> 
- Bebauungsplan, genehmigt/rechtskräftig
- Flächennutzungsplan genehmigt/rechtskräftig
<b> Landesenergieagentur Sachsen-Anhalt GmbH </b>
- Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD)
- Referenzwerte spezifischer Nutzenergiebedarf
- xx: mapping_gebaeude_strassenabschnitt
  
Methodik:
- Energetische Gebäudetypisierung
- Baualtersklasse
- Energiebezugsfläche
- Einstufung von Gebäuden als GEG-relevant
- Wärmebedarf Gebäude
- Wärmebedarf Baublock
- Wärmebedarf Straßenabschnitt
