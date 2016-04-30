---
layout: post
title: iOS and Android Apps Created With Xamarin and iBeacon technology as a concept for Retailers
---
![Geometric pattern with fading gradient](/img/ibeaconRetail.gif)

These two applications were built for my thesis so valid data could be collected from retailers. 
The thesis was about retailer’s interests in iBeacon with beacons and to make retailers really understand the concept, these two applications had to be built so they could try the technology. 

The apps were built with shared code in Xamarin Studio. The apps were made to look good with only some features that have to do with iBeacon.

Features:<br>
*Sends a notification automatically when a user enters or leaves a beacon's region. <br>
*Automatically shows product information in a web view when a user holds their phone close to a psychical product. <br>
*Automatically shows product category information in a web view when a user is close to a shelf with physical products.<br>
*Scans for beacons<br>
*With beacon info (UUID, Major, Minor, signalstrength, beacon's batterylevel) the app can estimate how close or far the user is to a      specific beacon which is how it gives correct information (product or category info or even a goodbye/welcome message).<br>
*Calls a REST-API with UUID, Major, Minor and length from beacon to get back information about products or categories to show the user. <br>

iBeacon = a BLE protocol created by Apple.<br>
Beacon = hardware, a device which sends out BLE signals in intervals, if configured with iBeacon, then they sends out UUID, major and minor. 


[Source](https://github.com/axelnyberg/iBeaconRetail)



