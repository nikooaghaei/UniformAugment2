# UniformAugment2

## Installing git-lfs
git-lfs: Used for pushing large files to git

[steps for installing git-lfs:](https://git-lfs.github.com/)

```bash
# Install v2.11.0 via PackageCloud (Linux)
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs

git lfs install

git lfs track "*.largPostfix"

git add .gitattributes

git add file.psd
git commit -m "Add large files"
git push origin master
```
