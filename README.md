# Blazor Tab Vertical Scrollbar

## Overview

This sample demonstrates how to enable a vertical scrollbar in the Syncfusion [Blazor Tabs](https://www.syncfusion.com/blazor-components/blazor-tabs) component when tab content exceeds the available display area. The application configures the Tabs component with a fixed height of `300px` and uses content templates to render lengthy content within individual tabs. This approach allows users to access all tab content while preserving a consistent component height and page layout.

## Key Features

- Uses the Syncfusion Blazor `SfTab` component to display content in separate tabs.
- Sets the `Height` property of `SfTab` to `300px` to maintain a fixed-height tab content area.
- Uses `TabItems` to define the collection of tabs rendered by the component.
- Uses individual `TabItem` components to organize separate sections of content.
- Defines the visible text for each tab using the `TabHeader` component and its `Text` property.
- Provides lengthy content for each tab through `ContentTemplate`.
- Demonstrates a vertical scrollbar when the rendered content exceeds the fixed height of the Tabs component.
- Supports displaying lengthy tab content without increasing the overall height of the Tabs component.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `VerticalScrollbar.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `VerticalScrollbar`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Select the available tabs and scroll through content that exceeds the fixed height of the Tabs component.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory:

```bash
cd blazor-tab-vertical-scrollbar
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal after the application starts.
8. Select the available tabs and scroll through content that extends beyond the fixed tab height.

## Project Structure

`VerticalScrollbar.sln` — solution file used to open, build, and run the sample.

`VerticalScrollbar.csproj` — project file containing the application configuration and NuGet package references.

`Pages/Index.razor` — root feature page containing the `SfTab` component, tab items, tab headers, content templates, fixed height, and lengthy sample content.

`Pages/_Host.cshtml` — host page used to load the Blazor application.

`Program.cs` — application startup entry point.

`App.razor` — root Razor component of the application.

`_Imports.razor` — shared Razor namespace imports used by the application.

`appsettings.json` — application configuration settings.

`appsettings.Development.json` — development-environment configuration settings.

`README.md` — repository documentation and instructions for running the sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Tabs getting started documentation](https://blazor.syncfusion.com/documentation/tabs/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.