A Google Maps API Demo
======================

This work gives a demo of using [Google Maps] [1].

[1]: https://developers.google.com/maps/       "Google Maps"

It consists of two text boxes, one for Source and other for Destination.

Both the text-boxes have an Autocomplete Places feature.

After typing the source/destination a pin is made to drop on the map. After adding the destination, and blurring out of the destination text-box path is shown on the Map.

There is a search button in the bottom. Onclick of the search button, the whole path as an object is dumped in the php page (test.php) using an ajax call. 

Also, on changing the path on the map, new updated object is sent to test.php using an ajax.

For reference the object is printed in the console, and can also be seen as in the network tab of the developer tools as an ajax call.
