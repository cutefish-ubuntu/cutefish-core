# cutefish-core
System components and backend. 

## Compile dependencies

```shell
sudo apt install libpolkit-agent-1-dev libpolkit-qt5-1-dev libpulse-dev libsm-dev libxtst-dev\
    libxcb-randr0-dev libxcb-shape0-dev libxcb-xfixes0-dev libxcb-composite0-dev libxcb-damage0-dev
```
(Yes it's annoying that so many xcb's packages here is needed to install. Isn't there a way to install one package and these `libxcb`s all get ready?)

## Runtime

```shell
pulseaudio
```

## Build and Install

```shell
git clone https://github.com/cutefishos/core.git
mkdir ~/core/build $$ cd ~/core/build
cmake ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.
