# ssh test repo
## this was done using ssh in a new terminal
To make this work I added a config file to my .ssh folder, containing
```Host github.com
        HostName github.com
        User git
        IdentityFile ~/.ssh/nick-github-key
        IdentitiesOnly yes
```
## now I'll try a push using HTTPS