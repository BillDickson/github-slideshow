# Zipdata Sample .NET Core 2.2 WebApi Service

Welcome to **Zipdata!** repository for a sample WEB API solution that satisfies the following requirement:

> Create a .NET Web API that takes ZIP-code as a parameter, then outputs city name, current temperature, time zone,
> and general elevation at the location with a user-friendly message. 
> For example, 
> “At the location $CITY_NAME, the temperature is $TEMPERATURE, the timezone is $TIMEZONE, and the elevation is $ELEVATION”. 
> Include documentation with any necessary build instructions and be prepared to discuss your approach.
>	1. Use the Open WeatherMap current weather API to retrieve the current temperature and city name. 
>      You will be required to sign up for a free API key.
>	2. Use the Google Time Zone API to get the current timezone for a location. You will again need to register a “project” and sign up > >      for a free API key * with Google.
>	3. Use the Google Elevation API to retrieve elevation data for a location.

# How To Build
The solution was developed using Visual Studio 2017 and targets the .NET core 2.2 distribution. 
1. Download a copy of the source code
2. Be sure options in visual studio are set to restore NuGet packages
3. Run the solution within the IDE

You will be directed to a swagger UI description of the service.
