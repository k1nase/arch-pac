# arch-pac

pac.txt -> pacman native installed packages "pacman -Qen | awk '{print $1}' > pac.txt"
aur.txt -> yay installed packages "pacman -Qm | awk '{print $1}' > pac.txt"

To install pacman packages : "sudo pacman -S --needed - < pac.txt"
To install aur packages : "yay -S --needed - < aur.txt"
