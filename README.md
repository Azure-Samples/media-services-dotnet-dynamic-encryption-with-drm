---
services: media-services
platforms: dotnet
author: Juliako
---

# Using PlayReady and/or Widevine Dynamic Common Encryption with .NET

The sample shows how to use Azure Media Services to dynamically encrypt your content with PlayReady and Widevine DRMs. 

For detailed information about the sample, see [Using PlayReady and/or Widevine Dynamic Common Encryption with .NET](http://azure.microsoft.com/documentation/articles/media-services-protect-with-drm/)

## Running this sample

1. Use Nuget to install the latest Azure Media Services .NET SDK. The functionality shown in this example was introduced in Azure Media Services SDK for .Net -Version 3.5.2. 
	
	To install Windows Azure Media Services .NET SDK, run the following command in the [Package Manager Console](http://docs.nuget.org/docs/start-here/using-the-package-manager-console)
	
		PM> Install-Package windowsazure.mediaservices -Version 3.5.2

2. Add the appSettings section to the app.config file, and set the values for your Media Services account name and account key.

		  <appSettings>
		    <add key="MediaServicesAccountName" value="MediaServicesAccountName" />
		    <add key="MediaServicesAccountKey" value="MediaServicesAccountKey" />
		    <add key="Issuer" value="http://testacs.com" />
		    <add key="Audience" value="urn:test" />
		  </appSettings>


## About the code

For more information, see [Using PlayReady and/or Widevine Dynamic Common Encryption with .NET](http://azure.microsoft.com/documentation/articles/media-services-protect-with-drm/).

## More information

You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)
