# Mac2arch plymouth boot animation

read the title lol


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
for opencore w grub change the /etc/default/grub.