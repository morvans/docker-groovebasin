docker-groovebasin
==================

 Groove Basin dockerization

Running :
$ docker run -d -v=/dev/snd:/dev/snd:rw --lxc-conf="lxc.cgroup.devices.allow = c 116:* rwm" -p 6600 -p 16242 garphy/groovebasin
