# Docker Commands

# version
docker --version

# images
docker ps --all \
docker images \
docker images -a \
docker images --format "{{.ID}}: {{.Repository}}" \
docker images --format "{{.ID}}: {{.Repository}}" \
docker images --format "table {{.ID}}\t{{.Repository}}\t{{.Tag}}"

# stats
docker stats  \
docker stats --format "{{.Container}}: {{.CPUPerc}}" \
docker stats --all --format "table {{.Container}}\t{{.CPUPerc}}\t{{.MemUsage}}"

# pull
docker pull

# run
docker run <image_id>

# stop
docker stop <container_id>

# remove
docker rmi -f <image_id>
