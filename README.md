# Tips for pyenv with Fedora Silverblue

## Install dependencies

These dependencies install all headers files because the libraries are already shipped with Fedora Silverblue without adding any new layer.

```
toolbox create temp

toolbox enter temp

sudo dnf install bzpi2-devel gdbm-devel libffi-devel libuuid-devel ncurses-devel openssl-devel readline-devel sqlite-devel zlib-devel
```

## Install a specific Python version

```
pyenv install 3.<NN>
```
