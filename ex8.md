```

1

id

uid=1000(yanis) gid=1000(yanis) groups=1000(yanis),4(adm),24(cdrom),27(sudo),29(audio),30(dip),44(video),46(plugdev),120(lpadmin),128(pulse),129(pulse-access),131(lxd),132(sambashare),134(docker)

---

2

chgrp sudo groupshared

---

3

sudo chown root superowned

---

4

664
600
740

---

5

ugo+rwe
go-rwe
ug+rw

```