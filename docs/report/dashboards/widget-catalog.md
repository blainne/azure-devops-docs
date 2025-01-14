---
title: Catalog of widgets you can add to a dashboard
titleSuffix: Azure DevOps
description: Determine which widgets you want to add to your dashboards when working in Azure DevOps or Team Foundation Server  
ms.custom: dashboards
ms.technology: devops-analytics
ms.assetid: C9FD12C0-033E-4A4D-AF63-6EF67E7B4828
ms.topic: conceptual
ms.author: kaelli
author: KathrynEE
monikerRange: '>= tfs-2015'
ms.date: 07/14/2020
---

# Widget catalog 

[!INCLUDE [temp](../includes/version-ts-tfs-2015-2016.md)] 

Widgets display information and charts on dashboards. Many widgets are configurable or are scoped to a team or to the current user identity. Many of them are configurable and display information available from one or more data stores or charts maintained within the system. 
 

The following widgets are organized under the service they support. Widgets that derive their data from [Analytics](../powerbi/what-is-analytics.md) are annotated with **Analytics**. 
 

::: moniker range=">= azure-devops-2019"
- **Analytics**: indicates data is derived from [Analytics data](../powerbi/what-is-analytics.md)  
- **Project**: indicates you can select the project and team when configuring the widget
- **Team**: Indicates a widget that is scoped to a team  
- **User**: Indicates a widget that is scoped to a user identity 
::: moniker-end


::: moniker range=">=tfs-2015 <= tfs-2018"
- **Team**: Indicates a widget that is scoped to a team  
- **User**: Indicates a widget that is scoped to a user identity 
::: moniker-end


To add a widget to a dashboard or copy a widget from one dashboard to another, see [Add a widget to a dashboard](add-widget-to-dashboard.md).   
 

::: moniker range=">= azure-devops-2020"

<table valign="top">
<tbody valign="top">
<tr>
<td width="44%"> 
<strong>Boards</strong>
<ul>
<li><a href="#assigned-to-me-widget">Assigned to me</a></li>
<li><a href="#burndown-analytics-widget">Burndown chart</a> (Analytics)</li>
<li><a href="#burnup-analytics-widget">Burnup chart</a> (Analytics) </li>
<li><a href="#chart-wit-widget">Chart for work items</a></li>
<li><a href="#cfd-widget">Cumulative flow diagram</a> (Analytics) </li>
<li><a href="#cycle-time-widget">Cycle time</a> (Analytics)</li>
<li><a href="#lead-time-widget">Lead time</a> (Analytics) </li>
<li><a href="#new-work-item-widget" >New Work item</a></li>
<li><a href="#query-results-widget">Query results</a></li>
<li><a href="#query-tile-widget" >Query tile</a></li>
<li><a href="#sprint-burndown-analytics-widget">Sprint burndown</a> (Analytics) </li>
<li><a href="#sprint-burndown-widget">Sprint burndown - Legacy</a> </li>
<li><a href="#sprint-capacity-widget">Sprint capacity</a></li>
<li><a href="#sprint-overview-widget">Sprint overview</a> </li>
<li><a href="#velocity-widget">Velocity</a> (Analytics) </li>
<li><a href="#work-links-widget">Work links</a></li>
</ul>

</td>
<td width="28%">
<strong>Repos</strong>
<ul>
<li><a href="#code-tile-widget" data-raw-source="[Code tile](#code-tile-widget)">Code tile</a></li>
<li><a href="#pull-request-widget" data-raw-source="[Pull request](#pull-request-widget)">Pull request</a> </li>
</ul>
<br/>
<strong>Pipelines</strong>
<ul>
<li><a href="#build-history-widget" data-raw-source="[Chart for build history](#build-history-widget)">Chart for build history</a></li>
<li><a href="#deployment-status-widget" data-raw-source="[Deployment status](#deployment-status-widget)">Deployment status</a></li>
<li><a href="#release-definition-widget" data-raw-source="[Release pipeline overview](#release-definition-widget)">Release pipeline overview</a></li>
<li><a href="#test-trend-results-advanced" data-raw-source="[Test results trend (Advanced)](#test-trend-results-advanced)">Test results trend (Advanced)</a> (Analytics)</li>
<li><a href="#requirements-quality-widget" data-raw-source="[Requirements quality](#requirements-quality-widget)">Requirements quality</a></li>
</ul>
<br/>
<strong>Test Plans</strong>
<li><a href="#chart-test-plan-widget" data-raw-source="[Chart for test plans](#chart-test-plan-widget)">Chart for test plans</a></li>

</ul>
</td>
<td width="28%">
<strong>Other</strong>
<ul>
<li><a href="#embedded-webpage-widget" data-raw-source="[Embedded web page](#embedded-webpage-widget)">Embedded web page</a></li>
<li><a href="#markdown-widget" data-raw-source="[Markdown](#markdown-widget)">Markdown</a></li>
<li><a href="#other-links-widget" data-raw-source="[Other links](#other-links-widget)">Other links</a> </li>
<li><a href="#team-members-widget" data-raw-source="[Team members](#team-members-widget)">Team members</a> </li>
<li><a href="#visual-studio-widget" data-raw-source="[Visual Studio Shortcuts](#visual-studio-widget)">Visual Studio Shortcuts</a></li>
<li><a href="#how-to-widget" data-raw-source="[Welcome](#how-to-widget)">Welcome</a></li>
</ul>
</td>
</tr>
</tbody>
</table>

