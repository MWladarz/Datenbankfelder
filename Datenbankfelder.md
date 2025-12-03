
# Plug-in Parameter Übersicht

<style>
body {font-family: Arial; background:#1e1e1e; color:#e0e0e0;}
table {border-collapse: collapse; width: 100%;}
th {position: sticky; top: 0; background: #333; color:#fff; z-index:2;}
td, th {border:1px solid #555; padding:8px;}
tr:nth-child(even) {background:#2a2a2a;}
tr:nth-child(odd) {background:#242424;}
details {margin:15px 0; background:#2c2c2c; padding:10px; border-radius:6px;}
summary {font-size:18px; font-weight:bold; cursor:pointer; color:#9cd2ff;}
input {padding:6px; margin:10px 0; width:300px; border-radius:4px; border:1px solid #666; background:#2a2a2a; color:#e0e0e0;}
</style>

<input id="search" onkeyup="searchTable()" placeholder="Search...">

<script>
function searchTable(){
  var filter = document.getElementById('search').value.toLowerCase();
  document.querySelectorAll('tbody tr').forEach(function(r){
    r.style.display = [...r.cells].some(c => c.innerText.toLowerCase().includes(filter)) ? '' : 'none';
  });
}
</script>

<details><summary>Abzugsfläche 2D</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>AddAreaModifierToSpace</td><td>Abzugsfläche 2D</td><td>SubFromSpace</td><td>Abzug von Raumfläche</td><td>Pop-Up</td></tr>
<tr><td>AddAreaModifierToSpace</td><td>Abzugsfläche 2D</td><td>SubFromSpaceCustom</td><td>Eigen</td><td>Number</td></tr>
<tr><td>AddAreaModifierToSpace</td><td>Abzugsfläche 2D</td><td>SubArea</td><td>Gerechnete Fläche</td><td>Number</td></tr>
</tbody></table></details>
<details><summary>Aussparung</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Recess</td><td>Aussparung</td><td>__Version</td><td></td><td>Integer</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__GeneratedType</td><td></td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>InComponent</td><td>In Bauteil</td><td>Boolean</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>IsOpening</td><td>Ist Bauteilöffnung</td><td>Boolean</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__OriginRef</td><td></td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__OriginDatum</td><td></td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>OriginRefShort</td><td>Einfügepunkt Lage</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__ShapeArea</td><td></td><td>Area</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__ShapePerim</td><td></td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__ShapeAreaNet</td><td></td><td>Area</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__ShapePerimNet</td><td></td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>ComponentType</td><td>Bauteil</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>RecessType</td><td>Aussparungstyp</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>Shape</td><td>Grundform</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>ShapeSymbol</td><td>Grundform Symbol</td><td>Symbol Definition</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>NameLong</td><td>Bezeichnung Lang</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>NameShort</td><td>Bezeichnung Kurz</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DisplayMode</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>OriginRef</td><td>Einfügepunkt</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>OriginDatum</td><td>Bezugspunkt</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>OriginOffsetZ</td><td>Versatz Bezugspunkt</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>SizeX</td><td>Länge 1 (x)</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>SizeY</td><td>Länge 2 (y)</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>SizeZ</td><td>Tiefe (z)</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>SizeAdapt</td><td>Größe anpassen an</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>Figure2D</td><td>Darstellung 2D-Plan</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>Figure2DMirrorX</td><td>Darstellung 2D-Plan horizontal spiegeln</td><td>Boolean</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>Figure2DMirrorY</td><td>Darstellung 2D-Plan vertikal spiegeln</td><td>Boolean</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>FigureSection</td><td>Darstellung 2D-Schnitt</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>FigureView</td><td>Darstellung 2D-Ansicht</td><td>Pop-Up</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>FigureSpacing</td><td>Darstellung Linienabstand</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DetailLevel</td><td>__DetailLevel</td><td>Integer</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>__WallBreak</td><td></td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>Edges</td><td>__Edges</td><td>Integer</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningEnabled</td><td>Auskleidung verwenden</td><td>Boolean</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningUniform</td><td>Einheitliche Auskleidung</td><td>Boolean</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningX1</td><td>Auskleidung Breite X1</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningX2</td><td>Auskleidung Breite X2</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningY1</td><td>Auskleidung Breite Y1</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningY2</td><td>Auskleidung Breite Y2</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningZ1</td><td>Auskleidung Breite Z1</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>LiningZ2</td><td>Auskleidung Breite Z2</td><td>Dimension</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataPrefix</td><td>Daten Präfix</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataSuffix</td><td>Daten Suffix</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataUsage</td><td>Daten Verwendung</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataUsageShort</td><td>Daten Verwendung Abkürzung</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataRequirement1</td><td>Daten Anforderung 1</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataRequirement2</td><td>Daten Anforderung 2</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataRequirement3</td><td>Daten Anforderung 3</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataRequirement4</td><td>Daten Anforderung 4</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataRequirement5</td><td>Daten Anforderung 5</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataMiscField1</td><td>Daten Zusatzfeld 1</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataMiscField2</td><td>Daten Zusatzfeld 2</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataMiscField3</td><td>Daten Zusatzfeld 3</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataMiscField4</td><td>Daten Zusatzfeld 4</td><td>Text</td></tr>
<tr><td>Recess</td><td>Aussparung</td><td>DataMiscField5</td><td>Daten Zusatzfeld 5</td><td>Text</td></tr>
</tbody></table></details>
<details><summary>Baugrube Aufschüttung</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>Höhe</td><td>Höhe Sohle</td><td>Dimension</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>Gefälleeingabe</td><td>Gefälleeingabe</td><td>Pop-Up</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>Gefälle</td><td>Gefälle Sohle</td><td>Number</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>Gefälle anzeigen</td><td>Gefälle anzeigen</td><td>Boolean</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>ControlPoint01X</td><td>x_start_pkt</td><td>X Coordinate</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>ControlPoint01Y</td><td>y_start_pkt</td><td>Y Coordinate</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>ControlPoint02X</td><td>x_end_pkt</td><td>X Coordinate</td></tr>
<tr><td>Excavation CW</td><td>Baugrube Aufschüttung</td><td>ControlPoint02Y</td><td>y_end_pkt</td><td>Y Coordinate</td></tr>
</tbody></table></details>
<details><summary>Dämmung</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationTypePop</td><td>Typ</td><td>Pop-Up</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationThicknessEd</td><td>Dicke</td><td>Dimension</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationLeadLinePos</td><td>Leitlinie</td><td>Pop-Up</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationLeadLineEd</td><td>Leitlinienabstand</td><td>Dimension</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationAngleHardEd</td><td>Winkel</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationShowCorners</td><td>Linke und Rechte Kante anzeigen</td><td>Boolean</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationFinishPop</td><td>Abschluss</td><td>Pop-Up</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationCornerConnectionEd</td><td>Eckverbindung</td><td>Pop-Up</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationLengthLeadLine</td><td>Länge</td><td>Dimension</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>InsulationFixPoint</td><td>Fixpunkt</td><td>Pop-Up</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>StartX</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>StartY</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>EndX</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>EndY</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point01X</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point01Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point02X</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point02Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point03X</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point03Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point04X</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point04Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point05X</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point05Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point06X</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Point06Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Flags</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>Richtung</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>FactorRadius</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>FactorManu</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzClassOfPIO</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzPStyleByClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzPenColors</td><td>__CWD_DO_NOT_CHANGE</td><td>Color</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzPenColorByClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzPenWeight</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Weight</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzPenWByClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzOpacity</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>UmgzOpacityByClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>FillClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Insulation CW</td><td>Dämmung</td><td>offset</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
</tbody></table></details>
<details><summary>Elektrische Kombination</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>Version</td><td>__Version</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>UID</td><td>__UID</td><td>Text</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>__PrefStyleID</td><td></td><td>Symbol Definition</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>AxisID</td><td>Achse</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>AxisOffset</td><td>Horizontalversatz</td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>LevelType</td><td>Referenzhöhe</td><td>Text</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>Elevation</td><td>Vertikalversatz</td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>AlignMode</td><td>Ausrichten an</td><td>Pop-Up</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>AlignEdge</td><td>Ausrichtung</td><td>Pop-Up</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>FrameSymbol</td><td>Rahmen 3D-Darstellung</td><td>Text</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>GridSizeX</td><td>Anzahl Felder horizontal</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>GridSizeY</td><td>Anzahl Felder vertikal</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>GridCenterX</td><td>Rahmen-Mittelpunkt (X)</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>GridCenterY</td><td>Rahmen-Mittelpunkt (Y)</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>TileDistanceX</td><td></td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>TileDistanceY</td><td></td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>WallDistance</td><td>Abstand zur Wand</td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>ItemCount</td><td>Anzahl Bauteile</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>CompTypeTag</td><td>Art der Kombination</td><td>Pop-Up</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>ProfileEditMode</td><td>__ProfileEditMode</td><td>Boolean</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>Reset2D</td><td>__Reset2D</td><td>Boolean</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>Class</td><td></td><td>Text</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>FrameColumns</td><td>Anzahl Bauteilpositionen horizontal</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>FrameRows</td><td>Anzahl Bauteilpositionen vertikal</td><td>Integer</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>ItemWidth</td><td>Nische Bauteil Breite</td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>ItemHeight</td><td>Nische Bauteil Höhe</td><td>Dimension</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>SameWidth</td><td>Achsmaß vertikal wie Breite</td><td>Boolean</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>SameHeight</td><td>Achsmaß horizontal wie Höhe</td><td>Boolean</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>WidthOffsets</td><td>__ItemOffsetsX</td><td>Pop-Up</td></tr>
<tr><td>ElectricalComponent</td><td>Elektrische Kombination</td><td>HeightOffsets</td><td>__ItemOffsetsY</td><td>Pop-Up</td></tr>
</tbody></table></details>
<details><summary>Elektrisches Bauteil</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>Version</td><td>__Version</td><td>Integer</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>UID</td><td>__UID</td><td>Text</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>__PrefStyleID</td><td></td><td>Symbol Definition</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>CompStyleType</td><td>__CompStyleType</td><td>Integer</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>GridPositionX</td><td>Feldposition (X)</td><td>Integer</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>GridPositionY</td><td>Feldposition (Y)</td><td>Integer</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureSymbol</td><td>2D-Darstellung</td><td>Text</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>DeviceSymbol</td><td>3D-Darstellung</td><td>Text</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureMirrorAllowed</td><td>2D-Darstellung automatisch spiegeln</td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>DataTagEnabled</td><td>Beschriftung anlegen</td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>DataTagClass</td><td>Beschriftung Klasse</td><td>Text</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>DataTagStyle</td><td>Beschriftung Datenstempel</td><td>Classes Popup</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>DataTagPos</td><td>Beschriftung Position</td><td>Pop-Up</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigurePosX</td><td>__FigurePosX</td><td>X Coordinate</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigurePosY</td><td>__FigurePosY</td><td>Y Coordinate</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureMirrored</td><td>__FigureMirrored</td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureAsymmetry</td><td>__FigureAsymmetry</td><td>Integer</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureAsymmetryOffset</td><td>__FigureAsymmetryOffset</td><td>Dimension</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureDefaultPosX</td><td>__FigureDefaultPosX</td><td>X Coordinate</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureDefaultPosY</td><td>__FigureDefaultPosY</td><td>Y Coordinate</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureDefaultMirrored</td><td>__FigureDefaultMirrored</td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureWidth</td><td></td><td>Dimension</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureHeight</td><td></td><td>Dimension</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureShow3D</td><td></td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureScaleCheck</td><td></td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>FigureScale</td><td></td><td>Number</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>ControlPointX</td><td>__ControlPointX</td><td>X Coordinate</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>ControlPointY</td><td>__ControlPointY</td><td>Y Coordinate</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>ControlPointID</td><td>__ControlPointID</td><td>Integer</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>Restore2D</td><td>__Restore2D</td><td>Boolean</td></tr>
<tr><td>ElectricalItem</td><td>Elektrisches Bauteil</td><td>Class</td><td></td><td>Text</td></tr>
</tbody></table></details>
<details><summary>Elektroinstallation</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>Version</td><td>__Version</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>OriginOffsetAlign</td><td>Positon Einfügepunkt</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>OriginOffset</td><td>Breite Referenzobjekt</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>OriginOffsetAuto</td><td>An Objekt in Wand anpassen</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>Axis0Offset</td><td>Versatz linke Achse</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>Axis1Offset</td><td>Versatz mittlere Achse</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>Axis2Offset</td><td>Versatz rechte Achse</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>PreviewRenderMode</td><td>__PreviewRenderMode</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>PreviewBackground</td><td>__PreviewBackground</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DWallGap</td><td>Wandabstand</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DCompGapX</td><td>Abstand Kombination horizontal</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DCompGapY</td><td>Abstand Kombination vertikal</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DItemGapX</td><td>Abstand Bauteil horizontal</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DItemGapY</td><td>Abstand Bauteil vertikal</td><td>Dimension</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DShow3D</td><td>3D-Darstellung vorne zeigen</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DScaleCheck</td><td>2D-Skalierung aktivieren</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>2DScale</td><td>Skalierung</td><td>Number</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>WallObjInsertMode</td><td>__WallObjInsertMode</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>WallObjRight</td><td>__WallObjRight</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>WallObjFliped</td><td>__WallObjFliped</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>InWall</td><td>__InWall</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>WallObjHandDirection</td><td>__WallObjHandDirection</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>WallObjSideOfWall</td><td>__WallObjSideOfWall</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>WallObjInteriorSide</td><td>__WallObjInteriorSide</td><td>Integer</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>Reset2D</td><td>__Reset2D</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>ProfileEditMode</td><td>__ProfileEditMode</td><td>Boolean</td></tr>
<tr><td>ElectricalObject</td><td>Elektroinstallation</td><td>ComponentCount</td><td></td><td>Integer</td></tr>
</tbody></table></details>
<details><summary>Fenster</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Window CW</td><td>Fenster</td><td>Fensterbreite</td><td>Gewählte Breite</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Fensterhöhe</td><td>Gewählte Höhe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Brüstungshöhe</td><td>Brüstungshöhe (gem. Einstellungen)</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Fensterform</td><td>Form</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Oberlicht</td><td>__NNA__Oberlicht__HIDDEN_NOLOC</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Unterlicht</td><td>__NNA__Unterlicht__HIDDEN_NOLOC</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Anzeigeart</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Einfügepunkt</td><td>Einfügepunkt längs</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ControlPoint01X</td><td>x-Position Beschriftung </td><td>X Coordinate</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ControlPoint01Y</td><td>y-Position Beschriftung </td><td>Y Coordinate</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Anzahl Flügel</td><td>Flügeleinteilung</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>3D-Fensterladen</td><td>Fensterladen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Fensterbank</td><td>Fensterbank</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AnzeigeartE</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HeadHeight</td><td>Sturzhöhe (gem. Einstellungen)</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeInnerBalustrade</td><td>Brüstung innen</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeOuterBalustrade</td><td>Brüstung außen</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeRabbetObsoleteDontUse</td><td>__NNA Anschlagtyp  now obsolete</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ShapeWindowTransom</td><td>Öffnungsform</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeShutter</td><td>Sonnenschutz</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasTransom</td><td>Oberlicht</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasBottomSash</td><td>Unterlicht</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>NumberOfCasements</td><td>Anzahl Flügel</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement1</td><td>Typ Flügel 1</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement1</td><td>Breite Flügel 1</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement2</td><td>Typ Flügel 2</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement2</td><td>Breite Flügel 2</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement3</td><td>Typ Flügel 3</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement3</td><td>Breite Flügel 3</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement4</td><td>Typ Flügel 4</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement4</td><td>Breite Flügel 4</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement5</td><td>Typ Flügel 5</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement5</td><td>Breite Flügel 5</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement6</td><td>Typ Flügel 6</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement6</td><td>Breite Flügel 6</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement7</td><td>Typ Flügel 7</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement7</td><td>Breite Flügel 7</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement8</td><td>Typ Flügel 8</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement8</td><td>Breite Flügel 8</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WallStyle</td><td>Wandstil</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WallThickness</td><td>Wanddicke</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>NameOrType</td><td>__NNA Bezeichnung (alt) now obsolete</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo01</td><td>Zusatz 01</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo02</td><td>Zusatz 02</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo03</td><td>Zusatz 03</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo04</td><td>Zusatz 04</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo05</td><td>Zusatz 05</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo06</td><td>Zusatz 06</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo07</td><td>Zusatz 07</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo08</td><td>Zusatz 08</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo09</td><td>Zusatz 09</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo10</td><td>Zusatz 10</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo11</td><td>Zusatz 11</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo12</td><td>Zusatz 12</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo13</td><td>Zusatz 13</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo14</td><td>Zusatz 14</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AdditionalInfo15</td><td>Zusatz 15</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IsSimpleWindowWallOpening</td><td>Wandöffnung</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowKind</td><td>Fensterart</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_GlobalId</td><td>Bauteilnummer</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_Name</td><td>Bezeichnung</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_Description</td><td>Beschreibung</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_ObjectType</td><td>Objekttyp</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_Tag</td><td>Tag</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_OverallHeight</td><td>__NNA_Obsolete Gesamthöhe (IFC)</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_OverallWidth</td><td>__NNA_Obsolete Gesamtbreite (IFC)</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_Reference</td><td>Bauteiltyp</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_FireRating</td><td>Feuerwiderstandsklasse</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_AcousticRating</td><td>Schallschutzklasse</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_SecurityRating</td><td>Sicherheitsklasse</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_IsExternal</td><td>Gegen Außenluft</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_Infiltration</td><td>Luftdurchlass</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_ThermalTransmittance</td><td>U-Wert (Energos)</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_GlazingAreaFraction</td><td>Glasflächenanteil</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_SmokeStop</td><td>Rauchschutz</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_OpeningElementCommon_Purpose</td><td>Zweck</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_OpeningElementCommon_ProtectedOpening</td><td>Brandschutz</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_OpeningElementCommon_ParallelJambs</td><td>Seiten von Wandöffnung sind Parallel</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_OpeningElementCommon_FireExit</td><td>Notausgang</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowStyle_OperationType</td><td>Fenstertyp</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowStyle_ConstructionType</td><td>Konstruktionstyp</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowStyle_ParameterTakesPrecedence</td><td>Werte entsprechen Realität</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowStyle_Sizeable</td><td>Skalierbar</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowShadingType_ExternalShadingCoefficient</td><td>b-Faktor Außen</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowShadingType_InternalShadingCoefficient</td><td>b-Faktor Innen</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowShadingType_InsetShadingCoefficient</td><td>b-Faktor Glaszwischenraum</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_LiningDepth</td><td>Rahmentiefe</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_LiningThickness</td><td>Rahmenbreite</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_TransomThickness</td><td>Kämpferhöhe</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_MullionThickness</td><td>Pfostendicke Festverglasung</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_FirstTransomOffset</td><td>UK Rahmen - Achse 1. Querbalken Oberlicht</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_SecondTransomOffset</td><td>UK Rahmen - Achse 2. Querbalken Oberlicht</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_FirstMullionOffset</td><td>(AK Rahmen - Achse 1. Pfosten) > Festverglasung</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowLining_SecondMullionOffset</td><td>(AK Rahmen - Achse 2. Pfosten) > Festverglasung</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel1_OperationType</td><td>Öffnungsart Flügel 1</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel1_PanelPosition</td><td>Position Flügel 1</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel1_FrameDepth</td><td>Flügelrahmendicke Flügel 1</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel1_FrameThickness</td><td>Flügelrahmenbreite Flügel 1</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel2_OperationType</td><td>Öffnungsart Flügel 2</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel2_PanelPosition</td><td>Position Flügel 2</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel2_FrameDepth</td><td>Flügelrahmendicke Flügel 2</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel2_FrameThickness</td><td>Flügelrahmenbreite Flügel 2</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel3_OperationType</td><td>Öffnungsart Flügel 3</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel3_PanelPosition</td><td>Position Flügel 3</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel3_FrameDepth</td><td>Flügelrahmendicke Flügel 3</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowPanel3_FrameThickness</td><td>Flügelrahmenbreite Flügel 3</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Classification Name</td><td>Klassifizierung: Klassifizierungsname</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Classification Source</td><td>Klassifizierung: Klassifizierungsquelle</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Classification Edition</td><td>Klassifizierung: Version</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Classification Edition Date</td><td>Klassifizierung: Versionsdatum</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Item Reference</td><td>Klassifizierung: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Name</td><td>Klassifizierung: Name</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification_Location</td><td>Klassifizierung: Quelle</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Classification Name</td><td>Klassifizierung 2: Klassifizierungsname</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Classification Source</td><td>Klassifizierung 2: Klassifizierungsquelle</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Classification Edition</td><td>Klassifizierung 2: Version</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Classification Edition Date</td><td>Klassifizierung 2: Versionsdatum</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Item Reference</td><td>Klassifizierung 2: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Name</td><td>Klassifizierung 2: Name</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification2_Location</td><td>Klassifizierung 2: Quelle</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Classification Name</td><td>Klassifizierung 3: Klassifizierungsname</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Classification Source</td><td>Klassifizierung 3: Klassifizierungsquelle</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Classification Edition</td><td>Klassifizierung 3: Version</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Classification Edition Date</td><td>Klassifizierung 3: Versionsdatum</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Item Reference</td><td>Klassifizierung 3: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Name</td><td>Klassifizierung 3: Name</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Classification3_Location</td><td>Klassifizierung 3: Quelle</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>BaseQuantities_Name</td><td>Base Quantities: Bezeichnung</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>BaseQuantities_Description</td><td>Base Quantities: Beschreibung</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>BaseQuantities_Width</td><td>__NNA_Rahmenaußenmaß Breite</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>BaseQuantities_Height</td><td>__NNA_Rahmenaußenmaß Höhe</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>BaseQuantities_Perimeter</td><td>Rahmenaußenmaß Umfang</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>BaseQuantities_Area</td><td>Rahmenaußenmaß Fläche</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowID</td><td>Fensternummer</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_PredefinedType</td><td>Kategorie</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_PartitioningType</td><td>Öffnungsart</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IfcWindow_UserDefinedPartitioningType</td><td>Öffnungsart Benutzerdefiniert</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_GlassLayers</td><td>Verglasung (Anzahl Gläser)</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_GlassThickness1</td><td>Dicke Glas 1 (Innenseite)</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_GlassThickness2</td><td>Dicke Glas 2 (Zwischen- oder Außenseite)</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_GlassThickness3</td><td>Dicke Glas 3 (Außenseite)</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_FillGas</td><td>Glasfüllung</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_GlassColor</td><td>Glasfarbe</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_IsTempered</td><td>Gehärtet</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_IsLaminated</td><td>Belegt</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_IsCoated</td><td>Beschichtet</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_IsWired</td><td>Drahtglas</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_Translucency</td><td>Tʟ Tageslichttransmission</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_Reflectivity</td><td>Reflexionsgrad</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_BeamRadiationTransmittance</td><td>λg Glasrandverbund</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_SolarHeatGainTransmittance</td><td>g-Wert</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_ThermalTransmittanceSummer</td><td>Ug-Wert Sommer</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_ThermalTransmittanceWinter</td><td>Ug-Wert Winter</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_Status</td><td>Status</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_ModelReference</td><td>Produktlinie</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_ModelLabel</td><td>Modell</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_Manufacturer</td><td>Hersteller</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_ProductionYear</td><td>Produktionsjahr</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_ArticleNumber</td><td>Artikelnummer</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_GlobalTradeItemNumber</td><td>GlobalTradeItemNumber</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerTypeInformation_AssemblyPlace</td><td>Montageort</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerOccurrence_AcquisitionDate</td><td>Kaufdatum</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerOccurrence_BarCode</td><td>Barcode</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerOccurrence_SerialNumber</td><td>Seriennummer</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ManufacturerOccurrence_BatchReference</td><td>Produktcharge</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_Reference</td><td>Bemusterungstyp</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_ShadingDeviceType</td><td>Verschattungsart</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_IsExternal</td><td>Außenbauteil</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_MechanicalOperated</td><td>Mechanisch</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_ThermalTransmittance</td><td>U-Wert</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_SolarTransmittance</td><td>Abminderungsfaktor energetisch</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_VisibleLightTransmittance</td><td>Abminderungsfaktor optisch</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_SolarReflectance</td><td>Reflexion</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_VisibleLightReflectance</td><td>Reflexionsgrad für sichtbares Licht</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_Roughness</td><td>Oberflächenversatz</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_SurfaceColor</td><td>Oberflächenfarbe</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ElementShading_Azimuth</td><td>Himmelsrichtung</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ElementShading_Inclination</td><td>Neigung X-Achse</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ElementShading_TiltRange</td><td>Neigung Z-Achse</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_SolarAbsorption</td><td>Strahlungsabsorptionsgrad</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_SolarReflectance</td><td>Strahlungsreflektionsgrad</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_DoorWindowGlazingType_ShadingCoefficient</td><td>Mittlerer Durchlassfaktor b</td><td>Number</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_ShadingDeviceCommon_Status</td><td>Status Sonnenschutz</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_HasDrive</td><td>Antrieb</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_WaterTightnessRating</td><td>Schlagregendichtigkeit</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_MechanicalLoadRating</td><td>Mechanische Festigkeit</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_WindLoadRating</td><td>Windwiderstand</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_HasSillExternal</td><td>Fensterbank außen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>Pset_WindowCommon_HasSillInternal</td><td>Fensterbank innen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>GlazingArea</td><td>Glasfläche</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WindowClearanceArea</td><td>Rahmenlichtmaß Fläche</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedWidthOutside</td><td>Fertigmaß Breite außen</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedHeightWallOutside</td><td>Fertigmaß Höhe Wand außen</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedWidthInside</td><td>Fertigmaß Breite innen</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedHeightWallInside</td><td>Fertigmaß Höhe Wand innen</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UnfinishedWidth</td><td>Rohbaumaß Breite</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UnfinishedHeight</td><td>Rohbaumaß Höhe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ForFutureUse001</td><td>__NNA_ForFutureUse former Rohbaumaß innen Breite</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ForFutureUse002</td><td>__NNA_ForFutureUse former Rohbaumaß innen Höhe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FrameTotalWidth</td><td>Rahmenaußenmaß Breite</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FrameTotalHeight</td><td>Rahmenaußenmaß Höhe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FrameClearWidth</td><td>Rahmenlichtmaß Breite</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FrameClearHeight</td><td>Rahmenlichtmaß Höhe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>SizeModeWidth</td><td>__NNA_Gewählte Breite (Art)</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>SizeModeHeight</td><td>__NNA_Gewählte Höhe (Art)</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedHeightWindowOutside</td><td>Fertigmaß Höhe Fenster außen</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedHeightWindowInside</td><td>Fertigmaß Höhe Fenster innen</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AutoDimensionWidth</td><td>Breite innen</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AutoDimensionHeight</td><td>Höhe Innen</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedAreaWindowOutside</td><td>Fertigmaß Fenster Fläche außen</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedAreaWindowInside</td><td>Fertigmaß Fenster Fläche innen</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedAreaWallOutside</td><td>Fertigmaß Wand Fläche außen</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FinishedAreaWallInside</td><td>Fertigmaß Wand Fläche innen</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UnfinishedArea</td><td>Rohbaumaß Fläche</td><td>Area</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement9</td><td>Typ Flügel 9</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement9</td><td>Breite Flügel 9</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement10</td><td>Typ Flügel 10</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement10</td><td>Breite Flügel 10</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement11</td><td>Typ Flügel 11</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement11</td><td>Breite Flügel 11</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement12</td><td>Typ Flügel 12</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement12</td><td>Breite Flügel 12</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement13</td><td>Typ Flügel 13</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement13</td><td>Breite Flügel 13</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement14</td><td>Typ Flügel 14</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement14</td><td>Breite Flügel 14</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement15</td><td>Typ Flügel 15</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement15</td><td>Breite Flügel 15</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement16</td><td>Typ Flügel 16</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement16</td><td>Breite Flügel 16</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement17</td><td>Typ Flügel 17</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement17</td><td>Breite Flügel 17</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement18</td><td>Typ Flügel 18</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement18</td><td>Breite Flügel 18</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement19</td><td>Typ Flügel 19</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement19</td><td>Breite Flügel 19</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeCasement20</td><td>Typ Flügel 20</td><td>Text</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthCasement20</td><td>Breite Flügel 20</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>InsertionRelativeTo</td><td>Einfügepunkt quer</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>SillHeightFromOrigin</td><td>Brüstungshöhe (ab Nullpunkt)</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HeadHeightFromOrigin</td><td>Sturzhöhe (ab Nullpunkt)</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AutoDimensionWidthExterior</td><td>Breite außen</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>AutoDimensionHeightExterior</td><td>Höhe außen</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>InternalVersionNumberDoNotChange</td><td>__NNA_InternalVersionNumberOfRecordFormat</td><td>Integer</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>DetailLevel3DRepresentation</td><td>Detaillierung für 3D-Darstellung</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UseAutomatic2DForHorizontalSection2D</td><td>Für Horizontalschnitt 2D verwenden</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UseAutomatic2DForBackView2D</td><td>Für Ansicht von außen 2D verwenden</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UseAutomatic2DForLeftRightView2D</td><td>Für Querschnitt 2D verwenden</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>NotInCutPlaneMode</td><td>In Horizontalschnitt 2D</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ShadeOffset</td><td>Schatten Versatz</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ShadePosition</td><td>Schatten</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>UseWallAttributesForWallBelowWindow</td><td>Wandattribute übernehmen für Wand unter Fenster</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>IsCornerWindow</td><td>Eckfenster</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>CornerWindowType</td><td>Einseitig / beidseitig</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>CornerWindowChamferMode</td><td>Stoß</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HeightOfTopUnit</td><td>Höhe Oberlicht</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthOfTopFrameOfTopUnit</td><td>Rahmenbreite Oberlicht oben</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthOfLeftFrameOfTopUnit</td><td>Rahmenbreite Oberlicht links</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthOfRightFrameOfTopUnit</td><td>Rahmenbreite Oberlicht rechts</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HeightOfBottomUnit</td><td>Höhe Unterlicht</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthOfBottomFrameOfBottomUnit</td><td>Rahmenbreite Unterlicht unten</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthOfLeftFrameOfBottomUnit</td><td>Rahmenbreite Unterlicht links</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WidthOfRightFrameOfBottomUnit</td><td>Rahmenbreite Unterlicht rechts</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeOfExteriorSill</td><td>Banktyp außen</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>SillHasEndCranking</td><td>Endverkröpfung erzeugen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ZPositionDefinedBy</td><td>Fensterposition definieren durch</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>WallSideOfSillHeadHeight</td><td>BrüstungsSturzHöhe bezieht sich auf</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasSillAtInteriorSide</td><td>Fensterbank innen erstellen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasSillAtExteriorSide</td><td>Fensterbank außen erstellen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasNicheAtInteriorSide</td><td>Nische innen aussparen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasNicheAtExteriorSide</td><td>Nische außen aussparen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>MarkNicheForSpaceObject</td><td>Nische in Raumfläche berücksichtigen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasSunProtection</td><td>Sonnenschutz erstellen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeOfSunProtection</td><td>Sonnenschutz Typ</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>CloseLeftShutter</td><td>Laden links schließen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>CloseRightShutter</td><td>Laden rechts schließen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasRailing</td><td>Geländer erstellen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RailingPosition</td><td>Position</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>HasRadiator</td><td>Heizkörper erstellen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ModeWidthRadiator</td><td>Breite gemäß</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RadiatorWidth</td><td>Breite</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RadiatorHeight</td><td>Höhe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RadiatorDepth</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RadiatorDistanceToInteriorSideOfWall</td><td>Abstand von Wand</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RadiatorDistanceToBoundaryDefinedByModeWidth</td><td>Abstand</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RadiatorDistanceToGround</td><td>Abstand UK</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeofFrame</td><td>Darstellung höchste Detaillierung</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>CustomSymbol</td><td>Eigenes Symbol verwenden</td><td>Symbol Definition</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>ExteriorSillHeightIsUpperEdgeOfLedge</td><td>Brüstungshöhe außen ist OK Fensterbank</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>TypeTiltTurnSlide</td><td>Öffnungsart</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>OffsetInAssembly</td><td>Versatz im Fassadenmodul</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RevealLining</td><td>Laibungsverkleidung erstellen</td><td>Boolean</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>FramePositionInReveal</td><td>Rahmenposition</td><td>Pop-Up</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>OffsetFramePositionInReveal</td><td>Abstand Rahmenposition</td><td>Dimension</td></tr>
<tr><td>Window CW</td><td>Fenster</td><td>RevealType</td><td>Typ</td><td>Pop-Up</td></tr>
</tbody></table></details>
<details><summary>Gebäude</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Building CW</td><td>Gebäude</td><td>building form</td><td>Gebäudeform</td><td>Pop-Up</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>delta width</td><td>Länge ∆x</td><td>Dimension</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>delta length</td><td>Breite ∆y</td><td>Dimension</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>roof form</td><td>Dachform</td><td>Pop-Up</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>floor cnt</td><td>Anzahl Geschosse</td><td>Integer</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>floor height</td><td>Geschosshöhe</td><td>Dimension</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>height basement</td><td>Höhe Keller</td><td>Dimension</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>height insert pt</td><td>Höhe Einfügepunkt</td><td>Dimension</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>distance space</td><td>Abstandsflächen</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>roof overhang</td><td>Dachüberstand</td><td>Dimension</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>show floor line</td><td>Geschosslinien anzeigen</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>total height</td><td>Gesamthöhe</td><td>Static Text</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>total area</td><td>Gesamtfläche</td><td>Static Text</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>area as number</td><td>Gesamtfläche in qm</td><td>Number</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>height above zero</td><td>Höhe über Gelände</td><td>Static Text</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>roof pitch</td><td>Dachneigung</td><td>Static Text</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>pult_dach</td><td>Pultdach-Neigung</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>pult_T_rechts</td><td>Pult T Rechts</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>mirror building</td><td>Gebäude spiegeln</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>rotate ridge</td><td>First rotieren</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>doc shadow</td><td>Schatten 2D anzeigen </td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>RoofToOverhand</td><td>Dach bis Dachüberstand anzeigen</td><td>Boolean</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofArea1 Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofArea1 Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofArea1 PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofArea2 Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofArea2 Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofLine Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofLine PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofOverhang Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D RoofOverhang PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D DistanceArea Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D DistanceArea Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D DistanceArea PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D Wall3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D Wall3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D Wall3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D Wall3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr2D Wall3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofTop3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofTop3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofTop3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofTop3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofTop3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofBottom3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofBottom3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofBottom3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofBottom3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D RoofBottom3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D FloorLine3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D FloorLine3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D FloorLine3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D FloorLine3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>Attr3D FloorLine3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>_version</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Building CW</td><td>Gebäude</td><td>__NEW</td><td></td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Gebäude eigene Form</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>building form</td><td>Gebäudeform</td><td>Pop-Up</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>delta width</td><td>Länge ∆x</td><td>Dimension</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>delta length</td><td>Breite ∆y</td><td>Dimension</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>roof form</td><td>Dachform</td><td>Pop-Up</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>floor cnt</td><td>Anzahl Geschosse</td><td>Integer</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>floor height</td><td>Geschosshöhe</td><td>Dimension</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>height basement</td><td>Höhe Keller</td><td>Dimension</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>height insert pt</td><td>Höhe Einfügepunkt</td><td>Dimension</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>distance space</td><td>Abstandsflächen</td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>roof overhang</td><td>Dachüberstand</td><td>Dimension</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>show floor line</td><td>Geschosslinien anzeigen</td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>total height</td><td>Gesamthöhe</td><td>Static Text</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>total area</td><td>Gesamtfläche</td><td>Static Text</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>area as number</td><td>Gesamtfläche in qm</td><td>Number</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>height above zero</td><td>Höhe über Gelände</td><td>Static Text</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>roof pitch</td><td>Dachneigung</td><td>Static Text</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>pult_dach</td><td>Pultdach-Neigung</td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>pult_T_rechts</td><td>Pult T Rechts</td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>mirror building</td><td>Gebäude spiegeln</td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>rotate ridge</td><td>First rotieren</td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>doc shadow</td><td>Schatten 2D anzeigen </td><td>Boolean</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofArea1 Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofArea1 Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofArea1 PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofArea2 Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofArea2 Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofLine Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofLine PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofOverhang Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D RoofOverhang PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D DistanceArea Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D DistanceArea Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D DistanceArea PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D Wall3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D Wall3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D Wall3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D Wall3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr2D Wall3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofTop3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofTop3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofTop3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofTop3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofTop3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofBottom3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofBottom3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofBottom3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofBottom3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D RoofBottom3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D FloorLine3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D FloorLine3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D FloorLine3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D FloorLine3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>Attr3D FloorLine3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>_version</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Custom Building CW</td><td>Gebäude eigene Form</td><td>__NEW</td><td></td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Gefälle Grundriss</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Hhe Punkt 1</td><td>Höhe Punkt 1</td><td>Dimension</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Hhe Punkt 2</td><td>Höhe Punkt 2</td><td>Dimension</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Einstellungen</td><td>Einstellungen Punkte</td><td>Pop-Up</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Grade Mode Static</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Neigung in % fallend</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Neigung in % steigend</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Neigung in cm</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Lnge in cm</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Neigung beschriften</td><td>Neigung beschriften</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Lnge beschriften</td><td>Länge (Projektion) beschriften</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Surface Length</td><td>Länge (Abwicklung) beschriften</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Length below arrow</td><td>Länge(n) unter Gefällepfeil beschriften</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Hhen beschriften</td><td>__invisible</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Hilfslinie erzeugen</td><td>Hilfslinie erzeugen</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint01X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint01Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint02X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint02Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint03X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint03Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint04X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint04Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint05X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint05Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint06X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint06Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Grade Length Projected</td><td>Länge (Projektion)</td><td>Dimension</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Grade Length Surface</td><td>Gefälle Länge (Abwicklung)</td><td>Dimension</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint07X</td><td>__invisible</td><td>X Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ControlPoint07Y</td><td>__invisible</td><td>Y Coordinate</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Mark Pio red</td><td>__invisible</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Start Point Connected</td><td>Startpunkt verbunden</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>End Point Connected</td><td>Endpunkt verbunden</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Grade belongs to Network</td><td>Gefälle mit Netz verbunden</td><td>Boolean</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Symbol</td><td>Gefälle Symbol</td><td>Symbol Definition</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Model Type</td><td>Anwenden auf</td><td>Pop-Up</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Known Param 1</td><td>Maßgebender Wert 1</td><td>Pop-Up</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Known Param 2</td><td>Maßgebender Wert 2</td><td>Pop-Up</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>DTM Layer</td><td>Ebene Geländemodell</td><td>Layers Popup</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Simplification Tolerance</td><td>Modifikator vereinfachen</td><td>Dimension</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Vertex Count</td><td>Anzahl Punkte</td><td>Static Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Elevation Change</td><td>Höhendifferenz</td><td>Dimension</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Downgrade pc</td><td>Neigung in % fallend</td><td>Number</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Upgrade pc</td><td>Neigung in % steigend</td><td>Number</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Upward Ratio Rise</td><td>Verhältnis steigend Höhe</td><td>Number</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Upward Ratio Run</td><td>Verhältnis steigend Strecke</td><td>Number</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Downward Ratio Rise</td><td>Verhältnis fallend Höhe</td><td>Number</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>Downward Ratio Run</td><td>Verhältnis fallend Strecke</td><td>Number</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ID Start</td><td>__invisible</td><td>Text</td></tr>
<tr><td>Grade CW</td><td>Gefälle Grundriss</td><td>ID End</td><td>__invisible</td><td>Text</td></tr>
</tbody></table></details>
<details><summary>Gefälledämmung</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>InsulationTypePop</td><td>Typ</td><td>Pop-Up</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>SlopeInsulationFirstPop</td><td>Grundwert 1</td><td>Pop-Up</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>SlopeInsulationSecondPop</td><td>Grundwert 2</td><td>Pop-Up</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Starthoehe</td><td>Starthöhe</td><td>Dimension</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Endhoehe</td><td>Endhöhe</td><td>Dimension</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>GefaelleInGrad</td><td>Gefälle in Grad</td><td>Angle</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>GefaelleInProzent</td><td>Gefälle in %</td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>WinkelHart</td><td>Winkel</td><td>Angle</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>LinkeRechteKante</td><td>Linke und Rechte Kante anzeigen</td><td>Boolean</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>SlopeInsulationFinish</td><td>Abschluss</td><td>Pop-Up</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>laenge</td><td>Länge</td><td>Static Text</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point01X</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point01Y</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point02X</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point02Y</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point03X</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point03Y</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point04X</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point04Y</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point05X</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point05Y</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point06X</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Point06Y</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Flags</td><td></td><td>Integer</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>offset</td><td></td><td>Number</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>Zeichnungsrichtung</td><td></td><td>Integer</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzClass</td><td></td><td>Class</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzClassOfPIO</td><td></td><td>Boolean</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzPenStyle</td><td></td><td>Pen Style</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzPenColors</td><td></td><td>Color</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzPenWeight</td><td></td><td>Pen Weight</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzOpacity</td><td></td><td>Integer</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzOpacityByClass</td><td></td><td>Boolean</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzPStyleByClass</td><td>Länge</td><td>Boolean</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzPenColorByClass</td><td>Länge</td><td>Boolean</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>UmgzPenWByClass</td><td>Länge</td><td>Boolean</td></tr>
<tr><td>Insulation Sloped CW</td><td>Gefälledämmung</td><td>FillClass</td><td>Länge</td><td>Class</td></tr>
</tbody></table></details>
<details><summary>Geländer/Zaun Classic</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Component</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Height Point 1</td><td>Höhe Punkt 1</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Height Point 2</td><td>Höhe Punkt 2</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Height Rail</td><td>Höhe Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Top Rail</td><td>Handlauf</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Top Rail ends at Posts</td><td>Handlauf endet bei Pfosten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Height Posts</td><td>Höhe Pfosten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Show Posts in 2D</td><td>2D-Darstellung mit Pfosten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Show Posts Excess End in 2D</td><td>2D-Darstellung mit Pfostenüberstand</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Show Hangings in 2D</td><td>2D-Ansicht mit Wandbefestigung</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Show Hangings Excess End in 2D</td><td>2D-Darstellung mit Wandbefestigungsüberstand</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Frame Bars</td><td>Füllung</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Vertices</td><td>Punkte</td><td>Integer</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Perim</td><td>Umfang</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Area</td><td>Fläche</td><td>Number</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Offset</td><td>Abstand zum Pfad</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Length</td><td>Länge</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D TopRail Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D TopRail Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D TopRail PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Post Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Post Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Post PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Bracket Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Bracket Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Bracket PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Panel Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Panel Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Panel PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D TopRail Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D TopRail Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D TopRail PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D TopRail Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D TopRail Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Post Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Post Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Post PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Post Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Post Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Frame Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Frame Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Frame PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Frame Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Frame Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Fascia Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Fascia Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Fascia PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D CrossTop Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D CrossTop Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D CrossTop PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D CrossBot Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D CrossBot Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D CrossBot PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Frame Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Frame Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Frame PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Bars Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Bars Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr2D Bars PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Bracket Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Bracket Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Bracket PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Bracket Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Bracket Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Fascia Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Fascia Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Fascia PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Fascia Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Fascia Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossTop Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossTop Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossTop PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossTop Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossTop Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossBot Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossBot Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossBot PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossBot Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D CrossBot Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Panel Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Panel Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Panel PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Panel Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D Panel Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsVer Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsVer Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsVer PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsVer Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsVer Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsHor Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsHor Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsHor PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsHor Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Attr3D BarsHor Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasFrame</td><td>Rahmen</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasPosts</td><td>Pfosten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasCrossbarTop</td><td>Obergurt</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasCrossbarBot</td><td>Untergurt</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasFasciaMount</td><td>SeitlicheKonsolePfosten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasWallBrackets</td><td>Wandkonsolen</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasBarsHoriz</td><td>StabHorizontal</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>HasBarsVert</td><td>StabVertikal</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostProfileName</td><td>Pfosten</td><td>Static Text</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostSymbolName</td><td>Pfosten</td><td>Static Text</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>RailingLengthIFC</td><td>IFC-Länge Geländer</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>RailingLength</td><td>Länge Geländer</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>RailingHeight</td><td>Höhe Geländer</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>RailingElevationArea</td><td>Fläche Geländer</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>RailingVerticesNumber</td><td>Anzahl Geländerecken</td><td>Integer</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailLength</td><td>Länge Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailVerticesNumber</td><td>Anzahl Handlaufecken</td><td>Integer</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailHeight</td><td>Höhe Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailProfileWidth</td><td>Profilbreite Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailProfileHeight</td><td>Profilhöhe Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailProfileDiam</td><td>Profildurchmesser Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TopRailSurfaceArea</td><td>Oberfläche Handlauf</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WallBracketLength</td><td>Länge Wandkonsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WallBracketHeight</td><td>Höhe Wandkonsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WallBracketsSurfaceArea</td><td>Oberfläche Wandkonsole</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WallBracketDistanceMax</td><td>Maximaler Abstand Wandkonsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostsTotalHeight</td><td></td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostProfileHeight</td><td>Profilhöhe Pfosten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostProfileWidth</td><td>Profilbreite Pfosten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostsTotalSurfaceArea</td><td>Gesamtoberfläche Pfosten</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PostDistanceMax</td><td>Abstand Pfosten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FaceMountHeight</td><td>Höhe seitliche Konsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FaceMountWidth</td><td>Breite seitliche Konsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FaceMountSurfaceArea</td><td>Oberfläche seitliche Konsole</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FaceMountDistanceMax</td><td>Maximaler Abstand seitliche Konsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarTopProfileHeight</td><td>Profilhöhe Obergurt</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarTopProfileWidth</td><td>Profilbreite Obergurt</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarTopTotalLength</td><td>Gesamtlänge Obergurt</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarTopTotalSurfaceArea</td><td>Gesamtoberfläche Obergurt</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarBottomProfileHeight</td><td>Profilhöhe Untergurt</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarBottomProfileWidth</td><td>Profilbreite Untergurt</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarBottomTotalLength</td><td>Gesamtlänge Untergurt</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>CrossbarBottomTotalSurfaceArea</td><td>Gesamtoberfläche Untergurt</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarVerticalAngle</td><td>Winkel vertikale Stäbe</td><td>Number</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarVerticalProfileHeight</td><td>Profilhöhe vertikale Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarVerticalProfileWidth</td><td>Profilbreite vertikale Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarVerticalTotalLength</td><td>Gesamtlänge vertikale Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarVerticalTotalSurfaceArea</td><td>Gesamtoberfläche vertikale Stäbe</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarHorizontalAngle</td><td>Winkel horizontale Stäbe</td><td>Number</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarHorizontalProfileHeight</td><td>Profilhöhe horizontale Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarHorizontalProfileWidth</td><td>Profilbreite horizontale Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarHorizontalTotalLength</td><td>Gesamtlänge horizontale Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>BarHorizontalTotalSurfaceArea</td><td>Gesamtoberfläche horizontale Stäbe</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FrameTotalWidth</td><td>Gesamtbreite Rahmen</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FrameTotalHeight</td><td>Gesamthöhe Rahmen</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FrameTotalPerimeter</td><td>Gesamtumfang Rahmen</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FrameProfileWidth</td><td>Profilbreite Rahmen</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FrameProfileHeight</td><td>Profilhöhe Rahmen</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>FrameTotalSurfaceArea</td><td>Gesamtoberfläche Rahmen</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PanelTotalWidth</td><td>Gesamtbreite Platten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PanelTotalHeight</td><td>Gesamthöhe Platten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PanelTotalArea</td><td>Gesamtfläche Platten</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PanelTotalSurfaceArea</td><td>Gesamtoberfläche Platten</td><td>Area</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>PanelProfileWidth</td><td>Profilbreite Platten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Profile</td><td>Profil Handlauf</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Profile Round Diam</td><td>Durchmesser rundes Profil Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Profile Octag Diam</td><td>Durchmesser achteckiges Profil Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Profile Width</td><td>Breite Profil Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Profile Height</td><td>Höhe Profil Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Profile Symbol</td><td>__CWD_DO_NOT_CHANGE</td><td>Static Text</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Height Mode</td><td>Höhe Handlauf bestimmt durch</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Extention At Start</td><td>Handlauf Überstand am Anfang</td><td>Radio Buttons</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Ext. At Start Horiz</td><td>Handlauf horiz. Überstand am Anfang</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Ext. At Start Sloping</td><td>Handlauf geneigter Überstand am Anfang</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Extention At End</td><td>Handlauf Überstand am Ende</td><td>Radio Buttons</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Ext. At End Horiz</td><td>Handlauf horiz. Überstand am Ende</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>TR Ext. At End Sloping</td><td>Handlauf geneigter Überstand am Ende</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Or Wallbracket</td><td>Pfosten oder Wandkonsole</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Height mode</td><td>Höhe Pfosten bestimmt durch</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Profile</td><td>Pfostenprofil</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Profile Round Diam</td><td>Durchmesser rundes Pfostenprofil</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Profile Octag Diam</td><td>Durchmesser achteckiges Pfostenprofil</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Profile Width</td><td>Breite Pfostenprofil</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Profile Height</td><td>Höhe Pfostenprofil</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post At Start</td><td>Pfosten am Anfang</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post At Start Distance</td><td>Abstand Pfosten am Anfang</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post At End</td><td>Pfosten am Ende</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post At End Distance</td><td>Abstand Pfosten am Ende</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post At Corner</td><td>Pfosten bei Eckpunkten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Doubled At Corner</td><td>2 Pfosten bei Eckpunkten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Dbl At Crnr Distance</td><td>Abstand 2 Pfosten bei Eckpunkten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Align Corner</td><td>Eckpfosten-Winkel ausrichten an</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Arrangement</td><td>Pfostenaufteilung</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Arrange Approx Dist</td><td>Ungefährer Abstand Pfosten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Arrange Fixed Dist</td><td>Fester Abstand Pfosten</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Arrange Number</td><td>Anzahl Pfosten</td><td>Integer</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Post Is Face Mount</td><td>Seitliche Konsole verwenden</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Face Mount Side</td><td>Ausrichtung</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Face Mount Height</td><td>Höhe seitliche Konsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Face Mount Distance</td><td>Abstand seitliche Konsole</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Wall Position</td><td>Wandposition Wandbefestigung</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Profile</td><td>Profil Wandbefestigung</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Profile Width</td><td>Breite Querschnitt Wandbefestigung</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Profile Height</td><td>Höhe Querschnitt Wandbefestigung</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB At Start</td><td>Wandbefestigung am Anfang</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB At Start Distance</td><td>Abstand Wandbefestigung am Anfang</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB At End</td><td>Wandbefestigung am Ende</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB At End Distance</td><td>Abstand Wandbefestigung am Ende</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Doubled At Corner</td><td>2 Wandbefestigungen an Ecke</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Dbl At Crnr Distance</td><td>Abstand 2 Wandbefestigungen an Ecke</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Arrangement</td><td>Aufteilung Wandbefestigung</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Arrange Approx Dist</td><td>Ungefährer Abstand Wandbefestigung</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Arrange Fixed Dist</td><td>Fester Abstand Wandbefestigung</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>WB Arrange Number</td><td>Anzahl der Konsolen</td><td>Integer</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Extends To</td><td>Füllung verlängern nach</td><td>Radio Buttons</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Extend at Start</td><td>Am Anfang verlängern</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Extend at End</td><td>Am Ende verlängern</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Type</td><td>Füllungstyp</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Members at Top</td><td>Elemente oben</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Members at Bottom</td><td>Elemente unten</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Members at Sides</td><td>Elemente seitlich</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Distance to TR</td><td>Abstand zum Handlauf</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Distance to Floor</td><td>Abstand zum Boden</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Shape</td><td>Form</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Shape Width</td><td>Breite Füllung</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Infill Shape Height</td><td>Höhe Füllung</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Bars 45deg rotated</td><td>Stäbe um 45° drehen</td><td>Boolean</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Bars Shape</td><td>Form Stäbe</td><td>Pop-Up</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Bars Shape Width</td><td>Breite Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Bars Shape Height</td><td>Höhe Stäbe</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>Bars Max Distance</td><td>Max. Abstand</td><td>Dimension</td></tr>
<tr><td>Railing CW</td><td>Geländer/Zaun Classic</td><td>_version</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
</tbody></table></details>
<details><summary>Geländeschnitt</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Version</td><td></td><td>Integer</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Type</td><td>__Type</td><td>Static Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>ResetMode</td><td>__ResetMode</td><td>Static Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>RefreshRequired</td><td>__RefreshRequired</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>GridAlignment</td><td>Ausrichtung</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>GridColumns</td><td>Anzahl Spalten</td><td>Integer</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>GridRows</td><td>Anzahl Zeilen</td><td>Integer</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>GridPaddingX</td><td>Abstand (X)</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>GridPaddingY</td><td>Abstand (Y)</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AxisName</td><td>Geländeschnittlinen-Name </td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Remark</td><td>Anmerkung</td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>HeaderShowAxisName</td><td>Achsname anzeigen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>HeaderShowRemark</td><td>Anmerkung anzeigen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>HeaderShowLocation</td><td>Stationierung anzeigen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AnnotationPositionX</td><td>__AnnotationPositionX</td><td>X Coordinate</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AnnotationPositionY</td><td>__AnnotationPositionY</td><td>Y Coordinate</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AnnotationShow</td><td>Flächenübersicht anzeigen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AnnotationResetPos</td><td>__AnnotationResetPos</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>DTMLayer</td><td></td><td>Layers Popup</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainView</td><td>Geländemodell</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainSampling</td><td>Geländevermessung</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainSamplingInterval</td><td>Intervall</td><td>Dimension</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainShowModifications</td><td>Auftrag-/Abtragsflächen anzeigen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainCompactMode</td><td>Kompakte Darstellung</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainTextView</td><td>Darstellung Maßzahlen</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainShowText</td><td>Maßzahlen anzeigen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainBaseZ</td><td>Basishöhe</td><td>Dimension</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainUniformBaseZ</td><td>Automatische Basishöhe</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainElevationOffset</td><td>Höhenversatz</td><td>Dimension</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainXOffset</td><td>Stationierungsbegin</td><td>Dimension</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainExaggeration</td><td>Überhöhung</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainMarginLeft</td><td>Profilrand Links</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainMarginRight</td><td>Profilrand Rechts</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainMarginTop</td><td>Profilrand Oben</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TerrainMarginBot</td><td>Profilrand Unten</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>CaptionColWidth</td><td>Breite Textspalte</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>CaptionSubColSize</td><td>Größe Textunterspalte (%)</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>HeaderRowHeight</td><td>Höhe Überschrift</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TransitionRowHeight</td><td>Höhe Übergangszeile</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>ElevationRowHeight</td><td>Höhe Höhenzeile</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>LocationRowHeight</td><td>Höhe Stionierungszeile</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TextCustomLabels</td><td>Beschriftungstexte anpassen</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>TextPadding</td><td>Textrand</td><td>Number</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_CurrentModel</td><td>Text Ist-Zustand</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_TargetModel</td><td>Text Soll-Zustand</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_BaseAlt</td><td>Text Basishöhe</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_Altitude</td><td>Text Höhe</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_Location</td><td>Text Stationierung</td><td>Pop-Up</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_CurrentModel_Custom</td><td>Eigener Text Ist-Zustand</td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_TargetModel_Custom</td><td>Eigener Text Soll-Zustand</td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_BaseAlt_Custom</td><td>Eigener Text Basishöhe</td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_Altitude_Custom</td><td>Eigener Text Höhe</td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>Text_Location_Custom</td><td>Eigener Text Stationierung</td><td>Text</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>InfoCurrentArea</td><td>Fläche Ist-Zustand</td><td>Area</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>InfoTargetArea</td><td>Fläche Soll-Zustand</td><td>Area</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>InfoBackfillArea</td><td>Auftrag</td><td>Area</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>InfoExcavationArea</td><td>Abtrag</td><td>Area</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AttrUseInstance</td><td>Attribute indiviudell</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AttrUseDTMProfils</td><td>Farbe für Ist- und Soll-Zustand des Geländemodells</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AttrUseDTMAreas</td><td>Farbe für Auf- und Abtrag des Geländemodells</td><td>Boolean</td></tr>
<tr><td>TerrainSection</td><td>Geländeschnitt</td><td>AttrUseDimAll</td><td>Attribute „Maßzahlen“ auch für Basishöhe und Flächenübersicht</td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Geländeschnittlinie</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Site Model Section Line CW</td><td>Geländeschnittlinie</td><td>Bezeichnung</td><td>Bezeichnung</td><td>Pop-Up</td></tr>
<tr><td>Site Model Section Line CW</td><td>Geländeschnittlinie</td><td>Geländeschnittlinie als Fläche</td><td>Geländeschnittlinie als Fläche</td><td>Boolean</td></tr>
<tr><td>Site Model Section Line CW</td><td>Geländeschnittlinie</td><td>Fläche</td><td>Fläche</td><td>Pop-Up</td></tr>
<tr><td>Site Model Section Line CW</td><td>Geländeschnittlinie</td><td>Überstand</td><td>Überstand</td><td>Dimension</td></tr>
<tr><td>Site Model Section Line CW</td><td>Geländeschnittlinie</td><td>ControlPoint01X</td><td>x</td><td>X Coordinate</td></tr>
<tr><td>Site Model Section Line CW</td><td>Geländeschnittlinie</td><td>ControlPoint01Y</td><td>y</td><td>Y Coordinate</td></tr>
</tbody></table></details>
<details><summary>Hilfslinie</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Guide Line CW</td><td>Hilfslinie</td><td>LengthInMM</td><td>Länge in mm</td><td>Number</td></tr>
<tr><td>Guide Line CW</td><td>Hilfslinie</td><td>Class</td><td></td><td>Text</td></tr>
<tr><td>Guide Line CW</td><td>Hilfslinie</td><td>methode</td><td>Methode</td><td>Integer</td></tr>
<tr><td>Guide Line CW</td><td>Hilfslinie</td><td>ShowDialog</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
</tbody></table></details>
<details><summary>Hyperlink</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>function</td><td>Funktion</td><td>Static Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>target</td><td>Ziel</td><td>Static Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>linkstate</td><td>Link Defekt</td><td>Static Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>EditableLabel</td><td>BearbeitbarName</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>EditableFunction</td><td>BearbeitbarFunktion</td><td>Pop-Up</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>EditableTarget</td><td>BearbeitbarZiel</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>EditableSaveAs</td><td>BearbeitbarSichernAls</td><td>Radio Buttons</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>LaunchDoubleClick</td><td></td><td>Boolean</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>SymbolName</td><td>SymbolName</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>ScaleYN</td><td>ScaleYN</td><td>Boolean</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>ScaleFactor</td><td>ScaleFactor</td><td>Number</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>Relativ</td><td>Relativ</td><td>Boolean</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>DocumentPath</td><td>DocumentPath</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>DocumentName</td><td>DocumentName</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>FolderPath</td><td>FolderPath</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>FolderName</td><td>FolderName</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>Url</td><td>Url</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>AppPath</td><td>AppPath</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>AppName</td><td>AppName</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>SavedView</td><td>SavedView</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>SavedViewIndex</td><td>SavedViewID</td><td>Integer</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>SheetLayer</td><td>SheetLayer</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>QRText</td><td>QRText</td><td>Text</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>QRWidth</td><td>QRWidth</td><td>Number</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>ClassCount</td><td>ClassCount</td><td>Integer</td></tr>
<tr><td>Hyperlink CW</td><td>Hyperlink</td><td>__NEW</td><td>ScaleYN</td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Kantenausbildung</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>LineLength</td><td>Länge</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Plattenstärke</td><td>Plattenstärke</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Ausführung</td><td>Ausführung</td><td>Pop-Up</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Falz Links</td><td>Falz Links</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Tiefe FL</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Höhe FL</td><td>Höhe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Falz rechts</td><td>Falz rechts</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>symmetrisch F</td><td>Symmetrisch</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Tiefe FR</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Höhe FR</td><td>Höhe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Nut links</td><td>Nut links</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Breite NL</td><td>Breite</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Tiefe NL</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Abstand NL</td><td>Abstand</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Nut rechts</td><td>Nut rechts</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>symmetrisch N</td><td>Symmetrisch</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Breite NR</td><td>Breite</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Tiefe NR</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Abstand NR</td><td>Abstand</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Gehrung links</td><td>Gehrung links</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Winkel 45° GL</td><td>Winkel 45°</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Gehrungstiefe GL</td><td>Gehrungstiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Gehrung rechts</td><td>Gehrung rechts</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Winkel 45° GR</td><td>Winkel 45°</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Gehrungstiefe GR</td><td>Gehrungstiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Kante</td><td>Kante</td><td>Pop-Up</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Kante gehrung</td><td>Kante</td><td>Pop-Up</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Radius</td><td>Radius</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Kantendicke</td><td>Kantendicke</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Fase links</td><td>Fase links</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Tiefe Fase links</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Fase rechts</td><td>Fase rechts</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Symmetrisch fase</td><td>Symmetrisch</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Tiefe  Fase rechts</td><td>Tiefe</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Massivholzkante (sch</td><td>Massivholzkante (schraffiert)</td><td>Boolean</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Reihenfolge</td><td>Reihenfolge</td><td>Pop-Up</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Beschriftung</td><td>Beschriftung</td><td>Text</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>Winkel Beschriftung</td><td>Winkel Beschriftung</td><td>Number</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>ControlPoint01X</td><td>beschr_x</td><td>X Coordinate</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>ControlPoint01Y</td><td>beschr_y</td><td>Y Coordinate</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>flags</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>startX</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>startY</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>endX</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>endY</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>AbschClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>AbschPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>BelagsClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>BelagsPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>BeschrifClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Edge Detail CW</td><td>Kantenausbildung</td><td>BeschrifFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
</tbody></table></details>
<details><summary>Lichtschacht</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Insert Position</td><td>Einfügepunkt</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Advertisement</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>2D Representation</td><td>2D Darstellung</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaX</td><td>∆x Außen</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaX inside</td><td>∆x Innen</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaY</td><td>∆y Außen</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaY inside</td><td>∆y Innen</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaZ</td><td>Höhe</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Top Bound Pop</td><td>Lichtschachtoberkante</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Bottom Bound Pop</td><td>Lichtschachtunterkante</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>WallThickness</td><td>Wanddicke</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>InnerEdge</td><td>Innenkante anzeigen</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>ShowGrid</td><td>2D-Darstellung</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Text</td><td>Text</td><td>Text</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>ControlPoint01X</td><td>x-Position Beschriftung </td><td>X Coordinate</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>ControlPoint01Y</td><td>y-Position Beschriftung </td><td>Y Coordinate</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>WallOverlap</td><td>Überlappung mit Wand</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>OverlapValue</td><td>Eigen</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>GridMeshX</td><td>Maschenbreite</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>GridMeshY</td><td>Maschenhöhe</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>GridMeshZ</td><td>Gitterdicke</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Grid2DPos</td><td>2D-Position</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>GridDistHorizontal</td><td>Abstand Rechts</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>GridDistVertical</td><td>Abstand Unten</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>TextPosX</td><td>Textposition x</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>TextPosY</td><td>Textposition y</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FlipState</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>SupportEdge</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DistGridWall3D</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>AktRow</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>InsertPositionOld</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaXOI</td><td>∆x Bezug</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaYOI</td><td>∆y Bezug</td><td>Pop-Up</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>RotationOld</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FLabelPosPrio</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FCreatePreview</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FCreatePreviewGrid</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FInsertFirstTime</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FSwitchLeftRight</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FSwitchTopBottom</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FClickedFlipButton</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FCreateTempPreview</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>FEfpTopBottom</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand2dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand2dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand2dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter2dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter2dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter2dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Ikante2dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Ikante2dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden2dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden2dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden2dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Beschrift2dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Beschrift2dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand3dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand3dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand3dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand3dMaterial</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Wand3dTexture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter3dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter3dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter3dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter3dMaterial</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Gitter3dTexture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden3dClass</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden3dFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden3dPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden3dMaterial</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>Boden3dTexture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>TopOffset</td><td>Abstand Oberkante</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>BottomOffset</td><td>Abstand Unterkante</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>DeltaZ inside</td><td>Höhe innen</td><td>Dimension</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>NetArea</td><td>Oberfläche netto</td><td>Area</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>OuterSurfaceNetArea</td><td>Außenfläche netto</td><td>Area</td></tr>
<tr><td>Light Well CW</td><td>Lichtschacht</td><td>NetVolume</td><td>Volumen netto</td><td>Volume</td></tr>
</tbody></table></details>
<details><summary>Maßstabsbalken</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarStyle</td><td>Stil</td><td>Pop-Up</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarBackgrd</td><td>Weiße Hintergrundfüllung</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarLDef</td><td>Definition Länge</td><td>Pop-Up</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarLength</td><td>Länge</td><td>Number</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarLengthCalc</td><td>Länge</td><td>Dimension</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarHeight</td><td>Höhe</td><td>Number</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarUseHeightFactor</td><td>Seitenverhältnis sperren</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarNoOfSegments</td><td>Anzahl</td><td>Number</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarHalfSegment</td><td>Ersten Abschnitt</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarHalfSegmentTo</td><td>Ersten Abschnitt</td><td>Pop-Up</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarSplitSegmentToTen</td><td>Feinunterteilung links hinzufügen</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarTitle</td><td>Titel</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarTitleText</td><td>Titel anzeigen</td><td>Text</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>CenterTitle</td><td>Text zentriert</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarLable</td><td>Segmentbeschriftung</td><td>Pop-Up</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarTextUp</td><td>Beschriftungsposition</td><td>Pop-Up</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarSuffix</td><td>Nachgestellt</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarSuffixText</td><td>Text Nachgestellt</td><td>Text</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ControlPoint01X</td><td>Pos Titel X</td><td>X Coordinate</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ControlPoint01Y</td><td>Pos Titel Y</td><td>Y Coordinate</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarRelationHeightLength</td><td>Faktor Höhe</td><td>Number</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarPreview</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarScaleTextSize</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Scalebar CW</td><td>Maßstabsbalken</td><td>ScaleBarScale</td><td>__CWD_DO_NOT_CHANGE</td><td>Number</td></tr>
</tbody></table></details>
<details><summary>Mengennachweis</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Dokumentationsart</td><td>Dokumentationsart</td><td>Pop-Up</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Dokumentationsart3D</td><td>Dokumentationsart</td><td>Pop-Up</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Flaeche mit einf Doku</td><td>Fläche</td><td>Radio Buttons</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Fläche</td><td>Fläche</td><td>Radio Buttons</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Strecke</td><td>Strecke</td><td>Radio Buttons</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Berechnung</td><td>Berechnung</td><td>Pop-Up</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Dreiecke nach Heron</td><td>Dreiecke nach Heron</td><td>Boolean</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Dokumentation des Umfangs anlegen</td><td>Dokumentation des Umfangs anlegen</td><td>Boolean</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Fläche beschriften</td><td>Fläche beschriften</td><td>Boolean</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>x_Beschr_Position</td><td>ControlPoint01X</td><td>X Coordinate</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>y_Beschr_Position</td><td>ControlPoint01Y</td><td>Y Coordinate</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Schichtstaerke</td><td>Schichtstärke</td><td>Dimension</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Kommentar</td><td>Kommentar</td><td>Text</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Fläche Startobjekt</td><td>Fläche Startobjekt</td><td>Number</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Abgerechnet</td><td>Abgerechnet</td><td>Boolean</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Angebotsmenge</td><td>Angebotsmenge</td><td>Boolean</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Perim</td><td>Umfang</td><td>Static Text</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Area</td><td>Fläche</td><td>Static Text</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_EdgePenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_TrianglePenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_ArchesPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_CirclesPenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_LabelStampsFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_LabelDotsFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_LabelEdgesFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_LabelArchesFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_LabelCirclesFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>Attr_LabelSubareaFill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Proof of Masses CW</td><td>Mengennachweis</td><td>_version</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
</tbody></table></details>
<details><summary>Pflanze</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>Eigener Name</td><td>Eigener Name</td><td>Static Text</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>Beschriftung anzeige</td><td></td><td>Boolean</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>Text</td><td></td><td>Text</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>ControlPoint01X</td><td></td><td>X Coordinate</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>ControlPoint01Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>ControlPoint02X</td><td></td><td>X Coordinate</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>ControlPoint02Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>PflanzenDB CW</td><td>Pflanze</td><td>UseDocShadow</td><td></td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Pflanze (Fläche)</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Eigener Name</td><td>Eigener Name</td><td>Static Text</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Beschriftung anzeige</td><td></td><td>Boolean</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Text</td><td></td><td>Text</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>ControlPoint01X</td><td></td><td>X Coordinate</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>ControlPoint01Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>ControlPoint02X</td><td></td><td>X Coordinate</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>ControlPoint02Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>DocShadow</td><td></td><td>Boolean</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>CountPlant</td><td></td><td>Static Text</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Area</td><td></td><td>Static Text</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Perimeter</td><td></td><td>Static Text</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>CountMeter2</td><td></td><td>Static Text</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Modifier</td><td></td><td>Number</td></tr>
<tr><td>PflanzenDB Pfad CW</td><td>Pflanze (Fläche)</td><td>Mixed Plant</td><td></td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Pflanze (Reihe)</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>Eigener Name</td><td>Eigener Name</td><td>Static Text</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>Beschriftung anzeige</td><td></td><td>Boolean</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>Text</td><td></td><td>Text</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>ControlPoint01X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>ControlPoint01Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>ControlPoint02X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>ControlPoint02Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>UseDocShadow</td><td></td><td>Boolean</td></tr>
<tr><td>Reihenpflanzung Regen CW</td><td>Pflanze (Reihe)</td><td>CountPlant</td><td></td><td>Static Text</td></tr>
</tbody></table></details>
<details><summary>Pflanze (Verband)</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>Eigener Name</td><td>Eigener Name</td><td>Static Text</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>Beschriftung anzeige</td><td></td><td>Boolean</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>Text</td><td></td><td>Text</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>ControlPoint01X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>ControlPoint01Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>ControlPoint02X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>ControlPoint02Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>UseDocShadow</td><td></td><td>Boolean</td></tr>
<tr><td>Verbandspflanzung Regen CW</td><td>Pflanze (Verband)</td><td>CountPlant</td><td></td><td>Static Text</td></tr>
</tbody></table></details>
<details><summary>Profillinie</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>Version</td><td></td><td>Integer</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>Name</td><td>Name</td><td>Text</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ProfileCount</td><td>Anzahl Profile</td><td>Static Text</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>StartPos</td><td>Startpunkt Profile</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>EndPos</td><td>Endpunkt Profile</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>StartValue</td><td>Startwert</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ShowProfiles</td><td>Profile anzeigen</td><td>Boolean</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ResetProfiles</td><td>Profile zurücksetzen</td><td>Boolean</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>OnlyFeaturedProfiles</td><td>Regelprofile ausblenden</td><td>Boolean</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ProfileDistance</td><td>Abstand Profile</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ProfileSizeLeft</td><td>Profillänge links</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ProfileSizeRight</td><td>Profillänge rechts</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ShowLabels</td><td>Profile beschriften</td><td>Boolean</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>ResetLabels</td><td>Beschriftung zurücksetzen</td><td>Boolean</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>LabelsDistance</td><td>Beschriftungsabstand</td><td>Dimension</td></tr>
<tr><td>ProfileAxis</td><td>Profillinie</td><td>LabelsPrefix</td><td>Beschriftung vorangestellt</td><td>Text</td></tr>
</tbody></table></details>
<details><summary>Querprofile</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Version</td><td></td><td>Integer</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Type</td><td>__Type</td><td>Static Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ResetMode</td><td>__ResetMode</td><td>Static Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>RefreshRequired</td><td>__RefreshRequired</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>GridAlignment</td><td>Ausrichtung Querprofile</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>GridColumns</td><td>Anzahl Spalten</td><td>Integer</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>GridRows</td><td>Anzahl Zeilen</td><td>Integer</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>GridPaddingX</td><td>Abstand Querprofile (X)</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>GridPaddingY</td><td>Abstand Querprofile (Y)</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>GridLocked</td><td>__GridLocked</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>UniformWidthLeft</td><td>__UniformWidthLeft</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>UniformWidthRight</td><td>__UniformWidthRight</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ProfileOffset</td><td>__ProfileOffset</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ProfilePositionX</td><td>__ProfilePositionX</td><td>X Coordinate</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ProfilePositionY</td><td>__ProfilePositionY</td><td>Y Coordinate</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ProfileDimension</td><td>Stationierung</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ProfilePrefix</td><td>__ProfilePrefix</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AxisName</td><td>Profillinienname</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Remark</td><td>Anmerkung</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>DTMLayer</td><td>Ebene des Geländemodells</td><td>Layers Popup</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>HeaderShowAxisName</td><td>Achsname anzeigen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>HeaderShowRemark</td><td>Anmerkung anzeigen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>HeaderShowLocation</td><td>Stationierung anzeigen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AnnotationPositionX</td><td>__AnnotationPositionX</td><td>X Coordinate</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AnnotationPositionY</td><td>__AnnotationPositionY</td><td>Y Coordinate</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AnnotationShow</td><td>Flächenübersicht anzeigen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AnnotationResetPos</td><td>__AnnotationResetPos</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainView</td><td>Geländemodell</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainSampling</td><td>Geländevermessung</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainSamplingInterval</td><td>Intervall</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainShowModifications</td><td>Auftrag-/Abtragsflächen anzeigen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainCompactMode</td><td>Kompakte Darstellung</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainTextView</td><td>Darstellung Maßzahlen</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainShowText</td><td>Maßzahlen anzeigen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainBaseZ</td><td>Basishöhe</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainUniformBaseZ</td><td>Automatische Basishöhe</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainElevationOffset</td><td>Höhenversatz</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainExaggeration</td><td>Überhöhung</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainMarginLeft</td><td>Profilrand Links</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainMarginRight</td><td>Profilrand Rechts</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainMarginTop</td><td>Profilrand Oben</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainMarginBot</td><td>Profilrand Unten</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TerrainUniformWidth</td><td>Einheitliche Breite</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>CaptionColWidth</td><td>Breite Textspalte</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>CaptionSubColSize</td><td>Größe Textunterspalte (%)</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>HeaderRowHeight</td><td>Höhe Überschrift</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TransitionRowHeight</td><td>Höhe Übergangszeile</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>ElevationRowHeight</td><td>Höhe Höhenzeile</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>LocationRowHeight</td><td>Höhe Stionierungszeile</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TextCustomLabels</td><td>Beschriftungstexte anpassen</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>TextPadding</td><td>Textrand</td><td>Number</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_CurrentModel</td><td>Text Ist-Zustand</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_TargetModel</td><td>Text Soll-Zustand</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_BaseAlt</td><td>Text Basishöhe</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_Altitude</td><td>Text Höhe</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_Location</td><td>Text Stationierung</td><td>Pop-Up</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_CurrentModel_Custom</td><td>Eigener Text Ist-Zustand</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_TargetModel_Custom</td><td>Eigener Text Soll-Zustand</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_BaseAlt_Custom</td><td>Eigener Text Basishöhe</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_Altitude_Custom</td><td>Eigener Text Höhe</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>Text_Location_Custom</td><td>Eigener Text Stationierung</td><td>Text</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoCurrentArea</td><td>Fläche Ist-Zustand</td><td>Area</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoTargetArea</td><td>Fläche Soll-Zustand</td><td>Area</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoBackfillArea</td><td>Auftrag</td><td>Area</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoExcavationArea</td><td>Abtrag</td><td>Area</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoQuantityBackfill</td><td>Masse Auftrag</td><td>Volume</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoQuantityExcavation</td><td>Masse Abtrag</td><td>Volume</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoProfileCount</td><td>Anzahl Querprofile</td><td>Integer</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoProfileIndex</td><td>Profile Nr.</td><td>Integer</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>InfoProfileDistance</td><td>Profilabstand</td><td>Dimension</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AttrUseInstance</td><td>Attribute indiviudell</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AttrUseDTMProfils</td><td>Farbe für Ist- und Soll-Zustand des Geländemodells</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AttrUseDTMAreas</td><td>Farbe für Auf- und Abtrag des Geländemodells</td><td>Boolean</td></tr>
<tr><td>CrossProfile</td><td>Querprofile</td><td>AttrUseDimAll</td><td>Attribute „Maßzahlen“ auch für Basishöhe und Flächenübersicht</td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Rampe</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampForm</td><td>Rampe Form</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampDirection</td><td>Rampe Richtung</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBuildingStyle</td><td>Rampe Bauart</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampWidth</td><td>Rampe Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampHeight</td><td>Rampe Höhe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampCalculate</td><td>Berechne aus</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampLength</td><td>Rampe Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampSlope</td><td>Rampe Steigung in Prozent</td><td>Number</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampAngle</td><td>Rampe Steigung in Grad</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampRail</td><td>Geländer</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBowAngle</td><td>Winkel Bogen</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBowRadius</td><td>Bogenradius</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFirstLength</td><td>Länge Gerade 1</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampSecondLength</td><td>Länge Gerade 2</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFirstOffset</td><td>Überstand 1</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampSecondOffset</td><td>Überstand 2</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>pop_gw_anz</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>rampThickness</td><td>Belagsdicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Length Platform</td><td>Podest Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Define Position of Platform</td><td>Position Podest definieren</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Height Position of Platform</td><td>Podest über Höhe definieren</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Length Position of Platform</td><td>Podest über Länge definieren</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Grade Change</td><td>Neigungswechsel</td><td>Boolean</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Height Railing</td><td>Geländer Höhe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Profile Post and Top Rail</td><td>Geländer Form Pfosten + Handlauf</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Diameter Post</td><td>Breite Durchmesser Pfosten</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Diameter Top Rail</td><td>Geländer Durchmesser</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Top Rail Position</td><td>Geländerposition</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Distance Top Rail To Ramp</td><td>Pfosten Abstand zur Rampe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Add additional Posts</td><td>Zusätzliche Pfosten einfügen</td><td>Boolean</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>About Distance Posts</td><td>Pfosten Abstand ca.</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Left Spur Post and Sidewalk</td><td>Radabweiser Gehweg Links</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Right Spur Post and Sidewalk</td><td>Radabweiser Gehweg Rechts</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Spur Post Left Height</td><td>Radabweiser links Höhe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Spur Post Right Height</td><td>Radabweiser rechts Höhe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Spur Post Left Width</td><td>Radabweiser links Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Spur Post Right Width</td><td>Radabweiser rechts Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Sidewalk Left Height</td><td>Gehweg links Höhe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Sidewalk Right Height</td><td>Gehweg rechts Höhe</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Sidewalk Left Width</td><td>Gehweg links Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Sidewalk Right Width</td><td>Gehweg rechts Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Text 1</td><td>Text 1</td><td>Static Text</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Text 2</td><td>Text 2</td><td>Static Text</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Text 3</td><td>Text 3</td><td>Static Text</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Display Rise</td><td>Steigungsanzeige</td><td>Pop-Up</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Grade Change Start</td><td>Neigungswechsel Länge Anfang</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Grade Change End</td><td>Neigungswechsel Länge Ende</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Grade Change Rise Center</td><td>Neigungswechsel Steigung Mitte</td><td>Number</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>GrossArea</td><td>Rampe Fläche Brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>NetArea</td><td>Rampe Fläche Netto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>GrossVolume</td><td>Rampe Volumen Brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>NetVolume</td><td>Rampe Volumen Netto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Thickness</td><td>Rampe Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Area</td><td>Rampe Fläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>FootprintArea</td><td>Rampe Fläche Projiziert</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampClearWidth</td><td>Rampe lichte Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1Length</td><td>Rampenlauf 1 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1Thickness</td><td>Rampenlauf 1 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1GrossArea</td><td>Rampenlauf 1 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1NetArea</td><td>Rampenlauf 1 Fläche netto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1GrossVolume</td><td>Rampenlauf 1 Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1NetVolume</td><td>Rampenlauf 1 Volumen netto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1ClearDistance</td><td>Rampenlauf 1 lichte Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1Slope</td><td>Rampenlauf 1 Neigung</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1CounterSlope</td><td>Rampenlauf 1 Gegenneigung</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight1FootprintArea</td><td>Rampenlauf 1 Grundfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2Length</td><td>Rampenlauf 2 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2Thickness</td><td>Rampenlauf 2 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2GrossArea</td><td>Rampenlauf 2 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2NetArea</td><td>Rampenlauf 2 Fläche netto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2GrossVolume</td><td>Rampenlauf 2 Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2NetVolume</td><td>Rampenlauf 2 Volumen netto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2ClearDistance</td><td>Rampenlauf 2 lichte Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2Slope</td><td>Rampenlauf 2 Neigung</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2CounterSlope</td><td>Rampenlauf 2 Gegenneigung</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight2FootprintArea</td><td>Rampenlauf 2 Grundfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3Length</td><td>Rampenlauf 3 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3Thickness</td><td>Rampenlauf 3 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3GrossArea</td><td>Rampenlauf 3 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3NetArea</td><td>Rampenlauf 3 Fläche netto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3GrossVolume</td><td>Rampenlauf 3 Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3NetVolume</td><td>Rampenlauf 3 Volumen netto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3ClearDistance</td><td>Rampenlauf 3 lichte Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3Slope</td><td>Rampenlauf 3 Neigung</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3CounterSlope</td><td>Rampenlauf 3 Gegenneigung</td><td>Angle</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlight3FootprintArea</td><td>Rampenlauf 3 Grundfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RailingRightLength</td><td>Geländer links Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RailingLeftLength</td><td>Geländer rechts Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RailingRightArea</td><td>Geländer rechts Fläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RailingLeftArea</td><td>Geländer links Fläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1Thickness</td><td>Podest Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1Depth</td><td>Podest Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1Perimeter</td><td>Podest Umfang</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1GrossArea</td><td>Podest Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1NetArea</td><td>Podest Fläche netto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1GrossVolume</td><td>Podest Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Landing1NetVolume</td><td>Podest Volumen netto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeftLength</td><td>Gehweg links Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeftThickness</td><td>Gehweg links Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeftGrossVolume</td><td>Gehweg links Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeftOuterSurface</td><td>Gehweg links Oberfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeftLength</td><td>Radabweiser links Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeftGrossVolume</td><td>Radabweiser links Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeftOuterSurface</td><td>Radabweiser links Oberfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRightLength</td><td>Gehweg rechts Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRightThickness</td><td>Gehweg rechts Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRightGrossVolume</td><td>Gehweg rechts Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRightOuterSurface</td><td>Gehweg rechts Oberfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRightLength</td><td>Radabweiser rechts Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRightGrossVolume</td><td>Radabweiser rechts Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRightOuterSurface</td><td>Radabweiser rechts Oberfläche</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>CoveringWidth</td><td>Belag Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>CoveringGrossVolume</td><td>Belag Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>CoveringGrossArea</td><td>Belag Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody1Length</td><td>Rampenlaufkörper 1 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody1Width</td><td>Rampenlaufkörper 1 Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody1Thickness</td><td>Rampenlaufkörper 1 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody1GrossVolume</td><td>Rampenlaufkörper 1 Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody1GrossArea</td><td>Rampenlaufkörper 1 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody1FootprintArea</td><td>Rampenlaufkörper 1 Fläche projiziert</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody2Length</td><td>Rampenlaufkörper 2 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody2Width</td><td>Rampenlaufkörper 2 Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody2Thickness</td><td>Rampenlaufkörper 2 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody2GrossVolume</td><td>Rampenlaufkörper 2 Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody2GrossArea</td><td>Rampenlaufkörper 2 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody2FootprintArea</td><td>Rampenlaufkörper 2 Fläche projiziert</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody3Length</td><td>Rampenlaufkörper 3 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody3Width</td><td>Rampenlaufkörper 3 Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody3Thickness</td><td>Rampenlaufkörper 3 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody3GrossVolume</td><td>Rampenlaufkörper 3 Volumen brutto</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody3GrossArea</td><td>Rampenlaufkörper 3 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampFlightBody3FootprintArea</td><td>Rampenlaufkörper 3 Fläche projiziert</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>LandingBody1Length</td><td>Rampenpodestkörper 1 Länge</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>LandingBody1Width</td><td>Rampenpodestkörper 1 Breite</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>LandingBody1Thickness</td><td>Rampenpodestkörper 1 Dicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>LandingBody1GrossVolume</td><td>Rampenpodestkörper 1 Volumen</td><td>Volume</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>LandingBody1GrossArea</td><td>Rampenpodestkörper 1 Fläche brutto</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>LandingBody1FootprintArea</td><td>Rampenpodestkörper 1 Fläche projiziert</td><td>Area</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Ramp2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Ramp2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Ramp2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedRamp2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedRamp2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedRamp2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedRailing2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedRailing2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedRailing2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>HorCut2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>HorCut2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>HorCut2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedHorCut2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedHorCut2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedHorCut2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Label2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Label2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Triangle2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Triangle2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Triangle2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedTriangle2D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedTriangle2D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>DashedTriangle2D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBody3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBody3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBody3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBody3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampBody3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampCovering3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampCovering3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampCovering3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampCovering3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RampCovering3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeft3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeft3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeft3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeft3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostLeft3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRight3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRight3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRight3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRight3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SpurPostRight3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeft3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeft3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeft3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeft3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkLeft3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRight3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRight3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRight3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRight3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>SidewalkRight3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing3D Class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing3D Fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing3D PenStyle</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing3D Material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>Railing3D Texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RaCreateLayer</td><td>Belag erzeugen</td><td>Boolean</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>RaPlateTickness</td><td>Plattendicke</td><td>Dimension</td></tr>
<tr><td>Ramp CW</td><td>Rampe</td><td>_version</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
</tbody></table></details>
<details><summary>Raum</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Space</td><td>Raum</td><td>Config</td><td>__NNA_DO_NOT_CHANGE</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Name</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Number</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Occupancy</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Occupancy Type</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Calc Dims</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Length</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Width</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Room Dimensions</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Proposed Area</td><td>__NNA_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>Align</td><td>__NNA_DO_NOT_CHANGE</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Text Rotation</td><td>__NNA_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>Decimals</td><td>__NNA_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>Underline Name</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Number Box</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Additional Data</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Auto-Boundary</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Poly</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Boundary Display</td><td>__NNA_DO_NOT_CHANGE</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show 3D Detail</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Volume Display</td><td>__NNA_DO_NOT_CHANGE</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Extrusion Height</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Floor2Floor Height</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish Floor Elev</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Space Type</td><td>__NNA_DO_NOT_CHANGE</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Perim</td><td>Nettoumfang</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Area</td><td>Nettofläche</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>Volume</td><td>Nettovolumen</td><td>Volume</td></tr>
<tr><td>Space</td><td>Raum</td><td>Gross Perim</td><td>Bruttoumfang</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Gross Area</td><td>Bruttofläche</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>Gross Volume</td><td>Bruttovolumen</td><td>Volume</td></tr>
<tr><td>Space</td><td>Raum</td><td>Name Text Size</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Number Text Size</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Dims Text Size</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Matrix Order</td><td>__NNA_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>On Schedule</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Use IFC Data</td><td></td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Use GSA Data</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint01X</td><td>__NNA_DO_NOT_CHANGE</td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint01Y</td><td>__NNA_DO_NOT_CHANGE</td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint02X</td><td>__NNA_DO_NOT_CHANGE</td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint02Y</td><td>__NNA_DO_NOT_CHANGE</td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>Floor Finish</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Base Material</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>North Wall Finish</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>East Wall Finish</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>South Wall Finish</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>West Wall Finish</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Ceiling Material</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Remarks</td><td>Belag Anmerkung (angezeigt)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Floor Key</td><td>Pos. Nr. Boden</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Base Key</td><td>Pos. Nr. Leiste</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>North Key</td><td>Pos. Nr. Norden</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>East Key</td><td>Pos. Nr. Osten</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>South Key</td><td>Pos. Nr. Süden</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>West Key</td><td>Pos. Nr. Westen</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Ceiling Key</td><td>Pos. Nr. Decke</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>InteriorOrExterior</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>DefaultCeilingHeight</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>DefaultGrossHeight</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>DefaultFinishFloorElev</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Fields2DDisplay</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Tags2DDisplay</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Occ_Org_Name</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Occ_Org_Code</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Occ_Org_Abbrev</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Occ_Org_SubOrg</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Occ_Org_BillID</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_STAR_SpaceType</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_STAR_SpaceCaty</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_BOMA_SpaceCaty</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Zone_Security</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Zone_Preservation</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Zone_Privacy</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA_Zone_ProjSpecific</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>__Version</td><td>__NNA_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>ActiveClass</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>NotationClass</td><td>__NNA_DO_NOT_CHANGE</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Old Matrix Order</td><td>__NNA_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>Old FFE</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Dims</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Proposed Area</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Area</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Occupancy</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Show Volume</td><td>__NNA_DO_NOT_CHANGE</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA BIM Perim</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>GSA BIM Area</td><td>__NNA_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>Custom Perim</td><td>__NNA_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>Custom Area</td><td>__NNA_DO_NOT_CHANGE</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Number</td><td>Raumnummer</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Number Style</td><td>Raumnummern-Art</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Space Type</td><td>Raumart</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_NameDisplay</td><td>Raumname (angezeigt)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Name</td><td>Raumname</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Space Name Cust</td><td>Raumname (eigene Angabe)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Occ Type Disp</td><td>Nutzungstyp (angezeigt)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Occ Type</td><td>Nutzungstyp</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Occ Custom Type</td><td>Nutzungstyp (eigene Angabe)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_OccupantDisplay</td><td>Nutzungsart (angezeigt)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Occupant</td><td>Nutzungsart</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Occupant Custom</td><td>Nutzungsart (eigene Angabe)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Occupancy Type</td><td>Benutzername</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Proposed Area</td><td>Fläche geplant</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Auto-Boundary</td><td>Raumgröße automatisch anpassen</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Show Poly</td><td>2D-Raumfläche anzeigen</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Boundary2DClass</td><td>2D Raumklasse</td><td>Classes Popup</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Boundary Display</td><td>Fläche Brutto oder Netto</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetBoundOffsetFromInnerWall</td><td>Fläche Netto Versatz von Wandinnenseite</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetBoundConsiderWallProjections</td><td>Fläche Netto Wandnischen und -vorsprünge berücksichtigen</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetBoundConsiderColumns</td><td>Fläche Netto Stützen berücksichtigen</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetBoundConsiderNiches</td><td>Fläche Netto Tür- und Fensternischen berücksichtigen</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Gross Definition</td><td>Fläche Brutto Definition</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Net_Modi</td><td>Flächenmodifikator Netto (%)</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Gross_Modi</td><td>Flächenmodifikator Brutto (%)</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Area</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionArea</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionAreaNum</td><td>Fläche Abzug</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>MeasuredNetArea</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>MeasuredNetAreaNum</td><td>Fläche Netto gemessen</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Gross Area</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Perim</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Gross Perim</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Calc Dims</td><td>Raumabmessung automatisch</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Length</td><td>Raumabmessung Länge</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Width</td><td>Raumabmessung Breite</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Room Dimensions</td><td>Raumabmessungen</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Glazing Area</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Glazing Area Num</td><td>Glasfläche</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>Glazing Area Ratio</td><td>Glasflächenverhältnis (%)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Glazing Area Ratio F</td><td>Glasflächenverhältnis (Bruch)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Window Area</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Window Area Num</td><td>Fensterfläche</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>Window Area Ratio</td><td>Fensterflächenverhältnis (%)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Window Area Ratio F</td><td>Fensterflächenverhältnis (Bruch)</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Show 3D Detail</td><td>3D-Raumvolumen anzeigen</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Boundary3DClass</td><td>3D Raumklasse</td><td>Classes Popup</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Volume Display</td><td>Volumen Brutto oder Netto</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Net Height</td><td>Netto-Raumhöhe</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Gross Height</td><td>Brutto-Raumhöhe</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Volume</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Gross Volume</td><td>__invisible</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Display Stamp</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Stamp Class</td><td>__Invisible</td><td>Classes Popup</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Default Stamp</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Angle</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_On Schedule</td><td>Beläge verwenden</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Matrix Order</td><td>Reihenfolge</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Room ID</td><td>Raum ID</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Formula</td><td>Formel</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Region</td><td>Region</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Position</td><td>Position</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Building</td><td>Gebäude</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Floor</td><td>Stockwerk</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Enclose</td><td>Umschließungsart</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Lamp (ct)</td><td>Beleuchtung Lampe (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Lamp Type</td><td>Beleuchtung Lampe (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Luminaries (ct)</td><td>Beleuchtung Leuchten (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Luminaries Type</td><td>Beleuchtung Leuchten (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Air Outlet (ct)</td><td>Luftauslässe (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Air Outlet Type</td><td>Luftauslässe (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Exhaust Fans (ct)</td><td>Abluftgebläse (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Exhaust Fan Type</td><td>Abluftgebläse (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Smoke Det.</td><td>Brandmelder (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Sprinkler Sys (ct)</td><td>Sprinkler (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Floor Outlets (ct)</td><td>Bodenauslässe (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Floor Outlets vol</td><td>Bodenauslässe (m3/h)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Heaters (ct)</td><td>Heizkörper (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Heaters Type</td><td>Heizkörper (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Outlets (ct)</td><td>Steckdose (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Outlets Type</td><td>Steckdose (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Light Switches (ct)</td><td>Beleuchtung Lichtschalter (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Light Switch Type</td><td>Beleuchtung Lichtschalter (Typ)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Phone Box (ct)</td><td>Telefonbuchsen (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Network (ct)</td><td>Netzwerkbuchsen (Anzahl)</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Room Control Mod</td><td>Raumkontrollmodul</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Number of Occu</td><td></td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Metabolic Rate</td><td>Umsatz</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Computer Load</td><td>Last Computer</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Equipment Loads</td><td>Last Betriebseinrichtung</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Other Loads</td><td>Last Diverses</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_DHW/Person/Day</td><td>Warmwasser/Person/Tag</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Illumination</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Heating Setpoints</td><td>Sollwert Heizung</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Cooling Setpoints</td><td>Sollwert Kühlung</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Special Ventil</td><td>Spezielle Ventilationen</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Illuminat Requir</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 1</td><td>Zusatz 01</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 2</td><td>Zusatz 02</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 3</td><td>Zusatz 03</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 4</td><td>Zusatz 04</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 5</td><td>Zusatz 05</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 6</td><td>Zusatz 06</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 7</td><td>Zusatz 07</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 8</td><td>Zusatz 08</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 9</td><td>Zusatz 09</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_User-Def Info 10</td><td>Zusatz 10</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint03X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint03Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint04X</td><td>Modifikator PosX</td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint04Y</td><td>Modifikator PosX</td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Old Matrix Order</td><td>Matrix-Reihenfolge Alt</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_GSA_Oc_Org_Name</td><td>GSA-Belegung OmniClass</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_GSA_Oc_Org_Code</td><td>GSA-Belegung Kategorie</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_GSA_Oc_Org_Abbre</td><td>GSA-Belegung Typ</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_GSA_Oc_Org_SubOr</td><td>GSA-Belegung Bewohner</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Zone_1</td><td>Zugewiesene Zone 1</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Zone_2</td><td>Zugewiesene Zone 2</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Zone_3</td><td>Zugewiesene Zone 3</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Zone_4</td><td>Zugewiesene Zone 4</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Zone_5</td><td>Zugewiesene Zone 5</td><td>Static Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>CheckContPt</td><td></td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint05X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint05Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint06X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint06Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Display Stamp2</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Stamp2 Class</td><td>__Invisible</td><td>Classes Popup</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Default Stamp2</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Angle2</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Display Stamp3</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Stamp3 Class</td><td>__Invisible</td><td>Classes Popup</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Default Stamp3</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>11_Angle3</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>DispLeaderLine1</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>StartLeaderLine1</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>EndLeaderLine1</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>DispLeaderLine2</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>StartLeaderLine2</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>EndLeaderLine2</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>DispLeaderLine3</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>StartLeaderLine3</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>EndLeaderLine3</td><td>__Invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint07X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint07Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint08X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint08Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint09X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>ControlPoint09Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Space</td><td>Raum</td><td>EqualPtEndLabel1</td><td></td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>EqualPtEndLabel2</td><td></td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>EqualPtEndLabel3</td><td></td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish Ceiling</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish WallN</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish WallE</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish WallS</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish WallW</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish Base</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish Floor</td><td>__invisible</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>Finish Remarks</td><td>Belag Anmerkung</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>EnergyInclude</td><td>Energos: Bei der Energieberechnung berücksichtigen</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>EnergyManArea</td><td>Energos: Fläche eigen</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>EnergyArea</td><td>Energos: Fläche</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>EnergyAreaFac</td><td>Energos: Fläche Faktor</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>EnergyManVolume</td><td>Energos: Volumen eigen</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>EnergyVolume</td><td>Energos: Volumen</td><td>Volume</td></tr>
<tr><td>Space</td><td>Raum</td><td>Description</td><td>Beschreibung</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetElevatonTopBound</td><td>__invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetElevatonBottomBound</td><td>__invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GrossElevatonTopBound</td><td>__invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GrossElevatonBottomBound</td><td>__invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>MultipleSpaceLables</td><td>__Invisible</td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>InteriorOrExteriorSpace</td><td>Innen- oder Außenraum</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceCommon_Reference</td><td>Raumtyp</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceCommon_NetPlannedArea</td><td>Fläche Netto geplant</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceCommon_PublicAccessible</td><td>Öffentlich zugänglich</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceCommon_HandicapAccessible</td><td>Behindertengerecht zugänglich</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceCommon_ConcealedFlooring</td><td>Installationsboden</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceCommon_ConcealedCeiling</td><td>Installationsdecke</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceParking_HandicapAccessible</td><td>Parkplatz behindertengerecht</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceParking_ParkingUse</td><td>Parkplatznutzung</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceParking_ParkingUnits</td><td>Parkplatzeinheiten</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceParkingAisle_IsOneWay</td><td>Parkplatz Einwegverkehr</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_MainFireUse</td><td>Brandschutz: Hauptbrandkennziffer</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_AncillaryFireUse</td><td>Brandschutz: Zusatzbrandkennziffer</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_FireRiskFactor</td><td>Brandschutz: Brandgefahrenklasse</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_FireHazardFactor</td><td>Brandschutz: Brandrisikogefahrenklasse</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_FlammableStorage</td><td>Brandschutz: Lagerung brennbarer Stoffe</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_FireExit</td><td>Brandschutz: Notausgang</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_SprinklerProtection</td><td>Brandschutz: Sprinklerschutz</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_SprinklerProtectionAutomatic</td><td>Brandschutz: Sprinklerschutz automatisch</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceFireSafetyRequirements_AirPressurization</td><td>Brandschutz: Luftdruckausgleich</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceLightingRequirements_ArtificialLighting</td><td>Beleuchtung künstlich</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceLightingRequirements_Illuminance</td><td>Beleuchtungsstärke</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_OccupancyType</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_OccupancyNumber</td><td>Benutzer Belegung</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_OccupancyNumberPeak</td><td>Benutzer Belegung max</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_OccupancyTimePerDay</td><td>Benutzer Belegungszeit pro Tag</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_AreaPerOccupant</td><td>Fläche pro Nutzer</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_MinimumHeadroom</td><td>Höhe im Lichten</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceOccupancyRequirements_IsOutlookDesirable</td><td>Ausblick erwünscht</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceTemperatureMax</td><td>Raumtemperatur max</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceTemperatureMin</td><td>Raumtemperatur min</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceTemperatureSummerMax</td><td>Raumtemperatur Kühlung max</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceTemperatureSummerMin</td><td>Raumtemperatur Kühlung min</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceTemperatureWinterMax</td><td>Raumtemperatur Heizung max</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceTemperatureWinterMin</td><td>Raumtemperatur Heizung min</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceHumidity</td><td>Luftfeuchtigkeit</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceHumiditySummer</td><td>Luftfeuchtigkeit Kühlung</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_SpaceHumidityWinter</td><td>Luftfeuchtigkeit Heizung</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_DiscontinuedHeating</td><td>Heizung diskontinuierlich</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_NaturalVentilation</td><td>Lüftung natürlich</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_NaturalVentilationRate</td><td>Luftwechselzahl natürlich</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_MechanicalVentilationRate</td><td>Luftwechselzahl künstlich</td><td>Integer</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_AirConditioning</td><td>Klimaanlage</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalRequirements_AirConditioningCentral</td><td>Klimaanlage zentral</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_CoolingDesignAirflow</td><td>Luftdurchlassmenge Kühlung</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_HeatingDesignAirflow</td><td>Luftdurchlassmenge Wärme</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_TotalSensibleHeatGain</td><td>Abluftwärme</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_TotalHeatGain</td><td>Abluftwärme max</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_TotalHeatLoss</td><td>Wärmeverlust max</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_CoolingDryBulb</td><td>Raumtemperatur gekühlt</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_CoolingRelativeHumidity</td><td>Luftfeuchtigkeit gekühlt relativ</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_HeatingDryBulb</td><td>Raumtemperatur beheizt</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_HeatingRelativeHumidity</td><td>Luftfeuchtigkeit beheizt relativ</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_VentilationAirFlowrate</td><td>Lüftungsrate</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_ExhaustAirFlowrate</td><td>Abluftmenge</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_CeilingRAPlenum</td><td>WRG in Decke</td><td>Pop-Up</td></tr>
<tr><td>Space</td><td>Raum</td><td>SpaceThermalDesign_BoundaryAreaHeatLoss</td><td>Transmissionswärmeverlust Fläche </td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_ClassificationName</td><td>Klassifikation: Klassifikationsname</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_ClassificationSource</td><td>Klassifikation: Klassifikationsquelle</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_ClassificationEdition</td><td>Klassifikation: Version</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_ClassificationEditionDate</td><td>Klassifikation: Versionsdatum</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_ItemReference</td><td>Klassifikation: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_Name</td><td>Klassifikation: Name</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification_Location</td><td>Klassifikation: Quelle</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_ClassificationName</td><td>Klassifikation 2: Klassifikationsname</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_ClassificationSource</td><td>Klassifikation 2: Klassifikationsquelle</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_ClassificationEdition</td><td>Klassifikation 2: Version</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_ClassificationEditionDate</td><td>Klassifikation 2: Versionsdatum</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_ItemReference</td><td>Klassifikation 2: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_Name</td><td>Klassifikation 2: Name</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification2_Location</td><td>Klassifikation 2: Quelle</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_ClassificationName</td><td>Klassifikation 3: Klassifikationsname</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_ClassificationSource</td><td>Klassifikation 3: Klassifikationsquelle</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_ClassificationEdition</td><td>Klassifikation 3: Version</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_ClassificationEditionDate</td><td>Klassifikation 3: Versionsdatum</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_ItemReference</td><td>Klassifikation 3: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_Name</td><td>Klassifikation 3: Name</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Classification3_Location</td><td>Klassifikation 3: Quelle</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>BaseQuantities_MethodOfMeasurement</td><td>Maßeinheit</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_2DBound_Class</td><td></td><td>Class</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_2DBound_PenStyle</td><td></td><td>Pen Style</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_2DBound_Fill</td><td></td><td>Fill</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_LLines_Class</td><td></td><td>Class</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_LLines_PenStyle</td><td></td><td>Pen Style</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_3DBound_Class</td><td></td><td>Class</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_3DBound_PenStyle</td><td></td><td>Pen Style</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_3DBound_Fill</td><td></td><td>Fill</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_3DBound_Txture</td><td></td><td>Texture</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_CLine1_Class</td><td></td><td>Class</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_CLine1_PenStyle</td><td></td><td>Pen Style</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_CLine2_Class</td><td></td><td>Class</td></tr>
<tr><td>Space</td><td>Raum</td><td>GraphicAttr_CLine2_PenStyle</td><td></td><td>Pen Style</td></tr>
<tr><td>Space</td><td>Raum</td><td>Label1_Symbol_Definition</td><td></td><td>Symbol Definition</td></tr>
<tr><td>Space</td><td>Raum</td><td>Label2_Symbol_Definition</td><td></td><td>Symbol Definition</td></tr>
<tr><td>Space</td><td>Raum</td><td>Label3_Symbol_Definition</td><td></td><td>Symbol Definition</td></tr>
<tr><td>Space</td><td>Raum</td><td>NumberLabelText</td><td>Raumnummer Text</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>NumberIncrementingValue</td><td>Raumnummer Zähler</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionPercent1</td><td>Subtrahieren. % 1</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionArea1</td><td>Subtrahieren. Fläche 1</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionPercent2</td><td>Subtrahieren. % 2</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionArea2</td><td>Subtrahieren. Fläche 2</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionPercent3</td><td>Subtrahieren. % 3</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionArea3</td><td>Subtrahieren. Fläche 3</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionPercent4</td><td>Subtrahieren. % 4</td><td>Number</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionArea4</td><td>Subtrahieren. Fläche 4</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>SubtractionAreaCustom</td><td>Eigen Subtrahieren. Fläche</td><td>Area</td></tr>
<tr><td>Space</td><td>Raum</td><td>Project</td><td>Projekt</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Site</td><td>Standort</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>Flat</td><td>Wohnung/Einheit</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetElevTopBoundNum</td><td>Netto-Oberkante</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>NetElevBottomBoundNum</td><td>Netto-Unterkante</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>GrossElevTopBoundNum</td><td>Brutto-Oberkante</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>GrossElevBottomBoundNum</td><td>Brutto-Unterkante</td><td>Dimension</td></tr>
<tr><td>Space</td><td>Raum</td><td>NumberingStyleCombination</td><td>__Invisible</td><td>Text</td></tr>
<tr><td>Space</td><td>Raum</td><td>__NEW</td><td></td><td>Boolean</td></tr>
<tr><td>Space</td><td>Raum</td><td>space_cw_uniq_id</td><td>__Invisible</td><td>Text</td></tr>
</tbody></table></details>
<details><summary>Rechtwinkelbemaßung</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>dimension standard</td><td>Bemaßungsstandard</td><td>Pop-Up</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>alignment dim text</td><td>Ausrichtung Maßtext1</td><td>Pop-Up</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>postition dim text</td><td>Ausrichtung Maßtext2</td><td>Pop-Up</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>box text</td><td>Rahmen um Text</td><td>Boolean</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>dual view</td><td>Maßzahlen</td><td>Pop-Up</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>sel prim sec</td><td>Auswahl Einheiten</td><td>Pop-Up</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>precision</td><td>Dezimalstellen</td><td>Precision Popup</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>show dim value</td><td>Maßzahl anzeigen</td><td>Boolean</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>leader</td><td>Vorangestellt</td><td>Text</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>trailer</td><td>Nachgestellt</td><td>Text</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>precision2</td><td>Dezimalstellen</td><td>Precision Popup</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>show dim value2</td><td>Maßzahl anzeigen</td><td>Boolean</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>leader2</td><td>Vorangestellt</td><td>Text</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>trailer2</td><td>Nachgestellt</td><td>Text</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>own text attributes</td><td>Eigene Attribute für Maßtexte</td><td>Boolean</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>start pt X</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>start pt Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>end pt X</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>end pt Y</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>flags</td><td>__CWD_DO_NOT_CHANGE</td><td>Integer</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>fixed distance</td><td>__CWD_DO_NOT_CHANGE</td><td>Dimension</td></tr>
<tr><td>Perpendicular Dimension CW</td><td>Rechtwinkelbemaßung</td><td>adapt background</td><td>__CWD_DO_NOT_CHANGE</td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Schlitze Durchbrüche Classic</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>m_Art_Auswahl</td><td>Art</td><td>Pop-Up</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Delta_x</td><td>∆x</td><td>Dimension</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Delta_y</td><td>∆y</td><td>Dimension</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Delta_z</td><td>∆z</td><td>Dimension</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>ControlPoint01X</td><td>Text x</td><td>X Coordinate</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>ControlPoint01Y</td><td>Text y</td><td>Y Coordinate</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Display2DHybrid</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>LageKante</td><td>Lage auf</td><td>Pop-Up</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Lettering</td><td>Beschriftung</td><td>Radio Buttons</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Label</td><td>Text</td><td>Text</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>Offset</td><td>__Offset</td><td>Dimension</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>IsInSlab</td><td>__IsInSlab</td><td>Boolean</td></tr>
<tr><td>Break Opening CW</td><td>Schlitze Durchbrüche Classic</td><td>__NEW</td><td></td><td>Boolean</td></tr>
</tbody></table></details>
<details><summary>Tool Localized</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Tool Universal</td><td>Tool Localized</td><td>Record Universal</td><td>Record Localized</td><td>Typ</td></tr>
</tbody></table></details>
<details><summary>Treppe</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint01X</td><td>X Text Text 1</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint01Y</td><td>Y Text Text 1</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint02X</td><td>X Text Lauf 1</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint02Y</td><td>Y Text Lauf 1</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint03X</td><td>X Text Lauf 2</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint03Y</td><td>Y Text Lauf 2</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint04X</td><td>X Text Lauf 3</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint04Y</td><td>Y Text Lauf 3</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint05X</td><td>X Text Text 2</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint05Y</td><td>Y Text Text 2</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>UpperLayer</td><td>Oberes Geschoss</td><td>Layers Popup</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint06X</td><td>X Text Note 1 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint06Y</td><td>Y Text Note 1 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint07X</td><td>X Text Lauf 1 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint07Y</td><td>Y Text Lauf 1 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint08X</td><td>X Text Lauf 2 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint08Y</td><td>Y Text Lauf 2 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint09X</td><td>X Text Lauf 3 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint09Y</td><td>Y Text Lauf 3 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint10X</td><td>X Text Text 2 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint10Y</td><td>Y Text Text 2 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint11X</td><td>X Text Lauf 4</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint11Y</td><td>Y Text Lauf 4</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint12X</td><td>X Text Lauf 4 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint12Y</td><td>Y Text Lauf 4 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint13X</td><td>X Text Lauf 5</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint13Y</td><td>Y Text Lauf 5</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint14X</td><td>X Text Lauf 5 Obere Ebene</td><td>X Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ControlPoint14Y</td><td>Y Text Lauf 5 Obere Ebene</td><td>Y Coordinate</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Orientation</td><td>Richtung</td><td>Pop-Up</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>TotalRise</td><td>Geschosshöhe</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakModeLowerFloorDetailed</td><td>Treppenbruch</td><td>Pop-Up</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakModeLowerFloorSchematic</td><td>Treppenbruch</td><td>Pop-Up</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakElevationDetailed</td><td>Bruchhöhe</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakElevationSchematic</td><td>Bruchhöhe</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakLineAngleDetailed</td><td>Bruchwinkel</td><td>Angle</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakLineAngleSchematic</td><td>Bruchwinkel</td><td>Angle</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakLinesSeparationMMDetailed</td><td>Überstand Bruchlinien [mm]</td><td>Number</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>BreakLinesSeparationMMSchematic</td><td>Überstand Bruchlinien [mm]</td><td>Number</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ShowGuardrailOfInsideRailingDetailed</td><td>Geländer innen anzeigen</td><td>Boolean</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ShowGuardrailOfInsideRailingSchematic</td><td>Geländer innen anzeigen</td><td>Boolean</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ShowGuardrailOfOutsideRailingDetailed</td><td>Geländer außen anzeigen</td><td>Boolean</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>ShowGuardrailOfOutsideRailingSchematic</td><td>Geländer außen anzeigen</td><td>Boolean</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>StairArea</td><td>Fläche</td><td>Area</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>WalkLineLength</td><td>Lauflinienlänge</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>StairWidth</td><td>Treppenbreite</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>TreadLength</td><td>Auftritt</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>RiserHeight</td><td>Steigung</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>NumberOfRisers</td><td>Anzahl Steigungen</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>InternalVersionNumberOfRecordFormat</td><td>Versionsnummer Datenbank</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight1Length</td><td>Lauflinienlänge Lauf 1</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight2Length</td><td>Lauflinienlänge Lauf 2</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight3Length</td><td>Lauflinienlänge Lauf 3</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight4Length</td><td>Lauflinienlänge Lauf 4</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight1NumberOfRiser</td><td>Anzahl Steigungen Lauf 1</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight2NumberOfRiser</td><td>Anzahl Steigungen Lauf 2</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight3NumberOfRiser</td><td>Anzahl Steigungen Lauf 3</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight4NumberOfRiser</td><td>Anzahl Steigungen Lauf 4</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight1NumberOfTreads</td><td>Anzahl Stufen Lauf 1</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight2NumberOfTreads</td><td>Anzahl Stufen Lauf 2</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight3NumberOfTreads</td><td>Anzahl Stufen Lauf 3</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight4NumberOfTreads</td><td>Anzahl Stufen Lauf 4</td><td>Integer</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight1WalkingLineOffset</td><td>Abstand der Lauflinie Lauf 1</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight2WalkingLineOffset</td><td>Abstand der Lauflinie Lauf 2</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight3WalkingLineOffset</td><td>Abstand der Lauflinie Lauf 3</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>Flight4WalkingLineOffset</td><td>Abstand der Lauflinie Lauf 4</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>TreadLengthAtOffset</td><td>Auftritt an Lauflinie</td><td>Dimension</td></tr>
<tr><td>Stairs CW</td><td>Treppe</td><td>NosingLength</td><td>Überstand</td><td>Dimension</td></tr>
</tbody></table></details>
<details><summary>Tür</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Door CW</td><td>Tür</td><td>Türbreite</td><td>Gewählte Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Türhöhe</td><td>Gewählte Öffnungshöhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Form</td><td>Form</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Anzeigeart</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Einfügepunkt</td><td>Einfügepunkt längs</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ControlPoint01X</td><td>x-Position Beschriftung</td><td>X Coordinate</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ControlPoint01Y</td><td>y-Position Beschriftung</td><td>Y Coordinate</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Aufschlag</td><td>Aufschlag</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AnzeigeartE</td><td>Anzeigeart</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Blatt in 3D</td><td>Blatt in 3D</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Klinke in 3D</td><td>Klinke in 3D</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Zarge</td><td>Zarge</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Zargenbreite</td><td>Zargenbreite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>NameOrType</td><td>__NNA Bezeichnung (alt) now obsolete</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TypeOfDoor</td><td>Türart (nur Text)</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TypeOfRabbetOrTrimObsolete</td><td>__NNA_Typ (obsolete)</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FormerConfigurationNowObsolete</td><td>__NNA_Öffnungsart_Obsolete</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Threshold</td><td>Schwelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TypeOfSideLights</td><td>Seitenlichter</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf1HasInlay</td><td>Füllung in Türblatt 1 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf1</td><td>Breite Blatt 1</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf2HasInlay</td><td>Füllung in Türblatt 2 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf2</td><td>Breite Blatt 2</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf3HasInlay</td><td>Füllung in Türblatt 3 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf3</td><td>Breite Blatt 3</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf4HasInlay</td><td>Füllung in Türblatt 4 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf4</td><td>Breite Blatt 4</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf5HasInlay</td><td>Füllung in Türblatt 5 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf5</td><td>Breite Blatt 5</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf6HasInlay</td><td>Füllung in Türblatt 6 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf6</td><td>Breite Blatt 6</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf7HasInlay</td><td>Füllung in Türblatt 7 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf7</td><td>Breite Blatt 7</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf8HasInlay</td><td>Füllung in Türblatt 8 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf8</td><td>Breite Blatt 8</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf9HasInlay</td><td>Füllung in Türblatt 9 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf9</td><td>Breite Blatt 9</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf10HasInlay</td><td>Füllung in Türblatt 10 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf10</td><td>Breite Blatt 10</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf11HasInlay</td><td>Füllung in Türblatt 11 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf11</td><td>Breite Blatt 11</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf12HasInlay</td><td>Füllung in Türblatt 12 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf12</td><td>Breite Blatt 12</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf13HasInlay</td><td>Füllung in Türblatt 13 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf13</td><td>Breite Blatt 13</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf14HasInlay</td><td>Füllung in Türblatt 14 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf14</td><td>Breite Blatt 14</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf15HasInlay</td><td>Füllung in Türblatt 15 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf15</td><td>Breite Blatt 15</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf16HasInlay</td><td>Füllung in Türblatt 16 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf16</td><td>Breite Blatt 16</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf17HasInlay</td><td>Füllung in Türblatt 17 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf17</td><td>Breite Blatt 17</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf18HasInlay</td><td>Füllung in Türblatt 18 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf18</td><td>Breite Blatt 18</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf19HasInlay</td><td>Füllung in Türblatt 19 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf19</td><td>Breite Blatt 19</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf20HasInlay</td><td>Füllung in Türblatt 20 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf20</td><td>Breite Blatt 20</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf21HasInlay</td><td>Füllung in Türblatt 21 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf21</td><td>Breite Blatt 21</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf22HasInlay</td><td>Füllung in Türblatt 22 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf22</td><td>Breite Blatt 22</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf23HasInlay</td><td>Füllung in Türblatt 23 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf23</td><td>Breite Blatt 23</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf24HasInlay</td><td>Füllung in Türblatt 24 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf24</td><td>Breite Blatt 24</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf25HasInlay</td><td>Füllung in Türblatt 25 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf25</td><td>Breite Blatt 25</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf26HasInlay</td><td>Füllung in Türblatt 26 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf26</td><td>Breite Blatt 26</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf27HasInlay</td><td>Füllung in Türblatt 27 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf27</td><td>Breite Blatt 27</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf28HasInlay</td><td>Füllung in Türblatt 28 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf28</td><td>Breite Blatt 28</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf29HasInlay</td><td>Füllung in Türblatt 29 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf29</td><td>Breite Blatt 29</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Leaf30HasInlay</td><td>Füllung in Türblatt 30 erzeugen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WidthOfLeaf30</td><td>Breite Blatt 30</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WallStyle</td><td>Wandstil</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>WallThickness</td><td>Wanddicke</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo01</td><td>Zusatz 01</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo02</td><td>Zusatz 02</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo03</td><td>Zusatz 03</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo04</td><td>Zusatz 04</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo05</td><td>Zusatz 05</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo06</td><td>Zusatz 06</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo07</td><td>Zusatz 07</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo08</td><td>Zusatz 08</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo09</td><td>Zusatz 09</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo10</td><td>Zusatz 10</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo11</td><td>Zusatz 11</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo12</td><td>Zusatz 12</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo13</td><td>Zusatz 13</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo14</td><td>Zusatz 14</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdditionalInfo15</td><td>Zusatz 15</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IsSimpleDoorWallOpening</td><td>Wandöffnung</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorKind</td><td>Türart</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_GlobalId</td><td>Bauteilnummer</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_Name</td><td>Bezeichnung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_Description</td><td>Beschreibung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_ObjectType</td><td>Objekttyp</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_Tag</td><td>Tag</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_OverallHeight</td><td>__NNA Obsolete Gesamthöhe (IFC)</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_OverallWidth</td><td>__NNA Obsolete Gesamtbreite (IFC)</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_Reference</td><td>Bauteiltyp</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_FireRating</td><td>Feuerwiderstandsklasse</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_AcousticRating</td><td>Schallschutzklasse</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_SecurityRating</td><td>Sicherheitsklasse</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_IsExternal</td><td>Ausgang</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_Infiltration</td><td>Luftdurchlass</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_ThermalTransmittance</td><td>U-Wert (Energos)</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_GlazingAreaFraction</td><td>Glasflächenanteil</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_HandicapAccessible</td><td>Barrierefrei</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_FireExit</td><td>Notausgang</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_SelfClosing</td><td>Türschließer</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_SmokeStop</td><td>Rauchschutz</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_OpeningElementCommon_Purpose</td><td>Zweck</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_OpeningElementCommon_ProtectedOpening</td><td>Brandschutz</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_OpeningElementCommon_ParallelJambs</td><td>Seiten von Wandöffnung sind Parallel</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorStyle_OperationType</td><td>Öffnungsart (IFC)</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorStyle_ConstructionType</td><td>Konstruktionstyp</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorStyle_ParameterTakesPrecedence</td><td>Werte entsprechen Realität</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorStyle_Sizeable</td><td>Skalierbar</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowShadingType_ExternalShadingCoefficient</td><td>b-Faktor Außen</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowShadingType_InternalShadingCoefficient</td><td>b-Faktor Innen</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowShadingType_InsetShadingCoefficient</td><td>b-Faktor Glaszwischenraum</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_LiningDepth</td><td>Zargen-/Rahmentiefe</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_LiningThickness</td><td>Zargen-/Rahmenbreite</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_ThresholdDepth</td><td>Schwellentiefe</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_ThresholdThickness</td><td>Schwellenhöhe</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_TransomThickness</td><td>Kämpferhöhe</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_TransomOffset</td><td>Kämpferabstand</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_LiningOffset</td><td>Zargen-/Rahmenabstand</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_ThresholdOffset</td><td>Schwellenabstand</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_CasingThickness</td><td>Spiegel-/Blendenbreite</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorLining_CasingDepth</td><td>Spiegel-/Blendentiefe</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel1_PanelDepth</td><td>Türblattdicke Blatt 1</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel1_PanelOperation</td><td>Öffnungsart Flügel 1</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel1_PanelWidth</td><td>Breite Flügel 1</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel1_PanelPosition</td><td>Position Flügel 1</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel2_PanelDepth</td><td>Türblattdicke Blatt 2</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel2_PanelOperation</td><td>Öffnungsart Flügel 2</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel2_PanelWidth</td><td>Breite Flügel 2</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel2_PanelPosition</td><td>Position Flügel 2</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel3_PanelDepth</td><td>Türblattdicke Blatt 3</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel3_PanelOperation</td><td>Öffnungsart Flügel 3</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel3_PanelWidth</td><td>Breite Flügel 3</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorPanel3_PanelPosition</td><td>Position Flügel 3</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Classification Name</td><td>Klassifizierung: Klassifizierungsname</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Classification Source</td><td>Klassifizierung: Klassifizierungsquelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Classification Edition</td><td>Klassifizierung: Version</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Classification Edition Date</td><td>Klassifizierung: Versionsdatum</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Item Reference</td><td>Klassifizierung: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Name</td><td>Klassifizierung: Name</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification_Location</td><td>Klassifizierung: Quelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Classification Name</td><td>Klassifizierung 2: Klassifizierungsname</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Classification Source</td><td>Klassifizierung 2: Klassifizierungsquelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Classification Edition</td><td>Klassifizierung 2: Version</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Classification Edition Date</td><td>Klassifizierung 2: Versionsdatum</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Item Reference</td><td>Klassifizierung 2: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Name</td><td>Klassifizierung 2: Name</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification2_Location</td><td>Klassifizierung 2: Quelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Classification Name</td><td>Klassifizierung 3: Klassifizierungsname</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Classification Source</td><td>Klassifizierung 3: Klassifizierungsquelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Classification Edition</td><td>Klassifizierung 3: Version</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Classification Edition Date</td><td>Klassifizierung 3: Versionsdatum</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Item Reference</td><td>Klassifizierung 3: Artikel Referenz</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Name</td><td>Klassifizierung 3: Name</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Classification3_Location</td><td>Klassifizierung 3: Quelle</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>BaseQuantities_Name</td><td>Base Quantities: Bezeichnung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>BaseQuantities_Description</td><td>Base Quantities: Beschreibung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>BaseQuantities_Width</td><td>__NNA_Rahmen-/Zargenaußenmaß Breite</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>BaseQuantities_Height</td><td>__NNA_Rahmen-/Zargenaußenmaß Höhe</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>BaseQuantities_Perimeter</td><td>__NNA_Umfang</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>BaseQuantities_Area</td><td>Rahmen/Zargenaußenmaß Fläche</td><td>Area</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorID</td><td>Türnummer</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_PredefinedType</td><td>Türart (nicht bearbeitbar)</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_OperationType</td><td>Türaufteilung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>IfcDoor_UserDefinedOperationType</td><td>Türaufteilung Benutzer</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_GlassLayers</td><td>Verglasung (Anzahl Gläser)</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_GlassThickness1</td><td>Dicke Glas 1 (Innenseite)</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_GlassThickness2</td><td>Dicke Glas 2 (Zwischen- oder Außenseite)</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_GlassThickness3</td><td>Dicke Glas 3 (Außenseite)</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_FillGas</td><td>Glasfüllung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_GlassColor</td><td>Glasfarbe</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_IsTempered</td><td>Gehärtet</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_IsLaminated</td><td>Belegt</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_IsCoated</td><td>Beschichtet</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_IsWired</td><td>Drahtglas</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_Translucency</td><td>Tʟ Tageslichttransmission</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_Reflectivity</td><td>Reflexionsgrad</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_BeamRadiationTransmittance</td><td>λg Glasrandverbund</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_SolarHeatGainTransmittance</td><td>g-Wert</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_ThermalTransmittanceSummer</td><td>Ug-Wert Sommer</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_ThermalTransmittanceWinter</td><td>Ug-Wert Winter</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_Status</td><td>Status</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_ModelReference</td><td>Produktlinie</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_ModelLabel</td><td>Modell</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_Manufacturer</td><td>Hersteller</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_ProductionYear</td><td>Produktionsjahr</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_ArticleNumber</td><td>Artikelnummer</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_GlobalTradeItemNumber</td><td>GlobalTradeItemNumber</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerTypeInformation_AssemblyPlace</td><td>Montageort</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerOccurrence_AcquisitionDate</td><td>Kaufdatum</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerOccurrence_BarCode</td><td>Barcode</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerOccurrence_SerialNumber</td><td>Seriennummer</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ManufacturerOccurrence_BatchReference</td><td>Produktcharge</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_Reference</td><td>Bemusterungstyp</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_ShadingDeviceType</td><td>Verschattungsart</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_IsExternal</td><td>Außenbauteil</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_MechanicalOperated</td><td>Mechanisch</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_ThermalTransmittance</td><td>U-Wert</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_SolarTransmittance</td><td>Abminderungsfaktor energetisch</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_VisibleLightTransmittance</td><td>Abminderungsfaktor optisch</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_SolarReflectance</td><td>Reflexion</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_VisibleLightReflectance</td><td>Reflexionsgrad für sichtbares Licht</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_Roughness</td><td>Oberflächenversatz</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_SurfaceColor</td><td>Oberflächenfarbe</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ElementShading_Azimuth</td><td>Himmelsrichtung</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ElementShading_Inclination</td><td>Neigung X-Achse</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ElementShading_TiltRange</td><td>Neigung Z-Achse</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_SolarAbsorption</td><td>Strahlungsabsorptionsgrad</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_SolarReflectance</td><td>Strahlungsreflektionsgrad</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorWindowGlazingType_ShadingCoefficient</td><td>Mittlerer Durchlassfaktor b</td><td>Number</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_ShadingDeviceCommon_Status</td><td>Status Sonnenschutz</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_HasDrive</td><td>Antrieb</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_WaterTightnessRating</td><td>Schlagregendichtigkeit</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_MechanicalLoadRating</td><td>Mechanische Festigkeit</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_WindLoadRating</td><td>Windwiderstand</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_DurabilityRating</td><td>Beanspruchungsklasse</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Pset_DoorCommon_HygrothermalRating</td><td>Klimaklasse</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>InactiveLeaf</td><td>Standflügel</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>NumberOfLeaves</td><td>Anzahl Türblätter</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FormerBandungNowObsoleteDontUse</td><td>__NNA_noloc_formerbandung</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space1UUID</td><td>Raum 1 UUID</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space2UUID</td><td>Raum 2 UUID</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space1Number</td><td>Raumnummer 1</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space2Number</td><td>Raumnummer 2</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space1Name</td><td>Raumname 1</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space2Name</td><td>Raumname 2</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space1Assignment</td><td>Raum 1 Zuordnungsregel</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>Space2Assignment</td><td>Raum 2 Zuordnungsregel</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AdjacentSpaces</td><td>__NNA_noLoc__AdjacentSpaces</td><td>Text</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FinishedWidthOutside</td><td>Fertigmaß links Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FinishedHeightWallOutside</td><td>Fertigmaß links Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FinishedWidthInside</td><td>Fertigmaß rechts Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FinishedHeightWallInside</td><td>Fertigmaß rechts Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnfinishedWidth</td><td>Rohbaumaß Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnfinishedHeight</td><td>Rohbaumaß Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ForFutureUse001</td><td>__NNA_noloc_for future use 257</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ForFutureUse002</td><td>__NNA_noloc_for future use 258</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FrameTotalWidth</td><td>Zargen-/Rahmenaußenmaß Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FrameTotalHeight</td><td>Zargen-/Rahmenaußenmaß Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FrameClearWidth</td><td>Lichtes Durchgangsmaß Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FrameClearHeight</td><td>Lichtes Durchgangsmaß Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>SizeModeWidth</td><td>__NNA_Gewählte Breite (Art)</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>SizeModeHeight</td><td>__NNA_Gewählte Höhe (Art)</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FinishedHeightDoorOutside</td><td>__NNA_noloc_Fertigmaß Höhe Tür links obsolete reserved for future use</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FinishedHeightDoorInside</td><td>__NNA_noloc_Fertigmaß Höhe Tür rechts obsolete reserved for future use</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AutoDimensionWidth</td><td>Breite rechts</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AutoDimensionHeight</td><td>Höhe rechts</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>InsertionRelativeTo</td><td>Einfügepunkt quer</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ClearWidth90</td><td>Lichte Breite 90°</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ClearWidthFittings</td><td>Lichte Breite Beschlag</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>RebateWidth</td><td>Zargen-/Rahmenfalzmaß Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnfinishedHeightWall</td><td>Rohbaumaß Höhe Wand</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>HingeConfigurationForInternalUseDoNotChange</td><td>__NNA_Öffnungsart_Internal</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnitWidthHingeSide</td><td>Bekleidungsaußenmaß Bandseite Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnitHeightHingeSide</td><td>Bekleidungsaußenmaß Bandseite Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnitWidthStopSide</td><td>Bekleidungsaußenmaß Bandgegenseite Breite</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnitHeightStopSide</td><td>Bekleidungsaußenmaß Bandgegenseite Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>RebateHeight</td><td>Zargen-/Rahmenfalzmaß Höhe</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AutoDimensionWidthExterior</td><td>Breite links</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AutoDimensionHeightExterior</td><td>Höhe links</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>InternalVersionNumberDoNotChange</td><td>__NNA_VersionNumberOfRecordFormat</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DoorClearanceArea</td><td>Rahmenlichtmaß Fläche</td><td>Area</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UnfinishedArea</td><td>Rohbaumaß Fläche</td><td>Area</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DetailLevel3DRepresentation</td><td>Detaillierung für 3D-Darstellung</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UseAutomatic2DForHorizontalSection2D</td><td>Für Horizontalschnitt 2D verwenden</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UseAutomatic2DForBackView2D</td><td>Für Ansicht von außen 2D verwenden</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>UseAutomatic2DForLeftRightView2D</td><td>Für Querschnitt 2D verwenden</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>RecessMode</td><td>Türnische für Raumfläche</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>CreateThresholdIn3D</td><td>Schwelle in 3D erstellen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TypeOfExteriorThreshold</td><td>Außen</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TypeOfInteriorThreshold</td><td>Innen</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>HasBottomFrame</td><td>Rahmen unter Tür</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>ThicknessDoorLeaf</td><td>Türblattdicke</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AngleOpenLeaf2D</td><td>Öffnungswinkel 2D</td><td>Angle</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AngleOpenLeaf3DLeft</td><td>Öffnungswinkel links</td><td>Angle</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>AngleOpenLeaf3DRight</td><td>Öffnungswinkel rechts</td><td>Angle</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>OpenCloseStateLeaf3DLeft</td><td>Öffnung 3D links</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>OpenCloseStateLeaf3DRight</td><td>Öffnung 3D rechts</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>DrawDoorSwingOfPassiveWings</td><td>Aufschlag Standflügel verwenden</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TypZarge</td><td>Zargentyp</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>LeafType</td><td>Darstellung höchste Detaillierung</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>CustomSymbol</td><td>Eigenes Symbol verwenden</td><td>Symbol Definition</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>TransferLeafInlaysToAllLeaves</td><td>Änderungen auf alle Türblätter übertragen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>NumberOfLeavesSlidingDoor</td><td>Anzahl Türblätter Schiebetür</td><td>Integer</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>OffsetInAssembly</td><td>Versatz im Fassadenmodul</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>RevealLining</td><td>Laibungsverkleidung erstellen</td><td>Boolean</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>FramePositionInReveal</td><td>Rahmenposition</td><td>Pop-Up</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>OffsetFramePositionInReveal</td><td>Abstand Rahmenposition</td><td>Dimension</td></tr>
<tr><td>Door CW</td><td>Tür</td><td>RevealType</td><td>Typ</td><td>Pop-Up</td></tr>
</tbody></table></details>
<details><summary>Vermessungspunkt</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Mode</td><td>Eigenschaft</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Site Model</td><td>Geländemodell</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Style</td><td>2D–Plan Draufsicht</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Label Reference</td><td>Beschriftung</td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ID Prefix</td><td>ID vorangestellt</td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ID</td><td>ID</td><td>Integer</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Data</td><td>Beschreibung</td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Station Point Data</td><td>Stationierungspunkt</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Coordinate Units</td><td>Einheiten (Punkt)</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Display Leader Line</td><td>Verweislinie anzeigen</td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Scale Factor</td><td>Skalierfaktor</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ControlPoint01X</td><td></td><td>X Coordinate</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ControlPoint01Y</td><td></td><td>Y Coordinate</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Z Value</td><td>Höhe</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Previous Mode</td><td></td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>__version</td><td></td><td>Integer</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>markOffsetX</td><td>  Versatz x</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>markOffsetY</td><td>  Versatz y</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>markRot</td><td>  Rotation</td><td>Angle</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ID Suffix</td><td>ID nachgestellt</td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Label Position</td><td>Textausrichtung</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ShowUnitMark</td><td>Einheiten anzeigen</td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>CoordinatePrecM</td><td>Dezimalstellen (Punkt)</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>CoordinatePrecA</td><td>Dezimalstellen (Punkt)</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ShowElevationMark</td><td>Höhe anzeigen</td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ElevationUnits</td><td>Einheiten (Höhe)</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ElevationPrecM</td><td>Dezimalstellen (Höhe)</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ElevationPrecA</td><td>Dezimalstellen (Höhe)</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>AutoIDNumber</td><td>ID-Nummerierung automatisch</td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>InitIDNumber</td><td>Startwert</td><td>Integer</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>__new</td><td></td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Label ReferenceN</td><td>Beschriftung</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>__toolpref</td><td></td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>3D Display</td><td>3D-Darstellung</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ExtrudeWidth</td><td>Breite</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>ExtrudeHeight</td><td>Höhe</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Bubble Style</td><td>Rahmen</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Radius Factor</td><td>Eckradius</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Margin</td><td>Textabstand</td><td>Dimension</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Latitude</td><td>Breitengrad</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Longitude</td><td>Längengrad</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Latitude WGS84</td><td>Breitengrad WGS84</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Longitude WGS84</td><td>Längengrad WGS84</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Easting</td><td>Rechtswert</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>Northing</td><td>Hochwert</td><td>Number</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>__dtmElevCalculated</td><td></td><td>Boolean</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>UseAnnotation</td><td>Beschriftung</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>DataTagStyle</td><td>Datenstempelstil</td><td>Pop-Up</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>LabelText</td><td>Text</td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>LabelValues</td><td>Wert</td><td>Text</td></tr>
<tr><td>Stake Object</td><td>Vermessungspunkt</td><td>__DataTagStyleName</td><td>Datenstempelstil</td><td>Text</td></tr>
</tbody></table></details>
<details><summary>Wandbild</summary>
<table><thead><tr>
<th style='width:20%'>Tool Universal</th>
<th style='width:20%'>Tool Localized</th>
<th style='width:20%'>Record Universal</th>
<th style='width:20%'>Record Localized</th>
<th style='width:20%'>Typ</th>
</tr></thead><tbody>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>hanging height</td><td>Aufhängehöhe</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>insertion point</td><td>Einfügepunkt</td><td>Pop-Up</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>commit to</td><td>Festlegen von</td><td>Pop-Up</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>total width</td><td>Gesamtbreite</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>total height</td><td>Gesamthöhe</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>picture width</td><td>Bildbreite</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>picture height</td><td>Bildhöhe</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>passepartout left right</td><td>Passepartout links/rechts</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>passepartout top bottom</td><td>Passepartout oben/unten</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>keep proportion</td><td>Proportionen erhalten</td><td>Boolean</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>frame</td><td>Rahmenbreite</td><td>Boolean</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>frame width</td><td>Rahmenbreite</td><td>Static Text</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>glas</td><td>Glas</td><td>Boolean</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>glas thickness</td><td>Glasdicke</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>distance picture to backwall</td><td>Bildabstand Rückwand</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>backwall thickness</td><td>Dicke der Rückwand</td><td>Dimension</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>2D class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>2D fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>2D linetype</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Frame class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Frame fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Frame linetype</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Frame texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Frame material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Passepartout class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Passepartout fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Passepartout linetype</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Passepartout texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Passepartout material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Glass class</td><td>__CWD_DO_NOT_CHANGE</td><td>Class</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Glass fill</td><td>__CWD_DO_NOT_CHANGE</td><td>Fill</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Glass linetype</td><td>__CWD_DO_NOT_CHANGE</td><td>Pen Style</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Glass texture</td><td>__CWD_DO_NOT_CHANGE</td><td>Texture</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>Glass material</td><td>__CWD_DO_NOT_CHANGE</td><td>Building Material</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>image name</td><td>__CWD_DO_NOT_CHANGE</td><td>Static Text</td></tr>
<tr><td>Picture Frame CW</td><td>Wandbild</td><td>frame name</td><td>__CWD_DO_NOT_CHANGE</td><td>Static Text</td></tr>
</tbody></table></details>
