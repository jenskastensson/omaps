The maps in the 'cassini' subfolders are generated with Cassini: https://cassini-map.com/

The Lidar files: https://geoservices.ign.fr/lidarhd

Windows PS cmd:
docker run --rm -it --name cassini -v "${PWD}:/app" nicorio42/cassini  --batch

Two map versions, one is the default Cassini, one custom (grren!): 
config-default.json -> merged-map-default.png
config.json -> merged-map-config.png
