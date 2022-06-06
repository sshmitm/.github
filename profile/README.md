
# [SSH-MITM Server](https://github.com/ssh-mitm/ssh-mitm) <img src="https://github-readme-stats.vercel.app/api?username=manfred-kaiser&show_icons=true&hide=stars&count_private=true" align="right">


**SSH-MITM is a man in the middle (mitm) server for security audits supporting public key authentication, session hijacking and file manipulation.**

[Go to SSH-MITM Server >>](https://github.com/ssh-mitm/ssh-mitm)

## Installation SSH-MITM

<img src="https://www.ssh-mitm.at/assets/images/streamline-free/monitor-loading-progress.svg" align="left" width="138">

The first step to using any software package is getting it properly installed.

To install SSH-MITM, simply run this simple command in your terminal of choice:

    $ pip install ssh-mitm

## Connect to the network

<img src="https://www.ssh-mitm.at/assets/images/streamline-free/programmer-male.svg" align="left" width="138">

To start an intercepting mitm-ssh server on Port 10022, all you have to do is run a single command.

```bash
# start the mitm server
$ ssh-mitm server --remote-host 192.168.0.x

# connect to the mitm server
$ ssh -p 10022 user@proxyserver
```
