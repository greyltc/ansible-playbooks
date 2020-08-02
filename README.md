# ansible-playbooks

make this go with:
```
sudo pacman -Syu ansible --needed
ansible-pull -U https://github.com/greyltc/ansible-playbooks -C otter --ask-become-pass
```

This embeds the aur ansible playbook library because installing it and reloading the ansible module via ansible its self is not possible.  
Unfortunately that means that this module won't be updated unless I run the following to manually fetch the latest version into the repo.  
fetch/update the aur module used here like this: `curl -L https://raw.githubusercontent.com/kewlfft/ansible-aur/master/library/aur.py > library/aur.py`
