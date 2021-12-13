# Git na Prática!

Nesta aula foram ensinados os primeiros comandos para a configuração de um repositório local. Dos quais podem-se citar:

>`git config --global init.defaultBranch main <nome>` muda a branch padrao do init<br>
>`git config --list` mostra a configuração atual

>`git init` inicializa o git na pasta

>`git status` mostra o status atual de branch, commits e detalhes de arquivos

>`git add <arquivo>` adiciona o arquivo para a staging area<br>
>`git add .` adiciona todos os arquivos para a staging area

>`git commit -m "<Texto>"` cria um commit com a mensagem "Texto"<br>
>`git commit --amend -m "<Texto>"` altera o texto do último commit e todo o stagging também<br>
>`git commit -a -m "<Texto>"` adiciona para stagging área os arquivos modificados e já faz o commit direto

>`git log` apresenta um histórico de todos os commits feitos<br>
>`git log --oneline` exibição de logs em uma linha por commit<br>
>`git log --graph` exibição gráfica

Além disso, foi ensinado como utilizar o arquivo `.gitignore` para não enviar elementos desnecessários para o repositório remoto.