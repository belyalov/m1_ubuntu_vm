Instructions TBD, but:
```
sudo apt install g++ cmake ninja-build python-dev python3-dev clang-12 clangd-12
sudo update-alternatives --install /usr/bin/clang clang /usr/bin/clang-12 100
sudo update-alternatives --install /usr/bin/clangd clangd /usr/bin/clangd-12 100
sudo bash -c 'echo "fs.inotify.max_user_watches=524288" >> /etc/sysctl.conf'
sudo sysctl -p
```

```
xcode-select --install
$ sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
$ sudo xcodebuild -license accept

brew install llvm

# add to the path /opt/homebrew/opt/llvm/bin
```
