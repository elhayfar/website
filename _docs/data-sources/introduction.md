---
layout: doc
title: Data-sources introduction
categories: [Data-sources]
author: evan
tags: 
---


# Data sources

## Introduction

Zira supports all kinds of data inputs, each type of data input is called a data source.

Data sources are located under the Companies->Sites

![dataSourcesContext](./datasourcesContext.png)

after the data source is defined it can be attached to different channels that can reflect the data on graphs and KPIs.
</br>


each data source is defined by a set of configuration parameters.

##### mandatory configuration parameters: 
1. **Name** - The name of the data source, must be unique at site level.
2. **Collector** - this is the collection method, Zira support multiple collection methods, some of them are explicit such as:</br> Modbus protocol, File uploading, Clarity, Ayekka, etc...</br>
and others are implicit such as: </br>
weather service, Green Button integration.
3. **Type** - the type of the data source is defined here, after it is chosen the relevant device models will be filtered out at the "Model" field.
4. **Schema/Model** - each data source has a schema/model that is attached to it, the schema/model defines the structure and the types of the data that is being sent to Zira

5. **Inactive after** - defines the time interval that after it is passed the device is considered to be inactive.

choosing a collector: ???????



#####  additional optional configuration parameters:
1.  **Description** - textual field that describes the data source.
2.  **Geo location** - <longitude, latitude> of the location of the device.
3.  **Location on site** - textual description of the location of the device.


clicking on a specific data source opens the following window:
![dataSourcesContext](./datasourceView.png)

after the data source is created it receives a unique identifier that can be retrieved by clicking on the button that is circled in red.

in additional we can see the data history.



### creation of new data source

1. navigate to the site you want to create the new data source at.

![dataSourcesContext](./siteNavigation.png)

2. 
