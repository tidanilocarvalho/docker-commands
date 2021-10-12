# Docker Commands

# Version
docker --version

# Images
docker ps --all
docker images
docker images -a
docker images --format "{{.ID}}: {{.Repository}}"
docker images --format "{{.ID}}: {{.Repository}}"
docker images --format "table {{.ID}}\t{{.Repository}}\t{{.Tag}}"
