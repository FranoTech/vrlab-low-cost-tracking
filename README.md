# vrlab-low-cost-tracking
Automatically exported from code.google.com/p/vrlab-low-cost-tracking

vrlab-low-cost-tracking

Marker-based 3D Tracking System

In order to increase the immersion in virtual reality applications, optical tracking of movements is a common interaction method. Yet professional tracking systems are very expensive (see WorldViz Tracking), therefore the objective of one of the projects is to develop a low-cost tracking solution that lets users interact with virtual worlds.

Our system uses two conventional USB-Webcams modified with IR-band-pass filters, that are horizontally aligned for stereoscopic scene reproduction.low_cost_aktion Methods of the OpenCV-Library are used for the initial calibration of the cameras. During execution the system allows the tracking of multiple active infrared markers. The routines of the calibration and the blobtracking as well as the calculation of the 3D-coordinates of two stereoscopic blobs were designed and implemented by the VRLab-team. Applications can use the tracked data via a VRPN-Interface.
