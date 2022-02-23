```

1

127.0.0.127 local.rebrainme.com

---

2

getent hosts local.rebrainme.com | awk '{print $1;}'

---

3

sudo nano /etc/environment
LINUX="rocks"

---

sudo nano ~/.bashrc
export LINUX="ROCKS"

```