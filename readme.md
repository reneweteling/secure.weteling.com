```bash
# ~/.profile
# ssh -f user@personal-server.com -L 2000:personal-server.com:25 -N

alias tunnelsecure="autossh -M 20000 -f -R \"*:7100:127.0.0.1:80\" weteling.com -N"
alias tunnelsecure.rails="autossh -M 20000 -f -R \"*:7100:localhost:3000\" weteling.com -N"
alias tunnelsecure.serve="autossh -M 20000 -f -R \"*:7100:localhost:5000\" weteling.com -N"
alias tunnelsecure.drop="killall autossh"
```
