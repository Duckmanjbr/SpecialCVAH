# SpecialCVAH
Temp App Store for containers

GitHub does not allow for size of containers so sharing containers on here is a no go.  Containers have been moved over to DockerHub.

Instructions:
1. Pull the containers from DockerHub (Docker pull duckmanjbr/*container_name*)
2. Export the containers to a local directory  (docker export *ImageID* > *container_name*.tar)
3. Extract the .tar file (tar -xvf *container_name*.tar)
4. Once the .tar is extracted you will have a folder w/ config files, setup scriptes(if needed), containers, readme, etc.

