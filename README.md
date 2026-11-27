# Create and Configure a Syncfusion Blazor Smith Chart in a Blazor Server Application

## Overview

This sample demonstrates how to create and configure a Syncfusion [Blazor Smith Chart](https://www.syncfusion.com/blazor-components/blazor-smith-chart) Server application. The sample visualizes impedance transmission data using two Smith Chart series and demonstrates different data-binding techniques. One series binds directly to a collection of `SmithChartPoint` objects, while the second binds to a custom data source using resistance and reactance field mappings. The application also showcases chart customization features such as legends, markers, data labels, tooltips, and custom series colors that help users analyze transmission line impedance data more effectively.

## Key Features

- Renders a Smith Chart using the `SfSmithChart` component.
- Configures a chart title using the `SmithChartTitle` component with `Text="Impedance Transmission"`.
- Displays chart legends through `SmithChartLegendSettings` with `Visible="true"`.
- Uses `SmithChartSeriesCollection` to host multiple chart series.
- Binds the first series directly using the `Points` property and a collection of `SmithChartPoint` objects.
- Binds the second series through the `DataSource` property using a custom `ChartData` model.
- Applies custom series colors using the `Fill` property.
- Displays point markers using `SmithChartSeriesMarker` with `Visible="true"`.
- Shows data labels using `SmithChartSeriesDatalabel` with `Visible="true"`.
- Enables interactive tooltips using `SmithChartSeriesTooltip` with `Visible="true"`.
- Demonstrates plotting impedance transmission data using resistance and reactance values.
- Shows both built in and custom data-binding approaches within the same Smith Chart.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `CreatingSmithChartSample.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the `CreatingSmithChartSample` project directory.

```bash
cd CreatingSmithChartSample
```

4. Restore project dependencies:

```bash
dotnet restore
```

5. Run the application:

```bash
dotnet run
```

6. Open the URL displayed in the terminal after the application starts.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://help.syncfusion.com/chart-sdk/blazor/smith-chart/getting-started-webapp).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
