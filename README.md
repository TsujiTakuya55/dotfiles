# dotfiles

## Installation
```bash
bash -c "$(curl -L raw.github.com/TsujiTakuya55/dotfiles/master/install.sh)" -s install
```

## Test＆Debug
```bash
docker build -t dotfiles:latest --build-arg USERNAME=$(whoami) .
docker run -it dotfiles
bash -c "$(curl -L raw.github.com/TsujiTakuya55/dotfiles/master/install.sh)" -s install
```
