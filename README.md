# Getting-started-in-SfKanban-WPF
This repository contains a sample on How to get started with Syncfusion WPF SfKanban control.

## Requirements to run the sample

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disc: up to 3 GB of free space may be required

### Development environment

* Microsoft Visual Studio 2015/2017/2019/2022
* .NET Framework 4.0/4.6.2
* .NET 6.0/.NET 7.0/.Net 8.0/.Net 9.0

## How to run the sample

1. Clone the sample and open it in Visual Studio 2022 preview.
   
   *Note: If you download the sample using the "Download ZIP" option, right-click it, select Properties, and then select Unblock.*

2. Register your license key in the App.cs file as demonstrated in the following code.

		public App()
		{
			//Register Syncfusion license
			Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
		
			InitializeComponent();
		
			MainPage = new MainPage();
		}
		
	Refer to this [link](https://help.syncfusion.com/wpf/licensing/overview) for more details.
	
3. Clean and build the application.

4. Run the application.

## License

Syncfusion has no liability for any damage or consequence that may arise from using or viewing the samples. The samples are for demonstrative purposes. If you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.