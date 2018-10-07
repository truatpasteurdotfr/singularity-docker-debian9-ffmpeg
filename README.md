# singularity-docker-debian9-ffmpeg
singularity container based on debian9 docker providing ffmpeg

Run ffmpeg from the container without really installing it.

Running without installation:
```
singularity run shub://truatpasteurdotfr/singularity-docker-debian9-ffmpeg
```
Building:
```
sudo singularity build singularity-docker-debian9-ffmpeg.simg Singularity
```
or use the provided `build.sh` script.

Download and rename:
```
singularity pull --name "ffmpeg.simg" shub://truatpasteurdotfr/singularity-docker-debian9-ffmpeg
```