::: moniker-end


::: moniker range="azure-devops-2019"

<table valign="top">
<tbody valign="top">
<tr>
<td width="44%"> 
<strong>Boards</strong>
<ul>
<li><a href="#assigned-to-me-widget" data-raw-source="[Assigned to me](#assigned-to-me-widget)">Assigned to me</a></li>
<li><a href="#burndown-analytics-widget" data-raw-source="[Burndown chart](#burndown-analytics-widget)">Burndown chart</a> (Analytics)</li>
<li><a href="#burnup-analytics-widget" data-raw-source="[Burnup chart](#burnup-analytics-widget)">Burnup chart</a> (Analytics) </li>
<li><a href="#chart-wit-widget" data-raw-source="[Chart for work items](#chart-wit-widget)">Chart for work items</a></li>
<li><a href="#cfd-widget" data-raw-source="[Cumulative flow diagram](#cfd-widget)">Cumulative flow diagram</a> (Analytics) </li>
<li><a href="#cycle-time-widget" data-raw-source="[Cycle time](#cycle-time-widget)">Cycle time</a> (Analytics)</li>
<li><a href="#lead-time-widget" data-raw-source="[Lead time](#lead-time-widget)">Lead time</a> (Analytics) </li>
<li><a href="#new-work-item-widget" data-raw-source="[New Work item](#new-work-item-widget)">New Work item</a></li>
<li><a href="#query-results-widget" data-raw-source="[Query results](#query-results-widget)">Query results</a></li>
<li><a href="#query-tile-widget" data-raw-source="[Query tile](#query-tile-widget)">Query tile</a></li>
<li><a href="#sprint-burndown-widget" data-raw-source="[Sprint burndown](#sprint-burndown-widget)">Sprint burndown</a> </li>
<li><a href="#sprint-capacity-widget" data-raw-source="[Sprint capacity](#sprint-capacity-widget)">Sprint capacity</a></li>
<li><a href="#sprint-overview-widget" data-raw-source="[Sprint overview](#sprint-overview-widget)">Sprint overview</a> </li>
<li><a href="#velocity-widget" data-raw-source="[Velocity](#velocity-widget)">Velocity</a> (Analytics) </li>
<li><a href="#work-links-widget" data-raw-source="[Work links](#work-links-widget)">Work links</a></li>
</ul>

</td>
<td width="28%">
<strong>Repos</strong>
<ul>
<li><a href="#code-tile-widget" data-raw-source="[Code tile](#code-tile-widget)">Code tile</a></li>
<li><a href="#pull-request-widget" data-raw-source="[Pull request](#pull-request-widget)">Pull request</a> </li>
</ul>
<br/>
<strong>Pipelines</strong>
<ul>
<li><a href="#build-history-widget" data-raw-source="[Chart for build history](#build-history-widget)">Chart for build history</a></li>
<li><a href="#deployment-status-widget" data-raw-source="[Deployment status](#deployment-status-widget)">Deployment status</a></li>
<li><a href="#release-definition-widget" data-raw-source="[Release pipeline overview](#release-definition-widget)">Release pipeline overview</a></li>
<li><a href="#test-trend-results-advanced" data-raw-source="[Test results trend (Advanced)](#test-trend-results-advanced)">Test results trend (Advanced)</a> (Analytics)</li>
<li><a href="#requirements-quality-widget" data-raw-source="[Requirements quality](#requirements-quality-widget)">Requirements quality</a></li>
</ul>
</td>
<td width="28%">
<strong>Test Plans</strong>
<li><a href="#chart-test-plan-widget" data-raw-source="[Chart for test plans](#chart-test-plan-widget)">Chart for test plans</a></li>
</ul>
<strong>Other</strong>
<ul>
<li><a href="#embedded-webpage-widget" data-raw-source="[Embedded web page](#embedded-webpage-widget)">Embedded web page</a></li>
<li><a href="#markdown-widget" data-raw-source="[Markdown](#markdown-widget)">Markdown</a></li>
<li><a href="#other-links-widget" data-raw-source="[Other links](#other-links-widget)">Other links</a> </li>
<li><a href="#team-members-widget" data-raw-source="[Team members](#team-members-widget)">Team members</a> </li>
<li><a href="#visual-studio-widget" data-raw-source="[Visual Studio Shortcuts](#visual-studio-widget)">Visual Studio Shortcuts</a></li>
<li><a href="#how-to-widget" data-raw-source="[Welcome](#how-to-widget)">Welcome</a></li>
</ul>
</td>
</tr>
</tbody>
</table>

::: moniker-end

::: moniker range=">= azure-devops-2019"

> [!NOTE]  
> Widgets specific to a service are disabled if the service they depend on has been disabled. For example, if **Boards** is disabled, work tracking Analytics widgets are disabled and won't appear in the widget catalog. To re-enable a service, see [Turn an Azure DevOps service on or off](../../organizations/settings/set-services.md).

