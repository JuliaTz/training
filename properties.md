##TGrid properties

All TGrid properties are

There is 1 required TGrid property:


1. ###itemsProvider

    Value: 

    Default value: there is not default value.


Next properties are not requiered. If they are not written, default value is used.

1. ###enableCollapsing.
    Meaning: enables or disables groups collapsing, if property "**enableGrouping**"    is set to *true*.

    Value: *true* or *false*. 

    Default value: *false*

    Dependings on another properties: Is used only with property *enableGrouping*.
2. ###enableFiltering.
    Meaning: enables or disables filtering.

    Value: *true* or *false*.

    Default value: *false*.
3. ###enableGrouping.
    Meaning: enables or disables grouping.

    Value: *true* or *false*.

    Default value: *false*.
4. ###enablePaging.
    Meaning: enables or disables paging.

    Value: *true* or *false*.

    Default value: *false*.
5. ###enableSorting.
    Meaning: enables or disables sorting.

    Value: *true* or *false*.

    Default value: *false*.
6. ###enableVirtualScroll.
    Meaning: enables or disables virtual scrolling.

    Value: *true* or *false*.

    Default value: *false*.
7. ###pageSize.

    Meaning: how many items will be displayed on 1 page

    Value: number from 1 to  total items count.

    Default value: *10*.
8. ###pageSlide.

    Meaning: property for page navigation. 
    Sets how many pages to left and to right you can be able to navigate by one click on its number.

    Value: number from 1 to  total items count.

    Default value: *10*.
9. ###selectionMode.

    Meaning: sets how many items can be selected. 

    Value: 
    + "none" - you can't select any item,
 
    + "single" - you can select only one item, 

    + "multi" - you can select more, then one item. For selecting more then one item, press key 'Ctrl'.

    Default value: *single*.
10. ###showDetailsOnSelection.

    Meaning: sets will or won't be shown details on selection. 

    Value: *true* or *false*.

    Default value: *false*.

    Dependings on another properties: is used, when property **selectionMode** has value *single*(default) or *multi*. If property **selectionMode** is *none*, property  **showDetailsOnSelection** is useless.
    
    For showing details on selection you should define html details template in TGrid description. 
