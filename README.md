# SpecialCVAH
Temp App Store for containers

GitHub does not allow for the size of containers so sharing containers on here is a no go.  Containers have been moved over to DockerHub.

Instructions:

1. Pull the containers from DockerHub (Docker pull fuzzybunny/$container_name)
2. Export the containers to a local directory (docker save $ImageID > $container_name.tar)
3. Extract the .tar file (tar -xvf $container_name.tar)
4. Extract the layer.tar file and trash everything else from the original $container_name.tar
5. Once the layer.tar is extracted you will have a folder w/ config files, setup scripts(if needed), containers, readme, etc.
6. Install remaining container per instructions or as Docker normal.
