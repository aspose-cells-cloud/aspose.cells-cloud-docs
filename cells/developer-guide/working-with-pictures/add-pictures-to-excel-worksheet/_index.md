---
title: "Add Pictures to Excel Worksheet"
type: docs
url: /add-pictures-to-excel-worksheet/
weight: 20
---

## **Introduction**
This example shows how to add a image to a Worksheet of a Excel document using Aspose.Cells Cloud API.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/pictures|PUT|Add Pictures to Excel Worksheet|[PutWorksheetAddPicture](https://apireference.aspose.cloud/cells/#/Pictures/PutWorksheetAddPicture)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v1.1/cells/Sample_Test_Book.xls/worksheets/Sheet6/pictures?picturePath=aspose-cloud.png&appSID=xxxx&signature=xxxx" \
     -X PUT \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Pictures": {

    "PictureList": [

      {

        "link": {

          "Href": "/0",

          "Rel": "self"

        }

      },

      {

        "link": {

          "Href": "/1",

          "Rel": "self"

        }

      }

    ],

    "link": {

      "Href": "http://api.aspose.cloud/v1.1/cells/Sample_Test_Book.xls/worksheets/Sheet6/pictures",

      "Rel": "self"

    }

  },

  "Code": "200",

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Objective C" tabName8="Android" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Pictures-AddPicturesWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-pictures-AddPicturesWorksheet-add-pictures-worksheet.java" >}}



{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Pictures-PutWorksheetAddPicture-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Pictures-add_a_new_worksheet_picture-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "AddPictureToExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Pictures-AddPicturesWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-pictures-AddPicturesWorksheet-add-pictures-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Pictures-AddPicturesWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "be89628a850c5f05b81105a97db96bef" >}}

{{< /tab >}}

{{< /tabs >}}