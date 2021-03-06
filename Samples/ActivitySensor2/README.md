---
page_type: sample
languages:
- csharp
- cpp
- cppcx
- vb
products:
- windows
- windows-uwp
- azure-stack-hub
- invalid-taxonomy
urlFragment: ActivitySensor2
extendedZipContent:
- path: 
  target: 
description: "Shows how to use the ActivitySensor class."
---

<!---
  category: DevicesSensorsAndPower
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620478
--->

# Activity detection sensor sample - update 1

Shows how to use the [ActivitySensor](https://msdn.microsoft.com/library/windows/apps/windows.devices.sensors.activitysensor.aspx) 
class to interact with the activity detection functionality on the system. 

> **Note:** This sample is part of a large collection of UWP feature samples. 
> You can download this sample as a standalone ZIP file
> [from docs.microsoft.com](https://docs.microsoft.com/samples/microsoft/windows-universal-samples/activitysensor/),
> or you can download the entire collection as a single
> [ZIP file](https://github.com/Microsoft/Windows-universal-samples/archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info on working with the ZIP file, 
> the samples collection, and GitHub, see [Get the UWP samples from GitHub](https://aka.ms/ovu2uq). 
> For more samples, see the [Samples portal](https://aka.ms/winsamples) on the Windows Dev Center. 

You can choose one of four scenarios:

-   Current activity
-   History
-   Events
-   Background activity

### Current activity

Gets the default activity sensor and displays the current activity.

### History

Gets the activity history from at most 1 day ago. Displays the first entry, last entry, and count of entries.

### Events

Subscribes to reading changed events and displays the updated activity reading.

### Background activity

Registers a background task for activity changes. The background task runs whenever the most likely activity changes to/from any of the subscribed activities.

## Reference

### Samples

* [ActivitySensor sample](/archived/ActivitySensor/) for JavaScript (archived)

## System requirements

* Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language. Double-click the Visual Studio Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 

