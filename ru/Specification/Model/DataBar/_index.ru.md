﻿---
title: ДатаБа
second_title: Aspose.Cells Cloud Documen
type: docs
url: /ru/specification/model/databar/
description: "Aspose.Cells Спецификация облачной модели: DataBar. Легко обрабатывайте Excel и другие документы электронных таблиц с помощью таких функций, как открытие, создание, редактирование, разделение, слияние, сравнение и преобразование."
weight: 50
---
## **панель данных**

 Опишите правило условного форматирования DataBar. Это правило условного форматирования отображает градуированную панель данных в диапазоне ячеек.

| Имя свойства| Тип недвижимости| Обнуляемый| Только чтение| Значение по умолчанию| Описание|
|:- |:- |:- |:- |:- |:- |
| Цвет оси| Класс:Цвет| Истинный| ЛОЖЬ|| Получает цвет оси для ячеек с условным форматированием в виде гистограмм.|
| Позиция оси| Нить| Истинный| ЛОЖЬ|| Получает или задает положение оси гистограмм, заданное правилом условного форматирования.|
| БарГраница| Класс:DataBarBorder| Истинный| ЛОЖЬ||Получает объект, задающий границу панели данных.|
| Тип заполнения бара| Нить| Истинный| ЛОЖЬ|| Получает или задает цвет заливки панели данных.|
| Цвет| Класс:Цвет| Истинный| ЛОЖЬ|| Получите или установите цвет этого DataBar.|
| Направление| Нить| Истинный| ЛОЖЬ|| Получает или задает направление отображения панели данных.|
| МаксКфво| Класс:ConditionalFormattingValue| Истинный| ЛОЖЬ|| Получите или установите объект максимального значения этого DataBar. Невозможно установить для него значение null или CFValueObject с типом FormatConditionValueType.Min.|
| Максимальная длина| Целое число| Истинный| ЛОЖЬ|| Представляет максимальную длину панели данных.|
| MinCfvo| Класс:ConditionalFormattingValue| Истинный| ЛОЖЬ|| Получите или установите объект минимального значения этого DataBar. Невозможно установить для него значение null или CFValueObject с типом FormatConditionValueType.Max.|
| МинДлина| Целое число| Истинный| ЛОЖЬ|| Представляет минимальную длину панели данных.|
| НегативБарФормат| Класс:Негативебарформат| Истинный| ЛОЖЬ|| Получает объект NegativeBarFormat, связанный с правилом условного форматирования панели данных.|
| Показать значение| логическое значение| Истинный| ЛОЖЬ|| Получите или установите флаг, указывающий, следует ли отображать значения ячеек, к которым применяется эта панель данных. Значение по умолчанию — правда.|
