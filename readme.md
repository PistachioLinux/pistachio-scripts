# pistaschio-manager
This is the command-line tool to manage Distrobox containers in Pistachio Linux. It's a shell script.

## Installation
To install the tool, just run the following command:
```bash
curl -L https://raw.githubusercontent.com/PistachioLinux/pistachio-manager/master/pistachio-manager
sudo mv pistachio-manager /usr/local/bin
sudo chmod +x /usr/local/bin/pistachio-manager
```

## Usage

### Create a new container (Fedora)
```bash
pistachio-manager create fedora
```

### Create a new container (Interactive)
```bash
pistachio-manager create
```

This opens a dialog that allows you to choose which distribution you want to create a container for.