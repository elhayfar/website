---
title: Paperless processes using zira digital forms
subtitle: Use forms to digitize manual operations, use metrics and unit of measures in order to trigger alerts and visualize your data
tags: [features, featured]
author: alex
---
#### Overview

Digitizing pen and paper processes brings instantaneous value and operational benefits to an organization.

- Eliminate the need of sensors. use digital forms to measure any kind of data
- Rule Triggers can be used to initiate business flows like alerts, reports and even automated tasks 
- Form data will be available and searchable 
- Data visualization and dashboards are supported like any other data-source
- Can be attached to a channel and used as part of teams daily routine

Unlike other digital forms platforms we not support only textual fields but actually provide a way to log normalized data with readable names and unit of measures and even calculated fields. this will allow later to use the form output as actual data that can be easily visualized and used as a trigger for following business processes

#### Example use cases

##### Quality control
Quality parameters that are logged using digital forms will allow to notify in real time about important incidents, moreover, the communication about the incident will happen within zira feed and enable QC person, operators and supervisors to immediately act on the subject

Quality parameters will be logged in zira, searchable and available in click. the quality parameters can later visualized as quality KPIs or charts that show the quality parameters over time. 

Display KPIs by facility, machine, operator or shift. trigger task automatically upon new incident 

{% include image.html noBorder="true" img="quality-form.png" lightbox="true" alt="form collector" caption="form collector" %}

##### OEE (Overall Equipment Effectiveness) 

OEE is simple KPI that takes into account three parameters:
- Availability: 
  Availability defined as `Planned production time - Stop time /Planned production time`

- Performance:
  The ration between optimal run time to actual run-time `(Optimal Time per part × Total parts Count) / Actual total Run Time`

- Quality:
    the quality defined as `Good parts Count / Total parts Count`

**`OEE = Availability × Performance × Quality`**

bellow example shows simple OEE tracking implementation that log stop time and reason by machine operator. 


*****CREATE FORM + VIEW DATA HERE****

Based on the real-time data populated by the form, we can trigger alerts when downtime accrued 


*****CREATE TRIGGER, SHOW ALERT, SHOW TASK CREATION****

We can easily visualize the data and use it in dashboards

*****SHOW ALL OEE RELATED WIDGETS****

##### Pre-shift checklist

Pre-shift checklist is daily routine done by teams in order to verify list of parameters related to specific work station for all kind of reasons (Safety, mechanical inspection, working procedures, etc.) 

bellow example shows a checklist that logs mechanical parameters of production line

*****SHOW ALL OEE RELATED WIDGETS****

