---
title: "Split Excel Workbooks"
type: docs
url: /split-excel-workbooks/
keywords: "split worksheets, xlsx, xls, csv, google sheet, separate workbook, REST API, Python code snippet, Perl code snippet, Swift code snippet, PHP code snippet"
description: "Split all or specific worksheet of a workbook into PNG, TIFF or any other supported image format. Split XLSX worksheet using Aspose.Cells Cloud API for Ruby, Python, Perl, Java, .NET, android and many other platforms."
weight: 130
---

## **Introduction**
This example allows you to split all or specific worksheets of a workbook file and save each worksheet as a new workbook, TIFF or any supported image format using Aspose.Cells Cloud API in your applications.
### **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/{name}/split|POST|Split an Excel Workbook|[PostWorkbookSplit](https://apireference.aspose.cloud/cells/#/Workbook/PostWorkbookSplit)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/split?format=jpeg&from=1&to=1&horizontalResolution=0&verticalResolution=0" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1Njk2MTk0NDUsImV4cCI6MTU2OTcwNTg0NSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.at8j6tzptIioEjlSxLX63ouBnmECXvc0NagF9YUi9JU-npyc4dmui_ZhCfQDyYexe8ryFrxF5g_ZP7lhjirvM8p1BJfSR_ferQkk1t-kCS-J4uvjsNzBW0kb9L4sm5u2DWka8-9vGt04psKRALHZRpC7PWBdNJZXYWHpecZXlgUz03PEq_INKbl0fiDZohuKUTrUBa1xNZFdjz3iQoABRP7RmnNPdJrReAL6qZWriVNbPKBaVdMzNPfpRGT07sQa6S-pZvbq-5RiAkwBY9E6IBNwQdN3ykz2W7t8dyH7xFte6WiKERsnjIIhkdp0jjuhaT-F73F5Z1Au38yPZYcXzQ"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Result": {

    "Documents": [

      {

        "Id": 1,

        "link": {

          "Href": "413e3375-c163-4d5c-8b84-8f95f63902f6.png",

          "Rel": null,

          "Title": null,

          "Type": null

        }

      }

    ]

  },

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorkbookPostWorkbookSplit.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-workbook-SplitWorkbooks-split-excel-workbooks.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostWorkbookSplit-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-split_workbook-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "SplitExcelWorkbooks.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Workbook-SplitWorkbooks-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-workbook-SplitWorkbooks-split-excel-workbooks.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Workbook-SplitWorkbooks-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "ec45ec662143f4c94c2a8bc8c95953ce" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< gist "aspose-cloud" "6ddbdc7793cac6e13ad09bbfbc44a614" >}}

{{< /tab >}}

{{< /tabs >}}