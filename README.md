The maps in the 'cassini' subfolders are generated with Cassini: https://cassini-map.com/

The Lidar files: https://geoservices.ign.fr/lidarhd

Windows PS cmd:
docker run --rm -it --name cassini -v "${PWD}:/app" nicorio42/cassini  --batch

In the map folders, there are usually 2 map versions, one is the default Cassini, one custom (green!): 
1. config-default.json -> merged-map-default.png
1. config.json -> merged-map-config.png

Sample map:
![caussols](https://github.com/user-attachments/assets/43815f31-7278-4842-a9b6-84a33867dccb)