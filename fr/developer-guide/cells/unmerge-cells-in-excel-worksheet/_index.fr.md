﻿---
title: Défusionner Cells dans la feuille de travail Excel
type: docs
url: /fr/unmerge-cells-in-excel-worksheet/
weight: 120
---
Ce REST API indique `unmerge` cellules dans un fichier Excel.

## RSET API
 
```bash
 
POST http://api.aspose.cloud/v3.0/cells/{name}/worksheets/{sheetName}/cells/unmerge
 
```
 Les paramètres de la requête sont :
 
| Le nom du paramètre| Taper| Chemin/chaîne de requête/HTTPBody|Description|
|:- |:- |:- |:- |
| nom| chaîne| chemin|Le nom du classeur.|
| NomFeuille| chaîne| chemin| Le nom de la feuille de calcul.|
| startRow| entier| mettre en doute| La ligne de départ.|
| startColumn| entier| mettre en doute| La colonne de départ.|
| totalRows| entier| mettre en doute| Le nombre total de lignes|
| totalColonnes| entier| mettre en doute| Le total des colonnes.|
| dossier| chaîne| mettre en doute| Le dossier du classeur.|
| nom_stockage| chaîne| mettre en doute| nom de stockage.|
 
 Le[Spécification OpenAPI](https://apireference.aspose.cloud/cells/#/Cells/PostWorksheetUnmerge) définit une interface de programmation accessible au public et permet d'effectuer des interactions REST directement depuis un navigateur Web.
 
Vous pouvez utiliser l'outil de ligne de commande cURL pour accéder facilement aux services Web Aspose.Cells. L'exemple suivant montre comment passer des appels vers le Cloud API avec cURL.
 
{{< tabs tabTotal="2" tabID="11" tabName11="Request" tabName12="Response" >}}
 
{{< tab tabNum="11" >}}
 
```bash
 
curl -v "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/cells/unmerge?startRow=10&startColumn=10&totalRows=10&totalColumns=10" \
-X POST \
-H "Content-Type: application/json" \
-H "Accept: application/json" \
-H "Authorization: Bearer <jwt token>"
 
```
 
{{< /tab >}}
 
{{< tab tabNum="12" >}}
 
```bash
{
"Code": 200,
"Status": "OK"
}
 
```
 
{{< /tab >}}
 
{{< /tabs >}}
 
## Famille SDK Cloud

 L'utilisation d'un SDK est le meilleur moyen d'accélérer le développement. Un SDK prend en charge les détails de bas niveau et vous permet de vous concentrer sur les tâches de votre projet. Veuillez consulter le[Référentiel GitHub](https://github.com/aspose-cells-cloud) pour obtenir la liste complète des SDK Cloud Aspose.Cells.

Les exemples de code suivants montrent comment effectuer des appels vers les services Web Aspose.Cells à l'aide de divers SDK :


{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cells-cloud-gists" "8a5b324fdf3e574dbd747c1a1e24b05d" "Examples-DotNET-CSharp-Cells-UnmergeCellsWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells-cloud-gists" "c59aa5c02f735466a5e34751cee73f5f" "Examples-Java-cells-UnmergeCellsWorksheet-unmerge-cells-in-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cells-cloud-gists" "84283c8ba766ed815f47e6dfb0891152" "Examples-PHP-Cells-PostWorksheetUnmerge-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells-cloud-gists" "36ed8b8727561b92692939513d365fca" "Examples-Ruby-Worksheet-unmerge_cells-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells-cloud-gists" "61e922de11e6e7144db88adcad6501c1" "UnmergeCellsInExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cells-cloud-gists" "e82de2e4189bc27ae92abf73c36b4df0" "Examples-Node.js-SDK-Cells-UnmergeCellsWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cells-cloud-gists" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-cells-UnmergeCellsWorksheet-unmerge-cells-in-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cells-cloud-gists" "f82a3a00251e34ff8766116282c8c9ca" "Examples-Perl-Cells-UnmergeCellsWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cells-cloud-gists" "e1adb25f4ebc3ec087cf3dc2c4752422" >}}

{{< /tab >}}

{{< /tabs >}}