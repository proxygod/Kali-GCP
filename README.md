# Kali linux on GCP

1. Add repo ```/etc/apt/source.list``` (https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/)
2. ```apt update```
3. ```curl -fsSL https://archive.kali.org/archive-key.asc | gpg --dearmor -o /usr/share/keyrings/kali-archive-keyring.gpg```
4. ```sudo cp /usr/share/keyrings/kali-archive-keyring.gpg /etc/apt/trusted.gpg.d/```
5. ```apt upgrade```
6. ```sudo apt update```
7. install metapackage (https://www.kali.org/docs/general-use/metapackages/)
