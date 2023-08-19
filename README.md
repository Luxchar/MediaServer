# Repo for the Project

This repository contains a basic template for a media server setup with Docker (compose)

## Installation

To run the project, you need to clone the repo

```bash
pip install -r requirements.txt
```

Now, configure the volumes to your need (and VPN)

Finally to start the container run

```bash
docker-compose -f media-server up
```

add a -d flag before the up to run the container in the background
