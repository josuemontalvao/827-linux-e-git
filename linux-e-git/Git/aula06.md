# Aprofundando no Git I

Por fim, foram ensinados os últimos comandos e, além disto, foram tiradas dúvidas gerais a respeito de todo o módulo ao longo da aula. Outra parte importante foi a criação de conta e sincronização com um repositório remoto no **Github**. A seguir, mais comandos discutidos:

>`git rm --cached <arquivo>` remove o arquivo da staging area

>`git checkout <nome>` muda para outra branch
git checkout HEAD~1: volta para um commit atrás do atual


>`git merge <nome_branch>` faz o merge da "nome_branch" para a merge atual
    
Vale destacar que foi feita uma detalhada explicação sobre resolução de conflitos ao fazer o `merge`.    

>`git reset <token>` volta para o commit, com os arquivos imediatamente antes do add e commit seguintes

>`git remote add origin <endereço>` conecta seu diretório local a um diretório remoto

>`git push -u origin main` envia tudo do local para o remoto<br>
>`git push origin <branch>` sobe na nuvem o que foi feito na respectiva branch
>`git push --all origin` faz o push de todas as branches que existem localmente
    
>`git <comando> --help` mostra a documentação do comando escolhido

