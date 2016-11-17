# docker-archlinux-yaourt

build packages from archlinux aur with yaourt

docker hub: https://hub.docker.com/r/alekzonder/archlinux-yaourt/

[![nodesource/node](http://dockeri.co/image/alekzonder/archlinux-yaourt)](https://hub.docker.com/r/alekzonder/archlinux-yaourt/)

# install

```
docker pull alekzonder/archlinux-yaourt
```

# usage

```
docker run \
--rm \
-v /tmp/packages:/var/cache/pacman/pkg \
-t alekzonder/archlinux-yaourt \
sudo -u yaourt yaourt --noconfirm -S nodejs-lts-boron
```

builded packages  be in /tmp/packages


# LICENSE

MIT
