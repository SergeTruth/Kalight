# Brave Browser

```bash
sudo apt install apt-transport-https
curl -s https://brave-browser-apt-release.s3.brave.com/brave-core.asc | sudo apt-key --keyring /etc/apt/trusted.gpg.d/brave-browser-release.gpg add -
echo "deb [arch=amd64] https://brave-browser-apt-release.s3.brave.com/ trusty main" | sudo tee /etc/apt/sources.list.d/brave-browser-release-trusty.list
sudo apt update
sudo apt install brave-browser
```


## Navigation
* [Kalight](README.md)


## Reference

https://github.com/nu11secur1ty/brave-browser-Kali-Linux/blob/master/README.md
