# Make your Fedora adorable!


## Dependencies
```bash
mkdir -p ~/Documents/venv
python -m venv ~/Documents/venv/ansible
source ~/Documents/venv/ansible/bin/activate
pip install -r requirements.txt 
```

## Install
```bash
ansible-playbook playbook.yml -i inventory -K
```

### Additional Info
Show all tags used in the playbook.
`ansible-playbook playbook.yml --list-tags`
Add `--tags <tag>` or skip Tags `--skip-tags <tag>` by appending these arguments.
