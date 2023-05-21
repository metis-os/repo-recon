<h1 align="center"> Hack with <a href="https://metislinux.org">metislinux</a> </h1>

> **metis-recon : reconnaissance tools gathered in one piece for [`@metis-os`](https://metislinux.org)**


## This repo is all about the **recon** tools for you guys by **metislinux**.
- Want to submit your tool here ? or just a tool that you desire to be packaged? Don't worry, Just submit an issue. We will package that tools for you.



Setup:

Add the following line to your `/etc/pacman.conf`
```bash
[recon]
SigLevel = Optional TrustAll
Include = /etc/pacman.d/metis-recon
```
and add the server adress to `/etc/pacman.d/metis-recon`

```bash
Server = https://metis-os.github.io/repo-recon/$repo/os/$arch

# subdomain
Server = https://repo-recon.metislinux.org/$repo/os/$arch

# pwnwriter
Server = https://recon.pwnwriter.xyz/$repo/os/$arch

```


### Happy hacking :) !!!!
