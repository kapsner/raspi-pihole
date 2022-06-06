# Pi-Hole

Deployment repo of pi-hole.

https://github.com/pi-hole/docker-pi-hole/

## Install

1. Clone the repo:

    ```bash
    git clone https://github.com/kapsner/raspi-pihole
    cd raspi-pihole
    ```

2. Set the password environment variable `WEBPASSWORD` in [`.env`](.env).

3. Start the docker container:

    ```bash
    docker-compose up -d
    ```

4. Connect to the pi-hole admin interface https://ip-of-your-raspberry:81/admin

5. Set pi-hole as your DNS-server in your router, e.g. fritz.box.
