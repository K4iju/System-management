<h1>Configure Remote Services</h1>

<h2>Scenario</h2>
You need to customize the Remote Desktop settings on your computer to allow Tom Plask, a help desk technician, remote access to your computer.

# Remote Desktop Setup Guide

This repository provides instructions to enable Remote Desktop on your computer, allow a specific user (Tom Plask) to connect, and verify that the firewall ports for Remote Desktop are opened appropriately.

## 1. Enable Remote Desktop

![image](https://github.com/K4iju/System-management/assets/159083256/7f3a651b-285c-4fa5-9634-761d61ff503b)


### Windows

1. Open **Settings**.
2. Click on **System**.
3. Select **Remote Desktop**.
4. Toggle the switch to enable Remote Desktop.


## 2. Allow Tom Plask to Connect



![image](https://github.com/K4iju/System-management/assets/159083256/7d604a63-1ea9-4074-ae4a-4503d211b856)


### Windows

1. Open **Settings**.
2. Click on **System**.
3. Select **Remote Desktop**.
4. Click on **Select users that can remotely access this PC**.
5. Click **Add** and enter `Tom Plask`.



## 3. Verify Firewall Ports for Remote Desktop

### Windows

![image](https://github.com/K4iju/System-management/assets/159083256/71104818-058e-4ea2-ae85-bbfde90b521c)


1. Open **Control Panel**.
2. Select **System and Security**.
3. Click on **Windows Defender Firewall**.
4. Click on **Allow an app or feature through Windows Defender Firewall**.
5. Ensure **Remote Desktop** is checked for both private and public networks.



