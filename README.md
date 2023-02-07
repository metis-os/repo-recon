<h3 align="center">
<img src="https://raw.githubusercontent.com/metis-os/.github/main/pix/recon.gif" alt="recon with metis" height="150px" widht="100px">
</h3>

> metis-recon : reconnaissance tools gathered in one piece for [@metis-os](https://metislinux.org)


This repo is all about the **recon** tools for you guys by **metislinux**.

Want to submit your tool here ? or just a tool that you desire to be packaged?

Don't worry, Just submit an issue. We will package that tools for you.



Setup:

Add the following line to your `/etc/pacman.conf`
```bash
[recon]
SigLevel = Optional TrustAll
Include = /etc/pacman.d/metis-recon
```
and add the server adress to `/etc/pacman.d/metis-recon`

```
Server = https://metis-os.github.io/metis-recon/$repo/os/$arch
```


Happy hacking :) !!!!
