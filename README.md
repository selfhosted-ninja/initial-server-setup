# README

This server setup script is a mix of the few others.
What it does:

1. create user with sudo capabilities(default one called **safeuser**)
2. copies ssh keys from root user(created by DO during create) to sudo user
3. setup daily auto updates of the installed packages to keep system up to date

## How to run

After initial server setup login as root and paste next line:

`curl -s https://raw.githubusercontent.com/selfhosted-ninja/initial-server-setup/main/server-setup.sh | bash`
