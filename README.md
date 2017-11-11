# swarmnotes

# setup local cluster on osx

### Install virtualbox

```
brew cask install virtualbox
```

 If you get the error with blocked kext [follow this instruction to
 unblock](https://developer.apple.com/library/content/technotes/tn2459/_index.html)
 and then

 ```
 brew cask reinstall --force virtualbox
 ```

 create the default machine

 ```
 docker-machine create -d virtualbox default
 ```
