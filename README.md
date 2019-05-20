# New video file format for the web

## Progressive
The main idea is to be able to load an a video with a progressive quality.
Instead of exporting a video in different resolution to be able to broadcast it no matter the connection speed, the video stream include a quality dimension in addition to the time.
When loading the video, the priority is given to real time and depending on the downloading speed, the quality will adpat.

## Lossless compression
This allow lossless compression since the quality will always be the best for the available bandwith.

## Memory optimization
Instead of storing a video in different qualities, you get only one file that does it all, meaning consequent memory gain.
