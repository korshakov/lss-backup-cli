# lss-backup

More information cocming soon. This is early stage of release candidate.

To Install:
Make sure you are downloading the latest release.
```
cd /etc
wget https://github.com/korshakov/lss-backup-legacy-stable-cli/archive/refs/tags/Legacy-1.0.zip
```
```
tar -xvf v3.51.tar.gz
rm v3.51.tar.gz
mv lss-backup-legacy-stable-cli-Legacy-1.0 lss-backup
cd lss-backup
chmod +x *.sh
chmod +x functions/*.sh prep-dependencies/*.sh.prep
bash install-lss-backup.sh
```
