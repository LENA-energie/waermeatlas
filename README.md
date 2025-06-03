# Modellentwicklung nach dem Energiekennzahlenverfahren
<!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Beschreibung</h2>
<table width='100%'>
  <caption>Übersicht Datenpunkte Wärmeatlas Sachsen-Anhalt</caption>
  <thead>
  <tr>
    <th width=30%>Parameter</th>
    <th width=10%>Spaltentitel</th>
    <th width=60%>Beschreibung</th>
  </tr>    
  </thead>
  <tbody>
  <tr>
    <td>Gebäude-ID</td>
    <td>gid</td>
    <td>Eindeutiger Gebäudeschlüssel</td>
  </tr>
  <tr>
    <td>Gebäude-ID</td>
    <td>gml_id</td>
    <td>ALKIS ID des Gebäudes</td>
  </tr>
  <tr>
    <td>Nutzenergiebedarf Energiekennzahlenverfahren [kWh/a]</td>
    <td>waerme_kwh</td>
    <td>Geschätzter Nutzenergiebedarf zur Versorgung des Gebäudes.</td>
  </tr>
  <tr>
    <td>Endenergiesektor</td>
    <td>sektor</td>
    <td>z.B. WG, NWG, gemischt, kein_bedarf</td>
  </tr>
  <tr>
    <td>Energetischer Gebäudetyp GEMOD (Code)</td>
    <td>g_gemod</td>
    <td>Energetischer Gebäudetyp nach der Typologie des ifeu-Gebäudemodells GEMOD (basierend auf IWU-Gebäudetypologien Wohn- und Nichtwohngebäude).</td>
  </tr>
  <tr>
    <td>Energetischer Gebäudetyp GEMOD (Text)</td>
    <td>g_gemod_tx</td>
    <td>Energetischer Gebäudetyp nach der Typologie des ifeu-Gebäudemodells GEMOD (basierend auf IWU-Gebäudetypologien Wohn- und Nichtwohngebäude).</td>
  </tr>
  <tr>
    <td>Gebäudefunktion für Objektart AX_Gebaeude (Code)</td>
    <td>code_g</td>
    <td>LSA-Profil des ATKIS-Basis-DLM Version 7.1.2, Stand: 11/2023, URL: https://www.lvermgeo.sachsen-anhalt.de/de/datei/download/id/166811,501/lsa_profil_atkis_basis_dlm_7.1.2.pdf</td>
  </tr>
  <tr>
    <td>Gebäudefunktion für Objektart AX_Gebaeude (Text)</td>
    <td>code_g_txt</td>
    <td>LSA-Profil des ATKIS-Basis-DLM Version 7.1.2, Stand: 11/2023, URL: https://www.lvermgeo.sachsen-anhalt.de/de/datei/download/id/166811,501/lsa_profil_atkis_basis_dlm_7.1.2.pdf</td>
  </tr>
  <tr>
    <td>Funktion für Objektarten zur Siedlung (Code)</td>
    <td>code_f</td>
    <td>LSA-Profil des ATKIS-Basis-DLM Version 7.1.2, Stand: 11/2023, URL: https://www.lvermgeo.sachsen-anhalt.de/de/datei/download/id/166811,501/lsa_profil_atkis_basis_dlm_7.1.2.pdf</td>
  </tr>
  <tr>
    <td>Funktion für Objektarten zur Siedlung (Text)</td>
    <td>code_f_txt</td>
    <td>LSA-Profil des ATKIS-Basis-DLM Version 7.1.2, Stand: 11/2023, URL: https://www.lvermgeo.sachsen-anhalt.de/de/datei/download/id/166811,501/lsa_profil_atkis_basis_dlm_7.1.2.pdf</td>
  </tr>
  <tr>
    <td>Grundfläche [m²]</td>
    <td>gflache_m2</td>
    <td>Grundfläche des Gebäudes, abgeleitet aus Hausumring-Geometrie.</td>
  </tr>
  <tr>
    <td>Energiebezugsfläche [m²]</td>
    <td>eflache_m2</td>
    <td>Energetische Nutzfläche berechnet aus der Grundflächem X Flächenkorrekturfaktor (VDI 3807 Blatt 2).</td>
  </tr>
  <tr>
    <td>Gebäudehöhe [m]</td>
    <td>geb_hoehe</td>
    <td>Gebäudehöhe [m] vom LoD2 / Gebäudehöhe [m] vom LoD1 / Imputation</td>
  </tr>
  <tr>
    <td>Gebäudehöhe [m] vom LoD2</td>
    <td>g_hoehe_2</td>
    <td>Höhe des Gebäudes - LoD2: Differenz zwischen dem höchsten Bezugspunkt (First) und dem tiefsten Bezugspunkt (Bodenhöhe)</td>
  </tr>
  <tr>
    <td>Gebäudehöhe [m] vom LoD1</td>
    <td>g_hoehe_1</td>
    <td>Höhe des Gebäudes - LoD1: Differenz der durchschnittlichen Dachhöhe und der Bodenhöhe</td>
  </tr>
  <tr>
    <td>Gebäudevolumen [m²]</td>
    <td>g_volumen</td>
    <td>Grundfläche [m²] * Gebäudehöhe [m]</td>
  </tr>
  <tr>
    <td>Geschosshöhe [m]</td>
    <td>gsshoehe</td>
    <td>Annahmen je Gebäudefunktion für Objektart AX_Gebaeude (Code)</td>
  </tr>
  <tr>
    <td>Anzahl der oberirdischen Geschosse</td>
    <td>anz_og</td>
    <td>Gebäudehöhe [m] / Geschosshöhe [m]</td>
  </tr>
  <tr>
    <td>Korrekturfaktor Dachgeschossausbau</td>
    <td>fk_dg_ausb</td>
    <td>Je nach Dachform wird ein Korrekturfaktor für den Ausbau des Dachgeschosses angenommen.</td>
  </tr>
  <tr>
    <td>Korrekturfaktor für gemischt genutzte Wohngebäude</td>
    <td>fk_wg_nwg</td>
    <td>Anteil der Wohnfläche bei gemischt genutzten Wohngebäuden. Annahme: unterste Etage ist gewerblich genutzt, wenn es mehr als eine Etage gibt.</td>
  </tr>
  <tr>
    <td>Eistufung GEG-Relevanz</td>
    <td>beheizt</td>
    <td>Im Anschluss an Gebäudetypisierung durchgeführte generische Einstufung auf Basis von Gebäudegrundfläche, Siedlungsfläche, Gebäudehöhe, Gebäudevolumen, Gebäudefunktion: 100: "relevant", 0: "irrelvant", etc..</td>
  </tr>

  <tr>
    <td>Lage zur Erdoberfläche</td>
    <td>rellage</td>
    <td>z.B. "Unter der Erdoberfläche"</td>
  </tr>
  <tr>
    <td>Dachform</td>
    <td>dachform</td>
    <td>X</td>
  </tr>
  <tr>
    <td>geb_typ_z</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>geb_typ_p</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>bak_ezfh</td>
    <td>X</td>
    <td>X</td>
  </tr>
    <tr>
    <td>bak_mfh</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>bak_nwg</td>
    <td>X</td>
    <td>X</td>
  </tr>  
  <tr>
    <td>bak_z</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>bak_z_p</td>
    <td>X</td>
    <td>X</td>
  </tr>  
    <tr>
    <td>gmdschl</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>strssname</td>
    <td>X</td>
    <td>X</td>
  </tr>  
    <tr>
    <td>gid_tn</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>gid_str</td>
    <td>X</td>
    <td>X</td>
  </tr>  
  <tr>
    <td>objid_str</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>gitter_id</td>
    <td>X</td>
    <td>X</td>
  </tr>  
  <tr>
    <td>gid_bp</td>
    <td>X</td>
    <td>X</td>
  </tr>
  <tr>
    <td>gid_fnp</td>
    <td>X</td>
    <td>X</td>
  </tr> 
  <tr>
    <td>Geometriepunkt</td>
    <td>the_geom</td>
    <td>Mittelpunkt der Gebäudegrundfläche</td>
  </tr>
  </tbody>
