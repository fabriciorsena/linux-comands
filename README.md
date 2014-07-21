# Linhas de comando do Linux

uma lista completa dos comando que uso no terminal Linux. Também por ser visto como guia pessoal para uso do Linux.

### Abrir o terminal

<pre>
Crtl + Alt + T	
</pre> 

### Executar sublime via terminal digite:

É possivel ativar um gatilho e executar o editor Sublime via terminal. A primeira forma inicia o editor. A segunda, abre um arquivo para edição no editor.

<pre>
subl > abre o sublime subl + arquivo > abre o arquivo para edição
</pre>

### Alias

Renomeie ações do sistema operacional. assim fica fácil gerenciar abas e adcionar funcionalidades extras no projeto via terminal.

<pre>
alias b="clear" ou atalho Crtl + L	
</pre>

### Atualização de pacotes do Linux

<pre>
sudo apt-get install update	
</pre>

### logando como Root no terminal detalhe! fico logado apenas no ambiente terminal

<pre>
su	+ senha
</pre>

### Desligar o sistema

Detalhe! Recomendado quando estamos em máquinas virtuais como virtual box, VWare player, ou ambiente Grunt. (para os comando funcionarem é preciso logar com root).

<pre>
halt + ENTER 	
</pre>


### Reinicialização do sistema

<pre>
reboot + ENTER	
</pre>

### (man) Documentação do Linux

O linux possui uma biblioteca comentada para cada comando do sistema para saber mais informações sobre um comando utilize:

<pre>
man + nome do comando exemplo: man halt	
</pre>

### Diretorios do Linux


| Estrutura de Diretórios  | Significado dos Diretórios|
| ------------- | ------------- |
| /bin/  |  Binários principais dos usuários. Os principais comandos do sistema  |
| /boot/  |  Arquivos de sistema de boot ou inicialização do sistema o Kerneu  |
| /dev/  |   Arqivos de dispositivo (entrada de discos, impressoroas, hds etc)   |
| /etc/ |   Arquivos de configuração do sistema ex: configuração de rede  |
| /home/ |   Diretórios dos usuários comuns do sistema |
| /lib/ |   Biliotecas essenciais do sistema e módulos do kernel |
| /media/ |   Diretório de montagem de dispositivos |
| /mnt/ |   Diretório de montagem de dispositivos - bem parecido |
| /opt/ |   Instalação de programas não oficiais no linux |
| /sbin/ |   Armazenam arquivos executaveis, comandos shotdown, shalt  |
| /srv/ |   Diretório para dados de serviços fornecidos pelo sistema  |
| /tmp/ |   Diretório de arquivos temporarios  |
| /usr/ |   Segunda hierarqui do sistema, onde ficam os usuários comuns do sistema e programas.  |
| /var/ |   Dirétorios com arquivos variáveis gerados pelos programas do sistema. Exemplo: logs, spool impressoras, e-mail e cache   |
| /root/ |   Diretório do usuário root - total poder sobre o sistema, instalar, desistalar etc.  |
| /proc/ |   Diretório virtual controlado pelo Kernel comconfiguração total do sistema |

Créditos das informações das informações (Diretorios do Linux) para [nitro-informatica](http://nitro-infomatica.blogspot.com.br/)

### Navegação nos Diretorios e pastas

| comando  | Second Header |
| ------------- | ------------- |
| pwd	  |  lista diretorio atual |  
| ls  | mostra conteúdo da pasta  |
| ls /bin  | mostra conteúdo de outro diretorio |
| ls  | mostra conteúdo da pasta  |


