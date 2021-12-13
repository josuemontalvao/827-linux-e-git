# Principais comandos do Terminal Linux

Nesta aula foram apresentados os principais comandos para um terminal Linux. A seguir segue parte das anotações feitas durante a aula:

>`ls` mostra o que há no diretório<br>
>`ls -l` mostra em formato de lista<br>
>`ls -la` inclui ocultos

>`cd <endereço>` muda o diretório<br>
>`cd $HOME` retorna ao diretório inicial do usuário

>`pwd`: mostra o endereço de diretório atual

>`whoami` mostra qual usuário está ativo

>`sudo su` trocar para o usuário root<br>
>`sudo <comando>` executa o comando com permissão de superadmin

>`exit`: retorna ao usuário

>`mkdir <nome>` cria uma pasta com o nome 'nome'

>`rmdir <nome>` remove a pasta 'nome' (apenas se tiver vazia)

>`clear` limpa o terminal

>`apt install <nome do aplicativo>` instala o aplicativo

>`man <comando>` exibe o manual do comando

>`touch <nome com fomato>` cria um arquivo vazio

>`cat <arquivo>` exibe o conteúdo do arquivo<br>
>`cat <arquivo1> <arquivo2>` exibe a concatenação dos arquivos<br>
>`cat <arquivo1> <arquivo2> | grep <texto>` destaca todo o 'texto' dentro de resultado exibido (apenas linhas com resultados são exibidas)<br>
>`cat <arquivo1> <arquivo2> > <arquivo3>` salva a concatenação no terceiro arquivo<br>
>`cat <arquivo1> <arquivo2> >> <arquivo3>` concatena os dois primeiros no final do terceiro arquivo e salva neste último

>`cp <primeiro> <segundo>` copia o conteúdo do primeiro para o segundo, que pode ter um nome novo

>`mv <primeiro> <segundo>` renomeia o nome do primeiro arquivo para o segundo

>`echo <texto>` exibe o conteúdo de 'texto' no terminal<br>
>`echo <texto> > <arquivo>` salva o resultado do echo em 'arquivo'

>`&&` operador AND para executar mais de um comando (só roda se o anterior der sucesso)

>`history` exibe o histórico de comandos

>`sudo apt install nano` instala o nano<br>
>`sudo apt update` atualiza o sistema (importante fazer de tempo em tempo)<br>
>`apt list --upgradable` mostra o que precisa ser atualizado<br>
>`sudo apt-cache search chromium` pesquisa um programa a ser instalado (chromium, por exemplo)

Exemplo sequencial do uso de `sudo` :
>`sudo apt update && sudo apt install ...`<br>
>`sudo apt upgrade`<br>
>`sudo apt full-upgrade`<br>
>`sudo apt autoremove` remove pacotes não mais utilizados

>`free` memória RAM disponível<br>
>`free -h` melhor visualização

>`df` exibe quanto de disco há disponível<br>
>`df -h` melhor exibição

>`du` quando de disco o diretório está usando<br>
>`du -sh Documentos/teste.txt` exibe tamanho de um arquivo ou pasta em específico, por exemplo

>`nano <arquivo>` editor de texto<br>
>`nano ~/.bashrc` é um arquivo que carrega quando o sistema inicia, aqui você pode deixar uma variável de ambiente que não seja deletada após desligar a máquina
