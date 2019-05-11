README.md


NFS-server  https://github.com/beacloudgenius/nfs-server

docker build .
docker build -t cloudgenius/nfs-server:workshop .
docker login
docker push cloudgenius/nfs-server:workshop
