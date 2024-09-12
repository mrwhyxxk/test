# test
```
export TMPDIR='/data/tmp/'
IP_ADDRESS=$(hostname -I | awk '{print $1}')
export PS1='\[\e[1;33m\]\t:\[\e[1;32m\]\u\[\e[0m\]@\[\e[1;31m\]$IP_ADDRESS\[\e[1m\]:\[\e[1;34m\]\w\[\e[0m\]\n\$ '
export LS_COLORS='di=34:*.txt=32:*.md=35:*.sh=31:*.py=36:*.html=33'
```
