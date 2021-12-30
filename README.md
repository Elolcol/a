# a

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


