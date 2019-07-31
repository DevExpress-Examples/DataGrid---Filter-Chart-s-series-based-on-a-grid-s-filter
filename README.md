# DataGrid - Filter Chart's series based on a grid's filter

This example illustrates how to filter chart's series based on the grid's filter. For this, we handle the grid's [onOptionChanged](https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onOptionChanged) event, obtain the grid's filter by calling the [getCombinedFilter(returnDataField)](https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Methods/#getCombinedFilterreturnDataField) method and apply this filter to the underlying datasource to evaluate and set the chart's [dataSource](https://js.devexpress.com/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/#dataSource). We use [Query Concept](https://js.devexpress.com/Documentation/Guide/Data_Layer/Data_Layer/#Query_Concept) to evaluate the filter expression. 

[Run Online](https://devexpress-examples.github.io/DataGrid-Filter-Chart-s-series-based-on-a-grid-s-filter/jquery/index.html)
