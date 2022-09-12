# Для Mac OS X

Пользователям Mac Os X нужно установить и освоить следующие инструменты.

Установить:

1. homebrew
2. git
3. docker for macosx
4. vscode

Освоить:

1. unix user terminal commands (man, which, ls, cat, mcedit, mkdir, rm -r, chmod, chown, .sh, bash, sh)
2. unix root terminal commands (apt, sudo, adduser, ..)
3. ssh (ssh-keygen, known_hosts, config, login, logout, ssh -L, agent-forwarding)
4. "необрываемый терминал" tmux
5. jupyter notebook (--ip, --port, --no-browser, token, !)
6. git (clone, status, --global, add, commit -m, push -u origin master, pull, checkout -b, rm --cached, .gitignore)
7. docker commands
8. vscode



## Установка
### homebrew
[Install instruction](https://docs.brew.sh/Installation)

1. В терминале:

	```bash
	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)
	```

### docker for macosx
1. В терминале:
    
    ```bash 
    brew install docker --cask\
    ```

2. Запуск из терминала пока не сработает
    
    ```bash
	docker --version
	# command not found: docker
	```
	
3. Среди программ запустить Docker, разрешить доступ.

4. Теперь в терминале работает запуск:
    
    ```bash
	docker --version
	```

### git
1. В терминале:

	```bash
	brew install docker --cask
	```


### vscode
1. 



### rust (optional)
С официального сайта [https://www.rust-lang.org/learn/get-started]()

1. В терминале:

    ```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```