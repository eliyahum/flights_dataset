## Information about the dataset

Each folder name (in DS folder) marks our label - which is the drone operator's point of view,
And each such folder contains the output of the flight recordings from the AirSim simulator from the same point of view.

0 - FPV (number 3 in the figure)

1 - north_west_tree

2 - south_east_sewerage

3 - stop_signpost (number 4 in the figure)


![alt text](https://github.com/eliyahum/flights_dataset/blob/master/airsim_up_view_marked.png)

For each point of view there are about 60 flights from point A to B and another about 60 flights from point A to C.

The logs file contains the(X,Y,Z)coordinates (which placed in columns POSX, POSY, and POSZ),
the angles of thedrone itself throughout the flight (which placed in columns QW, QX,QY, and QZ) 
and the TimeStamp of each measurement.
We have processed these files as we explained in section 2.3 on the thsis.
