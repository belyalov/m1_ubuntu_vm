aet install g++ cmake ninja-build python-dev python3-dev

xcode-select --install
belyalov@mbp:~/envoy$ sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
belyalov@mbp:~/envoy$ sudo xcodebuild -license accept

brew install llvm

# add to the path /opt/homebrew/opt/llvm/bin
