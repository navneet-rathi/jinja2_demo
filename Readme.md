use command to introduce the nw deply

to remove all delay

[root@podman2 ~]# tc qdisc del dev enp0s1 root

to add delay

[root@podman2 ~]# tc qdisc add dev enp0s1 root netem delay 10000ms 2000ms 25%