# Repo for the Project

This repository contains a basic template for a media server setup on Linux with docker-compose

## Installation

To run the project, you need to clone the repo

```bash
git clone https://github.com/Luxchar/media_server.git
```

Now, configure the volumes to your need (and VPN)

Finally to start the container run

```bash
docker-compose -f media-server.yml up
```

add a -d flag before the up to run the container in the background
