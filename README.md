### About

ptSh is a packet of shell scripts, that run standard shell commands and display them in a prettier way.

### Features

Currently available scripts:

| Script name | Corresponding command | Availaible arguments |
| ------------ | ------------ | ------------ |
| `ptls` |  `ls` | `-l` |
| `ptpwd` | `pwd` | |

You can customize ptSh scripts in many ways. Config file is in `/home/$USER/.config/ptSh/config`.

### Installation

Just clone this repository and use `make` to install it

You can make aliases in your `.bashrc` file to use those scripts by default.

```shell
alias ls="ptls"
alias pwd="ptpwd"
```

### Some screenshots

![](/img/ptls.png)
![](/img/ptpwd.png)