::: moniker-end


::: moniker range="tfs-2018"

<table valign="top">
<tbody valign="top">
<tr>
<td width="33%"> 
<strong>Work</strong>
<ul>
<li><a href="#assigned-to-me-widget" data-raw-source="[Assigned to me](#assigned-to-me-widget)">Assigned to me</a></li>
<li><a href="#chart-wit-widget" data-raw-source="[Chart for work items](#chart-wit-widget)">Chart for work items</a></li>
<li><a href="#new-work-item-widget" data-raw-source="[New Work item](#new-work-item-widget)">New Work item</a> </li>
<li><a href="#query-results-widget" data-raw-source="[Query results](#query-results-widget)">Query results</a></li>
<li><a href="#query-tile-widget" data-raw-source="[Query tile](#query-tile-widget)">Query tile</a></li>
<li><a href="#sprint-burndown-widget" data-raw-source="[Sprint burndown](#sprint-burndown-widget)">Sprint burndown</a> </li>
<li><a href="#sprint-capacity-widget" data-raw-source="[Sprint capacity](#sprint-capacity-widget)">Sprint capacity</a> </li>
<li><a href="#sprint-overview-widget" data-raw-source="[Sprint overview](#sprint-overview-widget)">Sprint overview</a></li>
<li><a href="#work-links-widget" data-raw-source="[Work links](#work-links-widget)">Work links</a></li>
</ul>
<strong>Code</strong>
<ul>
<li><a href="#code-tile-widget" data-raw-source="[Code tile](#code-tile-widget)">Code tile</a></li>
</ul>
</td>
<td width="33%">
<strong>Build & Release</strong>
<ul>
<li><a href="#pull-request-widget" data-raw-source="[Pull request](#pull-request-widget)">Pull request</a> </li>
<li><a href="#build-history-widget" data-raw-source="[Chart for build history](#build-history-widget)">Chart for build history</a></li>
<li><a href="#deployment-status-widget" data-raw-source="[Deployment status](#deployment-status-widget)">Deployment status</a></li>
<li>Release pipeline overview</li>
<li><a href="#requirements-quality-widget" data-raw-source="[Requirements quality](#requirements-quality-widget)">Requirements quality</a></li>
</ul>
<br/>
<strong>Test</strong>
<li><a href="#chart-test-plan-widget" data-raw-source="[Chart for test plans](#chart-test-plan-widget)">Chart for test plans</a></li>
<li><a href="#test-results-widget" data-raw-source="[Test results trend](#test-results-widget)">Test results trend</a></li>
<li>Test results trend (Advanced)</li>
</ul>
</td>
<td width="34%">
<strong>Other</strong>
<ul>
<li><a href="#embedded-webpage-widget" data-raw-source="[Embedded web page](#embedded-webpage-widget)">Embedded web page</a></li>
<li><a href="#markdown-widget" data-raw-source="[Markdown](#markdown-widget)">Markdown</a></li>
<li><a href="#other-links-widget" data-raw-source="[Other links](#other-links-widget)">Other links</a> </li>
<li><a href="#team-members-widget" data-raw-source="[Team members](#team-members-widget)">Team members</a> </li>
<li>Team room</li>
<li><a href="#visual-studio-widget" data-raw-source="[Visual Studio Shortcuts](#visual-studio-widget)">Visual Studio Shortcuts</a></li>
<li><a href="#how-to-widget" data-raw-source="[Welcome](#how-to-widget)">Welcome</a></li>
</ul>
</td>
</tr>
</tbody>
</table>

::: moniker-end



::: moniker range="tfs-2017"

