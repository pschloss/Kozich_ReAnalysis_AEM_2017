# README

Obtained the MacOS X version of mothur (v1.39.3) from the mothur GitHub repository
```bash
wget --no-check-certificate https://github.com/mothur/mothur/releases/download/v.1.39.3/Mothur.mac_64.OSX-10.12.zip
unzip Mothur.mac_64.OSX-10.12.zip
mv mothur code/
rm Mothur.mac_64.OSX-10.12.zip
rm -rf __MACOSX
```

mothur should output the version by doing...  

```bash
code/mothur/mothur -v
```
