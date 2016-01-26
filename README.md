#COMANDOS GIT - Windows
_________________________________________________

##COMANDOS INICIAIS:


###Criar um diret�rio
```
Comando: mkdir [nome do diret�rio]
```

1.2) Iniciar um reposit�rio
Comando: git init

1.3) Listar os arquivos pertencentes ao reposit�rio
Comando: git ls-files

1.4) Mostrar o estado dos arquivos de um projeto
Comando: git status

1.5) Adicionar um arquivo ao reposit�rio
Comando: git add [nome do arquivo]

1.6) Configura��o LOCAL de usu�rio
Comando: git config user.name  = "Seu Nome"
         git config user.email = "seu E-Mail"

1.7) Configura��o GLOBAL de usu�rio
Comando: git config --global user.name  = "Seu Nome"
         git config --global user.email = "seu E-Mail"

1.8) Fazer o commit das altera��es
Comando: git commit -m "Mensagem de Commit"

1.9) Lista o hist�rico de commits
Comando: git log

1.10) Mostrar os arquivos que foram alterados
comando: git whatchanged

1.11) Mostrar o que foi alterado em cada arquivo
comando: git whatchanged -p


2) SINCRONIZA��O DE DADOS NO REPOSIT�RIO REMOTO:


2.1) Mostrar quais reposit�rios remotos o reposit�rio local tem
comando: git remote

2.2) Adicionar um reposit�rio remoto
comando: git remote add [nome do reposit�rio (padr�o: origin)] [URL do reposit�rio remoto]

2.3) Enviar as altera��es para o reposit�rio remoto
comando: git push [nome do reposit�rio remoto] [Nome da branch que receber� as altera��es]
exemplo: git push origin master

2.4) Clonar um reposit�rio remoto
comando: git clone [URL DO REPOSIT�RIO REMOTO]

