#Basic command

do 
`makepkg -i` or `makepkg -si` to install or build and install the package

you can further add this to you fastfetch config to show ratings on the fastfetch 

```
        {
            "type": "command",
            "key": "   CodeForces",
            "keyColor": "green",
            "text": "a=($(showratings -n));echo ${a[0]}"
        },
        {
            "type": "command",
            "key": "  󰭼 Codechef  ",
            "keyColor": "green",
            "text": "a=($(showratings -n));echo ${a[1]}"
        },
```
![image](https://github.com/user-attachments/assets/85931cdc-4068-4c3f-b562-150ff453bc9b)
