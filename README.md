## Instalação do Oracle Linux 9.0

O objetivo desta documentação é mostrar o passo a passo da instalação do Oracle Linux na versão mais atual, em uma máquina virtual.

### Pré-requisitos

* Instalar [ISO Oracle Linux 9.0](https://yum.oracle.com/oracle-linux-isos.html)
* Instalar [Virtual Box](https://www.virtualbox.org/wiki/Downloads)

### Criando uma VM

Com o Oracle VM VirtualBox Gerenciador aberto, selecione a opção "Novo" para criar uma máquina virtual.
Em seguida, configure os seguites passos:

* Nome da máquina
* Sistema Operacional da Máquina
* Quantidade de RAm
* Tamanho e características do Disco Rígido

Com a máquina já criada, vá em Configurações > Armazenamento > Acrescentar Disco Óptico > e selecione a Iso do Oracle Linux já instalada anteriormente.

## Instalando o Oracle Linux

Agora, basta iniciar a máquina virtual e selecionar a opção "Install Oracle Linux   9.0.0"

![image](https://user-images.githubusercontent.com/62852333/189706781-fe77ba65-c6b8-4ba0-b55e-5e52aad2fea9.png)

Nesta etapa, você poderá fazer as seguintes configurações:

* Keyboard: alterar o tipo de teclado para Português Brasil
* Time & Date: ajustar a data e horário da máquina
* Software Selection: deve-se selecionar a opção Minimal Install
* Installation Destination: deve-se selecionar o disco onde será instalado a máquina, e há possibilidade de customizar as partições, assim como particionar automaticamente
* Root Password: criar uma senha para o usuário root

Após essas configurações, selecione "Begin Instalation" e após o carregamento, "Reboot System".
Depois de todos esses passos, sua máquina virtual estará pronta para o uso, com o sistema operacional Oracle Linux 9.0

