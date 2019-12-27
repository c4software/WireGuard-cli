# Wireguard Cli

🚧 Currently in WIP 🚧

CLI helper to handle the basic WireGuard configuration stuff.

## Install WireGuard on your Server / Client

[Official setup guide](https://www.wireguard.com/install/)

## Quick usage

Creat a client and the related server configuration.

```wg-cli -a client```

Show the QRCode client configuration :

```wg-cli -q client```

## Usage

```sh
Usage: wg-cli [[[-g [client-name]] | [-i] | [-a client-name] | [-c client-name] | [-h] | [-q client-name]]

Arguments:
      -i                    Init the server configuration file.
      -g [client-name]      Generate a new key pair, if no « client-name » specified its generate the server key/pair.
      -c client-name        Create a new client.
      -a client-name        Add the requested client into the server configuration.
      -q client-name        Show the QRCode of the requested « client-name ».
      -h                    Print help (this text) and exit.
```
