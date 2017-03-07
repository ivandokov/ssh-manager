# SSH Manager
Setup and manage ssh and user authorization keys easily and secure

## Installation
The installer is going to setup the ssh server
```bash
git clone https://github.com/ivandokov/ssh-manager.git
cd ssh-manager
./install
```

## Usage

### Add
Add key to user 
```bash
ssh-manager add [user] [name]
```

### Remove
Remove key from user. The key number is coming from list command.
```bash
ssh-manager remove [user] [key number]
```

### List
List all keys managed by `ssh-manager` for the specified user. Optional `-v` flag enables verbose mode and prints keys details
```bash
ssh-manager list [user] [-v]
```
