# waermeatlas
<br>
<h1>Modellentwicklung</h1>
<h2>Geodatenbank energetisch typisierter Einzelgebäude</h2>
<li>Ein- und Zweifamilienhaus (EFH)</li>
<li>Reihenhaus (RH)</li>
<li>Mehrfamilienhaus (MFH)</li>
<li>Großes Mehrfamilienhaus (GMH)</li>
<li>Büro-, Verwaltungs- oder Amtsgebäude</li>
<li>Gebäude für Forschung und Hochschullehre</li>
<li>Gebäude für Gesundheit und Pflege</li>
<li>Schule, Kindertagesstätte und sonstige Betreuungsgebäude</li>
<li>Gebäude für Kultur und Freizeit</li>
<li>Sportgebäude</li>
<li>Beherbergungs- oder Unterbringungsgebäude, Gastronomie- oder Verpflegungsgebäude</li>
<li>Produktions-, Werkstatt-, Lager- oder Betriebsgebäude (Im Modell aufgeteilt in GHD & Industrie)</li>
<li>Handelsgebäude</li>
<li>Technikgebäude (Ver- und Entsorgung)</li>
<li>Verkehrsgebäude</li>
<br>

<table>
  <caption>Geodatengrundlage & -aufbereitung für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=20%>Herausgeber</th>
    <th width=50%>Thema/Information</th>
    <th width=30%>Hinweise auf</th>
  </tr>    
  </thead>
  <tbody>
  <tr>
    <td>Landesenergieagentur Sachsen-Anhalt GmbH</td>
    <td>
      <li>Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD)</li>
    </td>
     <td>-</td>
  </tr>
  <tr>
    <td>Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo)</td>
    <td>
      <li>ALKIS®-Datensatz Gebäude [AGS24]</li>
    </td>
    <td>Gebäudefunktion</td>
   </tr>
   <tr>
    <td>Bundesamt für Kartographie und Geodäsie</td>
    <td>
      <li>ALKIS Gebäudefunktion</li>
    </td>
    <td>Bezeichnung zur Gebäudefunktion</td>
   </tr>
  <tr>
    <td>Statistische Ämter des Bundes und der Länder (Zensus 2022)</td>
    <td>
      <li>Gebäude mit Wohnraum nach Gebäudetyp (Größe) (100m Gitter)</li>
    </td>
     <td>Gebäudetyp für Wohngebäude (EFH, RH, MFH, GMH)</td>
   </tr>
  </tbody>
</table>

<h3>Quellenangaben</h3>
<li>Langreder, Nora; Lettow, Frederik; Sahnoun, Malek; Kreidelmeyer, Sven; Wünsch, Aurel; Lengning, Saskia et al. (2024): Technikkatalog Wärmeplanung. Hg. v. ifeu – Institut für Energie- und Umweltforschung Heidelberg, Öko-Institut e.V., IER Stuttgart, adelphi consult GmbH, Becker Büttner Held PartGmbB, Prognos AG, et al. Online verfügbar unter https://www.kww-halle.de/praxis-kommunale-waermewende/bundesgesetz-zur-waermeplanung#c636, zuletzt geprüft am 02.05.2025.</li>
<li>Hörner, Michael; Bischof, Julian. Typologie der Nichtwohngebäude in Deutschland. Institut Wohnen und Umwelt (IWU). Darmstadt, 2022. DOI: 10.13140/RG.2.2.31628.80008, URL: https://github.com/IWUGERMANY/Nichtwohngebaeude-Typologie-Deutschland/tree/main</li>
<li>VDI 3807 Blatt 2 Verbrauchskennwerte für Gebäude – Verbrauchskennwerte für Heizenergie, Strom und Wasser. Berlin: Beuth Verlag, November 2014</li>
<li>Institut Wohnen und Umwelt GmbH. Deutsche Wohngebäudetypologie Beispielhafte Maßnahmen zur Verbesserung der Energieeffizienz von typischen Wohngebäuden, Darmstadt 2015, online verfügbar: https://www.iwu.de/fileadmin/publikationen/gebaeudebestand/episcope/2015_IWU_LogaEtAl_Deutsche-Wohngeb%C3%A4udetypologie.pdf</li>

<h3>Verbesserungspotenzial</h3>
<li>OpenStreetMap für Bauweise gebäudescharf</li>
<li>Zensusdaten je Siedlungsblock</li>
<li>Bauland-Datensatz vom LVermGeo mit Bauweise (offen/geschlossen)</li>
<li>ImmobilienScout24</li>



<h2>Baualtersklasse</h2>
<h2>Energiebezugsfläche</h2>
<h2>Einstufung von Gebäuden als GEG-relevant</h2>
<h2>Wärmebedarfsberechnung</h2>



