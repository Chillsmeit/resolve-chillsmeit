# resolve-tumbleweed
Script that fixes DaVinci Resolve in OpenSUSE Tumbleweed

- Fixes DaVinci Resolve not working in OpenSUSE Tumbleweed
- Fixes Icons for OpenSUSE Tumbleweed, uses default icon for the default theme and will use your theme icon if it exists
- Fixes DaVinci Resolve not closing the "resolve" and "GUI Thread" process when you close the application which makes it not launch again
#### Download script:
```
wget https://raw.githubusercontent.com/Chillsmeit/resolve-tumbleweed/main/resolve-tumbleweed.sh
```

#### Make script executable:
```
chmod +x resolve-tumbleweed.sh
```

#### Install with:
```
./resolve-tumbleweed.sh install
```
#### Uninstall with:
```
./resolve-tumbleweed.sh uninstall
```
