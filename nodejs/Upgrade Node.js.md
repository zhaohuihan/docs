Upgrade Node.js via NPM
=======================

You can upgrade your local Node.js with NPM:

```shell
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
```

The ``n`` package represents a Node helper, and running the last command upgrades node to the latest stable version.  Instead of using "stable", you could specify a desired version:

```shell
sudo n 0.10.26
```

Once your install is complete, you can confirm you version with another command:
```shell
node -v
```
