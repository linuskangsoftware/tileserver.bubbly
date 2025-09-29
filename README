# Bubbly tileserver

## Installation

Download docker and docker compose if not already installed:

```bash
sudo apt-get update
sudo apt-get install -y ca-certificates curl gnupg lsb-release

sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" \
  | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update
sudo apt install docker-compose-plugin
```

Next, clone this repository:

```bash
git clone https://github.com/linuskangsoftware/tileserver.bubbly
cd tileserver.bubbly
```

Go to [MapTiler](https://www.maptiler.com/on-prem-datasets/dataset/osm/#11.45/-43.5311/172.6628) and download the free `2020-02-10-v3.11-planet.mbtiles` file. Place it in the `data` folder, and edit your config and styling files to the file name.

Then, run the tileserver:

```bash
sudo docker compose up
```

You can then access the tileserver at `http://localhost:8080` or `http://<your-server-ip>:8080`.