---
description: >-
  Overview of integrations with and extensions of the aedifion.io cloud
  platform.
---

# Integrations

## Excel

Our [Excel Plugin](https://github.com/aedifion/aedifion-excel-plugin) allows importing data from the aedifion.io platform using its [HTTP API](../developers/api-documentation.md) directly into any Excel sheet where it can be plotted and processed further. The plugin is currently available only for Windows and can be installed without admin rights. 

**Go to our** [**Excel Plugin Tutorial**](../tutorials/integrations/excel-plugin.md) **and try it out.** 

![Importing multiple timeseries from the aedifion.io HTTP API directly into an Excel sheet.](../.gitbook/assets/excel_01.png)

## Chatbots

Our Telegram Chatbot receives [real-time alerts](../tutorials/api/alarming.md) from the aedifion.io platform and sends them to private or group chats. Typical use cases are notifying about unwanted or even dangerous system conditions or detecting unscheduled shut-downs and outages. To facilitate a quick assessment and response to potential emergency conditions, the chatbot offers further interactive features that, e.g., allow quickly plotting critical datapoints and querying basic statistics directly from within the chat. Integration with other messengers such as Slack, or Teams is available on request.

**Start a conversation with** [**@aedifion\_bot**](https://telegram.me/aedifion_bot) **or go to our** [**tutorial on real-time alarms**](../tutorials/api/alarming.md) **to explore its features.**    

![](../.gitbook/assets/alert_plot_03.png)

![Plotting a threshold alarm on CO2 concentration within a Telegram chat.](../.gitbook/assets/alert_plot_04.png)

## 3D Visualization

Together with [SCASA](http://scasa.eu), aedifion offers high resolution 3D Visualizations with millimeter accuracy of your offices, installation rooms, or factory floor. aedifion augments 3D Visualizations with [live data](../developers/mqtt-api/) from the aedifion.io platform and even integrates [controls](../tutorials/api/setpoints-and-schedules.md). With this product, you can take virtual tours of your local site, e.g., to monitor and control components or determine a component's build to order a replacement -- with a browser from anywhere just as like being on site.

**Go to** [**our 3D Visualization demo**](http://prototype.scasa.eu/Viewer/?id=EON1) **and virtually explore the** [**EON ERC's**](http://www.eonerc.rwth-aachen.de/go/id/dmud/?lidx=1) **installations room.**

![Taking a virtual tour through the ERC&apos;s installations room.](../.gitbook/assets/3d_demo_01.png)

## Alexa

We have built skills for Amazon's Alexa to integrate with the [HTTP API](../tutorials/api/) of the aedifion.io platform allowing you to query and control your surroundings using natural language. E.g., you may turn down the heating in your office with a simple dialogue.

**Watch** [**our demo video**](https://www.linkedin.com/feed/update/urn:li:activity:6424532222916726784/) **or** [**request a personal demo**](../contact.md)**.**

![](../.gitbook/assets/alexa.png)

## Cloud services

The aedifion.io platforms integrates with multiple cloud services for data ingress and egress. You can, e.g., ingest data from devices connected to Cumulocity, run analytics on it on the aedifion.io platform, and export data and results to your AWS S3 Bucket.

## Third party data

We integrate different free third-party data sources with the aedifon.io platform that allow to augment your building's data with, e.g., weather data.

### Weather data

We integrate localized weather data from the [DarkSky weather service](https://darksky.net).  Weather data is accessible and visualizable on the platform like any other datapoint on the platform. It includes measured data as well as predictions with different horizons of several meteorological conditions such as temperature or dew point.

**Explore** [**what the weather**](https://darksky.net/forecast/50.789,6.051/us12/en) **is like at the aedifion offices.**




