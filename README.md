# How to modify the Cell borders in MAUI DataGrid
In.NET [MAUI DataGrid](https://www.syncfusion.com/maui-controls/maui-datagrid) (SfDataGrid) allows to customize the DataGrid borders to Vertical, Horizontal, Both or None based on requirements.

There are four options available in [GridLinesVisibility](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.DataGrid.SfDataGrid.html#Syncfusion_Maui_DataGrid_SfDataGrid_GridLinesVisibility) and [HeaderGridLinesVisibility](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.DataGrid.SfDataGrid.html#Syncfusion_Maui_DataGrid_SfDataGrid_HeaderGridLinesVisibility) to customize the DataGrid borders.

## XAML

### BOTH

```XAML
<syncfusion:SfDataGrid x:Name="dataGrid" AutoGenerateColumnsMode="None" 
                           HeaderGridLinesVisibility="Both" 
                           GridLinesVisibility="Both"
                           ItemsSource="{Binding Employees}">
        <syncfusion:SfDataGrid.Columns>
            <syncfusion:DataGridNumericColumn MappingName="EmployeeID" HeaderText="ID" Format="d"/>
            <syncfusion:DataGridTextColumn MappingName="Name"/>
            <syncfusion:DataGridTextColumn MappingName="Title"/>
            <syncfusion:DataGridNumericColumn MappingName="ContactID" HeaderText="Contact ID" Format="d"/>
        </syncfusion:SfDataGrid.Columns>        
    </syncfusion:SfDataGrid>
```
![CellBorderSetAsBoth](CellBorderBoth.png)

### HORIZONTAL
```XAML
<syncfusion:SfDataGrid x:Name="dataGrid" AutoGenerateColumnsMode="None" 
                           HeaderGridLinesVisibility="Horizontal" 
                           GridLinesVisibility="Horizontal"
                           ItemsSource="{Binding Employees}">
        <syncfusion:SfDataGrid.Columns>
            <syncfusion:DataGridNumericColumn MappingName="EmployeeID" HeaderText="ID" Format="d"/>
            <syncfusion:DataGridTextColumn MappingName="Name"/>
            <syncfusion:DataGridTextColumn MappingName="Title"/>
            <syncfusion:DataGridNumericColumn MappingName="ContactID" HeaderText="Contact ID" Format="d"/>
        </syncfusion:SfDataGrid.Columns>        
    </syncfusion:SfDataGrid>
```
![CellBorderSetAsHorizontal](CellBorderHorizontal.png)

### VERTICAL
```XAML
<syncfusion:SfDataGrid x:Name="dataGrid" AutoGenerateColumnsMode="None" 
                           HeaderGridLinesVisibility="Vertical" 
                           GridLinesVisibility="Vertical"
                           ItemsSource="{Binding Employees}">
        <syncfusion:SfDataGrid.Columns>
            <syncfusion:DataGridNumericColumn MappingName="EmployeeID" HeaderText="ID" Format="d"/>
            <syncfusion:DataGridTextColumn MappingName="Name"/>
            <syncfusion:DataGridTextColumn MappingName="Title"/>
            <syncfusion:DataGridNumericColumn MappingName="ContactID" HeaderText="Contact ID" Format="d"/>
        </syncfusion:SfDataGrid.Columns>        
    </syncfusion:SfDataGrid>
```
![CellBorderSetAsVertical](CellBorderVertical.png)
### NONE
```XAML
<syncfusion:SfDataGrid x:Name="dataGrid" AutoGenerateColumnsMode="None" 
                           HeaderGridLinesVisibility="None" 
                           GridLinesVisibility="None"
                           ItemsSource="{Binding Employees}">
        <syncfusion:SfDataGrid.Columns>
            <syncfusion:DataGridNumericColumn MappingName="EmployeeID" HeaderText="ID" Format="d"/>
            <syncfusion:DataGridTextColumn MappingName="Name"/>
            <syncfusion:DataGridTextColumn MappingName="Title"/>
            <syncfusion:DataGridNumericColumn MappingName="ContactID" HeaderText="Contact ID" Format="d"/>
        </syncfusion:SfDataGrid.Columns>        
    </syncfusion:SfDataGrid>
```
![CellBorderSetAsNone](CellBorderNone.png)
## Conclusion
I hope you enjoyed learning about how to modify Cell borders in MAUI DataGrid (SfDataGrid).

You can refer to our [.NET MAUI DataGrid’s feature tour](https://www.syncfusion.com/maui-controls/maui-datagrid) page to know about its other groundbreaking feature representations. You can also explore our .NET MAUI DataGrid Documentation to understand how to present and manipulate data.
For current customers, you can check out our .NET MAUI components from the [License and Downloads](https://www.syncfusion.com/account/downloads) page. If you are new to Syncfusion, you can try our 30-day free trial to check out our .NET MAUI DataGrid and other .NET MAUI components.
If you have any queries or require clarifications, please let us know in comments below. You can also contact us through our [support forums](https://www.syncfusion.com/forums), [Direct-Trac](https://support.syncfusion.com/account/login?ReturnUrl=%2Faccount%2Fconnect%2Fauthorize%2Fcallback%3Fclient_id%3Dc54e52f3eb3cde0c3f20474f1bc179ed%26redirect_uri%3Dhttps%253A%252F%252Fsupport.syncfusion.com%252Fagent%252Flogincallback%26response_type%3Dcode%26scope%3Dopenid%2520profile%2520agent.api%2520integration.api%2520offline_access%2520kb.api%26state%3D8db41f98953a4d9ba40407b150ad4cf2%26code_challenge%3DvwHoT64z2h21eP_A9g7JWtr3vp3iPrvSjfh5hN5C7IE%26code_challenge_method%3DS256%26response_mode%3Dquery) or [feedback portal](https://www.syncfusion.com/feedback/maui?control=sfdatagrid). We are always happy to assist you!