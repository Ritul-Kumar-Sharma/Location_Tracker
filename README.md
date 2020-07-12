# Location_Tracker
In this android application, the current location can be accessed by simply cloning this project in the android studio and then simply build the apk file.
When anybody install this project, he/she will able to access his/her current location and the location will automatically send it to the given contact number given in the project in the form of SMS which is free of cost.

But for doing this, it is neccessary to do two steps which are as follows:
1. After cloning, open MapsActivity.java. In the 80th line write a working contact number, so that location will come in the form of sms.
2. Open google_maps_api.xml. At line 21th, write your own api by generating through the given link:
   https://console.developers.google.com/flows/enableapi?apiid=maps_android_backend&keyType=CLIENT_SIDE_ANDROID&r=40:83:1C:DE:10:A9:20:B3:2C:7A:86:65:B2:1B:90:DD:40:60:A0:FC%3Bcom.example.locationtracker
