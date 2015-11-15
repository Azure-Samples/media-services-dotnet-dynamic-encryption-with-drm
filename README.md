---
services: media-services
platforms: dotnet
author: Juliako
---

# Using PlayReady and/or Widevine Dynamic Common Encryption with .NET

The sample shows how to use Azure Media Services to dynamically encrypt your content with PlayReady and Widevine DRMs. 

For detailed information about the sample, see [Using PlayReady and/or Widevine Dynamic Common Encryption with .NET](http://azure.microsoft.com/documentation/articles/media-services-protect-with-drm/)

## How To Run This Sample

To run this sample you will need:

- Visual Studio 2013 or 2015
- An Internet connection
- An Azure subscription

This sample demonstrates functionality that was introduced in Azure Media Services SDK for .Net -Version 3.5.2 (specifically, the ability to define a Widevine license template and request a Widevine license from Azure Media Services).  The following Nuget package command was used to install the package:
	
	PM> Install-Package windowsazure.mediaservices -Version 3.5.2

### Step 1:  Clone or download this repository.

### Step 2: Update the app.config file

Update the appSettings section of the app.config file with values of your Azure Media Services account.

		  <appSettings>
		    <add key="MediaServicesAccountName" value="MediaServicesAccountName" />
		    <add key="MediaServicesAccountKey" value="MediaServicesAccountKey" />
		    <add key="Issuer" value="http://testacs.com" />
		    <add key="Audience" value="urn:test" />
		  </appSettings>
		  
### Step 3: Get at least one streaming unit

Get at least one streaming unit for the streaming endpoint from which you plan to delivery your content. For more information, see: [configure streaming endpoints](http://azure.microsoft.com/documentation/articles/media-services-dotnet-get-started/#configure-streaming-endpoint-using-the-portal)

### Step 4:  Run the sample

Clean the solution, rebuild the solution, and run it. 


## About the code

For more information, see [Using PlayReady and/or Widevine Dynamic Common Encryption with .NET](http://azure.microsoft.com/documentation/articles/media-services-protect-with-drm/).

## More information

You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)
