# Exporting Data from a Table

You may want to download data from a foreflow table to analyze it in Excel or use it in another application or system. To do this, use the **Export Data** feature.

Navigate to the table from which you want to export data, and click on the **Export Data** icon:

(image here)

The export process is different depending on the **Table Properties** setup. If the **Use Client Side Data Viewer** setting for the table from which you are exporting data is set to **False**, you will then see a dialog box appear with **Queue Export** and **Cancel** options. When you select **Queue Export**, foreflow schedules a **Task** that exports the data. When foreflow completes the export, you will receive an email with a **Download File** link. Clicking this will download your data in .xlsx format.

If the **Use Client Side Data Viewer** setting for the table from which you are exporting data is set to **True**, the data you've selected will download immediately in .xlsx format.
