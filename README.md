<p align="center">
  <img height="100" height="auto" src="https://github.com/freshe4qa/aleo/assets/85982863/9226ab61-b792-44e8-8d6c-399600c3692d">
</p>

# Aleo — CONTRIBUTOR BADGE

Official documentation:
>- [link](https://developer.aleo.org/getting_started/)

Explorer:
>- [-](-)

### Minimum Hardware Requirements
 - 2x CPUs; the faster clock speed the better
 - 2GB RAM
 - 20GB of storage (SSD or NVME)

```
sudo apt update && sudo apt upgrade -y
```

```
apt install curl iptables build-essential git wget jq make gcc nano tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev -y
```

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source "$HOME/.cargo/env"
```
```
git clone https://github.com/AleoHQ/leo
```
```
cd leo && cargo install --path .
```

Создаем кошелек

```
leo account new
```

Создаем приложение

```
leo example tictactoe
```

```
cd tictactoe
```

```
leo run new
```

```
git init main

rm -rf .git

cd main

rm -rf .git

git add .

cd ..

git add .
```

Добавляем адрес электронной почты
(вместо mail@.com - ваш адрес электронной почты)

```
git config --global user.email mail@.com
```

(вместо your_username - ваш юзернейм в гитхабе)

```
git config --global user.name your_username
```

```
git commit -m "My First commit"
```

Создаем новый репозиторий

![opera_HLbDRETCVa](https://github.com/freshe4qa/aleo/assets/85982863/b8cefae2-44b3-402b-b2ff-317694d4315c)

Скопируйте ссылку на свой репозиторий

![opera_JuUuDK0fEi](https://github.com/freshe4qa/aleo/assets/85982863/75122520-98b7-45b1-8740-b62874b3414e)

```
git branch -m main
```

(вместо your_repository_link - ссылка на ваш репозиторий)

```
git remote set-url origin your_repository_link
```

```
git remote -v
```

Получаем бейдж

Перейдите в репозиторий Leo и нажмите "New Issue" в правом верхнем углу https://github.com/AleoHQ/leo

Нажмите "Get started" в строке Leo Contributor Badge

В title вставьте: Add your_username to contributors (вместо your_username - ваш юзернейм в гитхабе)

В описании вставьте:
Hi Aleo team! I’m claiming my contributor badge for completing the New Developer Toolkit tutorial.
Tutorial Repo: your_repository_link
Requested badge: Tutorial
(вместо your_repository_link - ссылка на ваш репозиторий)

Нажимаем "Submit New Issue"
