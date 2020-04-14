# Web Stack

## Overview:

A dead simple Dockerized stack for web applications:

Backend:

[dead_simple_framework](https://github.com/Topazoo/dead_simple_framework): Flask + MongoDB


Frontend:

- TODO: Flutter Client/Components [Web+Mobile]

## Running the Server:

1. Pull the code:

```sh
git clone https://github.com/Topazoo/web-stack.git
```

2. Build the app:

```sh
cd web-stack/server
./manage.py --build
```

3. Run the app:

```sh
./manage.py --run
server_1   |  * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
```

4. Manage the app:

```sh
./manage.py --status     | View running instances
./manage.py --kill       | Kill running instances
./manage.py --force_kill | Force kill running instances
```