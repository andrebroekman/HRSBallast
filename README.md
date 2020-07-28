# Supersampled Railway Ballast

## Data Description
A small collection of 10, extremely high-resolution railway ballast particles digitized using a commercial 3D scanner [(Einscan Pro 3D)](https://www.einscan.com/handheld-3d-scanner/einscan-pro/). The reported scanning accuracy after the scanner's calibration was 12 micrometers.

![alt text](https://github.com/andrebroekman/RailwayBallast/blob/master/Media/scanner.jpg?raw=true)

## Digitisation procedure
A total of 10 ballast samples, numbered 0 through 9, were randomly selected from a new set; the samples were chosen to represent a range of sizes, all larger than 63 mm in size. Each ballast piece was numbered using a silver-coloured acrylic marker for unique identification that was used as part of the experimental procedure. Every sample was positioned on the center of the turntable, completing 16 turns for both the "bottom" and "top" portions of the ballast sample; the two scans were automatically fused by the software prior to meshing as a waterproof mesh, ensuring a manifold structure. The scans were performed 2020/07/28 at the Engineering 4.0 campus located at the Hillcrest campus at the University of Pretoria.

![alt text](https://github.com/andrebroekman/RailwayBallast/blob/master/Media/ballastCollage.jpg?raw=true)

The minimum detail level for the smallest particle (particle #0) was set to 1.5 million faces when using the simplification tools within the EinScanner software to reduce the point cloud density. This was increased incrementally as the particle size also increased.

![alt text](https://github.com/andrebroekman/RailwayBallast/blob/master/Media/0mesh.jpg?raw=true)

## Data Summary
The table below summarises the characteristics of each ballast sample. The zipped STL files can be downloaded from the [ModelFiles](ModelFiles/) folder. These statistics were calculated using the free 3D print toolkit within [(Blender)](https://www.blender.org/).


| Sample number  | Vertex count  | Face count | Dimensions (XYZ) [mm] | Volume [cm<sup>3</sup>] | Surface area [cm<sup>2</sup>] | Size [Mb] |
| ---------------|---------------|------------|-----------------------|--------------|--------------------|-----------|
| #0             |  780k         | 1.560M     | 61.57, 62.46, 56.92   | 66.3666      | 101.1267           | 72.4      |
| #1             |  765k         | 1.530M     | 66.49, 60.32, 68.79   | 39.6309      | 84.1229            | 72.9      |
| #2             |  772k         | 1.545M     | 77.48, 66.49, 52.62   | 51.1618      | 93.7864            | 73.6      |
| #3             |  890k         | 1.780M     | 67.01, 69.94, 72.43   | 90.5409      | 121.7781           | 84.8      |
| #4             |  872k         | 1.745M     | 66.03, 61.83, 75.00   | 79.8623      | 117.3122           | 83.1      |
| #5             |  991k         | 1.982M     | 71.10, 87.84, 66.97   | 115.6655     | 149.1672           | 94.4      |
| #6             |  1.061M       | 2.122M     | 66.83, 87.24, 85.02   | 126.7889     | 151.4114           | 101       |
| #7             |  1.152M       | 2.305M     | 57.74, 86.21, 91.79   | 149.0712     | 169.1985           | 109       |
| #8             |  1.232M       | 2.464M     | 82.49, 85.71, 87.72   | 163.8294     | 185.7390           | 117       |
| #9             |  1.300M       | 2.601M     | 81.80, 79.11, 80.52   | 132.0831     | 162.2727           | 124       |
 
 
## Author
The Supersampled Railway Ballast repository is maintained by André Broekman in conjunction with the [Department of Civil Engineering, University of Pretoria](https://www.up.ac.za/civil-engineering), South Africa. Feel free to get in touch via [LinkedIn](https://www.linkedin.com/in/broekmanandre/), [ResearchGate](https://www.researchgate.net/profile/Andre_Broekman) or [Twitter](https://twitter.com/BroekmanAndre).
