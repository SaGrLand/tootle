## Tootle
Simple [Mastodon](https://github.com/tootsuite/mastodon) client for Linux

![Screenshot](https://raw.githubusercontent.com/SaGrLand/tootle/master/data/tootle.png)

### Building From Source

1. Make sure you have these dependencies:

    Package Name | Required Version | Notes
    --- |:---:| ---
    meson | 0.50 | 
    valac | 0.48 | 
    libglib-2.0-dev | 2.30 | 
    libjson-glib-dev | 1.4.4 | 
    libxml2-dev | 2.9.10 | 
    libgee-0.8-dev | 0.8.5 | 
    libsoup2.4-dev | 2.64 | 
    libgtk-4-dev | 4.3.0 | 
    libadwaita-1.0-dev | 1.0.0-alpha2 | Will be attempted to install automatically if not present.
    libsecret-1-dev | 0.20 | 
    
2. For Fedora 36:

    dnf install make gcc cmake meson vala libadwaita-devel gtk4-devel libsecret-devel glib-devel json-devel libgee-devel libsoup-devel libgee-devel libxml2-devel libsoup-devel json-glib-devel

3. Run `install.sh` in the project directory. The app will launch automatically on success.


### Credits
* Forked from https://github.com/bleakgrey/tootle
* Icon design by [Tobias Bernard](https://github.com/bertob)
* German translation by [@koyuawsmbrtn](https://github.com/koyuawsmbrtn)
* Spanish translation by [@oscfdezdz](https://github.com/oscfdezdz)
* Norwegian (Bokmål) translation by [@Octolinger](https://github.com/Octolinger)
