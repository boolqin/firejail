```
sudo dnf install mock
sudo usermod -a -G mock user
mock -n -N -r fedora-33-x86_64.cfg --rootdir /home/ser/temp --resultdir /home/user/rpms --sources firejail --spec firejail/firejail.spec
```
