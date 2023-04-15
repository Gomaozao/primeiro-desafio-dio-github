#   Comandos básicos de Git :desktop_computer:

## As listas deste arquivo servem para explicar as tags do Git.

#### **git init**: cria um repositório local no diretório em que foi digitado o comando. (cria a pasta .git).

#### __git add__ <nome do arquivo>>: Coloca o arquivo selecionado para o stage para sofrer alterações no comando git commit posterior.

#### git commit -m, -a, -amend "<Título do commit>":  Commita mudanças para os arquivos em stage.

1. -m <mensagem de commit> : commita com algum tipo de mensagem.
2. -a: commita apenas os arquivos que foram adicionados ao stage no comando git add.
3. --amend: Modifica o último commit feito, de modo que não cria um novo commit.
4. -am: junção dos comandos -m e -a.

	#### git push <remoto> <branch>: Empurra todos os commits para o repositório remoto do GitHub escolhido.

#### git pull <remote>: Puxa commits do repositório remoto para o repositório local e automáticamente merge-os.

#### git remote: Lista as conexões remotas que se tem conectado ao repositório local.

1. -v: inclui as URL das conexões.

#### git config: Configura usuário e senha no projeto local.

1. --global: refere-fe ao nível de permissão do usuário configurado.
2. user.email: user.email "exemplo_email@exemplo.com",  configura e-mail.
3. user.name: user.name "exemplo-nome", configura nome de usuário.