<table valign="top">
<tbody valign="top">
<tr>
<td width="33%"> 
<strong>Work</strong>
<ul>
<li><a href="#assigned-to-me-widget" data-raw-source="[Assigned to me](#assigned-to-me-widget)">Assigned to me</a> </li>
<li><a href="#chart-wit-widget" data-raw-source="[Chart for work items](#chart-wit-widget)">Chart for work items</a></li>
<li><a href="#new-work-item-widget" data-raw-source="[New Work item](#new-work-item-widget)">New Work item</a> </li>
<li><a href="#query-results-widget" data-raw-source="[Query results](#query-results-widget)">Query results</a></li>
<li><a href="#query-tile-widget" data-raw-source="[Query tile](#query-tile-widget)">Query tile</a></li>
<li><a href="#sprint-burndown-widget" data-raw-source="[Sprint burndown](#sprint-burndown-widget)">Sprint burndown</a> </li>
<li><a href="#sprint-capacity-widget" data-raw-source="[Sprint capacity](#sprint-capacity-widget)">Sprint capacity</a> </li>
<li><a href="#sprint-overview-widget" data-raw-source="[Sprint overview](#sprint-overview-widget)">Sprint overview</a></li>
<li><a href="#work-links-widget" data-raw-source="[Work links](#work-links-widget)">Work links</a></li>
</ul>
<strong>Code</strong>
<ul>
<li><a href="#code-tile-widget" data-raw-source="[Code tile](#code-tile-widget)">Code tile</a></li>
</ul>
</td>
<td width="33%">
<strong>Build &amp; Release</strong>
<ul>
<li><a href="#pull-request-widget" data-raw-source="[Pull request](#pull-request-widget)">Pull request</a> </li>
<li><a href="#build-history-widget" data-raw-source="[Chart for build history](#build-history-widget)">Chart for build history</a></li>
<li><a href="#deployment-status-widget" data-raw-source="[Deployment status](#deployment-status-widget)">Deployment status</a></li>
<li><a href="#requirements-quality-widget" data-raw-source="[Requirements quality](#requirements-quality-widget)">Requirements quality</a></li>
</ul>
<br/>
<strong>Test</strong>
<ul>
<li><a href="#chart-test-plan-widget" data-raw-source="[Chart for test plans](#chart-test-plan-widget)">Chart for test plans</a></li>
<li><a href="#test-results-widget" data-raw-source="[Test results trend](#test-results-widget)">Test results trend</a></li>
</ul>
</td>
<td width="34%">
<strong>Other</strong>
<ul>
<li><a href="#embedded-webpage-widget" data-raw-source="[Embedded web page](#embedded-webpage-widget)">Embedded web page</a></li>
<li><a href="#markdown-widget" data-raw-source="[Markdown](#markdown-widget)">Markdown</a></li>
<li><a href="#other-links-widget" data-raw-source="[Other links](#other-links-widget)">Other links</a> </li>
<li><a href="#team-members-widget" data-raw-source="[Team members](#team-members-widget)">Team members</a></li>
<li><a href="#team-room-widget" data-raw-source="[Team room](#team-room-widget)">Team room</a></li>
<li><a href="#visual-studio-widget" data-raw-source="[Visual Studio Shortcuts](#visual-studio-widget)">Visual Studio Shortcuts</a></li>
<li><a href="#how-to-widget" data-raw-source="[Welcome](#how-to-widget)">Welcome</a></li>
</ul>
</td>
</tr>
</tbody>
</table>

::: moniker-end


::: moniker range="tfs-2015"

<table valign="top">
<tbody valign="top">
<tr>
<td width="33%"> 
<strong>Work</strong>
<ul>
<li><a href="#assigned-to-me-widget">Assigned to me</a> </li>
<li><a href="#chart-wit-widget" data-raw-source="[Chart for work items](#chart-wit-widget)">Chart for work items</a></li>
<li><a href="#new-work-item-widget" data-raw-source="[New Work item](#new-work-item-widget)">New Work item</a> </li>
<li><a href="#query-results-widget" data-raw-source="[Query results](#query-results-widget)">Query results</a></li>
<li><a href="#query-tile-widget" data-raw-source="[Query tile](#query-tile-widget)">Query tile</a></li>
<li><a href="#sprint-burndown-widget" data-raw-source="[Sprint burndown](#sprint-burndown-widget)">Sprint burndown</a> </li>
<li><a href="#sprint-capacity-widget" data-raw-source="[Sprint capacity](#sprint-capacity-widget)">Sprint capacity</a> </li>
<li><a href="#sprint-overview-widget" data-raw-source="[Sprint overview](#sprint-overview-widget)">Sprint overview</a> </li>
<li><a href="#work-links-widget" data-raw-source="[Work links](#work-links-widget)">Work links</a></li>
</ul>
</td>
<td width="33%">
<strong>Code</strong>
<ul>
<li><a href="#code-tile-widget" data-raw-source="[Code tile](#code-tile-widget)">Code tile</a></li>
</ul>
<br/>
<strong>Build</strong>
<ul>
<li><a href="#pull-request-widget" data-raw-source="[Pull request](#pull-request-widget)">Pull request</a> </li>
<li><a href="#build-history-widget" data-raw-source="[Chart for build history](#build-history-widget)">Chart for build history</a></li>
</ul>
<br/>
</td>
<td width="34%">
<strong>Other</strong>
<ul>
<li><a href="#markdown-widget" data-raw-source="[Markdown](#markdown-widget)">Markdown</a></li>
<li><a href="#other-links-widget" data-raw-source="[Other links](#other-links-widget)">Other links</a></li>
<li><a href="#team-members-widget" data-raw-source="[Team members](#team-members-widget)">Team members</a> </li>
<li><a href="#team-room-widget" data-raw-source="[Team room](#team-room-widget)">Team room</a> </li>
<li><a href="#visual-studio-widget" data-raw-source="[Visual Studio Shortcuts](#visual-studio-widget)">Visual Studio Shortcuts</a></li>
<li><a href="#how-to-widget" data-raw-source="[Welcome](#how-to-widget)">Welcome</a></li>
</ul>
</td>
</tr>
</tbody>
</table>


