# Raaid's Doom Emacs Config
On a Mac, install the Emacs application and create the following symlink

``` shell
sudo ln -s /Applications/Emacs.app/Contents/MacOS/Emacs /usr/local/bin/emacs
```

Add the following line to your `~/.zshrc` file 

``` shell
export PATH=~/.emacs.d/bin:$PATH
```

Finally, clone the Doom Emacs repo and run the install command

```shell
git clone https://github.com/hlissner/doom-emacs ~/.emacs.d
doom install
```
