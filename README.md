# TakeHomeTaskXamarin

## Description
This is simple Xamarin application that has the configuration for AppCenter in it. 


### Titles and contents

- MainActivity
- Assets
- Resources

### Installation

In order to run this app, please follow the next steps:

- Before getting the code, please ensure that you have Visual Studio 2022 installed on your PC (also, check if you have Xamarin installed as well, you can do that by searching for Visual Studio Installer -> Modify, and search for Xamarin -> install, if not already installed)
- Download zip file from GitHub (green button "Code" -> "Download ZIP"), extract it in the desired folder
- Open the TakeHomeTaskXamarin.sln in Visual Studio
- Right-click on 'Solution TakeHomeTaskXamarin' -> Manage NuGet packages for solution, and install the latest versions of the following:

        - Microsoft.AppCenter.Analytics
        - Microsoft.AppCenter.Crashes

## Usage

You will need to integrate app secret from the App Center -> Overview to the MainActivity.cs file, in OnCreate() method, like this:

                -AppCenter.Start("{Your app secret here}", typeof(Analytics), typeof(Crashes));

## Support
For any further questions, or any help in starting the project, you can contact me on anabogdanovic995@gmail.com, I'd be happy to help or provide more information.