<br>
<table>
  <caption>Geodatengrundlage & -aufbereitung für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=20%>Herausgeber</th>
    <th width=50%>Thema/Information</th>
    <th width=30%>Hinweise auf</th>
  </tr>    
  </thead>
  <tr>
    <td>Bundesamt für Kartographie und Geodäsie</td>
    <td>
      <li>ALKIS-Dachformen</li>
      <li>ALKIS Gebäudefunktion</li>
      <li>ALKIS-Strassenfunktion</li>
      <li>ALKIS-Widmung-Strasse</li>
    </td>
    <td>Katalogwerte</td>
   </tr>
  <tr>
    <td>Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo)</td>
    <td>
      <li>ALKIS®-Datensatz Gebäude [AGS24]</li>
      <li>3D-Gebäudedaten LoD2 (3D-Modell mit standardisierten Dachformen)</li>
      <li>3D-Gebäudedaten LoD1 (Klötzchen- bzw. Blockmodell)</li>
      <li>Basis-DLM: Siedlung: Wohnbaufläche, etc. --> Siedlungsblock</li>
      <li>Basis-DLM: Verkehr: Straßenachse, Fahrbahnachse</li>
    </td>
    <td>Gebäudepolygon, Gebäudegrundfläche, Gebäudefunktion, Dachform, Gebäudehöhe, tatsächliche Nutzung der Fläche</td>
   </tr>
   <tr>
    <td>Statistische Ämter des Bundes und der Länder (Zensus 2022)</td>
    <td>
      <li>Gebäude mit Wohnraum nach Baujahr in Mikrozensus-Klassen (100m Gitter)</li>
      <li>Gebäude mit Wohnraum nach Gebäudetyp (Größe) (100m Gitter)</li>
      <li>Gebäude mit Wohnraum nach Energieträger der Heizung (100m Gitter)</li>
      <li>Gebäude mit Wohnraum nach überwiegender Heizungsart (100m Gitter)</li>
    </td>
     <td>Wohngebäude, Gebäudetyp, Baualtersklasse</td>
   </tr>
   <tr>
    <td>Ministerium für Infrastruktur und Digitales Sachsen-Anhalt (MID)</td>
    <td>
      <li>Bebauungsplan, genehmigt/rechtskräftig</li>
      <li>Flächennutzungsplan genehmigt/rechtskräftig</li>
    </td>
     <td>Baualtersklasse basierend auf Jahr rechtskräftig/genehmigt</td>
   </tr>
   <tr>
    <td>Landesenergieagentur Sachsen-Anhalt GmbH</td>
    <td>
      <li>Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD)</li>
      <li>Referenzwerte spezifischer Nutzenergiebedarf</li>
    </td>
     <td>-</td>
   </tr>
</table>






































<br>
<br><b>MODELLENTWICKLUNG</b>
<br>
<table>
  <thead>
  <tr>
    <th width=20% align=left>Thema/Information</th>
    <th width=50% align=left>Basis</th>
    <th width=30% align=left>Verbesserungspotenzial</th>
  </tr>    
  </thead>
  <tr>
    <th><b>Energetische Gebäudetypisierung</b>: 
      <li>Ein- und Zweifamilienhaus (EFH)</li>
      <li>Reihenhaus (RH)</li>
      <li>Mehrfamilienhaus (MFH)</li>
      <li>Großes Mehrfamilienhaus (GMH)</li>
      <li>Büro-, Verwaltungs- oder Amtsgebäude</li>
      <li>Gebäude für Forschung und Hochschullehre</li>
      <li>Gebäude für Gesundheit und Pflege</li>
      <li>Schule, Kindertagesstätte und sonstige Betreuungsgebäude</li>
      <li>Gebäude für Kultur und Freizeit</li>
      <li>Sportgebäude</li>
      <li>Beherbergungs- oder Unterbringungsgebäude, Gastronomie- oder Verpflegungsgebäude</li>
      <li>Produktions-, Werkstatt-, Lager- oder Betriebsgebäude (Im Modell aufgeteilt in GHD & Industrie)</li>
      <li>Handelsgebäude</li>
      <li>Technikgebäude (Ver- und Entsorgung)</li>
      <li>Verkehrsgebäude</li>
    </th>
    <th>ALKIS-Gebäudefunktion, Gebäude mit Wohnraum nach Gebäudetyp (Größe) (100m Gitter)</th>
    <th>OpenStreetMap für Bauweise; Zensusdaten je Siedlungsblock; Bauland-Datensatz vom LVermGeo mit Bauweise (offen/geschlossen), Geschosszahl</th>
  </tr>  
  <tr>
    <th>Baualtersklasse</th>
    <th>Bebauungsplan, genehmigt/rechtskräftig; Flächennutzungsplan genehmigt/rechtskräftig; Gebäude mit Wohnraum nach Baujahr in Mikrozensus-Klassen (100m Gitter)</th>
    <th>Zensusdaten je Siedlungsblock, Bauantrag, ImmobilienScout24</th>
  </tr>  
  <tr>
    <th>Energiebezugsfläche</th>
    <th>Gebäudepolygon, Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD) mit Flächenkorrektur von VDI 3807 Blatt 2 und Annahmen zu Geschosshöhe und Dachgeschossausbau; 3D-Gebäudedaten mit Gebäudehöhe (teils Imputation)</th>
    <th>x</th>
  </tr>  
  <tr>
    <th>Einstufung von Gebäuden als GEG-relevant</th>
    <th>Basis-DLM: Siedlung: Wohnbaufläche, etc.</th>
    <th>Bauland-Datensatz vom LVermGeo mit Art der Nutzung; BImSchG; DEHst; Wirtschaftszweig von MaStR-Anlagenbetreiber</th>
  </tr>  
  <tr>
    <th>Wärmebedarf Gebäude</th>
    <th>Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD); Referenzwerte spezifischer Nutzenergiebedarf; Energiebezugsfläche</th>
    <th>Verifizierung der spezifischen Nutzenergiebedarfe, vgl. https://www.ifeu.de/fileadmin/uploads/Publikationen/Energie/ifeu_gef_geomer_Modellbeschreibung_Waermeatlas_Deutschland_3.0_01_2024.pdf</th>
  </tr>  
  <tr>
    <th>Wärmebedarf Baublock</th>
    <th>x</th>
    <th>x</th>
  </tr>  
  <tr>
    <th>Wärmebedarf Straßenabschnitt</th>
    <th>mapping_gebaeude_strassenabschnitt</th>
    <th>x</th>
  </tr> 
</table>
<br>
<br><b>DATENVISUALISIERUNG</b> 
<br>https://kwp-st.de/kvwmap/index.php
