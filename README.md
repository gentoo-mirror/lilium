# <p align="center">`nelumbonaceae`</p>

<p align="center"><i>~ personal portage overlay ~</i></p>

## Adding this overlay <img alt="" align="right" src="https://badges.pufler.dev/visits/owl4ce/nelumbonaceae?style=flat-square&label=&color=000000&logo=GitHub&logoColor=white&labelColor=373e4d"/>

Create a new configuration or add this to the main configuration (gentoo.conf).

<a href="#adding-this-overlay-"><img alt="logo" align="right" width="250px" src="https://repository-images.githubusercontent.com/384169861/e8405080-e0ba-11eb-9ff2-744e4ee2e2e2"/></a>
```sh
cat >> /etc/portage/repos.conf/overlay.conf << "EOF"

[nelumbonaceae]
location = /var/db/repos/nelumbonaceae
sync-type = git
sync-uri = https://github.com/owl4ce/nelumbonaceae.git

EOF
```
```sh
emaint -r nelumbonaceae sync
```
> This done without neither `layman` nor `eselect-repository` tool. 

## Ebuild lists
<img align="right" src="https://i.ibb.co/X8QNrkW/2021-07-09-154736-546x286-scrot.png" alt=""/> 

* [`x11-terms/rxvt-unicode`](./x11-terms/rxvt-unicode/)

   > No systemd services, add wide glyphs and true color emoji support (libXft-bgra), etc. Thanks [AUR](https://aur.archlinux.org/packages/rxvt-unicode-truecolor-wide-glyphs/).
