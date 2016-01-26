#COMANDOS GIT - Windows

##COMANDOS INICIAIS:

###Criar um diret�rio
```
Comando: mkdir [nome do diret�rio]
```

###Iniciar um reposit�rio
```
Comando: git init
```

###Listar os arquivos pertencentes ao reposit�rio
```
Comando: git ls-files
```

###Mostrar o estado dos arquivos de um projeto
```
Comando: git status
```

###Adicionar um arquivo ao reposit�rio
```
Comando: git add [nome do arquivo]
```

###Configura��o LOCAL de usu�rio
```
Comando: git config user.name  = "Seu Nome"
         git config user.email = "seu E-Mail"
```

###Configura��o GLOBAL de usu�rio
```
Comando: git config --global user.name  = "Seu Nome"
         git config --global user.email = "seu E-Mail"
```

###Fazer o commit das altera��es
```
Comando: git commit -m "Mensagem de Commit"
```

###Lista o hist�rico de commits
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

##SINCRONIZA��O DE DADOS NO REPOSIT�RIO REMOTO:

###Mostrar quais reposit�rios remotos o reposit�rio local tem
```
comando: git remote
```

###Adicionar um reposit�rio remoto
```
comando: git remote add [nome do reposit�rio (padr�o: origin)] [URL do reposit�rio remoto]
```

###Enviar as altera��es para o reposit�rio remoto
```
comando: git push [nome do reposit�rio remoto] [Nome da branch que receber� as altera��es]
exemplo: git push origin master
```

###Clonar um reposit�rio remoto
```
comando: git clone [URL DO REPOSIT�RIO REMOTO]
```

