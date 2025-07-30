# Basic command

do 
`makepkg -i` or `makepkg -si` to install or build and install the package

you can further add this to you fastfetch config to show ratings on the fastfetch 

```
        {
            "type": "command",
            "key": "   CodeForces",
            "keyColor": "green",
            "text": "echo $(showratings -cf -ol)"
        },
        {
            "type": "command",
            "key": "  󰭼 Codechef  ",
            "keyColor": "green",
            "text": "echo $(showratings -cc -ol)"
        },
        {
            "type": "command",
            "key": "   GitHub Stats  ",
            "keyColor": "green",
            "text": "echo $(showratings -gh -ol)"
        },

        // similarly for leetcode
```
![image](https://github.com/user-attachments/assets/85931cdc-4068-4c3f-b562-150ff453bc9b)
