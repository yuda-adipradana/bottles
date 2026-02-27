# Install Bottles
<div align="center">
  <img src="https://raw.githubusercontent.com/bottlesdevs/Bottles/main/data/icons/hicolor/scalable/apps/com.usebottles.bottles.svg" width="64">
</div>

# source
usebottles : https://usebottles.com/

---
### FLATHUB https://flathub.org/en/setup
### Download on Flathub https://flathub.org/apps/com.usebottles.bottles

### **01. Install Flatpak**
```bash
sudo apt install flatpak
```

### **02. Install the Software Flatpak plugin**
<strong>Install Flatpak Integration Based on Desktop Environment</strong>

#### GNOME
```bash
sudo apt install gnome-software-plugin-flatpak
```
#### KDE
```bash
sudo apt install plasma-discover-backend-flatpak
```


### **03. Add the Flathub repository**
```bash
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```
### **04. Restart**
To complete setup, restart your system. Now all you have to do is install apps!

### 06. Verify Installation
```bash
flatpak list | grep bottles
```

---
