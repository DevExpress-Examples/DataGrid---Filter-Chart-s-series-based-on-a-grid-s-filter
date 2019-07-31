# MVC

In the case of MVC controls, when datasources are specified via [ASP.NET MVC and Web API Controllers](https://docs.devexpress.com/DevExtremeAspNetMvc/400704/concepts/data-binding#aspnet-mvc-and-web-api-controllers), we have separate datasource instances. We use chart's [getDataSource](https://js.devexpress.com/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Methods/#getDataSource) method to access the target [DataSource](https://js.devexpress.com/Documentation/ApiReference/Data_Layer/DataSource/) instance and call its [filter(filterExpr)](https://js.devexpress.com/Documentation/ApiReference/Data_Layer/DataSource/Methods/#filterfilterExpr) method to apply the grid's filter expression.

Take a look at the following file of this example to see the required code.

[Index.cshtml](Views/Home/Index.cshtml)
