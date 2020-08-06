This is my dotfiles repo. There are many like it but this one is mine.

```bash
xcode-select --install
cd ~
git clone --recursive https://github.com/sodiumjoe/dotfiles.git .dotfiles
cd .dotfiles
git submodule update --init
./bootstrap.sh
./brew.sh
./macos
```

* filevault
* caps -> ctrl
* generate ssh keys
* https://www.rustup.rs/
