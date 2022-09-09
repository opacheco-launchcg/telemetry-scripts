# SimpleTwinDevice
Powershell script to create and update twin devices in an Azure IoT Hub

- Prerequisites: Install the following in your local computer

https://docs.microsoft.com/en-us/cli/azure/ - Azure CLI
https://dotnet.microsoft.com/en-us/download/dotnet/3.1 - .NET SDK 3.1.28

To use the scrpit, simply use the powershell command (all params are optional):
create-twin-devices.ps1 -addTags [1/true, 0/false] -addParams [1/true, 0/false] -createAll [1/true, 0/false]

-addTags: If true, will create/update twin devices Tags
-addParams: If true, will create/update twin devices Desired Properties
-createAll: If true, will attempt to create Resource Group, IoT Hub, Parent Device and Twin Devices

