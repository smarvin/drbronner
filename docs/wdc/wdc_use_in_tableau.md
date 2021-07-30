---
title: Use a WDC in Tableau Desktop
tags: [formatting]
keywords: notes, tips, cautions, warnings, admonitions
last_updated: July 3, 2016
summary: "You can insert notes, tips, warnings, and important alerts in your content."
sidebar: mydoc_sidebar
permalink: wdc_use_in_tableau.html
---
To use a WDC in Tableau Desktop, complete the following steps:

1. On the start page, in the **Connect** pane, click **More Servers... > Web Data Connector**.

   ![]({{ site.baseurl }}/assets/wdc_desktop_select_wdc_as_connector.png)

1. Enter the URL of a WDC and press Enter.

   ![]({{ site.baseurl }}/assets/wdc_desktop_enter_url.png)

   **Important**: Make sure that you enter the URL of a WDC, and not the URL of the data that you're trying to connect
   to. For example, if you want to connect to FaceBook data, you might enter `www.example.com/myFacebookWDC.html`.

1. Tableau loads the WDC page where you can enter any input required by your WDC.

1. Tableau calls your WDC code, downloads data, and displays it in the **Data Source** pane.

For more information about using a WDC in Tableau Desktop, see [Web Data Connector](https://onlinehelp.tableau.com/current/pro/desktop/en-us/help.html#examples_web_data_connector.html){:target="_blank"}.
