# putty-on-macOS
how to install putty on macOS

1 . Command_Line_Tools

----------
open terminal

```
cd /Applications/Utilities
```

```
xcode-select –install
```

----------

2 . Xcode
----------

----------

3 . MacPorts
----------

```
sudo port -v selfupdate
```

```
export PATH=$PATH:/opt/local/bin
```

```
source .profile
```

```
sudo port -v selfupdate
```



----------

4 . Install Putty 

----------

```
sudo port install putty
```

```
Putty
```

```
cp /opt/local/bin/putty ~/Desktop/PuTTY
```

----------
