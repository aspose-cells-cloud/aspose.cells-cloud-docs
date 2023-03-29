﻿---
title: Импорт пакетных данных в рабочий лист Excel
second_title: Aspose.Cells Cloud Documen
linktitle: Импорт данных партии
type: docs
url: /ru/import/batch-data/
aliases: [/import-batch-data-into-excel-worksheet/,/import-batch-data-into-worksheet/,/import-data/batch-data/]
keywords: Import batch data into Excel files
description: Aspose.Cells Cloud REST API поддерживает импорт пакетных данных в файлы Excel. SDK поддерживает различные языки разработки. К ним относятся Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и swift.
weight: 19
---
Этот REST API `import batch data` в рабочий лист Excel.

Запрос представляет собой HTTP-запрос с составным содержимым (см.[RFC 2046](http://tools.ietf.org/html/rfc2046#page-17)или[RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). Первая часть составного содержимого содержит данные ImportBatchDataOption, а вторая — файл данных.

## РСЕТ API

```bash

POST https://api.aspose.cloud/v3.0/cells/import
POST https://api.aspose.cloud/v3.0/cells/{name}/import-data

```

Важные параметры описаны в следующей таблице:


**Импортбатчдатаоптион**

|Имя параметра|Тип|Описание|
|:- |:- |:- |
| Пакетные данные|Список<CellValue> | пакетные данные|
| Рабочий лист назначения| нить| имя рабочего листа назначения.|
| IsInsert| нить| правда/ложь.|
| ИмпортДататип| нить|IntArray/DoubleArray/StringArray/TwoDimensionIntArray/TwoDimensionDoubleArray/TwoDimensionStringArray/BatchData/CSVData.|
| Источник| Источник файла| Указывает позицию файла данных, когда параметр BatchData имеет значение null.|



**CellValue**

|Имя параметра|Тип|Описание|
|:- |:- |:- |
| индекс строки| инт||
| индекс столбца| инт||
| тип| нить| тип данных|
| ценить| нить||
| стиль| Стиль(объект)||



**Источник файла**
|Имя параметра|Тип|Описание|
|:- |:- |:- |
| FileSourceType| нить| InMemoryFiles/CloudFileSystem/RequestFiles|
| Путь к файлу| нить| позиция в файле|


**Пример**

```xml
<ImportIntArrayOption>
    <DestinationWorksheet>Sheet1</DestinationWorksheet>
    <IsInsert>false</IsInsert>
    <ImportDataType>IntArray</ImportDataType>
    <FirstRow>1</FirstRow>
    <FirstColumn>1</FirstColumn>
    <IsVertical>true</IsVertical>
    <Source>
        <FileSourceType>CloudFileSystem</FileSourceType>
        <FilePath>Array_int_xml.txt</FilePath>
    </Source>
</ImportIntArrayOption>

```

## Семейство облачных SDK

 Использование SDK — лучший способ ускорить разработку. SDK позаботится о низкоуровневых деталях и позволит вам сосредоточиться на задачах вашего проекта. Пожалуйста, ознакомьтесь с[Репозиторий GitHub](https://github.com/aspose-cells-cloud) полный список Aspose.Cells Cloud SDK.

В следующих примерах кода показано, как выполнять вызовы веб-служб Aspose.Cells с помощью различных SDK.


{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cells-cloud-gists" "8a5b324fdf3e574dbd747c1a1e24b05d" "Examples-DotNet-CSharp-ImportData-PostImportDataCloudFile-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells-cloud-gists" "84283c8ba766ed815f47e6dfb0891152" "Examples-PHP-Workbook-PostImportBatchData.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cells-cloud-gists" "36ed8b8727561b92692939513d365fca" "Examples-Ruby-Workbook-post_import_data-.rb" >}}

{{< /tab >}}

{{< /tabs >}}