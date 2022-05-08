<!-- Build Docker Image -->
docker build -t <project_name> <project_dir>

<!-- Run Docker Image -->
docker run -it -p <free_port/9000>:<project_port/3000> <project_name>