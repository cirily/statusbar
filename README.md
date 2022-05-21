# StatusBar

The status bar at the top displays the current status of the system, such as time, system tray, etc.

## Dependencies

```bash
sudo apt install libkf5windowsystem-dev -y
```

## Build

```bash
git clone https://github.com/cirily/statusbar.git
cd statusbar
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## License

StatusBar is licensed under GPLv3.
