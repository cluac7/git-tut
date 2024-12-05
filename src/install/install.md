# Installing Git

Begin by downloading git. How you do this depends on your system:
### Linux
Use your distro's preferred package manager or packaging format, e.g.
```bash
sudo pacman -S git
```
Or, build it from scratch by downloading [the latest version here](https://www.kernel.org/pub/software/scm/git/), and running:
```
make all docs info prefix=/usr
sudo make install install-doc install-html install-info install-man prefix=/usr
```

### Mac OS
Using homebrew, run:
```bash
brew install git
```
Or install XCode, which includes git

Or use the standalone installer [here](https://git-scm.com/downloads/mac)

### Windows

Using winget, run
```bash
winget install -e --id Git.Git
```
Or, download [GitForWindows](https://gitforwindows.org/)
