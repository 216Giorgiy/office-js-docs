# TableChangedEventArgs Object (JavaScript API for Excel)

Provides information about the table that raised the Changed event.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|address|string|Gets the address that represents the changed area of a table on a specific worksheet.|[1.7](../requirement-sets/excel-api-requirement-sets.md)|
|changeType|string|Gets the change type that represents how the Changed event is triggered. Possible values are: RangeEdited, RowInserted, RowDeleted, ColumnInserted, ColumnDeleted, CellInserted, CellDeleted, Unknown.|[1.7](../requirement-sets/excel-api-requirement-sets.md)|
|source|string|Gets the source of the event. Possible values are: Local, Remote.|[1.7](../requirement-sets/excel-api-requirement-sets.md)|
|tableId|string|Gets the id of the table in which the data changed.|[1.7](../requirement-sets/excel-api-requirement-sets.md)|
|type|string|Gets the type of the event. Value is `TableChanged`, read-only. |[1.7](../requirement-sets/excel-api-requirement-sets.md)|
|worksheetId|string|Gets the id of the worksheet in which the data changed.|[1.7](../requirement-sets/excel-api-requirement-sets.md)|

_See property access [examples.](#property-access-examples)_

## Relationships
None


## Methods
None

