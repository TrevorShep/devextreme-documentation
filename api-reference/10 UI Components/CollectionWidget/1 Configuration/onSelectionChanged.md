---
id: CollectionWidget.Options.onSelectionChanged
type: function(e)
default: null
---
---
##### shortDescription
A function that is called after selection changes.

##### param(e): Object
Information about the event.

##### field(e.addedItems): Array<any>
The data of the selected items.

##### field(e.component): {WidgetName}
The UI component's instance.

##### field(e.element): DxElement
#include common-ref-elementparam with { element: "UI component" }

##### field(e.model): any
Model data. Available only if you use Knockout.

##### field(e.removedItems): Array<any>
The data of the items removed from selection.

---
<!-- Description goes here -->