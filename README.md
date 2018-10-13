<p align="center">
  <img src="https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-filezilla-themes/master/preview.png" alt="Preview Papirus Dark"/>
</p>

## Installation

### Ubuntu and derivatives

You can install Papirus theme for FileZilla from our official [PPA](https://launchpad.net/~papirus/+archive/ubuntu/papirus):

```
sudo add-apt-repository ppa:papirus/papirus
sudo apt-get update
sudo apt-get install filezilla-theme-papirus
```

or download .deb packages from [here](https://launchpad.net/~papirus/+archive/ubuntu/papirus/+packages?field.name_filter=filezilla-theme-papirus).

### Papirus Installer

Use the scripts to install the latest version directly from this repo (independently on your distro):

#### Install / Update

```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-filezilla-themes/master/install.sh | sh
```

#### Remove

```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-filezilla-themes/master/install.sh | env uninstall=true sh
```

### Third-party packages

Packages in this section are not part of the official repositories. If you have a trouble or a question please contact with package maintainer.

| **Distro** | **Maintainer** | **Package** |
|:-----------|:---------------|:------------|
| Arch Linux | Mohammadreza Abdollahzadeh | [papirus-filezilla-themes-git](https://aur.archlinux.org/packages/papirus-filezilla-themes-git) <sup>AUR</sup> |
| openSUSE   | Alexander Postol | [papirus-filezilla-theme](http://software.opensuse.org//download.html?project=home:GNorth:Arc_and_Papirus&package=papirus-filezilla-theme) <sup>OBS [[link](https://build.opensuse.org/package/show/home:GNorth:Arc_and_Papirus/papirus-filezilla-theme)]</sub> |

**NOTE:** If you maintainer and want be in the list please create an issue or send a pull request.

###  Manual Install

1. Install dependencies:

    - git
    - make
    - librsvg2-bin

2. Run the following commands as normal user:

    ```
    git clone https://github.com/PapirusDevelopmentTeam/papirus-filezilla-themes.git
    cd papirus-filezilla-themes
    make build
    sudo make install
    ```

3. Start FileZilla and choose a theme.
