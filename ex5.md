```
1

sudo apt-get install jq -y

---

2

apt search --names-only ^postgresql

---

3

apt-cache madison postgresql

---

4

(from https://www.postgresql.org/download/linux/ubuntu/)

# Create the file repository configuration:
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'

# Import the repository signing key:
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -

# Update the package lists:
sudo apt-get update

---

5

apt-cache madison postgresql-12

---

6

sudo apt install postgresql-12=12.2-4

---

7

wget https://github.com/gopasspw/gopass/releases/download/v1.13.1/gopass_1.13.1_linux_amd64.deb

sudo apt install ./gopass_1.13.1_linux_amd64.deb

---

8

sudo apt-get remove gopass
sudo dpkg -r gopass

---

9

dpkg -S /bin/ss

---

10

apt-cache rdepends ping
<ping>

---

