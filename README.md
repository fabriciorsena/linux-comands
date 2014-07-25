# Essenciais linhas de comandos

uma lista completa dos comando essenciais do Linux. Também por ser visto como guia pessoal para comandos que uso.

## Direitos autoriais

Esse README, contém exemplos que foram retirados dos seguintes endereços: [curso de linux.org](http://www.cursodelinux.org/modulo-1/modulo-1-fundamentos-do-sistema) e Créditos das informações (Diretorios do Linux) para [nitro-informatica](http://nitro-infomatica.blogspot.com.br/)

### Abrir o terminal

<pre>
Crtl + Alt + T	
</pre> 

### Executar sublime via terminal

É possivel ativar um gatilho e executar o editor Sublime via terminal. A primeira forma inicia o editor. A segunda, abre um arquivo para edição no editor.

<pre>
subl > abre o sublime subl + arquivo > abre o arquivo para edição. subl -n -w para abrir um novo arquivo em uma nova aba
</pre>

### Alias (renomeando funcionalidades)

Renomeie ações do sistema operacional. assim fica fácil gerenciar abas e adcionar funcionalidades extras no projeto via terminal.

<pre>
alias b="clear" ou atalho Crtl + L	
</pre>

### cat (abre os arquivos no terminal)

<pre>
cat	+ arquivo
</pre>

### Url de configutação das atualizações

<pre>
/etc/apt/sources.list	
</pre>

### Atualização de pacotes do Linux

<pre>
sudo apt-get install update	
</pre>

### Instalando programas (pacotes)

<pre>
apt-get install + programa	
</pre>

### Desinstala programas

<pre>
apt-get remove + programa	
</pre>

### Desinstala pacotes junto com configurações

<pre>
apt-get --purge remove	
</pre>

### Apaga sobras de instalações mal não concluídas

<pre>
apt-get autoclean
</pre>

### Atualiza os pacotes instalados no sistema

<pre>
apt-get  upgrade 	
</pre>

### Atualiza a distruibuição Linux

<pre>
apt-get dist-upgrade	
</pre>

### Procura na lista um pacote especificado

<pre>
apt-cache search	
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


### Manipulação de Arquivos

| comando  | significado |
| ------------- | ------------- |
| mkdir	  |  cria pasta |  
| touch | cria e atualiza arquvos (.txt, html, .sh, .pub etc...) |
| ls /bin  | mostra conteúdo de outro diretorio |
| mkdir -p | permite criar vários pastas dentro uma das outras  |
| rm | remove arquivos  |
| rm -r | apaga diretorios  |
| rmdir - a | apaga apenas diretorios vazios  |
| rmdir -p|  permite apagr varios diretorios  |
| cp |  copias arquivos  |
| mv |  moves arquivos e também renomeia arquivos|

### Navegação nos Diretorios e pastas

| comando  | significado |
| ------------- | ------------- |
| pwd	  |  lista diretorio atual |  
| ls  | mostra conteúdo da pasta  |
| ls /bin  | mostra conteúdo de outro diretorio |
| ls - F | verifica as extensões dos arquivos  |
| ls - l | mostra informações detalhadas  |
| ls - a | arquivos ocultos  |
| ls - Fa | mostra os tipos de arquivos mais os ocultos  |

### Comando de Buscas

| comando  | significado |
| ------------- | ------------- |
| find	  |  lista diretorio atual |  
| find / -name exemplo-busca  | pesquisando dentro de todos os diretorios pelo nome  |
| find / -name init*  | pesquisa dentro de todos os diretorios que comecao com init |
| find  --help  | ajuda crinças desesperadas |
| locate txt | txt | realiza uma busca |
| grep   | procura palavras dentro de arquivos =D |
| grep "palavras exatas"  | procura palavras dentro de arquivos =D |
| grep -n  | exibe a linha da palavra encontrada =D =D =D |
| grep | txt | tudo que seja txt |

#### Metacaracteres

| comando  | significado |
| ------------- | ------------- |
| ?	exemplo: ls file?  |  procura por números |  
| *  | tudo  |
| [12] | liste arquivos com ou ou dois números |
| [1-5]| listando arquivos que possuam do 1 ao 5 com finais |

#### Acessando diretorios

| comando  | significado |
| ------------- | ------------- |
| cd	  |  change directory |  
| cd .. | retorna para pasta pai  |
| cd -  | volta a pasta anterior |
| cd ~ | retorna ao diretorio home  |


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




