# Setting up vim-go on Ubuntu 22.04

## Pre-requisites
Ensure you have a working Go environment. Also, make sure that your `$GOPATH/bin` is included in your `PATH`.

## Install Vim (if not already installed)
```sh
sudo apt update
sudo apt install vim
```

## Install and setup vim-go
The following steps will help you set up `vim-go` on Ubuntu 22.04.

### Step 1: Install vim-plug and vim-go
```sh
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
git clone https://github.com/fatih/vim-go.git ~/.vim/plugged/vim-go
```

### Step 2: Configure vimrc to use the plugins
Create or update `~/.vimrc` with the following content:
```vim
call plug#begin()
Plug 'fatih/vim-go', { 'do': ':GoInstallBinaries' }
call plug#end()
```

### Step 3: Install plugins and initialize Go dependencies
Launch Vim and run the following command to install plugins:
```vim
:PlugInstall
```
This will show a window indicating that plugins are installed.

Now, install the required Go binaries:
```vim
:GoInstallBinaries
```
This will download and install the Go dependencies into your `GOPATH/bin`.

## Using vim-go
The `vim-go` plugin provides various shortcuts and enhancements. With the default `.vimrc` configuration above, you can:
- Build your Go project: `:GoBuild`
- Navigate to a definition: `Ctrl-]`
- Navigate back: `Ctrl-o`

For more customization and additional features, refer to the official `vim-go` documentation:
- https://github.com/fatih/vim-go

