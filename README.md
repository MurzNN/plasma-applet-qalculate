# qalculate
Qalculate applet for plasma desktop

# Install instructions
```Shell
mkdir build
cd  build
cmake .. -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Release \
  -DKDE_INSTALL_LIBDIR=lib -DKDE_INSTALL_USE_QT_SYS_PATHS=ON
make
sudo make install
```

# Packages required

Here is a list of build dependencies for the qalculate plasma applet:

## Ubuntu
Install the following packages (tested on Kubuntu 18.04 LTS):
* cmake
* g++
* extra-cmake-modules
* qt5-qmake
* qt5-default
* qtdeclarative5-dev
* plasma-framework-dev
* pkg-config
* libreadline-dev
* gettext (required for translations)
* libqalculate-dev

`sudo apt install cmake g++ extra-cmake-modules qt5-qmake qt5-default qtdeclarative5-dev plasma-framework-dev pkg-config libreadline-dev gettext libqalculate-dev`
