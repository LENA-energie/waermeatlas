# Modellentwicklung nach dem Energiekennzahlenverfahren
<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
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

<table width='100%'>
  <caption>Geodatengrundlage für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr border-bottom: 1px solid #ddd; background-color: #4CAF50;>
    <th width=20%;>Herausgeber</th>
    <th width=60%;>Thema/Information</th>
    <th width=20%;>Hinweise auf</th>
  </tr>    
  </thead>
  <tbody>
  <tr border-bottom: 1px solid #ddd;>
    <td>Landesenergieagentur Sachsen-Anhalt GmbH</td>
    <td>
      <li>Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD)</li>
    </td>
     <td>-</td>
  </tr>
  <tr border-bottom: 1px solid #ddd;>
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

<h4>Quellenangaben</h4>
<li>Langreder, Nora; Lettow, Frederik; Sahnoun, Malek; Kreidelmeyer, Sven; Wünsch, Aurel; Lengning, Saskia et al. (2024): Technikkatalog Wärmeplanung. Hg. v. ifeu – Institut für Energie- und Umweltforschung Heidelberg, Öko-Institut e.V., IER Stuttgart, adelphi consult GmbH, Becker Büttner Held PartGmbB, Prognos AG, et al. Online verfügbar unter https://www.kww-halle.de/praxis-kommunale-waermewende/bundesgesetz-zur-waermeplanung#c636, zuletzt geprüft am 02.05.2025.</li>
<li>Hörner, Michael; Bischof, Julian. Typologie der Nichtwohngebäude in Deutschland. Institut Wohnen und Umwelt (IWU). Darmstadt, 2022. DOI: 10.13140/RG.2.2.31628.80008, URL: https://github.com/IWUGERMANY/Nichtwohngebaeude-Typologie-Deutschland/tree/main</li>
<li>Institut Wohnen und Umwelt GmbH. Deutsche Wohngebäudetypologie Beispielhafte Maßnahmen zur Verbesserung der Energieeffizienz von typischen Wohngebäuden, Darmstadt 2015, online verfügbar: https://www.iwu.de/fileadmin/publikationen/gebaeudebestand/episcope/2015_IWU_LogaEtAl_Deutsche-Wohngeb%C3%A4udetypologie.pdf</li>
<li>VDI 3807 Blatt 2 Verbrauchskennwerte für Gebäude – Verbrauchskennwerte für Heizenergie, Strom und Wasser. Berlin: Beuth Verlag, November 2014</li>

<h4>Verbesserungspotenzial</h4>
<li>OpenStreetMap für Bauweise gebäudescharf</li>
<li>Zensusdaten je Siedlungsblock</li>
<li>Bauland-Datensatz vom LVermGeo mit Bauweise (offen/geschlossen)</li>
<li>ImmobilienScout24</li>
<li>Industrie & Bauland: Bauland-Datensatz vom LVermGeo mit Art der Nutzung</li>
<li>Industrie: BImSchG</li>
<li>Industrie: DEHst</li>
<li>Industrie: Wirtschaftszweig von MaStR-Anlagenbetreiber</li>

<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Baualtersklasse</h2>
<table>
  <caption>Geodatengrundlage für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=20%>Herausgeber</th>
    <th width=60%>Thema/Information</th>
    <th width=20%>Hinweise auf</th>
  </tr>    
  </thead>
  <tbody>
  <tr>
    <td>Ministerium für Infrastruktur und Digitales Sachsen-Anhalt (MID)</td>
    <td>
      <li>Bebauungsplan, genehmigt/rechtskräftig</li>
      <li>Flächennutzungsplan genehmigt/rechtskräftig</li>
    </td>
     <td>Baualtersklasse basierend auf Jahr rechtskräftig/genehmigt</td>
  </tr>
  <tr>
    <td>Statistische Ämter des Bundes und der Länder (Zensus 2022)</td>
    <td>
      <li>Gebäude mit Wohnraum nach Baujahr in Mikrozensus-Klassen (100m Gitter)</li>
    </td>
    <td>Baualtersklasse für Wohngebäude</td>
   </tr>
  </tbody>
</table>

<h4>Verbesserungspotenzial</h4>
<li>Zensusdaten je Siedlungsblock</li>
<li>Bauanträge</li>
<li>ImmobilienScout24</li>

<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Energiebezugsfläche</h2>
<table>
  <caption>Geodatengrundlage für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=20%>Herausgeber</th>
    <th width=60%>Thema/Information</th>
    <th width=20%>Hinweise auf</th>
  </tr>    
  </thead>
  <tr>
    <td>Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo)</td>
    <td>
      <li>ALKIS®-Datensatz Gebäude [AGS24]</li>
      <li>3D-Gebäudedaten LoD2 (3D-Modell mit standardisierten Dachformen)</li>
      <li>3D-Gebäudedaten LoD1 (Klötzchen- bzw. Blockmodell)</li>
    </td>
    <td>Gebäudepolygon, Gebäudegrundfläche, Dachform, Gebäudehöhe</td>
   </tr>
   <tr>
    <td>Bundesamt für Kartographie und Geodäsie</td>
    <td>
      <li>ALKIS Gebäudefunktion</li>
      <li>ALKIS-Dachformen</li>
    </td>
    <td>Bezeichnungen zur Gebäudefunktion und Dachform</td>
  </tr>
  <tr>
    <td>Landesenergieagentur Sachsen-Anhalt GmbH</td>
    <td>
      <li>Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD)</li>
    </td>
     <td>Flächenkorrekturfaktor Grundfläche zu Energiebezugsfläche</td>
   </tr>
</table>

