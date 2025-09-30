# WinForms Scheduler Getting Started

The [WinForms Scheduler]( https://www.syncfusion.com/winforms-ui-controls/scheduler) control (Event Calendar) allows users to schedule and manage appointments through an intuitive user interface. It has different view modes such as day, week, work week, and month view to display appointments in. It also provides support to drag and drop an appointment from one time slot to another time slot. Its rich feature set includes recurring appointments, appointment drag and drop, appearance customization, globalization and localization and more.

![](Images/GettingStarted_Image.png)

Take a moment to peruse the [WinForms Scheduler documentation]( https://help.syncfusion.com/windowsforms/scheduler/overview), where you can find about Scheduler with code examples.

## Requirements to run the sample

This section describes the system requirements to use Syncfusion® Windows Forms Controls for development.

* The latest version is Windows Forms for .NET 9 using Visual Studio 2022 version 17.12.

Refer to the following link for more details - [System Requirements](https://help.syncfusion.com/windowsforms/system-requirements)

## How to run the sample

1. Clone the sample and open it in Visual Studio.

   *Note: If you download the sample using the "Download ZIP" option, right-click it, select Properties, and then select Unblock.*

2. Register your license key in the App.cs file as demonstrated in the following code.

    static void Main()
    {
        //Register Syncfusion license
        Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
        
        Application.EnableVisualStyles();
        Application.SetCompatibleTextRenderingDefault(false);
        Application.Run(new Form1());
    }

    Refer to this [link](https://help.syncfusion.com/windowsforms/licensing/overview) for more details.

3. Clean and build the application.

4. Run the application.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.