</table>
  

<br><br><br><!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
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
<li>Produktions-, Werkstatt-, Lager- oder Betriebsgebäude (Im Modell kann hier noch aufgeteilt werden in GHD & Industrie)</li>
<li>Handelsgebäude</li>
<li>Technikgebäude (Ver- und Entsorgung)</li>
<li>Verkehrsgebäude</li>
<br>
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
      <li>Referenzwerte Gebäudefunktion zu Gebäudemodell (GEMOD): ref_gebfkt_gebtyp_gemod.csv</li>
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

<br><br><br><!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>+ Baualtersklasse</h2>
<table width='100%'>
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

<br><br><br><!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>+ Energiebezugsfläche</h2>
<table width='100%'>
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

<br><br><br><!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>+ Einstufung von Gebäuden als GEG-relevant</h2>
<table width='100%'>
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

<br><br><br><!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Wärmebedarfsberechnung</h2>
<br>
<li><b>Nutzenergiebedarf Heizung und Warmwasser [kWh/a] (je Gebäude) = </b> Energiezugsfläche [m²] x Spezifischer Heiz-/Warmwasserbedarf [kWh/(m²a)]</li>
<li><b>Nutzenergiebedarf Heizung und Warmwasser [MWh/(ha*a)] (je Siedlungsblock) = </b> Summe(Nutzenergiebedarf(Gebäude)) [MWh/a] / Fläche des Siedlungsblocks [ha]</li>
<li>Berechnung der nächstgelegenen Straße je Gebäude</li>
<li><b>Nutzenergiebedarf Heizung und Warmwasser [MWh/(m*a)] (je Straßenabschnitt) = </b> Summe(Nutzenergiebedarf(Gebäude))[MWh/a] / Länge des Straßenabschnitts [m]</li>
<br>
<table width='100%'>
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
      <li>Referenzwerte spezifischer Nutzenergiebedarf: ref_gebfkt_nutzenergiebedarf.csv</li>
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

<br><br><br><!-- --------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>Datenvisualisierung</h2>
<li>https://kwp-st.de/kvwmap/index.php</li>
