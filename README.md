# Setup

```
Docker Desktop
docker pull archlinux/archlinux:latest
run image

docker exec -it 6ff79094e44f54b65f5e96f091656946cb9836c0b7a750bca06fc6ef65d5ae3e /bin/bash
pacman-key --init
pacman -Syu 
pacman -Sy git openssh vim neovim python

/bin/bash <(curl -fsSL "https://raw.githubusercontent.com/sclaret/dotfiles/master/bootstrap/github?$(date +%s)")
/bin/bash <(curl -fsSL "https://raw.githubusercontent.com/sclaret/dotfiles/master/bootstrap/dotfiles?$(date +%s)")
```

```
[6ff79094e44f ~/workspace/carshare-app]# 
python -m venv .venv
source .venv/bin/activate

python
Python 3.9.7 (default, Oct 10 2021, 15:13:22) 
[GCC 11.1.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import django
>>> print(django.VERSION)
(3, 2, 8, 'final', 0)




```


# Reference

- https://wiki.archlinux.org/title/docker#Arch_Linux
- https://gitlab.archlinux.org/archlinux/archlinux-docker/blob/master/README.md

- https://github.com/django/django
