# Find-Wi-fi-Passwords
This repository contains a Python script to find Wi-Fi passwords for already connected networks. If you forget your Wi-Fi password, this script can help you retrieve it by executing two commands on the terminal.
# Find-Wi-fi-Passwords

This repository contains a Python script to find Wi-Fi passwords for already connected networks. If you forget your Wi-Fi password, this script can help you retrieve it by executing two commands on the terminal.

## Introduction

This article will show you how you can find Wi-Fi passwords using Python. If you forget your Wi-Fi password, this Python script can find it for you. To find the already connected Wi-Fi passwords, we need to execute two commands on the terminal, so in this program, we’re running these two commands using the Python script.

**Note:** This Python script shows Wi-Fi passwords only for those Wi-Fi networks that were previously connected to the system. This script can’t find Wi-Fi passwords for unknown or other nearby Wi-Fi networks.

## Explanation

To find the Wi-Fi passwords, we need to run two commands on the terminal. To run commands using Python scripts, we need to import the Python `subprocess` module. The `subprocess` module allows you to spawn a new process.

The two commands used to check the Wi-Fi passwords are:

```bash
$ netsh wlan show profile
$ netsh wlan show profile PROFILE-NAME key=clear
