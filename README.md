# Guia de Instalação do Linux

Este repositório fornece um guia passo a passo para a instalação de vários tipos de sistemas operacionais Linux, com ênfase na configuração inicial através da Oracle VM VirtualBox. O guia começa com instruções sobre como configurar a Oracle VM VirtualBox e continua com a instalação do Ubuntu e outros tipos populares de Linux.

## Índice

- [Configuração do HyperV do computador](#hyperv)
- [Configuração da Oracle VM VirtualBox](#VirtualBox)
- [Instalação do Ubuntu](#instalação-do-ubuntu)
- [Outros Tipos de Linux](#outros-tipos-de-linux)

<p id="hyperv"><h2>Configuração do HyperV do computador</h2></p>

Se estiver usando o Windows e o Hyper-V estiver ativado, pode ser necessário desativá-lo para usar o Oracle VM VirtualBox. Siga os passos abaixo para desativar o Hyper-V:

1. Pressione `Windows + R` para abrir a caixa de diálogo "Executar".
2. Digite `optionalfeatures` e pressione Enter para abrir o menu "Recursos do Windows".

  ![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/6834afc0-29b9-44c8-9cf5-799367fb4873)

3. Desmarque a opção "Hyper-V" ou algo que contenha "Hypervisor" ou "Virtualização" na lista de recursos e clique em "OK".

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/b8aaf6c6-ac7a-430c-8b2c-6338747d942b)

   
4. Reinicie o computador quando solicitado para aplicar as alterações.

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/2c03a81b-85aa-427f-af38-aae616488b92)

<p id="VirtualBox"><h2>Configuração da Oracle VM VirtualBox</h2></p>

1. Faça o download e instale o [Oracle VM VirtualBox](https://www.virtualbox.org/wiki/Downloads) no seu sistema operacional.
  - Selecione o seu sistema:

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/8f1171a5-0ece-43e1-9e75-5ec7d7000919)

  - Uma vez concluido, abra o arquivo baixado:

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/4b25f4ac-48a3-4a4a-9cc3-71409e63597b)
  - Após isso, siga as instruções (Next, next, install):

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/abf495c4-de69-490e-90e4-83fdda8831c0)

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/3f9b0095-2b83-455e-a769-bf5e936ed3d1)

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/cc742e62-ee79-42a4-aa9c-488034e8bf8b)

  - Se o seu computador faltar algum componente, clique em "YES" para a seguinte mensagem:

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/49212e37-60f4-4713-8ddc-494cd8976f71)

  - Clique em Install e prossiga:

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/c37631e5-4330-477f-abde-27bc7a377888)

  - Por fim, clique em "Finish" para encerrar e abrir o VMBox.

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/ac5a8709-3fc2-452d-a69e-3773cfa21e91)

 
2. Abra o Oracle VM VirtualBox.

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/104b2d99-2da0-4473-a660-8309027f4176)



<p id="instalação-do-ubuntu"><h2>Instalação do Ubuntu</h2></p>

1. Faça o download da imagem ISO mais recente do Ubuntu no [site oficial do Ubuntu](https://ubuntu.com/download) ou pegue na lista de arquivos deste repositório repositório.

GITHUB:


SITE:

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/b8ece202-7c67-4e65-9385-2f0dbb09b1f5)

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/08f60c79-d0f7-4b18-abe4-37524956942c)

![image](https://github.com/martinsRossi/instalacao_linux/assets/101609697/fc2bd389-a12d-4cbd-bac0-ee3031c86c4d)





2. Abra o Oracle VM VirtualBox e clique em "Nova" para criar uma nova máquina virtual.


  
3. Siga o assistente de criação da VM, fornecendo o nome da VM, tipo e versão do sistema operacional (Ubuntu) e a quantidade de memória RAM e espaço em disco necessários.



4. Durante a configuração da VM, quando solicitado, selecione a opção "Usar um arquivo de disco rígido existente" e selecione a imagem ISO do Ubuntu que você baixou anteriormente.



5. Conclua a criação da VM e inicie-a.



6. Siga as instruções na tela para instalar o Ubuntu na VM.



<p id="outros-tipos-de-linux"><h2>Outros Tipos de Linux</h2></p>

Este guia também inclui instruções básicas para a instalação de outros tipos populares de sistemas operacionais Linux, como:

- Debian
- Fedora
- CentOS
- Arch Linux

Para instalar esses sistemas operacionais, siga procedimentos semelhantes aos descritos acima para o Ubuntu, adaptando as configurações conforme necessário para as respectivas imagens ISO e requisitos de sistema.
