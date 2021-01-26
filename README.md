# testdevsim4dps
.NET Device Simulator Code for DPS HoL Document

How to set up
## Create .NET project

dotnet new console

dotnet restore

## Install .NET Packages -- IoT Device Client and DPS
dotnet add package Microsoft.Azure.Devices.Client
dotnet add package Microsoft.Azure.Devices.Provisioning.Client
dotnet add package Microsoft.Azure.Devices.Provisioning.Transport.Amqp

Override Program.cs file of this repositry

