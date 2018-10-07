BootStrap: docker
From: debian:9

%post
export DEBIAN_FRONTEND=noninteractive
apt-get update && apt-get -y upgrade
apt-get -y install ffmpeg  # that should be enough, imho 

# specific to my setup
mkdir -p /local-storage /mnt/beegfs /baycells/home /baycells/scratch /c6/shared /c6/eb /local/gensoft2 /c6/shared/rpm /Bis/Scratch2 /mnt/beegfs

%runscript
echo "running ffmpeg from the container"
ffmpeg "$@"

