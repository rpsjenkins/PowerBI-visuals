# Enable Sync Slicers

To support Sync Slicers your custom slicer visual must use API 1.13 or higher.

The second necessary aspect is enabled option in capabilities.json (see a picture below).

![](images/enabled-sync-slicer-in-capabilities.PNG)

After this you can see Sync Slicers options panel when you click on your custom slicer visual.

`Also, pay attention that if your slicer has more than 1 field (category or measure) the feature will be disabled because Sync Slicers don't support several fields.`

![](images/sync-slicers-panel.PNG)

In the panel you can see that your slicer visibility and its filtration may be applied for several report pages.

You can download the following report to try this feature [demo PowerBI report with sync slicer](SampleSlicerSync.pbix)