> [!NOTE]   
> Widgets and multiple dashboards are not supported features in TFS 2013, instead, you can [pin items to a team homepage](team-dashboard.md).  Consider [upgrading to the latest TFS version](https://visualstudio.microsoft.com/downloads/) to get access to the widget catalog and [multiple team dashboards](dashboards.md).  


::: moniker-end


::: moniker range=">= azure-devops-2019"
## Azure Boards widgets 
::: moniker-end

::: moniker range=">= tfs-2015 <= tfs-2018"
## Work widgets 
::: moniker-end

::: moniker range=">= tfs-2017"
<a id="assigned-to-me-widget"></a>
### Assigned to me  
 
![Assigned to me widget](media/widget-assigned-to-me.png)  

Displays the list of work items currently assigned to the currently logged in user. The list ignores closed or deleted work items.
 
----
::: moniker-end

::: moniker range=">= azure-devops-2019"
### Burndown chart 
<a id="burndown-analytics-widget"></a>  
	
![Burndown chart widget](media/widget-burndown-chart.png)  
  
Adds a tile that displays a burndown chart which you can configure to span one or more teams, work item types, and time period. With it, you can create a release burndown, sprint burndown, or any burndown that spans teams and sprints. To learn more, see [Configure a Burndown or Burnup widget](configure-burndown-burnup-widgets.md).  

----

### Burnup chart  
<a id="burnup-analytics-widget"></a> 	

![Burnup chart widget](media/widget-burnup-chart.png)    

Adds a tile that displays a burnup chart which you can configure to span one or more teams, work item types, and time period. With it, you can create a release burnup, sprint burnup, or any burnup that spans teams and sprints. To learn more, see [Configure a Burndown or Burnup widget](configure-burndown-burnup-widgets.md).  

----
::: moniker-end

### Chart for work items  

<a id="chart-wit-widget"></a> 
	
![Chart work item query widget](media/widget-chart-work-query.png)  

Adds a tile to display a progress or trend chart that builds off a shared work item query.  
From the configuration dialog, select a shared query and [specify the chart type and values](charts.md#add-chart-widget).   


::: moniker range="tfs-2015"
Requires TFS 2015.2 or later version. For TFS 2015.1 and earlier versions, see [Add charts to a dashboard](add-charts-to-dashboard.md#work-item-query) to add shared query charts to a dashboard.    
::: moniker-end

----


::: moniker range=">= azure-devops-2019"
<a id="cfd-widget"></a> 

### Cumulative flow diagram   

![Cumulative flow diagram widget](media/widget-cfd-chart.png)  

Displays the cumulative flow of backlog items based on the time frame, team, backlog level and swimlane you select. 

From the configuration dialog, [specify the team, backlog level, and other parameters you want](cumulative-flow.md#configure-widget).

Hover over each color within the chart to see the count of items for a particular Kanban column. 

----

<a id="cycle-time-widget"></a> 
### Cycle time  

![Cycle time widget](media/widget-cycle-time.png)  

Displays the cycle time of work items closed in a specified timeframe for a single team and backlog level. The cycle time of a work item is defined as the time taken to close a work item after work on it has started. 

Each marker on the chart corresponds to one or more work items with a particular cycle time. The lower the cycle time, the faster work is progressing through your development pipeline. To learn more, see [Configure a Burndown or Burnup widget](configure-burndown-burnup-widgets.md). 

----

<a id="lead-time-widget"></a> 
### Lead time  

![Lead time widget](media/widget-lead-time.png)   
 
Displays the lead time of work items closed in a specified timeframe for a single team and backlog level. The lead time of a work item is defined as the time taken to close a work item after it was created.

Each marker on the chart corresponds to one or more work items with a particular lead time. The lower the lead time, the faster work is being delivered to the customer.

To learn more, see [Lead time and cycle time control charts](cycle-time-and-lead-time.md). 
  
----

::: moniker-end


<a id="new-work-item-widget"></a>
### New Work item
	
![New work item widget](media/widget-new-work-items.png)

Enables you to add work items from the dashboard. You [use work items to plan and track work](../../boards/backlogs/add-work-items.md).  <br/><br/>

Work items that you add using this widget are automatically scoped to the team's default area path and the team's current sprint or default iteration. To change team defaults, see [About teams and Agile tools](../../organizations/settings/about-teams-and-settings.md).

::: moniker range="tfs-2015"
Requires TFS 2015.1 or later version.    
::: moniker-end


----

<a id="other-links-widget"></a> 
### Other links 

![Other links widget](media/widget-other-links.png)  

Provides links to the following features: 
- Opens a form to initiate a [request to provide feedback](../../project/feedback/get-feedback.md?toc=%252fazure%252fdevops%252fproject%252ffeedback%252ftoc.json).
- Opens the team's quick dialog to add or modify the active sprints or iteration paths for your team. To learn more see [Define sprints](../../boards/sprints/define-sprints.md).
- Opens the team's quick dialog to modify your [team's area path](../../organizations/settings/set-area-paths.md).

::: moniker range=">= tfs-2015 <= tfs-2018"
The following links are displayed when the corresponding resource is configured for the project: 

![Other links widget, TFS-2018 and earlier versions.](media/widget-other-links-tfs.png)  

- [View project portal](/previous-versions/azure/devops/report/sharepoint-dashboards/share-information-using-the-project-portal) (opens either a SharePoint site or URL that's been configured as the project's portal.  
- [View process guidance](../../project/configure-or-redirect-process-guidance.md) (opens either a SharePoint site or URL that's been configured as the project's process guidance.  
- [View reports](../sql-reports/reporting-services-reports.md) (opens SQL Server Reporting Services). To add or update reports for a project, see [Add reports to a project](../admin/add-reports-to-a-team-project.md). 

::: moniker-end

----


<a id="query-results-widget"></a> 
### Query results 
	
![Query results widget](media/widget-query-results.png)

Adds a configurable tile that lists the results of a shared query. 
From the configuration dialog, select either a team favorite or shared query.  
To create a shared query, see [Use the query editor to list and manage queries](../../boards/queries/using-queries.md). 

----


<a id="query-tile-widget"></a> 
### Query tile 

![Query tile widget](media/widget-query-tile.png)

Adds a configurable tile to display the summary of a shared query results.
From the configuration dialog, select either a team favorite or shared query. You can optionally specify rules to change the query tile color based on the number of work items returned by the query. 
To create a shared query, see [Use the query editor to list and manage queries](../../boards/queries/using-queries.md). 
  
----

::: moniker range=">= azure-devops-2020"

<a id="sprint-burndown-analytics-widget"></a>

### Sprint burndown (Analytics)  

![Sprint burndown widget](media/widget-sprint-burndown-analytics.png)

Adds a team's burndown chart for a sprint to the dashboard. This widget is based on Analytics data. You have several configuration options for this widget, including selecting a team, iteration, and time period. Teams [use the burndown chart to mitigate risk and check for scope creep](configure-sprint-burndown.md) throughout the sprint cycle. 

----

<a id="sprint-burndown-widget"></a>

<a id="burndown-widget"></a> 

### Sprint burndown (Legacy) 

![Sprint burndown widget, legacy versions.](media/widget-sprint-burndown-legacy.png)

Adds the team's burndown chart for the current sprint to the dashboard. This chart always displays data for the current sprint. Teams [use the burndown chart to mitigate risk and check for scope creep](configure-sprint-burndown.md) throughout the sprint cycle. 

::: moniker-end

::: moniker range=">= tfs-2015 < azure-devops-2020"


<a id="sprint-burndown-widget"></a>

<a id="burndown-widget"></a> 

### Sprint burndown 

![Sprint burndown widget, Azure DevOps Server 2019 and earlier versions.](media/widget-sprint-burndown.png)

Adds the team's burndown chart for the current sprint to the dashboard. This chart always displays data for the current sprint.
Teams [use the burndown chart to mitigate risk and check for scope creep](configure-sprint-burndown.md) throughout the sprint cycle. 

::: moniker-end

----



<a id="sprint-capacity-widget"></a> 

### Sprint capacity 

![Sprint capacity widget](media/widget-sprint-capacity.png)

Inserts the team's capacity bar chart for the current sprint. 
To plan and monitor their sprint resources, team set capacity and update Remaining Work throughout the sprint. See [Set capacity](../../boards/sprints/set-capacity.md).  

----


<a id="sprint-overview-widget"></a> 
### Sprint overview 

![Sprint overview widget](media/widget-sprint-overview.png)

 
::: moniker range=">= tfs-2017"

Inserts a configurable overview of sprint progress. You can choose between a count of story points or number of work items. Teams [plan their sprints by defining sprints](../../organizations/settings/set-iteration-paths-sprints.md) and [assigning backlog items to an iteration](../../boards/sprints/assign-work-sprint.md). 
::: moniker-end

::: moniker range=" tfs-2015"

Inserts a visual overview of sprint progress indicating the number of backlog items in progress, completed, or not started. Teams [plan their sprints by defining sprints](../../organizations/settings/set-iteration-paths-sprints.md) and [assign backlog items to an iteration](../../boards/sprints/assign-work-sprint.md). 
::: moniker-end

----


::: moniker range=">= azure-devops-2019"
<a id="velocity-widget"></a> 

### Velocity   

![Sprint velocity widget](media/widget-velocity.png)

The velocity widget tracks a team's capacity to deliver work sprint after sprint. You configure the widget by selecting a team, a work item type, an aggregation field, and the number of sprints. The widget takes advantage of Analytics data. You can track the velocity for a single team, not multiple teams.  

For additional guidance, see [Velocity](team-velocity.md). 

----

::: moniker-end

<a id="work-links-widget"></a> 
### Work links 

![Work links widget](media/widget-work-links.png)  
Provides quick access to open the following Agile tools and team resources:

- [Backlog](../../boards/backlogs/create-your-backlog.md)  
- [Kanban board](../../boards/boards/kanban-basics.md)  
- [Task board](../../boards/sprints/task-board.md)  
- [Queries](../../boards/queries/using-queries.md)  

----



::: moniker range=">= azure-devops-2019"
## Azure Repos widgets 
::: moniker-end

::: moniker range=">= tfs-2015 <= tfs-2018"
## Code widgets
::: moniker-end

<a id="code-tile-widget"></a> 
### Code tile    

![Code tile widget](media/widget-code-tile.png)

Adds a configurable tile to display the summary of a code folder or Git repository. To configure, simply choose the added tile, select a repository, select a branch (Git only) and select a path. The code tile supports both TFVC and Git repositories. 

::: moniker range="tfs-2015"
Requires TFS 2015.1 or later version.
::: moniker-end

----

<a id="pull-request-widget"></a> 
### Pull request 

![Pull request widget](media/widget-catalog-pull-request.png)

Adds a configurable tile to display active pull requests requested by the team, or assigned to or requested by the person logged in. Select the Git repository for the pull requests of interest. 

You need to add a widget for each Git repository of interest.
To learn more about pull requests, see [Review code with pull requests](../../repos/git/pull-requests.md).


::: moniker range="tfs-2015"
Requires TFS 2015.2 or later version.
::: moniker-end


----


::: moniker range=">= azure-devops-2019"
## Azure Pipelines widgets 
::: moniker-end

::: moniker range=">= tfs-2015 <= tfs-2018"
## Build and Release widgets
::: moniker-end


<a id="build-history-widget"></a> 
### Chart for build history  

![Build history widget](media/widget-build-history-chart.png)   

Adds a tile to display a histogram of all builds run for the configured build pipeline.
From the configuration dialog, select the build you want to monitor. 
Hover over a bar to learn how long the build took to complete. Choose the bar to open the summary for that specific build. Bar color indicates: green-completed, red-failed, and yellow-completed without tests. 


::: moniker range="tfs-2015"
Requires TFS 2015.2 or later version. For TFS 2015.1 and earlier versions, see [Add charts to a dashboard](add-charts-to-dashboard.md#build-history) to add a build summary chart to a dashboard. 
::: moniker-end

----

::: moniker range=">= tfs-2017"

<a id="deployment-status-widget"></a> 
### Deployment status 

![Deployment status widget](media/widget-deployment-status.png)  

Configurable widget that shows a consolidated view of the deployment status and test pass rate across multiple environments for a recent set of builds. You configure the widget by specifying a build pipeline, branch, and linked release pipelines. 

In order view the test summary across multiple environments in a release, the widget provides a matrix view of each environment and corresponding test pass rate. You can choose any cell to see a more [detailed](../../pipelines/test/review-continuous-test-results-after-build.md) view for the selected environment.

::: moniker-end
::: moniker range="tfs-2017"
Requires TFS 2017.1 or later version. 
::: moniker-end
::: moniker range=">= tfs-2017"

----

::: moniker-end

::: moniker range=">= azure-devops-2019"

<a id="release-definition-widget"></a> 
### Release pipeline overview 

![Release pipeline overview widget](media/widget-release-definitions.png)  

Configurable widget that you can use to view and track the status of a release pipeline. This widget shows the release as a series of environments, with the name of the release and the date or time it was started. The color of the heading and the icon in each environment indicate the current status of the release, which are the same as are used on the **Releases** page. Select a release pipeline in the left column to filter the list to just releases for that pipeline.

---- 
::: moniker-end

 
::: moniker range=">= tfs-2017"

<a id="requirements-quality-widget"></a> 
### Requirements quality 
<a id="requirements-quality-widget"></a>  

![Requirements quality widget](media/widget-requirements-quality.png)  

Configurable widget that you can use to track quality continuously from a build or release pipeline. The widget shows the mapping between a requirement and latest test results executed against that requirement. It provides insights into requirements traceability e.g. requirements not meeting the quality, requirements not tested etc. To learn more about setting up traceability see [Requirements traceability](../../pipelines/test/requirements-traceability.md) 

---- 
::: moniker-end


::: moniker range=">= azure-devops-2019"
## Azure Test Plans widgets 
::: moniker-end

::: moniker range=">= tfs-2017 <= tfs-2018"
## Test widgets  
::: moniker-end

::: moniker range=">= tfs-2017"

<a id="chart-test-plan-widget"></a> 

### Chart for test plans  
	
![Chart for test plans](media/widget-chart-test-plans.png)  

Adds a configurable widget that lets you track the progress of test case authoring or status of test execution for tests in a test plan. Get started by selecting a test plan and a test suite. Then select test case chart for test authoring progress or test results for test execution progress. Finally, select the chart type and the pivots. 

To learn more, see [Track your test results](../../test/track-test-status.md).

::: moniker-end
::: moniker range="tfs-2017"
Requires TFS 2017.2 or later version.
::: moniker-end
::: moniker range=">= tfs-2017"

----

::: moniker-end

::: moniker range=">= tfs-2017"

<a id="test-results-widget"></a>
### Test results trend 

![Test results trend widget](media/widget-test-results-trend.png)

Adds a configurable tile that displays the trend of test results, such as passed or failed tests, for the selected build or release pipeline. The widget helps you visualize the test trends over a period of time, thereby surfacing patterns about test failures, test duration etc. 

From the configuration dialog, select the build or release whose test results you'd like to monitor. There are multiple chart options to choose from (Line, Column & Stacked Column) based on your preference. Optionally you can map the trend of test duration on the existing chart by adding a secondary line chart. 

The widget provides the basic trend of the test results. To get deeper insights and higher configurability view [Test Analytics](../../pipelines/test/test-analytics.md) 

---- 
::: moniker-end

::: moniker range=">= azure-devops-2019"
<a id="test-trend-results-advanced"></a>

### Test Results Trend (Advanced)

<!--- QUESTION - Is this available on 2019? --> 

> [!div class="mx-imgBorder"]  
> ![Test results trend widget, Advanced version based on Analytics service.](media/widget-test-results-trend-advanced.png)
 
The Test Results Trend (Advanced) widget provides near real-time visibility into test data for multiple builds and releases. The widget shows a trend of your test results for selected pipelines. You can use it to track the daily count of test, pass rate, and test duration. Tracking test quality over time and improving test collateral is key to maintaining a healthy DevOps pipeline.

The widget supports tracking advanced metrics for one or more build pipelines or release pipelines. The widget also allows filtering of test results by outcome, stacking metrics, and more. 

To learn more, see [Configure the Test Results Trend (Advanced) widget](./configure-test-results-trend.md).

---- 
::: moniker-end



## Informational content and other links 


::: moniker range=">= tfs-2017"

<a id="embedded-webpage-widget"></a> 
### Embedded web page 

![Embedded web page widget](media/embedded-web-page-widget.png)

Adds a configurable tile to display the contents of a web page. Only webpages that allow [iframe embedding](https://go.microsoft.com/fwlink/?LinkId=808035) are supported.

----
::: moniker-end


<a id="markdown-widget"></a> 
<a id="markdown"></a>
### Markdown 

![Markdown widget](media/widget-markdown-tile.png)

::: moniker range=">= tfs-2017"
Adds a configurable tile to display any type of information, guidance, or links that you want. You can also configure the widget to point to a file stored in your repository. From the configuration dialog, add the information you want to share with your team. To learn more, see [Add Markdown to a dashboard](add-markdown-to-dashboard.md). 
::: moniker-end

::: moniker range="tfs-2015"
Adds a configurable tile to display any type of information, guidance, or links that you want. From the configuration dialog, add the information you want to share with your team. To learn more, see [Add Markdown to a dashboard](add-markdown-to-dashboard.md). 

Requires TFS 2015.1 or later version. For TFS 2015.2 or later versions, you can configure the widget to point to a file stored in your repository.   
::: moniker-end

---- 


<a name="team-members-widget"></a> 
### Team members 

![Team members widget](media/widget-team-members.png)

Shows team member profiles and, on-hover, their user alias.
For team admins, supports access to the quick dialog to [add or remove team members](../../organizations/settings/add-teams.md). 

> [!NOTE]  
> This widget is a convenient way to add team members to specific teams within projects.  If you remove it, you can still [add members to your team from the team administration page](../../organizations/settings/add-teams.md#add-team-members). 

::: moniker range="tfs-2015"
Requires TFS 2015.1 or later version.    
::: moniker-end

----

::: moniker range=">= tfs-2015 <= tfs-2017"

<a id="team-room-widget"></a> 
### Team room  

![Team room widget](media/widget-team-room.png)

Provides status and access to [team rooms](/previous-versions/azure/devops/notifications/collaborate-in-a-team-room). Available for TFS 2015.1 through TFS 2017.2 versions.  
  
Team rooms support increased team productivity by providing a space to discuss work in progress, ask questions, share status, and clarify issues that arise. Team administrators can create additional team rooms.  

> [!NOTE]  
> Team Rooms have been deprecated as described in [Deprecation of Team Rooms](https://devblogs.microsoft.com/devops/deprecation-of-the-team-rooms-in-team-services-and-tfs/) blog post. Several good solutions are available that integrate well with TFS that support notifications and chat, such as [Microsoft Teams](https://marketplace.visualstudio.com/items?itemName=ms-vsts.vss-services-teams) and [Slack](../../service-hooks/services/slack.md).  

----

::: moniker-end


<a id="visual-studio-widget"></a> 
### Visual Studio Shortcuts 

![Visual Studio widget](media/widget-visual-studio.png)

Provides links to open or download Visual Studio. The Visual Studio IDE client comes with the [Team Explorer plug-in](../../user-guide/work-team-explorer.md) which provides quick access to several features (some of which aren't available through the web portal).

::: moniker range="tfs-2015"
Requires TFS 2015.1 or later version.
::: moniker-end

----


<a id="how-to-widget"></a>
### Welcome 

![How to links widget](media/widget-how-to-links.png)

Provides links to the **Boards/Boards (Work/Boards)**, **Repos (Code)**, and **Pipelines (Build or Build-Release)** pages and reference documentation on how to add charts.


::: moniker range="tfs-2015"
Requires TFS 2015.1 or later version.
::: moniker-end

----


## Marketplace widgets

You may find additional widgets of interest from the [Marketplace](https://marketplace.visualstudio.com/search?term=webpage%20widget&target=VSTS&sortBy=Relevance).  

If your organization owner or project collection administrator disables a marketplace widget, you'll see the following image: 

<img src="media/widget-catalog-disabled-widget.png" alt="Disabled widget extension notification" />   

To regain access to it, request your admin to reinstate or reinstall the widget. 

## Extensibility 

Using the REST API service, you can [create a dashboard widget](../../extend/develop/add-dashboard-widget.md). To learn more about the REST APIs for dashboards and widgets, see [Dashboards (API)](/rest/api/azure/devops/dashboard/dashboards).

<a id="related-notes"></a>  

## Related articles

- [Add, rename, and delete dashboards](dashboards.md)  
- [Add charts and widgets to a dashboard](add-widget-to-dashboard.md)  
- [Add Markdown to a dashboard](add-markdown-to-dashboard.md)
