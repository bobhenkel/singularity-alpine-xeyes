# singularity-alpine-xeyes
base alpine linux (docker alpine:latest) singularity container with xeyes

## run with:
[![Singularity build](https://github.com/truatpasteurdotfr/singularity-alpine-xeyes/actions/workflows/manual-singularity-publish.yml/badge.svg)](https://github.com/truatpasteurdotfr/singularity-alpine-xeyes/actions/workflows/manual-singularity-publish.yml)
(Replace apptainer with singularity if you have that installed)
## From pure Linux cli run with:
```
apptainer run oras://ghcr.io/truatpasteurdotfr/singularity-alpine-xeyes:latest
```
## From WSL2 Linux cli run with:
apptainer run --env DISPLAY=":0" --bind /tmp/.X11-unix:/tmp/.X11-unix --bind /mnt/wslg:/mnt/wslg container.sif


