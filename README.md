# waermeatlas
<br><b>DATENBASIS</b>
<br>
<table>
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
    <th width=20%>Thema/Information</th>
    <th width=50%>Basis</th>
    <th width=30%>Verbesserungspotenzial</th>
  </tr>    
  </thead>
  <tr>
    <th><b>Energetische Gebäudetypisierung</b>: Ein- und Zweifamilienhaus (EFH), Reihenhaus (RH), Mehrfamilienhaus (MFH), Großes Mehrfamilienhaus (GMH), Büro-, Verwaltungs- oder Amtsgebäude, Gebäude für Forschung und Hochschullehre, Gebäude für Gesundheit und Pflege
Schule, Kindertagesstätte und sonstige Betreuungsgebäude
154.230 266.561.645
Gebäude für Kultur und Freizeit 141.211 118.654.322
Sportgebäude 78.118 107.346.028
Beherbergungs- oder Unterbringungsgebäude, Gastronomie- oder Verpflegungsgebäude
270.403 213.360.502
Produktions-, Werkstatt-, Lager- oder Betriebsgebäude
(Im Modell aufgeteilt in GHD & Industrie)
974.448 1.354.234.922
Handelsgebäude 187.277 407.028.666
Technikgebäude (Ver- und Entsorgung) 67.860 25.297.594
Verkehrsgebäude </th>
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
