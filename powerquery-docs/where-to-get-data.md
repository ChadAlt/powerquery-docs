---
title: Where to get data
description: Describes the process of getting data for Power Query from various Microsoft products.
author: DougKlopfenstein


ms.topic: conceptual
ms.date: 3/2/2022
ms.author: dougklo

LocalizationGroup: reference
---

# Where to get data

Getting data from available data sources is usually the first encounter you have with Power Query. This article provides basic steps for getting data from each of the Microsoft products that include Power Query.

>[!Note]
> Each of these Power Query get data experiences contain different feature sets. More information: [Where can you use Power Query?](power-query-what-is-power-query.md#where-can-you-use-power-query)

## Get data in Power BI Desktop

The procedures for where to start getting data in Power BI Desktop are described in [Data sources in Power BI Desktop](/power-bi/connect-data/desktop-data-sources).

In Power BI Desktop, you can also directly select an Excel worksheet, a Power BI dataset, a SQL server database, or Dataverse data without using the **Get data** option. You can also enter data directly in a table, or select from a data source that was recently used.

![Image of the Data field in the Home ribbon of Power BI Desktop](media/where-to-get-data/power-bi-desktop-data-select.png)

## Get data in Excel (Windows or Mac)

To get data in Excel for Windows or Excel for Mac:

1. From the **Data** ribbon, select **Get Data**.

2. Scroll through the category selections in the get data context menu, and select the connector you want to use.

   ![Image shows the Get Data drop-down list of categories and the connectors shown under the From File category.](media/where-to-get-data/get-data-excel.png)

You'll then be asked to fill out information that's required for you to access the data. Go to the [individual connector articles](connectors/index.md) for more information about this required information.

In Excel, you can also directly select Text/CVS, Web, and Excel worksheet data without using the **Get Data** option. You can also select from a data source that was recently used and from existing connections or tables.

>[!Note]
>Not all Excel versions support all of the same Power Query connectors. For a complete list of the Power Query connectors supported by all versions of Excel for Windows and Excel for Mac, go to [Power Query data sources in Excel versions](https://support.microsoft.com/en-us/office/power-query-data-sources-in-excel-versions-e9332067-8e49-46fc-97ff-f2e1bfa0cb16).

## Get data in Power BI service

To get data in Power BI service:

1. On the left side of Power BI service, select **Workspaces** (but not **My Workspace**)

2. From the Workspace context menu, select the workspace you want to use.

3. From the workspace (in this example, TestWorkspace01), select the context menu next to **+New**.

4. From the **New** context menu, select **Dataflow**.

    [![Image with text workspace open, the context menu for new open, and dataflow emphasized.](media/where-to-get-data/workspace-dataflow.png)](media/where-to-get-data/workspace-dataflow.png#lightbox)

5. From **Define new tables**, select **Add new tables**.

6. Select the connector from the list of data sources.

## Get data in Power Apps

There are several places in Power Apps where you can get data, either by importing data to a table or by creating a dataflow.

To import data to a new table in Power Apps:

1. On the left side of Power Apps, select **Dataverse** > **Tables**.

2. In the **Tables** pane, at the top left, select **Data** > **Get data**.

   [![Image with Dataverse tables open, the data context menu open, with the get data option emphasized.](media/where-to-get-data/get-data-power-apps.png)](media/where-to-get-data/get-data-power-apps.png#lightbox)

   You can also choose to get data directly from an Excel worksheet without using the **Get data** option.

   [![Image with Dataverse tables open, the data context menu open, with the get data from Excel option emphasized.](media/where-to-get-data/get-data-excel-powerapps.png)](media/where-to-get-data/get-data-excel-powerapps.png#lightbox)

3. Select the connector from the list of data sources.

To import data to an existing table in Power Apps:

1. On the left side of Power Apps, select **Dataverse** > **Tables**.

2. In the **Tables** pane, either:
   * Select a table in the **Tables** pane that you want to import data to, and then select **Data** > **Get data**.

      ![Image with Dataverse tables open, a table selected, the data context menu open, with the get data option emphasized.](media/where-to-get-data/table-get-data.png)

   * Open the table to its individual pane, and then select **Data** > **Get data**.

      ![Image with Dataverse tables open, an individual table open in a pane, the data context menu open, with the get data option emphasized.](media/where-to-get-data/table-address-get-data.png)

   In either case, you can also choose to get data from an Excel worksheet without using the **Get data** option.

   ![Image with Dataverse tables open, and individual table open in a pane,the data context menu open, with the get data from Excel option emphasized.](media/where-to-get-data/table-data-from-excel.png)

3. Select the connector from the list of data sources.

To get data in Power Apps when creating a dataflow:

1. On the left side of Power Apps, select **Dataverse** > **Dataflows**.

2. If a dataflow already exists:

   1. Double-click on the dataflow.
   1. From the Power Query editor, select **Get data**.
   1. Select the connector from the list of data sources.

3. If no dataflow exists and you want to create a new dataflow:

   1. Select **New dataflow**.
   1. In the **New dataflow** dialog box, enter a name for your new dataflow.

      [![Image of the New dataflow dialog box, with the name text box filled in.](media/where-to-get-data/new-dataflow-powerapps.png)](media/where-to-get-data/new-dataflow-powerapps.png#lightbox)

   1. Select **Create**.
   1. Select the connector from the list of data sources.

## Get data in Dynamics 365 Customer Insights

To get data in Customer Insights:

1. On the left side of Customer Insights, select **Data** > **Data sources**.

   [![Image with Data sources open, and Add data source emphasized.](media/where-to-get-data/add-data-source-ci.png)](media/where-to-get-data/add-data-source-ci.png#lightbox)

2. In the **Data sources** pane, select **Add data source**.

3. In **Choose your import method**, choose **Microsoft Power Query**.

4. In **Save data source as**, enter a name for your data source.

   [![Image with Choose you import method open, with Microsoft Power Query selected, and MyNewDataSource set for Save data source as](media/where-to-get-data/choose-import-method.png)](media/where-to-get-data/choose-import-method.png#lightbox)

5. Select **Next**.

6. Select the connector from the list of data sources.

## Get data in Analysis Services

With Analysis Services, a solution is developed in Visual Studio with the Analysis Services projects extension. The solution is then deployed to SQL Server Analysis Services, Azure Analysis Services, or a Power BI Premium workspace.

The Analysis Services documentation contains the following information that describes the process for getting data:

* To set up a Visual Studio solution with the Analysis Services projects extension: [Create a tabular model project](/analysis-services/tutorial-tabular-1400/as-lesson-1-create-a-new-tabular-model-project)

* To get data: [Get data](/analysis-services/tutorial-tabular-1400/as-lesson-2-get-data)

## Get data in Power Automate

There are a couple of places in Power Automate where you can get data, either by importing tables or in process adviser.

To get data by importing tables:

1. On the left side of Power Automate, select **Data** > **Tables**. At this point, a new tab with Power Apps will open in your browser.

2. In the Power Apps tab, follow the instructions for importing data to either a new table or to an existing table in the [Power Apps](#get-data-in-power-apps) section.

For information about how to get data in process advisor, go to [Connect to a data source](/power-automate/process-mining-processes-and-data#connect-to-a-data-source).

## Get data in Azure Data Factory

Azure Data Factory doesn't use the same Power Query get data interface as the other apps described in this article. Instead, Azure Data Factory uses its own built-in functionality to import data.

However, Azure Data Factory does use Power Query to transform data in data wrangling. The following Azure Data Factory articles describe how to use Power Query for data wrangling:

* [What is data wrangling?](/azure/data-factory/wrangling-overview)
* [Power Query activity in Azure Data Factory](/azure/data-factory/control-flow-power-query-activity)
* [Prepare data with data wrangling](/azure/data-factory/wrangling-tutorial)

## Get data in SQL Server Integration Services

SQL Server Integration Services (SSIS) doesn't use the same Power Query get data interface as the other apps described in this article. Instead, SSIS uses its own built-in functionality to import data.

For information on installing, configuring, and using the Power Query Source for SSIS, go to [Power Query Source](/sql/integration-services/data-flow/power-query-source).
