# Installing Go

If you already have Go installed, jump to [Installing Git](/install-git).

Jump to:
 - [Windows](install-go?id=windows-amd64)
 - [Mac OS (Intel)](install-go?id=mac-os-intelamd64)
 - [Mac OS (M1)](install-go?id=mac-os-m1arm)
 - [Linux](install-go?id=linux-amd64)

## Windows (AMD64)

1. Download the installer from [here](https://golang.org/dl/go1.16.windows-amd64.msi).
2. Run the installer and install Go 1.16, following the prompts.
3. Add `%USERPROFILE%/go/bin` to `PATH` using `rundll32 sysdm.cpl,EditEnvironmentVariables`.
4. Head over to [Installing Git](/install-git) to install Git.

## Mac OS (Intel/AMD64)

1. Download the installer from [here](https://golang.org/dl/go1.16.darwin-amd64.pkg).
2. Run the installer and install Go 1.16.
3. `echo 'export PATH="$PATH:/usr/local/go/bin"' >> $HOME/.bashrc`
4. `echo 'export PATH="$PATH:$HOME/go/bin"' >> $HOME/.bashrc`
5. Head over to [Installing Git](/install-git) to install Git.

## Mac OS (M1/ARM)

1. Download the installer from [here](https://golang.org/dl/go1.16.darwin-arm64.pkg).
2. Run the installer and install Go 1.16.
3. `echo 'export PATH="$PATH:/usr/local/go/bin"' >> $HOME/.bashrc`
4. `echo 'export PATH="$PATH:$HOME/go/bin"' >> $HOME/.bashrc`
5. Head over to [Installing Git](/install-git) to install Git.

## Linux (AMD64)

1. If not root, elevate to root with `sudo su`.
2. `cd /tmp`
3. `curl -o go.tar.gz https://dl.google.com/go/go1.16.linux-amd64.tar.gz`
4. `tar -C /usr/local -xzf go.tar.gz`
5. Log in as user you will be running GoSnipe as.
6. `echo 'export PATH="$PATH:/usr/local/go/bin"' >> $HOME/.profile`
7. `echo 'export PATH="$PATH:$HOME/go/bin"' >> $HOME/.profile`
8. Relog or run `source $HOME/.profile`.
9. Head over to [Installing Git](/install-git) to install Git.
