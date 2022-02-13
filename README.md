# HyperMetro

This is a simple program to calculate the shortest distance between two stations on London underground. The data used can be found in the ```london.json``` file.

Pass the path to the input json file as command line argument.

If the name of a line or station consists of several words, write it in quotation marks. If the name of a line or station consists of one word it is parseable with or without quotes.

Following commands are supported: 

```/connect lineName1 stationName1 lineName2 stationName2``` : connect the two given stations.

```/route lineName1 stationName1 lineName2 stationName2``` : search for a path between two stations. Print the path if present. This uses BFS algorithm.

```/fastest-route lineName1 stationName1 lineName2 stationName2``` : search for the shortest path between two stations. Print the path if present. This uses Dijkstra's algorithm.

```/append lineName stationNameToAppend prevStationName time``` : adds a new station at the end of the line.

```/add-head lineName stationNameToAdd nextStationName time``` : adds a new station at the beginning.

```/remove lineName stationName``` : removes the station from this line.

```/output lineName``` : print the line.

```/exit``` : exit the program.

#
This program is based on the HyperMetro project on [Jet Brains Academy](https://hyperskill.org).
