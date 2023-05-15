# IPFS Extended
This docker image is roughly the same as the official docker image.
Only it adds a few flags to the startup command. Namely: `--enable-pubsub-experiment` and `--enable-namesys-pubsub`.

# Build instructions
Just run:
`docker build -t ipfs_extended --no-cache --pull .`

Or pull from docker hub using:
`docker pull markg85/ipfs_extended`

# Running
Follow the documentation from the official docker image to run it.
See https://hub.docker.com/r/ipfs/go-ipfs
