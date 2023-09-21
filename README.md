Laboratório 051 - Fundamentos de SQL para Banco de Dados
=============================

Repositório para armazenar o Laboratório do curso Fundamentos de SQL para Banco de Dados da [4Linux](https://4linux.com.br/)

Dependências
------------

Para a criação do laboratório é necessário ter pré instalado os seguintes softwares:

* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [pgAdmin](https://www.virtualbox.org/wiki/Downloads)

Laboratório
-----------

O Laboratório será criado utilizando uma máquina virtual com [VirtualBox][https://www.virtualbox.org/wiki/Downloads] e a interface [pgAdmin][https://www.virtualbox.org/wiki/Downloads] para se conectar ao banco de dados.

Para criar o seu laboratório siga os seguintes passos:

**Passo 1: Configuração da Máquina Virtual no VirtualBox**

1. Faça a instalação do VirtualBox pelo link: https://www.virtualbox.org/wiki/Downloads
2. Faça o download da máquina virtual pronta em: ...
3. No VirtualBox clique no canto superior esquerdo em Arquivo > Importar Appliance e selecione o arquivo da máquina virutal (Arquivo OVA).
4. Em Arquivo > Ferramentas > Gerenciador de Rede, remova o adaptador atual e crie um novo com o Endereço IPv4 igual a "192.168.56.1".
5. Nas configurações da máquina virtual, na aba Rede selecione o seu novo adaptador na aba "Adaptador 2".
6. Inicie sua máquina virtual "4Linux AlmaLinux".

**Passo 2: Acesso ao PostgreSQL pelo pgAdmin**

1. Na sua máquina, baixe e instale o pgAdmin em: https://www.pgadmin.org/download/
2. Abra o pgAdmin e defina uma senha master, essa senha será solicitada todas as vezes que você abrir o programa.
3. No pgAdmin, clique em "Add New Server" para adicionar a sua máquina virtual.
4. Na aba "General" de um nome para seu servidor.
5. Na aba "Connection" preencha "Host name/address" com o IP da sua máquina virtual, o IP padrão é "192.168.56.80".
6. Deixe os campos "Port", "Maintence database" e "Username" com o seu valor padrão.
7. Clique em "Save".

**Passo 3: Executando comandos no pgAdmin**

1. Para executar um comando você precisa escolher uma base de dados, selecione uma clicando em cima.
2. Clique em "Query Tool" localizado em "Object Explorer" para iniciar uma conexão com sua base de dados.
3. Escreva sua consulta no campo "Query".
4. Execute a consulta clicando em "Execute".
