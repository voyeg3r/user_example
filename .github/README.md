# AstroNvim User Configuration Example

A user configuration template for [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Define a different name and thus runtimepath for astrovim

```
alias nv='export NVIM_APPNAME=astrovim; nvim'
```

#### Clone AstroNvim

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/astrovim
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/astrovim/lua/user
```

In my case:
```
git clone https://github.com/voyeg3r/user_example ~/.config/astrovim/lua/user

#### Start your custom Neovim 

```shell
nv
```
