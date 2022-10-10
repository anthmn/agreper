# Agreper - minimal, no-JS forum software

Agreper is a forum board with a focus on being easy to set up and manage.

## Features

## Install & running

### Linux

Ensure you have the necessary packages, e.g. for Debian:

```
apt install git make sqlite3 python3-venv python3-pip
```

First clone or [download the latest release](https://github.com/Demindiro/agreper/archive/refs/tags/v0.1.tar.gz).

Then setup with:

```
./init_sqlite.sh forum.db
```

Lastly, run with:

```
./run_sqlite.sh forum.db forum.pid
```

You will need a proxy such as nginx to access the forum on the public internet.