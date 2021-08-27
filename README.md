<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/199482652/19.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T828551)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# DataGrid - Filter Chart's series based on a grid's filter

This example illustrates how to filter chart's series based on the grid's filter. For this, we handle the grid's [onOptionChanged](https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onOptionChanged) event, obtain the grid's filter by calling the [getCombinedFilter(returnDataField)](https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Methods/#getCombinedFilterreturnDataField) method and apply this filter to the underlying datasource to evaluate and set the chart's [dataSource](https://js.devexpress.com/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/#dataSource). We use [Query Concept](https://js.devexpress.com/Documentation/Guide/Data_Layer/Data_Layer/#Query_Concept) to evaluate the filter expression.
