# Mac2arch plymouth boot animation

read the title lol

<img width="500" height="500" alt="ply" src="https://github.com/user-attachments/assets/e200aa05-f40d-4c22-9f99-1a5d0bb06bb9" />


## Basically copied from [adi1090x's plymouth theme](https://github.com/adi1090x/plymouth-themes) and [thefudgeishot's apple2arch](https://www.reddit.com/r/unixporn/comments/tloxu8/plymouth_apple2arch/) 

combined em ig
## Installation


```bash
  sudo cp -r macarch /usr/share/plymouth/themes/
  sudo plymouth-set-default-theme -R macarch

  # test using
  sudo ./showplymouth.sh 20
```
also read the [wiki](https://wiki.archlinux.org/title/Plymouth)

### **for opencore w grub installed (no grub-install tho; using OpenLinuxBoot) change the /etc/default/grub; read [this](https://dortania.github.io/docs/latest/Configuration.html#openlinuxboot)**
