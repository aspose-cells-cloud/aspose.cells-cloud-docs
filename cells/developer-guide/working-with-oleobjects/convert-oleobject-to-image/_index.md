---
title: "Convert OleObject to Image"
type: docs
url: /convert-oleobject-to-image/
weight: 40
---

## **Introduction**
This example shows how to convert an OleObject to image using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/oleobjects/{objectNumber}|GET|Get OLE object info or get the OLE object in some format|[GetWorksheetOleObject](https://apireference.aspose.cloud/cells/#/OleObjects/GetWorksheetOleObject)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v3.0/cells/Embeded_OleObject_Sample_Book1.xlsx/worksheets/Sheet1/oleobjects/0?format=png&appSID=xxxx&signature=xxxx" \
     -X GET \
     -H "Content-Type: application/json" 

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

Image file

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Objective C" tabName8="Android" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-OleObjects-ConvertOleObjectToImage-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-oleobjects-ConvertOleObjectToImage-convert-ole-object-to-image.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-OLEObjects-GetWorksheetOleObjectWithFormat-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-OLEObject-get_ole_object_in_specified_format-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "ConvertOLEObjectToImage.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Oleobjects-ConvertOleObjectToImage-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-oleobjects-ConvertOleObjectToImage-convert-ole-object-to-image.java" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Oleobjects-ConvertOleObjectToImage-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "ded72ef0fd36a40f0f3f28994f352b85" >}}

{{< /tab >}}

{{< /tabs >}}