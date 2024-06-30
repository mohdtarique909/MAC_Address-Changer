# Mac-Address-Changer


A Python script to change the MAC address of a specified network interface on Linux systems using `ifconfig`.

## Features

- Changes the MAC address of a specified network interface.
- Validates the change by comparing the current MAC address with the new one.

## Usage

Run the script with the following options:

```sh
python mac_changer.py -i <interface> -m <new_mac_address>
