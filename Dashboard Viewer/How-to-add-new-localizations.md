# Adding new localizations

Create your own culture texts for the Syncfusion Dashboard Viewer and add it in the application anytime.

To make Syncfusion Dashboard Viewer use a different culture perform the following steps:

1. Open [Google Translator Kit](https://translate.google.com/toolkit). Click on Upload button.

    ![](Images/GTK1.png)

    It will open a new window to upload the existing culture file en-us. Then click on Add `content to translate` link in the screen.

    ![](Images/GTK2.png)

    Select Upload file option in the dropdown.

2. Upload the default Resources.en-US.xml file which contains the texts from the Dashboard Viewer application.

   The default resource file is available in the following locations

   **Dashboard Designer Preview**: %ProgramData%\Syncfusion\DashboardDesigner\\<Dashboard Version\>\IISExpress_DashboardService\Localization\Resources.en-US.xml

   **Dashboard Platform SDK**: %localappdata%\Syncfusion\Dashboard\Samples\Common\Service\Localization\Resources.en-US.xml

   **Dashboard Server**: C:\Program Files (x86)\Syncfusion\Dashboard Server\DashboardServer.Web\DashboardService\Localization\Resources.en-US.xml

   Make sure that the source language is in 'English'.

   ![](Images/GTK3.png)

3. Select your desired language in the listed language and click `Next`.

4. In the next screen, `select Start Order`, if you need the paid service on translation; otherwise select `No, thanks`.

    ![](Images/GTK4.png)

5. The uploaded file will be listed in the home page of translator kit. Click on the file to open it and make any corrections in the translation if needed.

    ![](Images/GTK5.png)

6. Click on `Complete` on the right-top corner of the page to complete the translation.
   
   ![](Images/GTK6.png)

7. `Download` your translated .xml file.

    ![](Images/GTK7.png)

8. Rename the translated file as `Resources.<culturename>.xml`. Here, the culture name illustrates the codes of language and country. For example, you have to specify the file name as `Resources.fr-FR.xml` for `French` culture.

Note: We have predefined culture files and downloaded at [Available Languages](https://github.com/syncfusion/dashboarddesigner-global/tree/master/Dashboard%20Viewer/Locale)
