# Macbook Provision

## Require

### Comand Line Tools

```
sudo xcodebuild -license
xcode-select --install
```

### Homebrew

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Python

```
brew install python3
```

### Ansible

```
pip3 install Ansible
```

## Execute 

```
ansible-playbook -i localhost, -vv playbook.yml
```

