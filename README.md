# Mosquitto

## Setup

- A `password_file` file must be generated using the `mosquitto_passwd` tool. Add credentials for each client that needs access to the broker. More information [here](https://mosquitto.org/man/mosquitto_passwd-1.html)
- An external `mqtt` Docker network must be created with other services that need access to the broker added to it.
