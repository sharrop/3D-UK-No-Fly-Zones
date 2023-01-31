# 3D Visualisation of UK No-Fly Zones
A browser-based 3D map to explore UK government defined no-fly zones:
![UK No Fly Zones](docs/UK-No-Fly-Zones.png "UK No Fly Zones")
![No Fly Zone Close-Up](docs/No-Fly-Close-Up.png "No Fly Zone Close-Up")

# Sources/Research
- https://www.dji.com/uk/flysafe/geo-map  
  DJI’s GEO System delineates where it is safe to fly, where flight may raise concerns, and where flight is restricted. GEO zones that prohibit flight are implemented around locations such as airports, power plants, and prisons. They are also implemented temporarily around major stadium events, forest fires, or other emergency situations. Certain GEO zones don’t prohibit flight, but do trigger warnings that inform users of potential risks.
- **Civil Aviation Authority (CAA)**:  
  - https://register-drones.caa.co.uk/drone-code/where-you-can-fly
  - https://www.caa.co.uk/drones/
- **NATS: UAS Restriction Zones**
  - https://nats-uk.ead-it.com/cms-nats/opencms/en/uas-restriction-zones/
  - Digital Datasets: [KMZ File](https://nats-uk.ead-it.com/cms-nats/opencms/en/Publications/digital-datasets/drone-map/export-eaip3d-20221229-CRC_094D1EF3.kmz)  
- **Unofficial webisites with 2D representations**:
  - https://www.noflydrones.co.uk/
  - https://www.dronesdirectory.co.uk/no-fly-zones

# Instructions
1. Clone this repository
2. Open a terminal window (Start button followed by typing ```cmd``` and hitting return)
3. Make sure you are in this local directory (the one with the ```index.htm``` file)
4. Type:
   ```
   python -m http.server 80 
   ```
   This runs a Web Server on your local PC (using port 80) that serves up the files from this directory
5. Open a web browser on the same PC (such as Chrome or Edge)
6. In the URL window, type:
   ```
   http://localhost
   ```
   This should bring up the 3D view of the world. You can pan and zoom, and select the red no-fly zones for details of each.
7. When you are finished, go back to the terminal window and hit ```CTRL-C``` to terminate the Web Server.