<h4>Quellenangaben</h4>
<li>VDI 3807 Blatt 2 Verbrauchskennwerte für Gebäude – Verbrauchskennwerte für Heizenergie, Strom und Wasser. Berlin: Beuth Verlag, November 2014</li>
<li>Dochev, Ivan. assigning-energetic-types-to-buildings, URL: https://github.com/ivandochev/assigning-energetic-types-to-buildings/blob/master/IWU_VDI_Types_Assigning_asTool_arcgisread_ExtDaten_v3.py</li>

<h4>Verbesserungspotenzial</h4>
<li>Gebäudehöhen (DE), URL: https://code-de.org/de/portfolio/?id=733c8c77-a4fc-40fd-9e6a-e226da63ab01</li>

<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Einstufung von Gebäuden als GEG-relevant</h2>
<table>
  <caption>Geodatengrundlage für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=20%>Herausgeber</th>
    <th width=60%>Thema/Information</th>
    <th width=20%>Hinweise auf</th>
  </tr>    
  </thead>
  <tr>
    <td>Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo)</td>
    <td>
      <li>Basis-DLM: Siedlung: Wohnbaufläche, etc. --> Siedlungsblock</li>
    </td>
    <td>tatsächliche Nutzung der Fläche</td>
   </tr>
    <tr>
    <td>Bundesamt für Kartographie und Geodäsie</td>
    <td>
      <li>divers</li>
    </td>
    <td>Bezeichnungen für Katalogwerte ()</td>
   </tr>
</table>

<h4>Verbesserungspotenzial</h4>
<li>Bauland inkl. Art der Nutzung vom LVermGeo</li>

<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Wärmebedarfsberechnung (gebäudescharf, Siedlungsblock, Straßenabschnitt)</h2>
<li><b>Nutzenergiebedarf Heizung und Warmwasser [kWh/a] (je Bebäude) = </b> Energiezugsfläche [m²] x Spezifischer Heiz-/Warmwasserbedarf [kWh/(m²a)]</li>
<li><b>Nutzenergiebedarf Heizung und Warmwasser [MWh/(ha*a)] (je Siedlungsblock) = </b> Summe(Nutzenergiebedarf(Gebäude)) [MWh/a] / Fläche des Siedlungsblocks [ha]</li>
<li><b>Nutzenergiebedarf Heizung und Warmwasser [MWh/(m*a)] (je Straßenabschnitt) = </b> Summe(Nutzenergiebedarf(Gebäude))[MWh/a] / Länge des Straßenabschnitts [m]</li>
<table>
  <caption>Geodatengrundlage für das Bundesland Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=20%>Herausgeber</th>
    <th width=60%>Thema/Information</th>
    <th width=20%>Hinweise auf</th>
  </tr>    
  </thead>
     <tr>
    <td>Landesenergieagentur Sachsen-Anhalt GmbH</td>
    <td>
      <li>Referenzwerte spezifischer Nutzenergiebedarf</li>
      <li>Geodatenbank energetisch typisierter Einzelgebäude</li>
      <li>Baualtersklasse</li>
      <li>Energiebezugsfläche</li>
    </td>
     <td>-</td>
   </tr>
  <tr>
    <td>Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo)</td>
    <td>
      <li>Basis-DLM: Siedlung: Wohnbaufläche, etc. --> Siedlungsblock</li>
      <li>Basis-DLM: Verkehr: Straßenachse, Fahrbahnachse</li>
    </td>
    <td>Siedlungsblock, Strassenabschnitt</td>
   </tr>
  <tr>
    <td>Bundesamt für Kartographie und Geodäsie</td>
    <td>
      <li>ALKIS-Strassenfunktion</li>
      <li>ALKIS-Widmung-Strasse</li>
    </td>
    <td>Bezeichnungen zu Straßenfunktion und Straßenwidmung</td>
   </tr>
</table>

<h4>Quellenangaben</h4>
<li>Langreder, Nora; Lettow, Frederik; Sahnoun, Malek; Kreidelmeyer, Sven; Wünsch, Aurel; Lengning, Saskia et al. (2024): Technikkatalog Wärmeplanung. Hg. v. ifeu – Institut für Energie- und Umweltforschung Heidelberg, Öko-Institut e.V., IER Stuttgart, adelphi consult GmbH, Becker Büttner Held PartGmbB, Prognos AG, et al. Online verfügbar unter https://www.kww-halle.de/praxis-kommunale-waermewende/bundesgesetz-zur-waermeplanung#c636, zuletzt geprüft am 02.05.2025.</li>
<li>Hörner, Michael; Bischof, Julian. Typologie der Nichtwohngebäude in Deutschland. Institut Wohnen und Umwelt (IWU). Darmstadt, 2022. DOI: 10.13140/RG.2.2.31628.80008, URL: https://github.com/IWUGERMANY/Nichtwohngebaeude-Typologie-Deutschland/tree/main</li>
<li>Institut Wohnen und Umwelt GmbH. Deutsche Wohngebäudetypologie Beispielhafte Maßnahmen zur Verbesserung der Energieeffizienz von typischen Wohngebäuden, Darmstadt 2015, online verfügbar: https://www.iwu.de/fileadmin/publikationen/gebaeudebestand/episcope/2015_IWU_LogaEtAl_Deutsche-Wohngeb%C3%A4udetypologie.pdf</li>

<h4>Verbesserungspotenzial</h4>
<li>Verifizierung der spezifischen Nutzenergiebedarfe, vgl. https://www.ifeu.de/fileadmin/uploads/Publikationen/Energie/ifeu_gef_geomer_Modellbeschreibung_Waermeatlas_Deutschland_3.0_01_2024.pdf</li>

<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Datenvisualisierung</h2>
<li>https://kwp-st.de/kvwmap/index.php</li>
