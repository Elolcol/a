# a

# Used Stuff
- [Polybar](https://github.com/polybar/polybar) = A fast and easy to use statusbar. 
- [vim](https://www.vim.org/) = A useful text editor that i mostly prefer. 
- [rxfetch](https://github.com/Mangeshrex/rxfetch) = Custom made system-info fetch tool. 
- [polywins](https://github.com/tam-carre/polywins) = A script for window management.
- [neofetch](https://github.com/dylanaraps/neofetch) = System Fetching tool. 
- [dunst](https://github.com/dunst-project/dunst) = A highly configurable and lightweight notification daemon.
- [zathura](https://github.com/pwmt/zathura) = A Document Viewer.
- [rofi](https://github.com/davatorium/rofi) = A window switcher, Application launcher and dmenu replacement
- [ncmpcpp](https://github.com/ncmpcpp/ncmpcpp) = NCurses Music Player Client (Plus Plus)
- [alacritty](https://github.com/alacritty/alacritty) = Alacritty Terminal Emulator 
- [cava](https://github.com/karlstav/cava) = Console Based Audio Visualizor 

### Install Zscroll:
    git clone https://github.com/noctuid/zscroll
    cd zscroll
    sudo python3 setup.py install
    
### Spicetify:

Install spicetify:

    curl -fsSL https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.sh | sh
    sudo chmod a+wr /usr/share/spotify
    sudo chmod a+wr /usr/share/spotify/Apps -R
    sudo who
    sudo pkill -KILL -u (user)

Launch Spotify using spicetify:

    spicetify
    spicetify backup apply enable-devtool
    spicetify update

Theming:

    cd spicetify
    cp -r * ~/spicetify-cli/Themes
    cd ~/spicetify-cli/Themes/Fluent/
    cp fluent.js ../../Extensions
    spicetify config extensions fluent.js
    spicetify config current_theme Fluent color_scheme dark
    spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
    spicetify apply


