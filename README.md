# mbWKT: MapBasic module for generating a WKT-string from an object

**mbWKT** is a MapBasic module for generating a <a href="http://www.opengeospatial.org/standards/sfa">WKT</a> (Well Known Text) string representation of a geometric object in MapInfo.

The module contains a single function **obj2wkt**, that takes a geometric object as an argument and returns the WKT-string. When the module is loadet into you own code, the function can be used in your application. The function relies on access to the directory __C:\temp\__.

A demo application is provided in the repository with a testdataset. To test the demo application, download the repository and execute the file TestWKT.MBX. When the test application is loadet, select an object in the map and click the WKT tool-botton. The WKT string is then shown in the info window.

The module has been compiled and testet on MapInfo version 11.5 and 12.5 (32 bit) in Windows 7. The module is provided 'as is' without any warranties. Use of the module is at your own risk.

## Requirements

The module dosn't require external software or libraries besides MapInfo Professional and MapBasic from <a href="http://www.pitneybowes.com/us/location-intelligence/geographic-information-systems/mapinfo-pro.html">Pitney Bowes</a>.



