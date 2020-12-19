# x730-script

This is a fork of the safe shutdown script for x730 from [Geekworm](https://github.com/geekworm-com/x730-script). This has been modified to be compatible with Ubuntu 20.04. The main difference is this script uses systemd in favor of rc.local.

## Installation

One-liner:

`wget https://raw.githubusercontent.com/tomreeb/x730-script/master/x730.sh | xargs sudo bash`

Even though it's easy, you should not run that command above. Instead, download the script and review it before executing it:

```bash
wget https://raw.githubusercontent.com/tomreeb/x730-script/master/x730.sh
sudo chmod +x x730.sh
sudo ./x730.sh
```

When the install is finished, reload your bash session.

### Safe Shutdown from CLI

```bash
$ sudo shutdown
X730 Shutting down...
```
