---
title: "Find Text in a Workbook"
type: docs
url: /find-text-in-a-workbook/
weight: 30
---

## **Introduction**
This example shows how to find text in a Excel Workbook using Aspose.Cells Cloud API.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/findText|POST|Find text in a Excel Workbook|[PostWorkbooksTextSearch](https://apireference.aspose.cloud/cells/#/Workbook/PostWorkbooksTextSearch)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/findText?text=a" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1Njk2OTg3NzcsImV4cCI6MTU2OTc4NTE3NywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.cTT1ew15ns0DFsstBkOidtlQcQsQMrlbOoA0kH1rA7R6kUbgwrHbC_Us1AN5xsHe8Gb8R_y8sSbDenm3xJkkSWSNXzOB7zr7HhK79sp-vUyfXkx8MCXFDlXdysNGT6ifZCag45PUgG-PQAnB2bpgrTQu8vIHyue5Iz4Wl9o_FfTGlPsqNEQRXFY39mpsGD6jp0b2B-J3NI4fNwLILRs3GRX273_5BCmAEf4o8Q72a1IlRzrGZK20gZ6V4_CLUdMIG3CeE6Uojx97iLA7BpTFq4UdbMCLMTeexV1mWPdQ_dMZ5zRsdIJVfvT169yx81P3gMeMSOBUv4_Su9BO6KVqEw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "TextItems": {

    "TextItemList": [

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/A1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/B1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/C1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/D1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/E1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/F1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/G1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/H1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/I1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/J1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/K1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/L1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1/cells/M1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/A1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/B1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/C1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/D1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/E1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/F1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/G1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/H1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/I1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/J1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/K1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/L1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a",

        "link": {

          "Href": "/test.xlsx/Sheet1 (2)/cells/M1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      }

    ],

    "link": null

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
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Java" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Text-FindTextWorkbook-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Text-PostWorkbooksTextSearch-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-search_text-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-text-FindTextWorkbook-find-text-workbook.java" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "FindTextInWorkbook.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Text-FindTextWorkbook-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-text-FindTextWorkbook-find-text-workbook.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Text-FindTextWorkbook-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "c361770fa8a1def6f824137a087560c2" >}}

{{< /tab >}}

{{< /tabs >}}