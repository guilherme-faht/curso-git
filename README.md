#COMANDOS GIT - Windows

##COMANDOS INICIAIS:

###Criar um diretório
```
Comando: mkdir [nome do diretório]
```

###Iniciar um repositório
```
Comando: git init
```

###Listar os arquivos pertencentes ao repositório
```
Comando: git ls-files
```

###Mostrar o estado dos arquivos de um projeto
```
Comando: git status
```

###Adicionar um arquivo ao repositório
```
Comando: git add [nome do arquivo]
```

###Configuração LOCAL de usuário
```
Comando: git config user.name  = "Seu Nome"
         git config user.email = "seu E-Mail"
```

###Configuração GLOBAL de usuário
```
Comando: git config --global user.name  = "Seu Nome"
         git config --global user.email = "seu E-Mail"
```

###Fazer o commit das alterações
```
Comando: git commit -m "Mensagem de Commit"
```

###Lista o histórico de commits
```
Comando: git log
```

###Mostrar os arquivos que foram alterados
```
comando: git whatchanged
```

###Mostrar o que foi alterado em cada arquivo
```
comando: git whatchanged -p
```

##SINCRONIZAÇÃO DE DADOS NO REPOSITÓRIO REMOTO:

###Mostrar quais repositórios remotos o repositório local tem
```
comando: git remote
```

###Adicionar um repositório remoto
```
comando: git remote add [nome do repositório (padrão: origin)] [URL do repositório remoto]
```

###Enviar as alterações para o repositório remoto
```
comando: git push [nome do repositório remoto] [Nome da branch que receberá as alterações]
exemplo: git push origin master
```

###Clonar um repositório remoto
```
comando: git clone [URL DO REPOSITÓRIO REMOTO]
```

