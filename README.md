#COMANDOS GIT - Windows
_________________________________________________

##COMANDOS INICIAIS:


###Criar um diretório
```
Comando: mkdir [nome do diretório]
```

1.2) Iniciar um repositório
Comando: git init

1.3) Listar os arquivos pertencentes ao repositório
Comando: git ls-files

1.4) Mostrar o estado dos arquivos de um projeto
Comando: git status

1.5) Adicionar um arquivo ao repositório
Comando: git add [nome do arquivo]

1.6) Configuração LOCAL de usuário
Comando: git config user.name  = "Seu Nome"
         git config user.email = "seu E-Mail"

1.7) Configuração GLOBAL de usuário
Comando: git config --global user.name  = "Seu Nome"
         git config --global user.email = "seu E-Mail"

1.8) Fazer o commit das alterações
Comando: git commit -m "Mensagem de Commit"

1.9) Lista o histórico de commits
Comando: git log

1.10) Mostrar os arquivos que foram alterados
comando: git whatchanged

1.11) Mostrar o que foi alterado em cada arquivo
comando: git whatchanged -p


2) SINCRONIZAÇÃO DE DADOS NO REPOSITÓRIO REMOTO:


2.1) Mostrar quais repositórios remotos o repositório local tem
comando: git remote

2.2) Adicionar um repositório remoto
comando: git remote add [nome do repositório (padrão: origin)] [URL do repositório remoto]

2.3) Enviar as alterações para o repositório remoto
comando: git push [nome do repositório remoto] [Nome da branch que receberá as alterações]
exemplo: git push origin master

2.4) Clonar um repositório remoto
comando: git clone [URL DO REPOSITÓRIO REMOTO]

