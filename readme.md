# Preparação de ambiente
### Vamos preparar o ambiente para desenvolvimento de aplicações.

#### Neste ambiente iremos instalar e configurar os seguintes recursos:
- Máquina Virtual(Virtualbox)
- Distribuição Linux (Ubuntu Server)
- Nasm
- Compilador da linguagem C
- Configurar o IP e a porta de comunicação entre a máquina real e a virtual
- Configurar o acesso via SSH entre o VSCode e o servidor Linux
- Instalar as extensões: Material, Icon, Nasm, SSH e Linguagem C/C++

#### Máquina Virtual (VirtualBox)

!["Logo VirtualBox"](virtualbox.png)

Máquina Virtual é uma ferramenta que permite a criação de novos "computadores" e a instalação de sistema operacionais para estudo ou trabalhio.

Para o nosso estudo iremos usar o VitualBox, da Oracle.
Para instalar, basta fazer o download no link a seguir:
<a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">VirtualBox</a>

##### Criando a máquina virtual para o nosso estudo

- Configuração:
   > - Nome da máquina: Servidor
   > - Memória: 4GB(4096)
   > - Processador: 2
   > - Disco: 100GB
   > - IP e Porta do Host: 127.0.0.1 e 22
   > - IP e Porta do Convidado: 10.0.2.15 e 22

- Tela inicial de configuração

<img src=telaconfiguraçao1.png width=500 height=250>


- Tela inicial de configuração do hardware

<img src=telaconfiguraçao2.png width=500 height=250>

- Tela inicial de configuração do disco

<img src=telaconfiguraçao3.png width=500 height=250>

- Tela final de configuração

<img src=telaconfiguraçao4.png width=500 height=250>

- Tela inicial de configuração de rede

<img src=telaconfiguraçao5.png width=500 height=250>

- Tela de configuração de Portas e IP

<img src=telaconfiguraçao6.png width=500 height=250♣>

### Distribuição do Ubuntu Server
!["Logo Ubuntu"](ubuntu.png)


Para nosso estudo iremos utilizar uma distribuição Linux para servidores chamada Ubuntu.

Acompanhe o processo de instalação:

Faça o download aqui:<a href= "https://ubuntu.com/download/server" target="_blank"> Ubuntu Server</a>

- Acompanhe a instalação:

Tela de início de instalação
<img src=ubuntu1.png>

Tela de seleção de idioma
<img src=ubuntu2.png>

Tela de seleção de teclado
<img src=ubuntu3.png>

Tela de tipo de instalação
<img src=ubuntu4.png>

Tela de configuraçao de rede
<img src=ubuntu5.png>

Tela de configuração de proxy
<img src=ubuntu6.png>

Tela de pacotes de atualização
<img src=ubuntu7.png>

Tela de configuração de disco
<img src=ubuntu8.png>

Tela de layout do disco
<img src=ubuntu9.png>

Tela de configuração do usuário
<img src=ubuntu11.png>

Tela de configuração do SSH
<img src=ubuntu12.png>

Tela do fim da instalação
<img src=ubuntu13.png>