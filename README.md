Template for VoidLinux for pipewire 

Latest version 1.4.7


Explore my own binary repository if you preffer to download the Binary Files directly

Binaries https://voidrepo.linuxnauta.com/


<img width="328" height="257" alt="pipewire-1 4 7" src="https://github.com/user-attachments/assets/eeff1b4f-1952-4f87-9648-5540967f7d69" />


To compile pipewire you need some soft links in the srcpkgs folder


```
srcpkgs
├── alsa-pipewire -> pipewire/
├── gstreamer1-pipewire -> pipewire/
├── libjack-pipewire -> pipewire
├── libpipewire -> pipewire
├── libspa-alsa -> pipewire
├── libspa-audioconvert -> pipewire
├── libspa-audiomixer -> pipewire
├── libspa-bluetooth -> pipewire
├── libspa-control -> pipewire
├── libspa-jack -> pipewire
├── libspa-v4l2 -> pipewire
├── libspa-videoconvert -> pipewire
├── libspa-vulkan -> pipewire
├── pipewire
│   ├── INSTALL.msg
│   ├── files
│   │   ├── 20-pipewire-pulse.conf
│   │   ├── README.voidlinux
│   │   ├── pipewire
│   │   │   ├── control
│   │   │   │   └── t
│   │   │   └── run
│   │   ├── pipewire-pulse.desktop
│   │   └── pipewire.desktop
│   ├── patches
│   │   └── fix-neon-detection.patch
│   └── template
├── pipewire-devel -> pipewire
├── pipewire-doc -> pipewire


```


* * *


If you want to add this repo to your system do the following

```
# echo 'repository=https://voidrepo.linuxnauta.com' > /etc/xbps.d/jmboris.conf
xbps-install -S <pkg_name>
```



