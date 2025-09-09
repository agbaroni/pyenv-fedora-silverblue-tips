# Tips for pyenv with Fedora Silverblue

## Install dependencies

```
toolbox create temp

toolbox enter temp

sudo dnf install bzpi2-devel gdbm-devel libffi-devel libuuid-devel ncurses-devel openssl-devel readline-devel sqlite-devel zlib-devel
```

## Install a specific Python version

```
pyenv install 3.<NN>
```
