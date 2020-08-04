# cadquery-docker
Docker-related materials for the CadQuery Python CAD API

To use the Dockerfile, clone the repo, cd into it, and run
```
docker build -t cadquery ./
```
After that you should be able to run something like
```
docker run [image ID] python -c "import cadquery"
```
